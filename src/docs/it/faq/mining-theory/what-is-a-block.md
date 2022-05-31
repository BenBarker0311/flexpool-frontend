---
title: 'Che cos''è un blocco?'
level: principiante
---

Per farla semplice, un blocco è una combinazione dei seguenti elementi:
| Blocco                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Transazioni                | Un elenco di un certo numero di transazioni dalla rete, la dimensione di questo elenco è limitata, quindi solo una certa quantità di transazioni può essere inclusa (l'ammontare delle operazioni che possono essere incluse varia in base alla moneta). Le transazioni includono anche una *tassa di transazione* che è data al minatore del blocco in cambio di includere tale transazione nel Blocco, le transazioni sono incluse in blocchi basati su queste commissioni di transazione, commissioni più elevate ottenere incorporati in blocchi più velocemente come i minatori stanno cercando di fare più profitto possibile. L'elenco delle transazioni include una transazione speciale che dà fondi al minatore del blocco, questi fondi sono "creati" quando il blocco viene trasmesso alla rete ed è noto come *Ricompensa del blocco*. |
| Hash Del Blocco Precedente | L'Hash del blocco precedente sulla blockchain - questo assicura che la catena non possa essere modificata, perché aggiustare qualsiasi cosa nei blocchi precedenti porterebbe a questo diventare invalido e causerebbe la rottura della catena.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Nonce                      | Standing for "Number used Once", this is a number which is generated by miners guessing randomly until they find a number that, when Hashed with the rest of the block data, results in a Hash of the required Difficulty (or higher) to make the Block _Valid_. A Block which does not yet have a Nonce is called a _Block Template_, this can be repeatedly Hashed with different Nonces to try to meet the Difficulty requirement of the coin and form a Block. If two Blocks are found by different pools at the same time they are both added to the chain and then the next block will only point its Previous Block Hash at one of these, the other is called an _Uncle_.                                                                                                                                                                    |