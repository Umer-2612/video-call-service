# video-service

LiveKit token issuance + the 1:1 video call (candidate + hiring manager).

Full plan: see the `platform` repo's README (sibling folder).

**Build order:** #2 — fastest path to a demoable feature.

**Lift from:**
- `Interview-Platform-Backend/src/modules/interview-rooms/interview-rooms.service.ts` — real LiveKit token issuance, extend for 2 named participants
- `Interview-Platform-Backend/livekit.yaml` + `docker-compose.yml` — LiveKit infra config
- `Interview-Platform-Frontend/src/components/interview/InterviewRoom.tsx` — built but unwired LiveKit React component; wire it into a real session page
