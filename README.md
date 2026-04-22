# ollama_user_guide
ollama使用指引(自用引导)

[ollama官网查看可用模型列表：](https://ollama.com/search)

### 查看模型列表：
`ollama list`
### 安装模型：
`ollama pull qwen3.5:9b`  
`ollama pull llama3.1:8b`
### 运行模型：
`ollama run qwen3.5:9b`  
`ollama run llama3.1:8b`
### 删除模型：
`ollama rm llama3:8b`  
`ollama rm llama3:8b qwen2.5:7b`
### 删除模型后 清理缓存和残留文件：
`ollama prune`
