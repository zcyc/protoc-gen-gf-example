# protoc-gen-gf-example


## example
假如已经安装了[protoc-gen-gf-logic](https://github.com/zcyc/protoc-gen-gf-logic)

测试命令
```bash
protoc -I ./api -I $GOPATH/src --gf-logic_out ./api --gf-logic_opt=paths=source_relative ./api/v1/article.proto
```