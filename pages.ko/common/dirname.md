# dirname

> 주어진 파일 혹은 디렉토리 경로의 부모 디렉토리를 계산한다.
> 더 많은 정보: <https://www.gnu.org/software/coreutils/manual/html_node/dirname-invocation.html>.

- 주어진 경로의 부모 디렉토리 계산:

`dirname {{경로/파일_또는_디렉토리}}`

- 복수 경로의 부모 디렉토리 계산:

`dirname {{경로/a_파일}} {{경로/b_디렉토리}}`

- 개행 대신 NUL 문자로 출력을 구분하기 (`xargs`와 결합 시 유용함):

`dirname --zero {{경로/a_디렉토리}} {{경로/b_파일}}`
