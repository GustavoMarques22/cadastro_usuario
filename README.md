# Cadastro de Usuário (Flutter)

Atividade prática de Desenvolvimento Mobile: tela de cadastro de usuário em Flutter, com captura dos dados, filtros de entrada, validação de cada campo e feedback visual.

## Campos

Nome completo, e-mail, CPF, telefone, senha e confirmação de senha.

## Validações

- Todos os campos são obrigatórios.
- O e-mail deve conter `@` e ter um formato válido (RegExp).
- CPF e telefone aceitam somente números (`FilteringTextInputFormatter.digitsOnly`).
- A senha deve ter no mínimo 6 caracteres e a confirmação deve ser igual.
- Os erros aparecem logo abaixo de cada campo inválido.
- SnackBar verde quando o cadastro é válido e vermelho quando há campos inválidos.
- Botão para mostrar/ocultar a senha.

## Resultado

<img width="1495" height="801" alt="image" src="https://github.com/user-attachments/assets/f993b721-ebeb-4693-9775-2bd8ac0a3d5b" />

## Como executar

```bash
flutter pub get
flutter run
```
