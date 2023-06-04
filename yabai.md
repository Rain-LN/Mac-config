# Yabai安装

## 环境

- Macbook Pro M1(v12.1)

## 安装

```shell
# 安装yabai
brew install koekeishiya/formulae/yabai

# 安装skhd
brew install koekeishiya/formulae/skhd

# 安装jq
brew install jq
```

> 未关闭ISP，部分功能不可用。具体安装[参考官网]([Installing yabai (latest release) · koekeishiya/yabai Wiki · GitHub](https://github.com/koekeishiya/yabai/wiki/Installing-yabai-(latest-release)

## 配置及启动

- yabai
  
  ```shell
  # 拷贝配置
  cp /opt/homebrew/opt/yabai/share/yabai/examples/yabairc ~/.yabairc
  
  # 启动服务
  yabai --install-service
  yabai --start-service
  ```
  
  > 具体配置[参考官网](https://github.com/koekeishiya/yabai/wiki/Configuration#configuration-file)

- skhd
  
  ```shell
  # 拷贝配置
  cp /opt/homebrew/opt/skhd/share/skhd/examples/skhdrc ~/.skhdr
  
  # 启动服务
  skhd --start-service
  ```
  
  > 获取要绑定的快捷键：`skhd --observe`
