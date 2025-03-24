Ticker ASML
ISIN USN070592100
CUSIP N07059210

Ticker MICROSTRATEGY INCORPORATED 0.0% 2029
ISIN US594972AR21




TITLE ISIN-Salt Proxy Factory
PROBLEM STATEMENT
• Duplicate asset proxies creating compliance risks
• Unpredictable addresses via CREATE
• Gas waste from redundant asset onramping 
• Off-chain legacy integration 
• Non-standard identifiers risking collisions
SOLUTION
• Deterministic salt via keccak256(ISIN)
• CREATE2 deployment for precomputable addresses
• Duplicate deployment check with revert
• Off-chain address predictability enabled
• Standardized ISIN ensures global uniqueness
