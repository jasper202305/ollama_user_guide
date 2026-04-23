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
### 查看所有运行中的模型
`ollama ps`  
- 1.如果模型已停止，输出为空
- 2.如果模型还在运行，会显示详细信息
### 停止指定模型
`ollama stop qwen3:4b`
### 停止所有运行中的模型
`ollama stop --all`
### Windows：在任务管理器中结束Ollama进程或者重启Ollama服务也可停止所有运行中的模型
- 然后重新启动`ollama serve`
