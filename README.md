# Plan:

collect data D from historical api,
process it to be useful,
train model X with data.
D can be any data spaced apart by any type of interval.

## Goal:

X needs to make decisions of buy and selling stocks as accurately as possible.
until Day Trading is permited, X must make trades of minimum a day long. X must not risk large amounts. X must give priorities to stocks which have higher success ratios to allocate more money to them.

D must be information dense with respect to timeframe. D must not be redundant to conserve speed.

## Future:

When I have access to a powerful enough GPU, train X on as many stocks as possible. Then finetune copies of X for multiple stocks. Finally, cash in.