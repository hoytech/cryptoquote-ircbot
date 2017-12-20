# CryptoQuote IRC Bot

Simple bot that connects to an IRC server and responds to requests for cryptocurrency quotes.

It uses the coinmarketcap.com ticker API.

## IRC usage

When the bot joins the channel, use the `!q` command with a symbol option, for example:

    <@Fractal> !q btc
    < cryptob0t> Bitcoin | 1 BTC = 16917.2 USD | 1h: -0.24%  24h: -5.15%  7d: +2.15%

You'll see colours in your IRC client too.

## Command-line usage
    Usage: cryptbot <cmd> [args]
      cryptobot serve <irc server> <channel> <nick>
      cryptobot test <nick> <message>

    Examples:
      cryptobot serve irc.choopa.net '#mychan' cbot123
      cryptobot test jimmy '!q btc'

## License

2-clause BSD, do whatever you want with it.
