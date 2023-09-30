- Time waiting at output link for transmission
- depends on congestion level of [[router]]
$$ \frac{L\cdot a}{R} : \frac{arrival\; rate\; of\; bits}{service\; rate\; of\; bits} $$
- $a$: average packet arrival rate
- $L$: packet length
- $R$: link bandwidth (bit transmission rate)

- $\frac{La}R$~ 0: avg. queueing delay is small
- $\frac{La}R$ -> 1: avg. queuing delay is large
- $\frac{La}R > 1$: "work" arriving is more than can be serviced - average delay is infinite