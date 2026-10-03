# TrendPilot

_AI-filtered 15m trend-following signal bot with non-custodial wallet execution_

## Summary

TrendPilot combines classic 15m trend-following indicators with a lightweight ML classifier trained to filter false breakouts, sending high-confidence trade signals via Telegram/Discord. Users connect their own Solana wallet, and the bot requests signature approval for each trade, keeping it fully non-custodial.

## Target users

Independent traders who want better signal quality but still control their own funds and execution

## Problem

Pure technical-indicator trend bots generate many false signals in choppy markets, eroding trust and consistency.

## Solution

An ML classifier trained on historical 15m candle patterns filters low-quality trend signals before alerting the user, improving signal win-rate while keeping fund custody with the user.

## MVP features

- 15m trend-following signal engine (EMA/ADX) for BTC/ETH/SOL
- ML classifier trained on historical candles to filter false breakouts
- Telegram/Discord bot delivering ranked, confidence-scored signals
- One-click trade approval via Solana wallet (Blinks/Actions) for execution
- Dashboard tracking signal win-rate and live/backtest performance

## Chains

Solana

## Tech

Python, scikit-learn, Pyth Network, Solana Actions/Blinks, Drift SDK, Telegram Bot API

## Category

AI

## Why now

Solana Actions/Blinks now make one-click, non-custodial trade execution from chat apps simple, pairing well with lightweight ML signal filtering.

## Roadmap

- Expand ML model with more features and live retraining pipeline
- Add portfolio-level risk management across BTC/ETH/SOL positions
- Launch mobile app with push notifications and in-app execution
