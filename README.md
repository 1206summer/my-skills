# my-skills

개인 Claude Code 스킬 모음 (플러그인 마켓플레이스). 스킬 내용은 복사하지 않고 원작자 저장소에서 바로 받아요.

## PC마다 한 번 등록 (Claude Code 데스크탑 앱 / 터미널)
```
/plugin marketplace add 1206summer/my-skills
```
그다음 쓰고 싶은 스킬을 설치해요:
```
/plugin install frontend-design@my-skills
/plugin install img2threejs@my-skills
/plugin install blender-skills@my-skills
/plugin install logo-design@my-skills
/plugin install sprite-gen@my-skills
/plugin install taste-skill@my-skills
/plugin install hallmark@my-skills
/plugin install ponytail@my-skills
```
업데이트: `/plugin marketplace update my-skills`

## 메모
- img2threejs·sprite-gen: 원본 저장소가 플러그인 형식이 아니라서 `plugins/` 안에 복사본으로 넣었어요 (Apache-2.0, 원본 커밋은 각 폴더의 UPSTREAM). 원본이 업데이트되면 다시 복사해야 해요.
- sprite-gen: 그림을 만들 때 ChatGPT(Codex)·Grok 로그인 또는 OpenAI 유료 API 키가 필요해요 (키를 쓰면 만들 때마다 요금).
- ponytail: 설치하면 모든 대화에 자동으로 켜지는 모드(대화 시작·메시지마다 실행되는 훅 포함). 끄기: 대화에서 `/ponytail off`, 완전히 빼기: `/plugin uninstall ponytail@my-skills`. 기본 설정으로 작업 기록을 내 PC의 ~/.config/ponytail/band/ 에 CSV로 남겨요(밖으로 안 보냄).
