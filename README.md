# ProjetoAcademia — App

App mobile do Projeto Academia: o usuário cadastra fichas de treino, registra série a série com
timer de descanso e acompanha o progresso por treino, exercício, semana e cardio.

Domínio, stack e convenções estão no
[`Planejamento.md`](https://github.com/Zanatta97/ProjetoAcademia/blob/main/Planejamento.md) do repo
pai.

## Stack

- React Native + Expo (TypeScript), development build (não Expo Go)
- Expo Router
- `expo-sqlite` como banco local
- `expo-notifications`, `expo-audio` e `expo-haptics` para o timer de descanso
- `lucide-react-native`
- Jest (`jest-expo`) + React Native Testing Library

## Distribuição

Build interno (APK) instalado manualmente no aparelho. Toda versão nova precisa da mesma chave de
assinatura e de um `versionCode` maior.

## Como rodar

> A preencher quando o projeto Expo for criado (pré-requisitos, `npm install`, build de
> desenvolvimento).
