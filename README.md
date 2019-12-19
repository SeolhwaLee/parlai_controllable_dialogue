# parlai_controllable_dialogue
Abigail See, Stephen Roller, Douwe Kiela, Jason Weston. What makes a good conversation? How controllable attributes affect human judgments. To appear in NAACL 2019.

## Installation ##
Load the conda envirionment.
```bash
pytorch_p36
```

## Usage ##
```bash
conda activate pytorch_p36
```

How to run the demo:

```bash
python projects/convai2/interactive.py -mf models:convai2/seq2seq/convai2_self_seq2seq_model -m legacy:seq2seq:0
```
If have some troubleshooting on the command 'cuda out of memory error', try like this:

```bash
python projects/convai2/interactive.py -mf models:convai2/seq2seq/convai2_self_seq2seq_model -m legacy:seq2seq:0 --no-cuda
```

## Related Project ##
* https://github.com/facebookresearch/ParlAI/tree/master/projects/controllable_dialogue
