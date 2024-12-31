
<img src="./readme/images/hibou_banner_v2.svg" alt="hibou banner" width="750">

# HIBOU
Fork of HIBOU, https://github.com/erwanM974/hibou_label

This has been created to add more options to the hibou_label `rng_gen_interactions` command 
The only change yet is the custom probabilities:

```
hibou_label rng_gen_interactions {path.hsf} {num_ints} custom {max_depth} {min_symbols} {seed} {pempty} {paction} {pstrict} {pseq} {pcoreg} {ppar} {ploopS} {ploopW} {ploopP} {palt} {pbasic} {ptransmission} {pbroadcast} {target_folder}
```
example: 
```
hibou_label rng_gen_interactions readme/examples/2/basic/sig.hsf 1 custom 15 10 1 0.1 0.1 0.1 0.1 0.1 0.1 0.1 0.1 0.1 0.1 0.0 0.0 0.0 here
```
