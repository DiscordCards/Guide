# Global Market
The global market is what keeps the economy of the game flowing *tl;dr moving money*.

## Types of offers

- Buying  
These offers have money put on the trade and the offer author will ask for a certain card and the price they will pay for each card you give them.

- Selling  
These offers have cards put on the trade and the offer author will ask for a sum of money per card on the offer.

## Understanding the offer
<div style='margin: 5px; padding: 20px; border-radius: 30px; background: #6a87fa; width:500px;'>
<div style='text-align: center; font-size: 25px; margin-bottom: 10px;'>
**Selling Trade**
</div>
<img style="width:100%" src="https://i-need.discord.cards/8a7d11.png"></div>

<div style='margin: 5px; padding: 20px; border-radius: 30px; background: #6a87fa; width:500px;'>
<div style='text-align: center; font-size: 25px; margin-bottom: 10px;'>
**Buying Trade**
</div>
<img style="width:100%" src="https://i-need.discord.cards/bd4eed.png">
</div>


**Details on these trades.**
- Type - *the type of trade*
- Buyer / Seller - *the author of the trade*
- Created - *when the trade was made (UTC String)*
- Stock - *the amount of cards in the deal*
- Amount Bought / Sold - *the amount of cards that are already sold/bought*
- Item - *the item that is being traded*
- Price *per card*

## Using the market

**I want to execute a trade.**
For the buying market, use `[]boexecute <offer-id> [amount]`
For the selling market, use `[]soexecute <offer-id> [amount]`

**How do I view a trade?**
For the buying market, use `[]boffer <offer-id>`
For the selling market, use `[]soffer <offer-id>`

**How do I start a trade?**
For the buying market, use `[]`
For the selling market, use `[]`

**How do I stop a trade?**
For the buying market, use `[]`
For the selling market, use `[]ostop`

**How do I view all of my trades?**
For the buying market, use `[]`
For the selling market, use `[]`

**How do I view all trades on the market?**
For the buying market, use `[]bolist [page]`
For the selling market, use `[]solist [page]`

**How do I search for an item on the market?**
For the buying market, use `[]bosearch [query] [page]`
For the selling market, use `[]sosearch [query]`

The following below can be used as search modifiers:
- `#CARD_ID` - Searches card offers with that ID
- `$RARITY` - Searches card offers with that rarity
- `%SERIES` - Searches card and card pack offers with that series ID

**Example Searches:**
- `[]sosearch b1nzy`  
Searches for any card with the name of `b1nzy`.
- `[]bosearch #63`  
Searches for any card with the ID 63.
- `[]sosearch $c`  
Searches for any card with the Common rarity.
- `[]bosearch %1`  
Searches for any card in the Discord series.
