#2. first 5 lines of your generated shakespeare char samples:#

AUTOLYCUS:
O, will you be straight.

MENENIUS:
Stirrd your gates?

CORIOLANUS:

#3. Remainder 0: Layers = 5, Heads ∈ {2, 3, 5, 7}, n_embd ∈ {128, 129, 130, 133}, training with 3000 iterations.#
Number of heads: 2, Loss at iteration 3000：1.5507, validation loss = 1.6355
Number of heads: 3, Loss at iteration 3000：1.5529, validation loss = 1.6190
Number of heads: 5, Loss at iteration 3000：1.5552, validation loss = 1.6204
Number of heads: 7, Loss at iteration 3000：1.5064, validation loss = 1.5973

layers=5, heads= 7, has lowest validation loss of 1.5973

#4. XYZ mod 2 = 0: Populate data/code generation/input.txt with open-source C or C++ code from GitHub.#
The new dataset is populated using following C code:
https://raw.githubusercontent.com/karpathy/llama2.c/refs/heads/master/run.c
https://raw.githubusercontent.com/karpathy/llama2.c/refs/heads/master/runq.c 
https://raw.githubusercontent.com/karpathy/llama2.c/refs/heads/master/test.c 
https://raw.githubusercontent.com/karpathy/llama2.c/refs/heads/master/win.c 
https://raw.githubusercontent.com/karpathy/llm.c/refs/heads/master/test_gpt2.c 
https://raw.githubusercontent.com/karpathy/llm.c/refs/heads/master/train_gpt2.c

train has 133,439 tokens
val has 14,827 tokens

first 20 lines of the generated samples:

        if (text[0] != '\0') {
                 }
          }

     // read in continuation byte, so we've read not writa preatuve preature (byte", byte_val b.sstr_buffer.cannn_layers
            max_i = -10000000;
             for (int i = 0; i < head_size; i++) {
                   float val = probs_bt[i] - index[i];
                  float val +== ix * (probs_bt[i] - max_val);
                     float val = 0.0f + pos * frob + i * n;
                   float val = 0.0f;
                  fl
---------------

                                                                                                                  int B, int T, int OC, int C) {
             for (int o = 0; o < OC; i++) {
                                     float val = 0.0f;
                     float val = 0.0f + val * (in + i * C) * weight[o + b * C + t * OC;
          }
            }

Personal favorite generated snippet(s):

if(next == 0 && prompt_tokens < num_prompt_tokens - 1) {
                          // encode the aing string prompt from this and excted prompt
                            strcpy(system_prompt);
                 }
