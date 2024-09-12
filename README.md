# Poker-Trading Simulator

This project explores the similarities between poker and trading through a Python-based simulation. It demonstrates how concepts like skill, risk management, and decision-making under uncertainty apply to both domains.

## Features

- Simulates multiple poker hands / trading sessions
- Incorporates skill level and confidence into decision-making
- Uses Kelly Criterion for bet sizing
- Analyzes and visualizes results

## Usage

To run the simulator, use the following command:

```python
python poker_trading_simulator.py
```

You can also use the provided Jupyter Notebook to interact with the simulator and visualize the results.

## How It Works

1. **Simulation**: The `PokerTradingSimulator` class simulates multiple poker hands or trading sessions. Each simulation starts with an initial capital and runs for 100 rounds or until the capital is depleted.

2. **Skill and Luck**: The `simulate_hand` method determines the outcome of each hand/trade based on a skill level parameter, reflecting how both poker and trading outcomes are a mix of skill and chance.

3. **Bet Sizing**: The `calculate_bet_size` method uses the Kelly Criterion to determine the optimal bet size based on the player's edge and current capital.

4. **Analysis**: The `analyze_results` method provides statistical analysis of the simulation results and generates a histogram to visualize the distribution of outcomes.

## Key Concepts Illustrated

- **Risk Management**: The bet sizing algorithm demonstrates how proper risk management is crucial in both poker and trading.
- **Skill vs. Luck**: The `skill_level` parameter shows how increased skill leads to better long-term results, despite short-term variance.
- **Bankroll Management**: The simulation tracks capital over time, showing how initial bankroll and proper management affect long-term success.
- **Statistical Thinking**: The analysis of results emphasizes the importance of thinking in probabilities and distributions rather than individual outcomes.

## Results

The simulation compares results for average skill level (0.5) and high skill level (0.7). The results demonstrate that higher skill leads to better outcomes over multiple simulations, mirroring the long-term advantage of skilled players in both poker and trading.

## Future Improvements

1. Implement more sophisticated models for market movements or poker hand distributions.
2. Add features to simulate specific poker scenarios or market events.
3. Incorporate machine learning models to optimize decision-making strategies.
4. Create interactive visualizations for real-time simulation and analysis.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
