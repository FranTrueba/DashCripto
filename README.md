Proyecto de Criptomonedas conectado a la API de Kraken.

El código de la aplicación se encuentra en el apartado de CriptDash.py

El primer paso del proyecto es la instalación de librerías para poder llevar a cabo su ejecución.
    - pandas
    - krakenex
    - Streamlit
    - plotly
    - pykrakenapi

Se genera un bucle "FOR" para seleccionar solo los pares de criptomonedas que deseamos ver en la conversión, ya sea dólares (USD) o ethereum (ETH).

Se genera una función para el cálculo del RSI


Se gráfica la criptomoneda
fig = go.Figure(data=[go.Candlestick(x=df['dtime'],
									 open=df['open'],
									 high=df['high'],
									 low=df['low'],
									 close=df['close'])])
                   
Se plotea la gráfica el OHLC, la media móvil, el RSI
