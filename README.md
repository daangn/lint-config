# Lint Config

당근마켓에서 사용하는 여러 linter의 공용 config를 저장하는 저장소에요.

## golangci-lint

당근마켓의 Go 프로젝트들에서는 Go linter로 [golangci-lint](https://golangci-lint.run/)를 사용하고 있어요. 
이 레포에서는 당근마켓의 Go 프로젝트에 맞게 커스터마이징된 [lint config](golangci-lint/default.golangci.yml)를 제공하고 있어요.

lint config는 저장소 루트 디렉터리에서 다음 명령어를 통해 다운로드 받을 수 있어요.

```shell
wget -O .golangci.yml https://raw.githubusercontent.com/daangn/lint-config/main/golangci-lint/default.golangci.yml
```
