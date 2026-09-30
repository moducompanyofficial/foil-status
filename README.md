# foil-status

foil.ink 외부 가동 감시. `.github/workflows/uptime.yml` 이 5분마다
`https://api.foil.ink/health`(`status` 와 `db` 가 모두 `ok`)와 `https://foil.ink/`(200)를 확인한다.
실패가 이어지면 `outage` 라벨 이슈가 열리고, 회복되면 자동으로 닫힌다. 비밀값 없음.
