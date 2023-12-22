# Intel_LLM_QnA_ansible_script

```bash
sudo docker build -t allen_ai_app .
```

```bash
sudo docker run -it -p 7860:7860 -e GRADIO_SERVER_NAME=0.0.0.0  allen_ai_app
```