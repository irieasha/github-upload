# やったー！
### Yahoo! Finance quote summaries as delicious, digestible JSON.

This is a humble Ruby script designed to scrape quote summaries from Yahoo! Finance and return them as JSON, ready to feed other hungry scripts that lack the enzyme for digesting HTML.

Originally authored by @darrowby385. Recreated here as part of an exercise.

![example](example.jpg)

## How to use it
From within this folder, run `ruby yattaa.rb <ticker>`, replacing `<ticker>` with the stock ticker you want to retrieve data for. If you don't get the results you expected, make sure the ticker you've specified matches the format used by Yahoo! Finance.

For example, `ruby yattaa.rb CSL.AX` will output the quote summary for CSL Limited on the Australian Securities Exchange (ASX). `ruby yattaa.rb MSFT` will output the quote summary for Microsoft Corporation on the Nasdaq, etc.

## Just to be clear
This software and its author are not affiliated, associated, authorized, endorsed by, or in any way officially connected with Yahoo or Verizon Media, any of their subsidiaries, or affiliates. The official Yahoo! Finance website can be found at http://finance.yahoo.com.

For other legal matters, please see the [LICENSE file](LICENSE).
