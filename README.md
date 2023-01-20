# [WhaleBooks](https://whalebooks.com/) - Release Notes
NOTE: To get notified quickly about new releases and other important information join our [WhaleBooks Telegram channel](https://t.me/whalebooks).
   
## Version 2023.01.201623   
   
**The Binance API prefers WhiteListing IP addresses. Otherwise, it will limit the key validity period. To authenticate access from WhaleBooks.com, use these IP addresses 104.248.131.14 and 139.59.136.33. Please note that IP addresses may change over time. We will try to find a solution to prevent this from happening.**   
   
### New Features   
ETD-745 [organizations] Accounting software settings.   
   
### Bug Fixes   
ETD-768 [containers] Coinbase & Binance CSV - import ignores transactions wrapped "".   
ETD-777 [organizations] Date of creation of the Organization.   
ETD-801 [portfolio] Stake / Other Rewards does not show in closed positions of trades when taxed On Acquisition.   
ETD-803 [connectors] API Connector does not return an error message in the synchronization log.   
ETD-804 [connectors] Coinmate API - can not download last tx timestamp Index 0 out of bounds for length 0.   
ETD-809 [organizations] The newly created user will be shown the default settings in the wrong priority and will not get to Walkthrough.       
   
## Version 2023.01.171755   
   
**It is recommended to re-synchronize the Coinmate API connector. Fixed a bug with the fee currency causing incorrect balances for your assets on previously downloaded transactions.**   
   
### New Features   
   
ETD-651 [containers] Export container to WhaleBooks format.   
   
### Improvements   
   
ETD-779 [containers] Binance CSV - Simple Earn.   
ETD-786 [portfolios] Deactivate switch Conversion of pairs to accounting currency for newly created portfolios.   
   
### Bug Fixes   
   
ETD-730 [containers] Errors when deleting and resynchronizing a container.   
ETD-789 [portfolios] Improvement mobile view of portfolio.   
ETD-795 [portfolios] Closed positions with zero amount at stake rewards and tax time On Acquisition.   
ETD-798 [portfolios] Warning message is not displayed when validating a transferred negative portfolio balances.   
ETD-800 [connectors] CoinMate API incorrectly identifies fee currency.   
   
## Version 2023.01.131629   
   
**This release includes corrections to some known portfolio errors in relation to the timing of taxation of rewards.**   
   
### Improvements   
   
ETD-692 [connectors] Use the Transaction History endpoint for the CoinMate API to support new transaction types.   
ETD-774 [containers] Binance CSV - Transaction type DISTRIBUTION identify as REWARD.   
ETD-775 [containers] Binance CSV - Transaction type FIAT DEPOSIT / WITHDRAWAL identify as DEPOSIT / WITHDRAWAL.   
ETD-791 [transactions] Remove the option to add a REBATE subtransaction from the transaction listing.   
   
### Bug Fixes   
   
ETD-778 [containers] The list of accounts is not loaded by opening the container detail.   
ETD-782 [portfolio] Correction of the calculation of rewards on the front end of the portfolio.   
ETD-784 [rate-server] Server returns error when downloading new currency rates.   
ETD-785 [transactions] The transaction detail is closed when I click on help.   
ETD-788 [frontend] Some buttons only respond on the second click.   
ETD-792 [transactions] The currency of the bound transaction does not respond to a change from the transaction detail.   
ETD-793 [portfolios] Unclear decimal point operations on charges.   
ETD-796 [transactions] Rewards do not call for a unit rate requirement.   
   
## Version 2023.01.071155 
   
**The main innovation of this version is the setting of the decisive moment of taxation of the received reward. We distinguish between taxation On Acquisition and On Sale. As it is not clear by law when rewards are taxed, the default value is set On Acquisition. Change the preference in Organization settings > Tax rules > Rewards. This version may contain errors that we will fix later.**   

### New Features   
ETD-174 [connectors] Kucoin.com API & CSV support.   
ETD-667 [organizations] Timing of taxation of rewards.   
ETD-673 [transactions] Stake Rewards / Other Rewards in taxation On Acquisition.   
ETD-678 [portfolios] Preference for taxation of Rewards.   
ETD-680 [transactions] Acquisition Price of Reward transactions.   
ETD-684 [portfolios] Portfolio Summary and includes rewards.   
   
### Improvements   
ETD-110 [transactions] Evidence time of recording new records.   
ETD-464 [transactions] In connected transfers we should display in summary target asset account name.   
ETD-621 [reports] Accounting report - Staking/other rewards.   
ETD-633 [organizations] Chart of Account - new account for rewards.   
ETD-658 [containers] WhaleBooks format 3.2 CSV update.   
ETD-663 [portfolios] Improving the relevance of portfolio sharing dialogue.   
ETD-681 [portfolios] Taxation of other rewards in trades.   
ETD-682 [help] OpenNode CSV support.   
ETD-683 [help] [WhaleBooks format 3.2](https://whalebooks.com/help/csv#whalebooks).   
ETD-686 [reports] Taxation of Rewards and Portfolio Summary.   
ETD-688 [organizations] Chart of Account - new accounts USA.   
ETD-689 [reports] Accounting report - Staking/other rewards - On Sale.   
ETD-692 [connectors] Use the Transaction History endpoint for the CoinMate API to support new transaction types.   
ETD-695 [portfolios] Market value of STAKED funds in the portfolio chart.   
ETD-696 [asset accounts] Adding an action to copy a crypto address.   
ETD-710 [reports] Accounting Report - format 1.1   
ETD-712 [asset accounts] Adding transaction note and transform export CSV to XLSX format.   
ETD-714 [reports] Accounting report - Unbounded FEE - Chart of account.   
ETD-718 [users] In the new password settings dialog, add password verification input.   
ETD-721 [connectors] Save hash of blockchain (BTC, ETH, LTC) transaction.   
ETD-722 [connectors] Quick access to connector settings.   
ETD-727 [help] KuCoin screenshots.   
ETD-733 [transactions] Minor improvements to transaction details.   
ETD-735 [organizations] Saving a selected preference for using analytics sub-accounts.   
ETD-739 [organizations] Sorting the list of accounts by account number.   
ETD-741 [organizations] Adding FIAT currency to account 568 - Unbound Fees.   
ETD-743 [pairs] Add ATOM to quote currency.   
ETD-752 [help] Gate.io logo   
ETD-756 [reports] Specify tax report terminology depending on the type of tax entity.   
ETD-758 [organizations] Update Sub-Accounts list.   
ETD-767 [pairs] Support for new symbols 22/12.   
ETD-773 [pairs] Add GRT, AMP, NEAR to quote.   
   
### Bug Fixes   
ETD-291 [Reports] Accounting report - Unbound fees.   
ETD-676 [containers] CSV file case sensitivity in file format.   
ETD-691 [pairs] To search for pairs in filtering it is necessary to enter a space around the slash.   
ETD-693 [connectors] Starting automatic API synchronization does not work correctly.   
ETD-700 [reports] TAX Statement - invalid counting 31.10.2022.   
ETD-701 [transactions] Unpaired transaction is not created.   
ETD-703 [administration] Pagination of the user listing.   
ETD-704 [organizations] Duplications in list of members of the organization.   
ETD-705 [support] The attachment from the contact form is not available on the link in the support ticket.   
ETD-706 [frontend] Minor bug fixes.   
ETD-707 [reports] Bounded fee for deposit/withdrawal.   
ETD-708 [organizations] Updating the end date of the trial version is not working.   
ETD-713 [reports] Tax Statement - bounded fee make incorrect calculation of cost/revenues.   
ETD-715 [frontend] Multiple minor bug fixes & changes.   
ETD-716 [connectors] Loading separate outgoing transactions on the BTC and LTC Blockchain.   
ETD-717 [organizations] The organization member edit dialog does not contain an active role.   
ETD-725 [portfolio] Copying AVCO portfolio balances returns an error.   
ETD-729 [organizations] White screen when inviting a member of the organization.   
ETD-731 [portfolio] Minor improvements taxation of rewards.   
ETD-736 [portfolio] When Tax Residency is Other, the portfolio doesn't return any Accounting Currency.   
ETD-738 [reports] Quantity rounding and Bound Fees in the Accounting Report.   
ETD-754 [connectors] Coinbase API timeout if there are too many wallets in the account.   
ETD-771 [portfolio] Undefined pair when copying AVCO portfolio balances.   
ETD-772 [containers] API containers not synchronizing.   
   
## Version 2022.11.091229   
   
**This version migrates the database to the new type. You can get a faster response. Focused performance optimizations will be delivered later. If you find bugs, please let us know.**   
   
## Version 2022-10-19T0935   
   
**This version migrates the backend to the new framework. You can get a faster response. If you find bugs, please let us know.**   
   
**The new version of the [WhaleBooks Universal Format 3.2](https://whalebooks.com/help/csv#whalebooks) includes new Staking and other rewards transaction types. It adds new columns: NOTE, LABELS.**   
   
### New Features   
ETD-636 [containers] OpenNode CSV Support.   
   
### Improvements   
ETD-672 [transactions] Changes in transaction statement columns.   
ETD-668 [connectors] WhaleBooks format 3.2 API update.   
ETD-658 [connectainers] [WhaleBooks format 3.2 CSV update](https://whalebooks.com/help/csv#whalebooks).   
ETD-472 [my profile] Translation of the application language selection.   
ETD-457 [transactions] Marking of the bound subtransaction on the transaction statement.   
   
### Bug Fixes   
ETD-670 [organizations] Capital letters in the address of a new member's invitation.   
ETD-655 [reports] Tax Statement - Short position transfer to long position and vice versa.   
ETD-654 [reports] Tax Statement - Short position tax base INCL. fee.   
ETD-645 [asset accounts] Edit bulk address entry on account entry.   
ETD-644 [transactions] Incorrect pagination during filtering.   
ETD-594 [reports] Rebate & fee in third-party wrongly calculated in Reports.   
ETD-574 [frontend] Invalidating the navigation cache after adding an organization.   
   
## Version 2022-10-05T1201   
   
### Improvements   
ETD-665 [containers] Coinbase CSV SEND transaction.   
ETD-660 [portfolios] Activate calculation switch for portfolios with inactive calculation.   
ETD-650 [organizations] Access to organization settings from the menu.   
ETD-637 [help] Add Accounting Report to Report Help.   
ETD-629 [transactions] Arrangement of controls and new style of add transaction button.   
ETD-557 [reports] Add TAX Rule Sets.   
ETD-556 [portfolio] Add TAX Rule Set name.   
ETD-207 [containers] CoinMate CSV reward for referrals.   
   
### Bug Fixes   
ETD-624 [organizations] Disable editing and deleting the default Rule Set in the Other residence.   
ETD-608 [VR] Portfolio does not show results.   
ETD-573 [mobile] Required input.   
   
## Version 2022-09-23T1320   
   
### Improvements   
ETD-424 [connectors] Binance API CONVERT transaction.   
   
### Bug Fixes   
ETD-661 [portfolios] Shared portfolio returns an error.   
ETD-647 [reports] Tax Statement is not generated.   
ETD-640 [containers] BitFlyer CSV format update.   
ETD-639 [connectors] CoinMate API Trying to import too many transactions.   
ETD-603 [reports] Short positions changes in Tax Statement.   
   
## Version 2022-09-15T1146   
### New Features   
ETD-607 [containers] Support Convert transactions in Coinbase CSV. (The Coinbase API does not have a convert enpoint!)   
   
### Bug Fixes   
ETD-614 [portfolios] Staking balances take over to the new portfolio.   
   
## Version 2022-09-08T142
   
### A major summer update!   
   
You can now record **STAKE** and **STAKE REWARDS** taxation with us. Portfolio will display the locked STAKING in a chart. We have a new widget for Staking and Rewards!   
   
We are adding new transaction types: **REWARD, AIRDROP, EARN, FORK.** All of them work as rewards and their taxation falls into the group of trades.   
   
The TAX REPORT will now calculate a separate TAX BASE for trades and separately for staking. TAX RULES can be applied to everything!   
   
The pop-up for pulling and portfolio management now responds to the TAX RULES. For this, TAX RESIDENCY and TAX SUBJECT are now mandatory. If you don't have it set up for an organization, it will be required as a mandatory pop-up.   
   
Due to the large number of changes, new errors may arise. If you will be part of any bugs, please email us. We are working on a fix!   
   
CSV and API imports may now not support the new transaction types. Support will be added on an ongoing basis. If you are unable to load your data, please email us. We will be happy to add support for other formats.   
   
### New Features   
ETD-630 [transactions] Support for new transaction types - REWARD, AIRDROP, EARN, FORK.   
ETD-622 [reports] Activity statement - Staking / other rewards.   
ETD-618 [portfolio] Staking Widget + Portfolio Chart.   
ETD-609 [transactions] Support for new transaction types: STAKE,  UNSTAKE,  STAKE REWARD.   
ETD-596 [brand] Updating the application style.   
ETD-561 [organizations] TAX Residency requiret Pop-up.   
ETD-555 [portfolios] TAX Rules in a Portfolio setting.   
   
### Improvements   
ETD-627 [containers] Coinbase CSV header format update.   
ETD-626 [transactions] Correct transaction names.   
ETD-616 [connectors] Kraken API add support for staking transactions. (Only last 90 days!)   
ETD-542 [transactions] A transaction with quantity = 0 is an ignored transaction.   
ETD-229 [connectors] API Binance STAKING a 'distribution' transactions types.   
ETD-162 [containers] Coinbase CSV EARN transactions support.   
   
### Bux Fixes   
ETD-619 [connectors] Coinmate API does not import crypto withdrawal transactions.   
ETD-615 [portfolio] Error saving portfolio after loading balances + negative fiat position.   
ETD-611 [connector] WhaleBooks universal API connector integration error.   
ETD-605 [containers] WhaleBooks CSV format imports BUY / SELL transaction with incorrect pair notation.   
   
## Version 2022-08-12T1417   
### New Features   
ETD-596 [brand] Updating the application style.   
ETD-593 [brand] TOP banner update at public homepage.   
ETD-490 [accounting] Taxation of crypto/crypto.   
   
### Bux Fixes   
ETD-592 [brand] Small content updates.   
ETD-578 [plugins] Failing connectors tests.   
ETD-550 [reports] TAX Report results don't match portfolio results due to short positions from previous accounting periods.   
   
## Version 2022-08-08T0858   
### Improvements   
ETD-597 [my profile] GoogleAuth library update.   
   
## Version 2022-08-03T1333

**We are happy to announce that we are now the [WhaleBooks](https://whalebook.com).**   
Although it's been a good time under the EveryTrade name, it's time to move on to a more emotional branding that reveals the essence of the product.

**What is [WhaleBooks](https://whalebook.com)?**   
It's a powerful accounting and tax tool for companies and traders who operate with cryptocurrencies.   
Do you see the **green visor** on the logo? It's a tribute to accountants who spent days and nights doing their best to make companies capable of planning and operating finance well. They used to wear **green visors** to protect their eyes from the bright light. And yes, it's a cool item.   
   
[WhaleBooks](https://whalebook.com) is able to transform your crypto flow to required reports and protect you from uncertainty in the crypto ocean.   
**More functions are about to come.**   
   
### New Features   
**ETD-587 [brand] Rename EveryTrade to WhaleBooks.**   
   
### Improvements   
ETD-591 [brand] Transaction e-mails rebranding.   
ETD-590 [brand] Reports rebranding.   
ETD-589 [brand] Name change information pop-up.   
ETD-588 [brand] EveryTrade logo change to WhaleBooks.   
   
### Bux Fixes   
ETD-595 [containers] LBTC currency (BTC) is not supported in Expense Currency field of GB CSV.   
ETD-586 [reports] Rebate in crypto wrongly calculated in Reports.   
   
## Version 2022-08-02T0918   
   
**Tax Rules can be found in Organizations > Organization detail > Tax Rules. If you cannot find your Tax Residency, select Other and make your own settings. Always make sure that the rules you select match your legislation. New Residencies and Tax Rules will be added over time.**   
   
### New Features   
ETD-568 [portfolio] Tax Base.   
ETD-567 [containers] Coinbase Advanced Trade CSV support.   
ETD-560 [reports] Add TAX Rules to PDF reports.   
ETD-539 [organizations] TAX Residency preferences & Tax Rules.   
ETD-489 [accounting] Time test.   
ETD-376 [connectors] Blockchain SegWit address support.   
   
### Improvements   
ETD-583 [reports] Rename the Tax Statement in Accounting Currency report to Tax Statement.   
ETD-582 [portfolio] Innactivate the Convert Pairs to Accounting Currency switch.   
ETD-580 [containers] ET doesn't parse properly LTC/USD and LTC/EUR pairs.   
ETD-575 [reports] Adapting the TAX Statement report to the TAX Rules.   
ETD-571 [reports] Footer - HIFO & LIFO explanation.   
   
### Bux Fixes   
ETD-569 [reports] Bad transactions merge in Tax Report.   
ETD-565 [reports] Fee in crypto wrongly calculated in Reports.   
ETD-562 [connectors] BTC Blockchain connector downloads duplicate transactions.   
ETD-56 [connectors] Blockchain BTC limited API response too many txs.   
   
## Version 2022-07-21T1238   
**The Chart of Accounts and the Accounting Report are now available to everyone! The Chart of Accounts settings can be found in the Organization detail.**   
   
### New Features   
ETD-538 [containers] Add SimpleCoin CSV import.   
   
### Improvements  
ETD-564 [help] Add SimpleCoin exchange logo.   
ETD-563 [reports] Period restriction when exporting an Accounting report.   
ETD-554 [organizations] The Chart of Account requires Tax Residency.   
ETD-551 [containers] Coinbase Pro update CSV format.   
   
### Bux Fixes   
ETD-566 [transactions] Improvements in transaction details.   
ETD-559 [organizations] Inviting a member of an organization with admin rights returns an error.   
ETD-553 [portfolio] Exclude the current portfolio from the balance copy dialog.   
ETD-552 [browsers] CSV import does not work in Firefox browser on Windows OS.   
   
## Version 2022-07-11T1402   
**The Chart of Accounts and the Accounting Report will be available to users later this month.**   
   
### New Features     
ETD-549 [pairs] Add new symbols 22/07.   
AIR, AMM, BCPT, DF, DOV, GAS, KIN, LUNC, NWC, ONG, ONT, VEN, VET, VTHO, WETH, GXC   
ETD-540 [reports] Accounting Report.   
ETD-493 [organizations] Chart of Account.   
ETD-492 [accounting] Computation methods LIFO, HIFO.   
ETD-448 [organizations] Members of the Organization.   
ETD-252 [containers] KRAKEN Ledgers CSV import.  
   
### Improvements   
ETD-543 [components] The This Portfolio option in the calendar component does not return any periods to the input.   
ETD-534 [accounting] Prioritising the search for a certified accountant.   
ETD-505 [portfolio] Accounting currency input don't search and alphabet sort by currency.   
ETD-501 [portfolio] Sorting the statement of asset accounts in subgroups by currency.   
ETD-476 [containers] Support for Ignored transactions in CSV containers.   
ETD-474 [organizations] Welcome to EveryTrade pop-up.   
   
### Bux Fixes   
ETD-548 [transactions] Pair search in bulk operation dialog does not work.   
ETD-547 [organizations] The user does not have permissions to manage members.   
ETD-545 [portfolio] Loading portfolio balances does not load fees correctly.   
ETD-541 [mobility] Mobile view fixes.   
ETD-537 [containers] CSV import takes too long.   
ETD-266 [connectors] Mining fees associated with Withdrawals or Deposits are not imported by blockchain connectors.   
   
## Version 2022-06-16T1228   
### New Features   
ETD-531 [pairs] Add new symbols 22/06.   
BICO, CITY, GTC, PYR, XDC, GAL   
   
### Improvements   
ETD-514 [portfolio] Currency addition for initial portfolio balances.   
   
### Bux Fixes   
ETD-530 [portfolio] New empty portfolio returns error 500.   
ETD-527 [containers] CSV in ET format fails on unexpected data.   
ETD-526 [datamanager] Cannot save connector name change.   
ETD-522 [connectors] Optimizing select query for Asset Accounts and Pairs bookmarks.   
ETD-497 [portfolio] Internal Error 500 without conversion of pairs to accounting currency.   
ETD-496 [portfolio] After changing transactions, the portfolio does not restore the cached results.   
ETD-495 [fee] Portfolio without conversion of pairs to accounting currency does not calculate the crypto/crypto exchange fee on the portfolio page.   
ETD-384 [containers] ROW_PARSING_FAILED 'Date(UTC)'.   
   
## Version 2022-06-09T1146 
### New Features   
ETD-393 [containers] Binance CSV Transaction History.   
   
### Improvements   
ETD-513 [transactions] Quick deletion of input content.   
   
### Bux Fixes   
ETD-528 [connectors] Unreliable linking of accounts to the connector.   
ETD-524 [reports] Buying FEE for AVCO wrongly in Real P/-L immediately.   
ETD-509 [reports] Buy transaction - realized profit/loss in the TAX report.   
ETD-507 [reports] Tax Statement in Accounting Currency - correct Totals for type of Immediate fees.   
ETD-503 [reports] Correct amount of Immediate fees.   
ETD-494 [accounting] The search for a certified accountant ends in error.   
   
## Version 2022-06-01T1157   
### Improvements   
ETD-502 [reports] Unifi terminology fee application Fully > Immediate.   
ETD-488 [portfolio] Portfolio calculation performance optimization.   
ETD-450 [transactions] Rounding of decimals for FIAT.   
ETD-410 [connectors] Optimization of connector detail loading.   
   
### Bug Fixes   
ETD-518 [portfolio] Zero market price portfolio with open future period.   
ETD-512 [pairs] Improving input pair performance in pop-up bulk operations.   
   
## Version 2022-05-25T0916   
### New Features   
ETD-477 [pairs] Add new currencies 22/05.   
APE, BABY, CFI, CVC, EBST, EXP, HT, MXC, OCN, SRN, SUPER, UBQ, XEL   
   
### Improvements   
ETD-454 [portfolio] A clickable link to the data manager from an empty portfolio.   
ETD-421 [reports] Account Statemets report translations.   
   
### Bug Fixes   
ETD-487 [organizations] Changing Organization is not reflected in the asset accounts page.   
ETD-486 [organizations] Useless scrollbar in organization detail.   
ETD-461 [portfolio] Values of initial asset account balances in non-edit mode are not formatted.   
ETD-459 [pairs] Pair selection interface performance optimization.   
ETD-453 [portfolio] Limitation of writing to the Accounting period input.   
ETD-395 [transactions] For BUY / SELL transactions, remove pairs with the same BASE / QUOTE.   
ETD-348 [accounts] Portfolio tags don't filter asset account transactions.   
ETD-301 [reports] Correction of diacritics in report file names.   
ETD-136 [containers] Diacritics in CSV file name.   
   
## Version 2022-05-12T1136   
### New Features   
ETD-447 [organizations] Organization settings.   
ETD-252 [containers] KRAKEN ledgers CSV import. Only DEPOSIT & WITHDRAWAL transactions.   
   
### Improvements   
ETD-471 [asset acccounts] Adding XPUB to the input name of the asset account address.   
ETD-428 [portfolio] For Walkthrough Portfolio activate conversion to Accounting currency.   
   
### Bug Fixes   
ETD-473 [transactions] Filter content position.   
ETD-470 [transactions] Invalid action from address field name.   
ETD-469 [reports] Confusing boxes with FIAT summarization for end-users.   
ETD-468 [reports] Adjust reporting numbers under columns Revenue and Cost for opening balance.   
ETD-466 [connectors] Changing the connector name disconnects asset accounts.   
ETD-463 [buckets] Typos and formatting issues in dialog when connecting transfers.   
ETD-462 [reports] CSV report of asset accounts has problems with czech letters.   
ETD-459 [pairs] Pair selection interface performance optimization.   
ETD-456 [transactions] Remove input addresses in BUY / SELL transaction detail.   
ETD-451 [organizations] List of organizations in main menu isn't sorted alphabetically.   
ETD-420 [portfolio] Error copying AVCO balances without portfolio time limitation.   
ETD-395 [transactions] For BUY / SELL transactions, remove pairs with the same BASE / QUOTE.   
ETD-266 [connectors] Mining fees associated with DEPOSIT or WITHDRAWAL aren't imported by blockchain connectors.   
   
## Version 2022-05-07T0651      
### Bug Fixes   
ETD-460 [portfolio] Setting initial pair balances doesn't work.   
   
## Version 2022-05-06T1235   
### New Features   
ETD-446 [organizations] Management of Organizations.  
ETD-445 [navigation] New menu item Organizations.  
ETD-435 [reports] New report: TAX Statement in Accounting Currency. (Only available when calculating the portfolio in accounting currency.)  
   
### Improvements   
ETD-444 [portfolio] Accounting currencies flags.   
ETD-443 [accounts] Rename "Accounts" to "Asset Accounts".   
ETD-437 [reports] Edit interface page Reports.   
   
### Bug Fixes   
ETD-433 [connectors] Some API connectors do’nt do automatic synchronization.   
ETD-425 [FEE] Under portfolio the buy fee not included in sumarization.   
ETD-412 [reports] Confusing boxes with FIAT summarization for end-users.   
ETD-411 [reports] Adjust reporting numbers under columns Proceeds and Cost basis.   
ETD-381 [reports] Totals for realized profit/loss for use in tax return.   
   
## Version 2022-04-27T1616  
This update brings many new pairs, fixes for API connectors and CSV imports. To maintain the health of your portfolios, we recommend performing manual maintenance. Re-sync your API connectors, and re-import your CSVs. Make sure your portfolios have Accounting Currency Conversion turn on. Delete and reload new opening balances for pairs and accounts in your portfolios. Load the balances in the direction from the oldest portfolio to the newest. Your results may change. Contact our support whenever you need help.  
  
### New Features  
ETD-436 [pairs] Add new crypto quotes 22/04.  
ADA, CRO, FRAX, HUSD, LINK, LTC, LUNA, LUSD, MANA, SOL, TUSD, USDN, UST  
ETD-434 [portfolio] Extension of the list of accounting currencies.  
ALL, ARS, BAM, BGN, BRL, BSD, BYN, CLP, CNY, COP, CRC, CUP, DKK, ECS, HRK, HUF, CHF, ILS, INR, ISK, JMD, JPY, KZT, MDL, MKD, MXN, NOK, PEN, PLN, RSD, SEK, TRY, UAH, VEF, ZAR  
ETD-419 [pairs] Add new currencies 22/04.  
1ST, ACH, AE, AEON, ALPACA, ANY, APE, APPC, AR, ARN, ARRR, ASR, AST, ATLAS, AUTO, BAR, BAY, BC, BCD, BCHA, BCN, BEPRO, BIA, BSW, BUY, CFX, CHAT, CHESS, CLOAK, CMT, CND, CSX, CVC, CWAR, DCT, DEXE, DGD, DLT, DNXC, DPI, DUSK, EDO, EMC2, EPS, EQZ, EVX, FARM, FIS, FLM, FRAX, FTX, FUEL, GAME, GEO, GMT, GO, GVT, HARD, HC, HORD, HUSD, INS, ISP, KCS, KDA, LEND, LUN, LUSD, MCO, MDA, MDX, MONA, MORE, MTH, MXM, NAS, NCASH, NXT, OAX, OG, OK, OST, PAY, PHB, POA, POE, POLS, PPT, PTOY, QLC, QRL, QSP, QWARK, RAY, RCN, RDD, RIF, RNDR, ROOK, RUB, SANTOS, SNGLS, SNM, SNT, SOLR, SPELL, STOPELON, STORM, STPT, SUB, SUPER, TNT, TRIBE, TRY, TUBE, UNFI, USDN, VIB, VIBE, VIDT, VRC, WIN, WRX, XCP, XTZ, XYM, ZCL  
  
### Improvements  
ETD-430 [portfolio] Edit the appearance of the portfolio.  
ETD-418 [help] Exchanges logos update.  
ETD-416 [connectors] Renaming OKEX to OKX.  
ETD-283 [containers] Add Bitstamp CSV support for DEPOSIT and WITHDRAWAL transactions. (Re-import your CSVs)  
  
### Bug Fixes  
ETD-438 [connectors] Bitstamp API downloads duplicate DEPOSIT & WITHDRAWAL transactions. (Re-sync your APIs)  
ETD-432 [connectors] Binance API duplicates transactions. (Re-sync your APIs)  
ETD-431 [connectors] Binance API does'nt download DEPOSIT & WITHDRAWAL older than 90 days. (Re-sync your APIs)  
ETD-423 [connectors] Coinbase Pro API reads pending transactions. (Re-sync your APIs)  
ETD-422 [portfolio] DOP accounting currency doesn't work.  
ETD-417 [portfolio] Scroll bar in the chart & crypto positions.  
ETD-415 [connectors] Kraken API "EGeneral:Internal error". (Re-sync your APIs)  
ETD-414 [connectors] Coinbase API "Unable to acquire JDBC Connection". (Re-sync your APIs)  
ETD-192 [connectors] Coinbase Pro API fix for DEPOSIT & WITHDRAWAL transaction downloads. (Re-sync your APIs)  
   
## Version 2022-04-01T0824   
### Improvements   
ETD-407 [reports] Third-party fee in reports and portfolio calculation.   
ETD-404 [containers] Enable third currency fee on CSV import.   
ETD-402 [reports] Delete lines in the report where 0 appears in all columns.   
   
## Version 2022-03-30T1523   
### Improvements   
**Please follow the instructions in the newsletter on how to properly migrate to the new features.**   
ETD-405 [account] Exclude all FEE transactions from the transaction limit by subscription type.   
ETD-397 [pairs] Extending the list of cryptocurrency pairs in BASE with QUOTE /BUSD, /USDT, /USDC, /DAI, /XRP. (We recommend re-synchronizing the API connectors or re-importing the CSV files. For API connectors with downloaded pairs, add new pairs.)   
ETD-390 [portfolio] Copying balances reflect DEPOSIT and WITHDRAWAL transactions. (We recommend deleting the portfolio balances and reloading them from the previous period.)   
ETD-394 [connectors] Optimizing the mobile API connector interface.   
ETD-391 [portfolio] Account sorting in balance copying.   
ETD-346 [connectors] Kraken API optimization "EAPI:Rate limit exceeded" + download address from DEPOSIT & WITHDRAWAL transactions. (Operation of overloaded connectors will be automatically bypassed.)   
ETD-286 [accounts] Quick account switching. (From the account details.)   
   
## Version 2022-03-29T1209   
### New Features   
**Please follow the instructions in the newsletter on how to properly migrate to the new features.**   
ETD-398 [portfolio] Switch to convert traded pairs to accounting currency.   
ETD-396 [connectors] Allow Binance API & CSV to load a fee in a third trade currency.   
ETD-392 [transactions] Third currency trade FEE transactions.   
ETD-305 [transactions] Last used pairs.   
   
### Improvements   
ETD-401 [help] EveryTrade CSV 3.1.1 specification expanded to include third currency fees.      
   
## Version 2022-03-24T0856   
### Improvements   
ETD-400 [reports] Amount of fee in the currency of the trade.   
ETD-399 [reports] Rename transactions of initial balance as opening balance. Originally Deposit.   
ETD-370 [connectors] Bittrex API v3 support - correct reporting of API invalid key to the log.   
   
### Bug Fixes   
Minor improvements and corrections to changes in the previous release.   
ETD-357 [portfolio] Invalid value for EpochDay - Error when copying FIFO portfolio balances.   
   
## Version 2022-03-22T1454   
### New Features   
ETD-329 [pairs] Convert pairs to accounting currency. (Requires manual activation in portfolio settings. More information in the newsletter.)   
ETD-310 [portfolio] Last used portfolio.   
   
### Improvements   
ETD-370 [connectors] Bittrex API v3 support.   
ETD-96 [pairs] Closing crypto positions.   
   
### Bug Fixes   
ETD-389 [transactions] Division 0 in transaction detail.   
ETD-387 [transactions] Transaction filter is active but shows no entries.   
ETD-358 [fee] Under portfolio the sell fee not recognized.   
ETD-328 [reports] Incorrect currency and quantity is displayed for deposits and withdrawals in one of the reports.   
ETD-327 [portfolio] Your Fiat assets are ignoring deposits and withdrawals.   
   
## Version 2022-03-11T1058   
### Improvements   
ETD-341 [transactions] Improved control of the mobile transaction statement.   
   
### Bug Fixes   
ETD-383 [connectors] Transaction count flashes when resynchronizing the connector.   
   
## Version 2022-03-08T1405   
### New Features   
ETD-342 [portfolio] Calendar filters.   
   
### Improvements   
ETD-378 [transactions] Default view of all transactions in datamanager.   
ETD-373 [support] Kraken API help update.   
ETD-372 [containers] Update Binance CSV format.   
ETD-350 [support] Update communication channel links from the footer.   
ETD-345 [containers] EveryTrade format import symbol XDG as DOGE.   
ETD-285 [accounts] Change the order of tabs in the account detail.   
ETD-284 [connectors] Sort accounts by name in connector.   
   
### Bug Fixes   
ETD-375 [transactions] Deleting the WITHDRAWAL transaction returns error 500.   
ETD-371 [containers] CSV container shows bad portfolio inclusion.   
ETD-369 [containers] EveryTrade CSV import errors.   
ETD-192 [connectors] Coinbase PRO - deposits and withdrawals.   
ETD-191 [connectors] Coinbase - deposits and withdrawals.   
   
## Version 2022-02-28T0919   
### New Features   
ETD-52 [languages] Add Spanish and German language support.   
ETD-251 [portfolio] Portfolio time period and movement calculations.   
ETD-309 [support] EveryTrade Release Notes.   
ETD-336 [containers] Anycoin exchange exports CSV in native EveryTrade format.   
   
### Improvements   
ETD-191 [connectors] Coinbase API - support deposits and withdrawals transactions.   
ETD-192 [connectors] Coinbase Pro API - support deposits and withdrawals transactions.   
ETD-324 [transactions] Address from / to in transaction details.   
ETD-338 [account] Crypto-accounting support query.   
ETD-350 [support] Update communication channel links from the footer.   
ETD-352 [pairs] Add new symbols and tokens 22/02.   
0xBTC, ARAW, AZ, BSOV, CPRO, CWV, CYFM, DREP, DTA, EKT, ELEC, ETHMNY, ETHPLO, EVC, FLOT, GVE, HEX, KICK, LPT, LXT, MNE, ODEX, POPCOIN, POWR, PYRO, RNT, SHE, SHIT, SHR, SINGH, SLV, ZLA, ADC, ADX, AGIX, AION, AMB, ANC, ATM, AUDIO, BADGER, BELT, BNC, BRD, BTS, BURGER, BZRX, CDT, CELO, CHR, COCOS, CREAM, CTXC, CVP, DATA, ELF, ETHOS, FLUX, FOR, GNO, HIGH, HODL, IDEX, IQ, JASMY, JST, JUV, KEY, LAZIO, LPT, MBL, MC, MDT, MINA, MLN, NBS, NFT, NKN, NULS, NXS, OHM, OHMv2, OM, PERL, POKT, PORTO, POWR, PSG, QI, RAMP, RARI, REPV2, SFP, SKY, STX, SUN, TBTC, TRU, TUSD, TVK, VR, VRT, WBTC, WTC, YFII, ACA, ALPINE, BCPT, BOBA, BSD, BTCST, BTTC, COP, DON, GRS, MEETONE, ONG, PURSE, SCRT, SGB, TKO, UST, VGX, WAXP, XN.   
ETD-353 [transactions] Receiver and sender address resolution in the transaction input.   
ETD-367 [portfolio] Update portfolio help.   
ETD-368 [portfolio] Rename Portfolio currency to Accounting currency.   
   
### Bug Fixes   
ETD-235 [connectors] Coinbase API block non-standard transactions.   
ETD-265 [portfolio] When you hover over the portfolio chart, the page content disappears.   
ETD-343 [connectors] Binance API duplicates DEPOSIT, WITHDRAWAL, FAILED transactions. (Fix automatically removes duplicate transactions.)   
ETD-344 [containers] EveryTrade CSV v3.1 import crashes when reading the transactions address.   
ETD-354 [transactions] Saving a bundled fee and discount returns error 400 for DEPOSIT and WITHDRAWAL transactions.   
ETD-363 [layout] Alignment of fees in the mobile version.   
ETD-365 [portfolio] Clicking on the end of the time period chart resets the time period.   
ETD-366 [portfolio] The portfolio chart shows the previous day of the selected portfolio time period.   
   
## Version 2022-02-03T1528   
### New Features   
ETD-321 [connectors] Support for reading ERC-20 tokens from the Ethereum Blockchain. (Resync your APIs. Support for additional tokens in currency pairs will be gradually added.)   
ETD-309 [support] EveryTrade Release Notes and link from navigation.   
  
### Improvements   
ETD-326 [reports] Trading statement in accounting currency returns total profit / - loss for the reporting period.   
ETD-300 [support] Documentation disclosure of EveryTrade [API](https://everytrade.io/help/api#everytrade) & [CSV](https://everytrade.io/help/csv#everytrade) format v3.1   
ETD-234 [containers] CoinMate CSV support for DEPOSIT & WITHDRAWAL transactions. (re-import your CSVs)   
ETD-225 [connectors] CoinMate API DEPOSIT & WITHDRAWAL have no address. (resync your APIs)   
ETD-205 [accounts] CoinMate CSV imports transaction addresses. (re-import your CSVs)   
   
### Bug Fixes   
ETD-319 [transactions] Cannot save REBATE changes.   
ETD-265 [portfolio] While hovering with mouse on ET portfolio dashboard page contains disappears. (Linux)   
ETD-254 [portfolio] Empty portfolio with balances not showing values.   
ETD-27 [connectors] Blockchain ETH limited API response to 10 000 transactions. (resync your APIs)   
   
## Version 2022-01-27T1409
### Bug Fixes   
ETD-318 [transactions] Downloaded deposit from Kraken API does not appear in transactions.   
ETD-317 [portfolio] Incorrect calculation of the purchase price in the AVCO model & Errors downloading reports.   
ETD-315 [transactions] Incorrectly identified additionally added commitment fee.   
ETD-311 [transactions] Binding fee is included 2 times in the purchase price.   
ETD-308 [portfolio] Shared portfolio will not display accounts without login.   
ETD-307 [portfolio] Portfolio sharing returns a 401 error.   
ETD-297 [pairs] Kraken CSV import symbol XDG as DOGE.   
ETD-287 [portfolios] Stretched portfolio currency switcher.   
   
## Version 2022-01-24T1532
### New Features   
ETD-196 [audit] Inclusion of fees in the purchase price.   
ETD-148 [accounts] Report account movements to CSV file.   
ETD-209 [connectors] Extension EveryTrade CSV v3.1 format, DEPOSIT & WITHDRAWAL transactions.   
ETD-256 [pairs] Support for new 139 symbols.   
ACE, AGLD, AIOZ, ALICE, ALPHA, AMP, ANCT, AOA, ARDR, ARK, ARPA, ATA, AVAX, AWC, AXS, BAKE, BETA, BETH, BNT, BNX, BOND, BTG, BTR, BUNNY, C98, CLV, COTI, CSPR, CTK, DAR, DCR, DEGO, DERC, DOCK, DODO, DYDX, EFI, ELA, ELON, ELONGATE, ENG, ENJ, ENS, EURS, EWT, FIO, FORTH, FOX, FTM, FXS, GALA, GAS, GNT, GRIN, GTO, HBAR, HIVE, HNT, IGNIS, INJ, IOTX, KAR, KAU, KEEP, KLAY, LCX, LINA, LIT, LOCG, LOOM, LTO, MAID, MBOX, MEPAD, MFT, MIR, MITH, MOVR, MTL, NAV, NEAR, NEBL, NEXO, NPXS, NU, OCEAN, OMI, ORN, OXT, PHA, PIVX, POLY, QKC, QNT, QUICK, RAD, RDN, REEF, REQ, REVV, RLY, ROSE, RSR, RUNE, SAFEMOON, SALT, SDN, SHIB, SIB, SKL, SLP, SOLO, SPARTA, STEEM, STMX, STRAX, STRONG, SYS, TCT, TFUEL, TLM, TONCOIN, TRB, TWT, UOS, VIA, VITE, VOXEL, VRM, VTHO, WABI, WAN, WIN, WING, WPR, XCH, XHV, XMY, XVS.   
   
### Improvements   
ETD-197 [portfolio] The purchase price of the portfolio includes commitment fees and shows their amount.   
ETD-198 [portfolio] Portfolio history chart includes commitment fees.   
ETD-200 [portfolio] Inclusion and display of commitment fees in open and closed positions.   
ETD-218 [portfolio] Correct naming of revenues.   
ETD-217 [reports] Reports correctly calculate bundled fees.   
ETD-28 [connectors] EveryTrade API supports V3.1 format.   
ETD-219 [VR] Support for displaying portfolio accounts on VR.   
   
### Bug Fixes   
ETD-299 [containers] Downloading the wrong transaction log file from CSV container.   
ETD-290 [reports] Changes to report names and calculations with fees.   
ETD-289 [reports] Limit the list of reported accounts by portfolio.   
ETD-281 [connectors] Coinmate API does not load transactions before 1.1.2019. (Official connector feature. Older transactions must be imported from CSV files.)   
ETD-275 [portfolio] Error 500 FIFO portfolio caused by a fee.   
ETD-273 [connectors] Coinmate API connector duplicates deposit transactions when updating.   
ETD-269 [transactions] Firefox browser creates duplicate transactions.   
ETD-268 [transactions] Cannot update fee and dicount transaction in data manager.   
ETD-253 [datamanager] The Remove Container from Portfolio flag is not saved.   
ETD-245 [connectors] Add support Mtub prefix Litecoin xpup adress wallet.   
ETD-240 [reports] Broken report generation after AVCO / FIFO model changes.   
ETD-210 [datamanager] Random display of duplicate container during CSV import.   
ETD-139 [connectors] Incomplete synchronization and its status in the database.   
