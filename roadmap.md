# Favoje Battle roadmap

Current request:
- Remove text chat and its settings.
- Make voice controls movable and available in every game mode, including lobbies.
- Improve voice connection cleanup, rejoining, and recovery.
- Apply the supplied public Firebase web configuration.
- Verify communication behavior with tests; real cross-network voice requires microphone access and Firebase permissions.

Done: solo CBT mode (timed courses, admin CBT tab), themes (15 × dark/light), app layout, sign-up/login/reset, home, 1v1 matchmaking, private rooms, 50 Players Rush, live battle + results, rankings, friends + challenges, notifications, profile, settings, admin (questions, players, app settings).

Open:
- Firebase console setup (enable Email sign-in, create Firestore, add preview domain to authorized domains, publish security rules, create first admin in `roles/{uid}` with `admin: true`). Blocked on: the owner doing this in Firebase.
- Move scoring to trusted backend (Cloud Functions). Blocked on: Firebase billing + deploy access.
- Voice chat in rooms/Rush (needs a paid voice service). 1v1 voice done.
- Tournaments, battle pass/missions, clans, store/wallet, access codes/payments, support tickets, sponsors, spectator/replay, installable app.
