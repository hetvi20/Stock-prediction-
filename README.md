**Stock at that timestamp📈**

Objective
1. Reinforce theoretical concepts covered in lectures.
2. Address a question from a real coding interview related to obtaining output from real-time data streaming.

Tools Required

You may need either the SortedDict from the sortedcontainers package or a heap.

Problem Description
You are given a stream of records about a particular stock. Each record contains a timestamp and the corresponding
price of the stock at that timestamp.
Unfortunately due to the volatile nature of the stock market, the records do not come in order. Even worse, some
records may be incorrect. Another record with the same timestamp may appear later in the stream correcting the price
of the previous wrong record.

Design an algorithm that:

● Updates the price of the stock at a particular timestamp, correcting the price from any previous records at the
timestamp.
● Finds the latest price of the stock based on the current records. The latest price is the price at the latest
timestamp recorded.
● Finds the maximum price the stock has been based on the current records.
● Finds the minimum price the stock has been based on the current records.
Implement the StockPrice class:
● StockPrice() Initializes the object with no price records.
● update(int timestamp, int price) Updates the price of the stock at the given timestamp.
● current() Returns the latest price of the stock.
● maximum() Returns the maximum price of the stock.
● minimum() Returns the minimum price of the stock
