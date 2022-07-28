# kafka_streaming_analytics
e-commerce system places customer orders into kafka topic: streaming.orders.input 

INPUT: the orders are in JSON format: (orderID, product, quantity, price)  

GOAL:  analyze orders every five seconds to compute total product value as: (quantity*price)  aggregated across time window

populate summaries to MariaDB table: order_summary
