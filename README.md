# btc-Revisited

This is a continuation of an older project [btc-investing](https://github.com/PPFilip/btc-investing) and tackles BTC investing related questions.

## Contents

### lump-vs-dca

Compare 2 investment strategies over a longer period of time


## Reading

These articles are published on [shitcoin.ninja](https://shitcoin.ninja) , but you can read them [directly from project directory](https://github.com/PPFilip/btc-Revisited/blob/main/out/) - just select a .md notebook of interest and open it.

## Building output

If you want to build files yourself, I suggest you use

```r
install.packages("ezknitr")
ezknit(file = 'lump-vs-dca.Rmd', out_dir = 'out')
```

In order to properly send output to a directory of your choice.
