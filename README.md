GPT-2 finetune over wikitext-2 dataset

## Results on perplexity over the test set:
- load gpt2_r2_epoch4_ppl26.63 with total params: 73728
    - Perplexity: 25.429397583007812
- load gpt2_r0_epoch4_ppl25.84 with total params: 21233664
    - Perplexity: 24.683578491210938
- load gpt2_r64_epoch7_ppl26.27 with total params: 2359296
    - Perplexity: 25.07568359375
- load gpt2_r8_epoch7_ppl26.26 with total params: 294912
    - Perplexity: 25.082033157348633
- load gpt2_r8_epoch4_ppl26.39 with total params: 294912
    - Perplexity: 25.192895889282227
- load gpt2_r2_epoch2_ppl26.06 with total params: 73728
    - Perplexity: 24.915809631347656
- load gpt2
    - Perplexity: 25.1879940032959

## hyperparameters
- num_epochs=5,
- batch_size=8,
- learning_rate=1e-5,
- weight_decay=0.01,
- warmup_steps=500,
- max_length=512
- alpha=16