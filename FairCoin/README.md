# Important Notice

The `FairCoinChain.json` is not signed by the creator because it is not a FairChain ( with OMNI Layer ).

So the file can't be used to run the FairChains client.


## ElectrumfairchainsX server

#### Install the ElectrumfairchainsX
( https://github.com/fairchainsx/electrumfairchainsx )

#### Copy the 3 files into data directory
~~~
/home/<username>/.faircoin2/fairchains.conf
/home/<username>/.faircoin2/FairCoinChain.json
/home/<username>/.faircoin2/FairCoinChain.electrumx.json
~~~

#### Run the ElectrumfairchainsX server on commandline
~~~
efcx_server --fairchains-path /home/<username>/.faircoin2/
~~~
