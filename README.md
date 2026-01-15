# MT5 StepTrail Break-Even Manager

Professional-grade MT5 Expert Advisor for rule-based break-even and step trailing stop management.

## Core Features
- Automatic move to Break-Even at predefined profit
- Progressive step-based trailing stop
- Profit lock-in framework
- No stop-loss widening (only protective logic)
- Broker stop-level validation
- Symbol-specific execution control

## Example Logic
- +20 pips → SL to Entry (BE)
- +30 pips → SL to +20
- +40 pips → SL to +30
- +50 pips → SL to +40
- etc.

## Use Case
Designed for systematic and prop-firm style trading where:
- Execution must be rule-based
- Risk must be mechanical
- Emotions must be fully removed from trade management

## Platform
- MetaTrader 5 (MT5)
- Language: MQL5

## Author
Teodor Dujin  
Forex & Crypto Trader | Trading Operations | Risk & Execution Automation
