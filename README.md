# Notes - understanding of  LLM , its parameters

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/70c7512f-75f4-4053-b569-6ab0e389b807)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/9ec71711-0b94-4b91-86be-2ffe034475d8)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/7e5882f5-2e08-4bae-9f53-6d662c3f79f4)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/5144f1b4-535f-4a1b-95b7-b10d9dfbec71)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/bea3082a-5652-4ae3-9f5d-b48f2d7d8af6)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/0f171272-5fc9-43a5-bd0a-ca5fa85a333e)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/9986e18e-4a8b-46c1-98aa-14169275ec7c)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/a27b6fa8-e636-41ca-bc10-ddc968098d57)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/a7c85758-04bf-44f6-870d-1b19693e2d8c)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/fe9af948-3636-4713-b7ca-175649a727e4)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/7e651624-c343-4eaf-902a-d844f12ce5a3)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/084a8f49-94cd-4cc1-9483-712a1734ec8d)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/6c1b603c-b9c3-4c07-88ad-81b755509205)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/a9425c88-96bf-409d-ac5d-a7c169521bbd)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/44f08b16-183e-4b81-b16b-6cf2639abbaf)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/ae06f9ab-8d99-47bb-98e1-15628e314615)

![image](https://github.com/Siddhartha082/Fine-Tuning---LLM--module-/assets/110781138/41031a82-47a5-4408-ad1f-a1fba1475b0f)

# Finetuning-LLM

Understanding how finetuning on LLM models can be performed uing QLORA,LORA, Quantization using LLama2, Gradient and Google Gemma model. This crash course includes both theoretical intuition and practical intuition on making you understand how we can perform finetuning.

## Finetuning using Mistral with QLora and PEFt

This section provides a guide on how to perform finetuning using Mistral with QLora and PEFt. The process involves the following steps:

1. **Setup Environment**: Ensure that your environment is set up with all the necessary dependencies for Mistral, QLora, and PEFt.
2. **Prepare Data**: Prepare your dataset for finetuning. This involves preprocessing your data into a suitable format for training.
3. **Configure Finetuning Parameters**: Set up the finetuning parameters, including the learning rate, batch size, and the number of epochs.
4. **Initiate Finetuning**: Start the finetuning process using Mistral with the QLora and PEFt configurations.
5. **Evaluate Model**: After finetuning, evaluate the performance of your model on a validation set to ensure that it meets your expectations.
6. **Deploy Model**: Once satisfied with the model's performance, you can deploy it for inference.

For a detailed demonstration of the finetuning process using Mistral, QLora, and PEFt, refer to the notebook `Fine_Tuning_with_Mistral_QLora_PEFt.ipynb` included in this repository.
