[toc]

# News

Crude oil price goes up again, for the first time in the interest raising cycle.

# Lecture

### Payment for order flow

Pyment for Order Flow is a practice in which a brokerage firm receives compensation for directing client trade orders to a particular market maker or trading venue, rather than directly executing the trade themselves. It allows brokers to offer "commission-free" trade to individual investors. For example, Robinhood directs its client's orders to Citadel, reciving million dollars per month (open data).

### Lit orders and hidden orders

Lit orders are orders whicha re visible on the public order book. They provide transparency by displaying the price and size to all market participants. Hidden orders ar enot displayed on the public order book. They are used by traders who do not want to reveal their trading intentions, often to avoid moving the market price. 

**Penalty**: Hidden orders still interact with visible orders, but are prioritezed lower than lit orders or cost more commission.

**Min-Display Amount**

Some exchanges require the minimum amount of the order that should be displayed on the public order book. For example, CME.

### Iceberg orders (crypto exchanges also have this function)

Only the "tip" of the iceberg order, a small portion of the total order size, is visible in the market's order book. Once the visible part of the order is executed, another portion becomes visible, and this cycle continues until the entire order is filled.

### Level of Data

1. Level 1 Data: provides only the BBO and the last price. The most basic.
2. Level 2 Data: lists multiple layers of bid and ask prices. Shows the number of shares or contracts available at each price level.
3. Level 3 Data: also known as the Market Maker's Screen, this level is generally reserved for market makers and provides the ability to enter quots and executes orders. It contains each individual order. It might also include identifiers for active market participants (using coded symbols not the real company names) . Sometimes, it comes with subscription fees.

### Pegged Order

Type of order that automatically adjust its price based on a reference price. For example. the order could be pegged to the best bid or best ask price. However, Binance and other crypto exchanges do not have this order type.

### Spoofing (Illegal in U.S.)

Spoofing is a manipulative practice. It places orders with the intent to cancel them before they're executed. The goal is to deceive other market participants by creating an artificial signals. An example as follows:

A trader places a buy order several layers from the best bid. Then, it places a large sell order at the same distance or even further away. The large order can create an illusion of downward pressure. Then probably, other buyers might cancel their bid orders. Your lower bid order is now the best bid.

### Other Order Types

- FOK/AON
- FAK/IOC
- Post only
- Midpoint Eligible
- Intermarket Sweep Orders
- Peg Orders
- IEX D-Peg (crumbling quote)