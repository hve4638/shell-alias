# shell-alias

자주 사용하는 shell alias 모음

## 설치

1. 저장소 클론:

```bash
git clone https://github.com/hve4638/shell-alias.git ~/shell-alias
```

2. `~/.bashrc` 또는 `~/.zshrc`에 추가:

```bash
for f in ~/shell-alias/.bashrc.d/*.bashrc; do
   [ -r "$f" ] && . "$f"
done
```

3. 셸 재시작 또는 `. ~/.bashrc` 실행