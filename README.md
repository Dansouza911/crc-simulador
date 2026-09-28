# ContaNexo Web — cópia de desenvolvimento

Esta pasta contém a primeira base navegável do ContaNexo para navegador. Ela importa as empresas, casos profissionais e 223 questões CFC da versão desktop e apresenta uma interface responsiva com dashboard, Minha Carteira, Casos Profissionais, Simulado CFC, Simulador MEI e Ranking.

## Execução local

Use um servidor HTTP na raiz da pasta:

```bash
python3 -m http.server 4173
```

Depois abra `http://localhost:4173`.

## Login de demonstração

- Aluno: `aluno@contanexo.local` / `contanexo123`
- Administrador: `admin@contanexo.local` / `admin123`

O login desta cópia é apenas uma demonstração local usando `localStorage`. Ele não é adequado para produção: ainda falta conectar um backend com banco, hash seguro de senha, sessões, recuperação de acesso, permissões administrativas e sincronização entre dispositivos.

A simulação do gov.br permanece fictícia. O sistema não deve solicitar ou armazenar credenciais reais nem transmitir dados ao governo.
