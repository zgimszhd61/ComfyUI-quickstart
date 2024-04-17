# ComfyUI-quickstart

ComfyUI是一个基于节点的界面，用于Stable Diffusion模型的图像生成，它允许用户通过图形界面操作和连接不同的节点来执行图像生成任务。以下是一个关于如何部署和使用ComfyUI的快速入门指南：

## 准备工作

在开始之前，请确保你的系统满足以下条件：

- 拥有NVIDIA GPU，支持CUDA。
- 已安装Python环境，版本为3.7或更高。
- 已安装Git。

## 安装步骤

1. **克隆ComfyUI仓库**

   打开终端或命令提示符，运行以下命令来克隆ComfyUI的GitHub仓库：

   ```bash
   git clone https://github.com/comfyanonymous/ComfyUI
   ```

2. **安装依赖**

   进入ComfyUI目录，安装所需的Python依赖：

   ```bash
   cd ComfyUI
   pip install -r requirements.txt
   ```

3. **下载模型**

   根据需要下载Stable Diffusion模型文件。这些模型文件通常是`.ckpt`格式。你可以从官方网站或其他资源获取模型文件。将模型文件放置在`ComfyUI/models`目录下。

4. **运行ComfyUI**

   在ComfyUI目录下，运行以下命令启动ComfyUI：

   ```bash
   python main.py
   ```

   这将启动ComfyUI的图形界面。

## 使用指南

1. **创建新节点**

   在ComfyUI界面中，右键单击空白区域，选择“新建节点”，然后选择你需要的节点类型。例如，选择“图像生成”节点来生成新的图像。

2. **配置节点**

   单击节点，在右侧的属性面板中配置节点的参数。例如，在“图像生成”节点中，你可以输入文本提示、选择模型等。

3. **连接节点**

   节点之间可以通过拖动连接点来连接。例如，将“图像生成”节点的输出连接到“显示图像”节点的输入，以显示生成的图像。

4. **执行工作流**

   配置好节点后，点击“执行”按钮运行整个工作流。你将在界面中看到生成的图像或其他输出结果。

5. **保存和加载工作流**

   你可以通过菜单选项“文件”->“保存工作流”来保存你的工作流配置，以便日后加载和再次使用。

## 注意事项

- 确保你的系统具备足够的GPU资源来运行模型。
- 根据你的具体需求，可能需要下载和安装额外的插件或节点。
- ComfyUI社区不断更新，建议定期检查GitHub仓库以获取最新的功能和修复。

以上是ComfyUI的快速入门指南，希望能帮助你轻松开始你的AI图像生成项目。

Citations:
[1] https://www.youtube.com/watch?v=FI8qSRIWsVE
[2] https://www.uisdc.com/stable-diffusion-comfyui
[3] https://blog.yanghong.dev/stable-diffusion-comfyui-introduction/
[4] https://cloud.baidu.com/article/3264759
[5] https://blog.csdn.net/u010618499/article/details/134010897
[6] https://www.uisdc.com/stable-diffusion-comfyui-7
[7] https://www.baseten.co/blog/how-to-serve-your-comfyui-model-behind-an-api-endpoint/
[8] https://juejin.cn/post/7326864191918686208
[9] https://blog.csdn.net/yunqiinsight/article/details/135753130
[10] https://aws.amazon.com/cn/blogs/china/stable-diffusion-comfyui-deployment-solution-based-on-amazon-eks/
[11] https://www.wehelpwin.com/m_article/4506
[12] https://help.aliyun.com/zh/pai/user-guide/eas-use-case-summary
[13] https://developer.aliyun.com/article/1450565
[14] https://aws.amazon.com/cn/blogs/china/category/serverless/feed/
[15] https://blog.csdn.net/phsruanjian/article/details/137192777
[16] https://www.volcengine.com/theme/4232232-R-7-1
