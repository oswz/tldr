# mkdir

> 디렉토리를 생성하고 해당 권한을 설정합니다.
> 더 많은 정보: <https://www.gnu.org/software/coreutils/manual/html_node/mkdir-invocation.html>.

- 특정 디렉토리 생성:

`mkdir {{경로/대상/폴더1 경로/대상/폴더2 ...}}`

- 필요시 특정 디렉토리와 그 [상위] 디렉토리를 생성:

`mkdir {{[-p|--parents]}} {{경로/대상/폴더1 경로/대상/폴더2 ...}}`

- 특정 권한으로 디렉토리 생성:

`mkdir {{[-m|--mode]}} {{rwxrw-r--}} {{경로/대상/폴더1 경로/대상/폴더2 ...}}`
