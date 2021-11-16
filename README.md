<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [CryptoChassis Non-Custodial Trading Service](#cryptochassis-non-custodial-trading-service)
  - [Objective](#objective)
  - [Fees and Expenses](#fees-and-expenses)
  - [Principal Strategy](#principal-strategy)
  - [Principal Risks](#principal-risks)
  - [Performance](#performance)
  - [Management](#management)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# CryptoChassis Non-Custodial Trading Service
This summary brochure is designed to provide customers with key information in a clear and concise format. The information presented here is periodically updated to reflect the most recent development. Before you start, please review all the details to understand the risks associated with trading and owning digital assets (a.k.a. cryptocurrencies).

## Objective
* The objective of the trading service is to provide customers with a hands-off approach on trading and owning a diversified portfolio of emerging digital assets. It focuses on screening and selecting digital assets that are on a trajectory of healthy growth and possess steady positive momentum. At the same time, it also allocates a certain portion of the portfolio to several well-established digital assets (e.g. Bitcoin) to mitigate the associated risks.

## Fees and Expenses
* Currently we waive all fees and expenses because the operating cost of running this strategy for one customer is negligibly small.

## Principal Strategy
* The strategy seeks its objective by purchasing and selling spot instruments on the exchange(s) of the customer's choice to establish exposures in healthy-emerging as well as well-established digital assets. It has significant exposure to emerging and frontier digital assets that are on a trajectory of healthy growth and possess steady positive momentum.
* The strategy expects to achieve its goal by periodically comparing the asset compositions of the customer's account under service against the target asset compositions generated from our proprietary portfolio management software and rebalancing the customer's account assets by taking various factors such as the degree of deviation and transaction costs into account. The strategy may also choose to hold a small amount of cash in the form of fiat currencies or stable coins.

## Principal Risks
* In general, digital assets are volatile in values. They are traded 24/7 by global traders and large fluctuations in their prices will translate to large fluctuations in the customer's account values. Digital asset prices may be unpredictably affected by financial regulations, government policies, tax reforms, central bank actions, and global economic conditions.
* Because the strategy allocates a significant portion of its portfolio in emerging digital assets, the values of the account under service can be adversely affected if there is a wide spread downturn in the overall market. Compared to well-established digital assets, these risks can be more significant for emerging digital assets. In addition, markets in emerging digital assets are typically substantially smaller, less liquid and more volatile than the major markets for well-established digital assets.

## Performance
* The following plot provides some indication of the returns and risks of the emerging digital asset trading service. The plot illustrates how the trading strategy's performance has varied from day to day since its inception. Its past performance is not necessarily an indication of future performance. It also shows how the strategy's cumulative returns for the periods indicated compare to those of a portfolio with Bitcoin alone.

<img src="https://marketdata-e0323a9039add2978bf5b49550572c7c-public.s3.amazonaws.com/emerging_asset_historical_performance.png" alt="Reference Historical Performance"/></br>
* There are multiple reasons that a customer account's actual performance is different from what is shown here.
  * The exchange of the customer's choice may not have all of the digital assets that our strategy has identified as emerging assets.
  * The customer's account balance may be too low to have allocations for all of the digital assets that our strategy has identified as emerging assets.
  * What is shown here is for daily portfolio rebalancing. The customer's choice of rebalancing frequency (see [Management section](#Management)) may be different from the frequency of daily rebalancing.
  * The portfolio rebalancing timing for each and every customer may be different to avoid excessive impact on the market which harms the return of each and every customer.
  * The exchange itself imposes transaction fees which reduce the account's values. The strategy may choose to defer certain rebalancing activities to avoid unnecessary transaction fees. In addition, the strategy will make best efforts to utilize maker orders instead of taker orders to reduce transaction costs.

## Management
* The trading service is completely non-custodial. A typical service lifecycle is described as follows.
  * The customer (a.k.a. you) chooses any exchange and creates an account there.
  * The customer creates a pair of API key and API secret and securely shares them with us via any password manager service of your choice (e.g. [LastPass](https://www.lastpass.com/)) or [GPG](https://gpgtools.org/).
  * The customer chooses a desired quote asset (e.g. USD) and chooses a desired rebalance check frequency anywhere between once-every-day to once-every-31-days (which may be changed later on at any time). The trading service will launch an application program for the customer accordingly. The program will periodically check the customer account's asset compositions. Upon checking, it may choose to perform necessary rebalance actions if various conditions are met. It may also choose to defer certain rebalance actions in order to reduce unnecessary transaction costs.
  * The customer may choose to stop the service at any time by giving us a courtesy notification. More importantly, the customer is always in full control of the account and may choose to terminate the service forcibly by deactivating/disabling/deleting the associated API key on the exchange at any time.
