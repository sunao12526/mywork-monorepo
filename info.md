pnpm create expo apps/mobile --template expo-template-default@sdk-52

pnpm config set node-linker=hoisted --location project

# 在 app-web 中引用 utils

pnpm --filter app-web add @my-org/utils@workspace:\*

pnpm why --recursive react-native

pnpm why @my-org/cool-package

pnpm --filter mobile run start
