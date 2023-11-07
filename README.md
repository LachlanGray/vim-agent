# Vim Agent
Can we control vim with a language model? [blog post](https://lachlan-gray.com/Controlling+Vim+With+ChatGPT)

Start neovim somewhere with
```
nvim --listen 127.0.0.1:7777
```

Then, run the script with `python vim_agent.py`. It will open a prompt for you to describe what you want done, then chatgpt will take requests and control neovim on your behalf. 

For the time being I wouldn't try it on any important files... it's not too reliable for now

<video src='https://publish-01.obsidian.md/access/8599d0814e49d01369b62a3313d64ab7/assets/llm_vim/vim%20agent%20demo.mp4' width=180/>

There's lots of low-hanging fruit to improve, so stay tuned!
