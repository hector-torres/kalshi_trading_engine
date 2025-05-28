# README

This collection of notebooks is used to extract and analyze market data from the Kalshi prediction market. 

## Glossary
 - Market: A single binary market.
 - Event: An event is a collection of markets.
 - Series: A series is a collection of related events. 
   - Each event should look at similar data for determination, but translated over another, disjoint time period.
   - Series should never have a logical outcome dependency between events.
   - Events in a series should have the same ticker prefix.