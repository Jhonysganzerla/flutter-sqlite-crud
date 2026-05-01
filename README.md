# flutter-sqlite-crud

Exemplo prático de CRUD em Flutter usando `sqflite` (SQLite local). Útil como referência para projetos pequenos com persistência offline.

## O que demonstra
- Migration inicial e operações CRUD em SQLite.
- Separação em camadas: `model` / `repository` / `ui`.
- Validação de formulário e tratamento de erro.

## Como rodar
```bash
flutter pub get
flutter run
```

## Estrutura
```
lib/
  models/        # entidades
  repositories/  # acesso ao SQLite
  pages/         # telas
  main.dart
```

## Licença
MIT.
