ICT Trading Bot Simulator
This repository contains an algorithmic trading simulator based on the concepts of Inner Circle Trader (ICT). The script is written in Python and uses popular libraries like pandas and numpy to analyze historical market data.

Features
ICT Pattern Detection: Automatically identifies Order Blocks and Fair Value Gaps to generate trading signals.

Backtesting: Simulates the strategy's execution on historical data to calculate performance, total PnL (Profit and Loss), and the number of trades.

Discord Notifications: Includes a function to send trading signal and backtesting reports to a Discord channel, provided a webhook URL is configured.

Modular Code: The main logic is separated into clear functions (find_order_blocks, find_fair_value_gaps, implement_strategy), making it easy to understand and modify.

Disclaimer
This project is strictly for educational and demonstration purposes. The market data used is simulated, and the bot has not been optimized or validated for live trading. Do not use it for real money operations. The ICT strategy is complex and requires a rigorous market analysis that this simple simulator cannot fully replicate.

Requirements
Python 3.x

pandas

numpy

requests
____________________________
ICT Trading Bot Simulator
Este repositorio contiene un simulador de trading algorítmico basado en los conceptos de Inner Circle Trader (ICT). El script está escrito en Python y utiliza bibliotecas populares como pandas y numpy para analizar datos históricos del mercado.

Características
Detección de Patrones ICT: Identifica automáticamente los Order Blocks (Bloques de Órdenes) y los Fair Value Gaps (Vacíos de Valor Justo) para generar señales de trading.

Backtesting: Simula la ejecución de la estrategia en datos históricos para calcular el rendimiento, el PnL (ganancia y pérdida) total, y el número de operaciones.

Notificaciones de Discord: Incluye una función para enviar notificaciones de señales de trading e informes de backtesting a un canal de Discord, si se proporciona una URL de webhook.

Código Modular: La lógica principal está separada en funciones claras (find_order_blocks, find_fair_value_gaps, implement_strategy), lo que facilita la comprensión y modificación.

Advertencia
Este proyecto es estrictamente para fines educativos y de demostración. Los datos de mercado utilizados son simulados, y el bot no ha sido optimizado ni validado para trading en vivo. No lo utilices para operaciones con dinero real. La estrategia ICT es compleja y requiere un análisis de mercado riguroso que este simple simulador no puede replicar por completo.
