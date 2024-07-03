# Grid Script for Long Orders

## Introduction

This Pine Script code implements a grid trading strategy specifically for long orders. It uses a grid system to place buy orders at lower price levels and sell orders at higher price levels. The strategy allows for both automatic and manual setting of grid boundaries, with options to define the source and lookback period for these bounds.

這段 Pine Script 代碼實現了一個專為多單設計的網格交易策略。它使用網格系統在較低的價格水平放置買入訂單，並在較高的價格水平放置賣出訂單。該策略允許自動和手動設置網格邊界，並可以選擇定義這些邊界的來源和回顧期。

## Strategy Explanation

The strategy calculates the grid lines within the defined boundaries and places buy orders when the price falls below a grid line. It then closes these orders when the price rises above the next grid line. The strategy uses a pyramiding approach, allowing multiple entries in the same direction. Grid lines and trading signals are plotted on the chart for visual reference.

該策略在設定的邊界內計算網格線，當價格跌破網格線時放置買入訂單，當價格升至下一個網格線上方時平倉。策略使用金字塔加倉方法，允許多次進入同一方向的訂單。網格線和交易信號被繪製在圖表上以供參考。

## Profitable Trading Approach

This approach aims to capture profits from market fluctuations by systematically entering and exiting positions at predefined levels. By setting grid boundaries and using a pyramiding approach, the strategy capitalizes on both small and large market movements. The visual representation of grid lines and signals helps traders make informed decisions and effectively manage their trades.

這種方法旨在通過系統地在預定水平進出倉位來捕捉市場波動的利潤。通過設置網格邊界並使用金字塔加倉方法，該策略利用市場的大小波動。網格線和信號的可視化表示幫助交易者做出明智的決策並有效管理他們的交易。

## Conclusion

With its systematic approach to placing and closing orders, customizable grid boundaries, and visual aids, the "Grid Script for Long Orders" strategy offers traders a robust tool to navigate market fluctuations. This strategy enhances the ability to capture profits in various market conditions by leveraging a grid-based trading system.

憑藉其系統的訂單放置和平倉方法、可自定義的網格邊界和可視化工具，“多單網格腳本”策略為交易者提供了一個強大的工具來應對市場波動。該策略通過利用基於網格的交易系統提高了在各種市場條件下捕捉利潤的能力。

## Backtest Result
1. ![10  Grid Script for Long orders](https://github.com/WhaleStrategy/Strategies/assets/174404765/1ba065d6-b7f2-4e21-841e-5c9ef4d79f5f)
2. ![10 2  Grid Script for Long orders](https://github.com/WhaleStrategy/Strategies/assets/174404765/3fe09525-7c41-474d-b427-e34190b86903)
