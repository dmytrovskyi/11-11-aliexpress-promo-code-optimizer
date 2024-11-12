# CouponOptimizer

**CouponOptimizer** is a Python tool designed to help shoppers maximize their savings during online sales events by optimizing the use of multiple coupons with different thresholds and benefits.

## To run this notebook in colab click button 

<a target="_blank" href="https://colab.research.google.com/github/dmytrovskyi/11-11-aliexpress-promo-code-optimizer/blob/main/calculator.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Overview

During major online sales events like Singles' Day (11.11), shoppers often have access to multiple coupons with varying thresholds and benefits. Managing these coupons effectively can be challenging, especially when aiming to minimize total spending while maximizing discounts.

**CouponOptimizer** automates this process by:

- Allocating items into batches to maximize the total benefit from coupons.
- Handling multiple coupons with different activation thresholds and benefits.
- Ensuring all items in your cart are included in the optimal batches.

## Features

- **Multiple Coupons Support**: Works with an unlimited number of coupons, each with its own threshold and benefit.
- **Dynamic Item Allocation**: Automatically groups items into batches that best meet coupon thresholds.
- **Benefit Maximization**: Prioritizes coupons based on their benefit-to-threshold ratio to maximize total savings.
- **Customizable**: Easily adjust item lists and coupon details to fit your specific shopping scenario.

## How It Works

The tool uses a greedy algorithm to:

1. **Calculate Benefit-to-Threshold Ratios**: Determines the value of each coupon relative to its threshold.
2. **Sort Coupons and Items**: Orders coupons by their ratios and items by price to optimize batch formation.
3. **Form Optimal Batches**: Groups items into batches that meet or exceed coupon thresholds, applying the most beneficial coupons first.
