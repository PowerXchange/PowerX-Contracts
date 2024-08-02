# PowerX-Contracts

contract address:    0x94CEf49053Af56beCAB11EaB12860D0c359EDa51

# Future contract enhancements in progress...

- ERC-721 Standard: Energy credits are now ERC-721 tokens, enhancing interoperability.
- Role-Based Access Control: Only the contract owner can create energy credits.
- Price Update Mechanism: Producers can update the price of their unsold credits.
- Marketplace Functions: Functions to list available credits and get detailed information.
- Commission Fee: Introduced a commission fee for each sale.

# Further Enhancements Explained
Metadata Storage and Update:

Added updateTokenURI to allow producers to update the metadata URI of their energy credits.
Events for Enhanced Tracking:

Added more specific events like CreditTransferred and CommissionFeeUpdated for better traceability.
Access Control:

Introduced a modifier onlyProducer to ensure that only producers can update or transfer their credits.
Pausing Contract:

Integrated the Pausable contract from OpenZeppelin to allow pausing/unpausing the contract for security.
Commission Fee Adjustment:

Added an event CommissionFeeUpdated for transparency when changing commission fees.
Energy Credit Transfer:

Added transferEnergyCredit to allow producers to transfer unsold credits.
Gas Optimization:

Implemented minor improvements, such as reusing storage variables to reduce gas costs.
