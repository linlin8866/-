bash <(curl -sL https://raw.githubusercontent.com/你的用户名/你的仓库/main/脚本.sh)

curl -sL https://raw.githubusercontent.com/你的用户名/你的仓库/main/脚本.sh -o /tmp/脚本.sh && chmod +x /tmp/脚本.sh && /tmp/脚本.sh

一键执行（最常用写法）
bash <(curl -Ls https://raw.githubusercontent.com/用户名/仓库名称/main/脚本.sh)

bash <(wget -qO- https://raw.githubusercontent.com/linlin8866/仓库名称/main/脚本.sh)


bash <(curl -L https://raw.githubusercontent.com/你的名字/仓库名/main/sinbox.sh) uninstall
