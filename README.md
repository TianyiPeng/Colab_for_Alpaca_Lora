# Colab for Alpaca LoRA
If you're looking to fine-tune a ChatGPT-level model but lack access to a GPU, Google Colab may be a useful solution to consider.

With a Google Colab Pro account, you can access a single 40GB A100 GPU ($10 for approximately 7.5 hours) or Tesla T4 GPU ($10 for approximately 50 hours), and sometimes these resources are available for free.

Here is a Google Colab Notebook Example for fine-tuning Alpaca Lora (within 2-3 hours with a single 40GB A100 GPU). In particular, [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) is a fine-tuning version of Meta LLaMA (a large lanuage model with tens of billions parameters) based on a small instruction set. [Alpaca LoRA](https://github.com/tloen/alpaca-lora) used [low-rank adaptation (LoRA)](https://arxiv.org/pdf/2106.09685.pdf) to optimize the speed and resource required for reproducing Alpaca.

This notebook just serves as an example. Check [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) and [Alpaca LoRA](https://github.com/tloen/alpaca-lora) for more usage instructions. 

### Resources
- [LLaMA weights](https://huggingface.co/decapoda-research/llama-7b-hf)
- [Discord community for Alpaca LoRA](https://discord.gg/prbq284xX5)
- [Using Colab for GitHub](https://medium.com/@ashwindesilva/how-to-use-google-colaboratory-to-clone-a-github-repository-e07cf8d3d22b#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6Ijk4NmVlOWEzYjc1MjBiNDk0ZGY1NGZlMzJlM2U1YzRjYTY4NWM4OWQiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJuYmYiOjE2Nzk2OTc1NDcsImF1ZCI6IjIxNjI5NjAzNTgzNC1rMWs2cWUwNjBzMnRwMmEyamFtNGxqZGNtczAwc3R0Zy5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsInN1YiI6IjEwMTc1NDYzNjExMjYxNDgyODU3MSIsImVtYWlsIjoidGlhbnlpcGVuZzk1QGdtYWlsLmNvbSIsImVtYWlsX3ZlcmlmaWVkIjp0cnVlLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJuYW1lIjoiVGlhbnlpIFBlbmciLCJwaWN0dXJlIjoiaHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUdObXl4WjFxUHR5TWZQLWlud1IxWHZ1UExkNUFqMlZrQ0N0TkttdjVLOWRrUT1zOTYtYyIsImdpdmVuX25hbWUiOiJUaWFueWkiLCJmYW1pbHlfbmFtZSI6IlBlbmciLCJpYXQiOjE2Nzk2OTc4NDcsImV4cCI6MTY3OTcwMTQ0NywianRpIjoiYzk0YThjOWQwYTZlMjA3YzUwMWI4MjcyYWI4ZGNiZDg4NDM5OWM1MiJ9.Djs8liGsTZDXxgiH0ToR_LZ_LFe8LHJaEc1sMKZnbsGQ7c3-6oP3LBoEbt3T4Erw6jyQrghYOBfhTO7LuIf05FYfiQTZpkckZEi_wP6qcXrB77vtREkS3YVMs8uHQLokXLgI2XBADU_59EhpILGtpRjSBkhk9uFgB9bOobQehkCEreZYRBfJJgkz687Qw42HIbnbn5J_8rxLsPXLJMsnz4k8UjgrWUa79JF4WgpQwQBjqsTyuHZzdwzPSGdQvXUxwWBxJIHzwlcxnV0uL17AGdMBsxDVtbxHz819XgYGo7ofygFgGTi7ge6edhfgkOqt2rO-IeewI5Iy5utay4sBag)
- [How to run Colab after closing the browser](https://stackoverflow.com/questions/55050988/can-i-run-a-google-colab-free-edition-script-and-then-shut-down-my-computer)
