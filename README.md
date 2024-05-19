# oscars2024_knowledge

Using model `TheBloke/Mistral-7B-Instruct-v0.2-GGUF/mistral-7b-instruct-v0.2.Q4_K_S.gguf`.
Model was hosted locally in LM Studio. 

```
ilab generate --endpoint-url http://localhost:1234/v1
...
100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 100/100 [47:52:49<00:00, 1723.69s/it]
INFO 2024-05-19 18:25:29,147 generate_data.py:606 100 instructions generated, 3792 discarded due to format (see generated/discarded_merlinite-7b-lab-Q4_K_M_2024-05-17T18_32_39.log), 41 discarded due to rouge score
INFO 2024-05-19 18:25:29,147 generate_data.py:610 Generation took 172370.36s
```

It took 2 days to complete synthetic data generation on an Apple M2 Pro with 16 GB memory.

![m2pro.png](m2pro.png)
