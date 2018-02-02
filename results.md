## Results

#### Todo - for LSTM and GRU

-[ ] Test embed size between 50 - 300 (50 inc) = 6


-[ ] Test Max features between 10000 - 60000 (10000 inc) = 6


-[ ] Test Maxlen between 50 - 300 (50 inc) = 6


-[ ] Take the best score for each individual target
-[ ] Mabe try a higher drop out for Toxic, Obs and Insult

---

**Source:** glove.6B.50D.txt

**Embed Size:** 50  **Max Features:** 20000  **Maxlen:** 100

**Layer:** LSTM

| Col   | Res                |
| ----- | ------------------ |
| Tox   | 0.9773197743442615 |
| S Tox | 0.9861784652119562 |
| Obs   | 0.988624495588207  |
| Thr   | 0.9724186986521712 |
| Ins   | 0.9818022556581923 |
| IDH   | 0.9762195729308453 |
|       |                    |

___

**Source:** glove.6B.50D.txt

**Embed Size:** 50  **Max Features:** 20000  **Maxlen:** 150

**Layer:** LSTM

| Col   | Res  |
| ----- | ---- |
| Tox   |      |
| S Tox |      |
| Obs   |      |
| Thr   |      |
| Ins   |      |
| IDH   |      |
|       |      |

