# ベースイメージとしてNode.jsの公式イメージを使用
FROM node:20.15.1-bullseye-slim

# 作業ディレクトリを設定
WORKDIR /workspace

# 必要なパッケージをインストール
RUN npm install -g create-react-app

# ポートを公開
# EXPOSE 3000

# サービスを起動
CMD ["npm", "start"]
