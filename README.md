## 目的

vite with react-tsをベースとして、XStateとFirebaseの組み合わせについて動作検証をする

## ToDo

- [x] install xstate / @xstate/react
- [x] write sample XState machine in App.tsx
- [ ] write sample of sharing states between multiple components by XState
- [ ] install firebase
- [ ] set up firebase's local emulator
- [ ] set up some firestore data like chat rooms: rooms and messages
- [ ] implement states with messages and rooms that are connected firestore
- [ ] test that the listeners of firestore will be stopped when the component unmounted
- [ ] test the behavior: when where condition changed, the snapshot listeners will be correctly stopped, and new listener will be bind