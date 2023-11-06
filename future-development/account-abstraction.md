# Account abstraction

Recently, a technological advancement known as "account abstraction" has matured, promising to significantly enhance the user experience of web3 applications. Account abstraction facilitates the following key use cases:

## Sponsoring Transactions&#x20;

Using Paymasters Traditional Ethereum transactions originate from what's termed an 'Externally Owned Account' (EOA). Controlled by user private keys, EOAs bear the responsibility of paying transaction gas fees. However, situations arise where it's beneficial for another party to cover these fees. This is when the concept of Paymasters comes into play. A Paymaster is a designated entity willing to cover the gas fees for a transaction. This is useful when onboarding new users lacking cryptocurrencies or for dApps aiming to offset transaction costs for their clientele. Through account abstraction, transaction formats can be redefined, enabling gas payments from parties other than the original sender, thus introducing a more adaptable transaction sponsorship model.

## Custodial Transactions&#x20;

Account abstraction paves the way for sophisticated custodial services, granting flexibility in transaction structures and authorisation methods. Users can endorse custodial actions using a basic account, eliminating the necessity for a crypto wallet. Ultimately, the on-chain wallet performs the declaration, linking signatures, product metadata, and creator credentials to the on-chain/smart contract wallet.

## Aggregate Signatures&#x20;

Aggregate signatures can combine signatures from multiple content declarations into one, resulting in notable gas savings and an increased convenience for the users. This means that users can make mass declarations without the need to individually sign each transaction.

## Key Rotation and Recovery&#x20;

Account abstraction offers solutions by supporting the rotation and recovery of cryptographic keys, a prevailing challenge in today's web3 applications. This addresses the single point of failure associated with the management of private keys by incorporating multiple signatories.&#x20;

In essence, account abstraction seeks to significantly enhance the user experience of the Ethereum transaction model, making it more adaptable and inclusive. By deviating from the conventional transaction format, it accommodates a broader spectrum of transaction types and applications, as highlighted above. This innovation promises to simplify blockchain interactions for users, elevating user experience and amplifying the convenience of using applications like the Liccium app.&#x20;

{% hint style="info" %}
References Account Abstraction Part 2: Sponsoring Transactions Using Paymasters, [https://www.alchemy.com/blog/account-abstraction-paymasters](https://www.alchemy.com/blog/account-abstraction-paymasters)&#x20;

Account Abstraction Part 4: Aggregate Signatures, [https://www.alchemy.com/blog/account-abstraction-aggregate-signatures](https://www.alchemy.com/blog/account-abstraction-aggregate-signatures)
{% endhint %}
