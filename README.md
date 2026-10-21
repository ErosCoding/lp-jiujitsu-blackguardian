# Black Guardian Jiu-Jitsu · Landing page

Site estático (HTML + CSS + JS, sem build) da academia Black Guardian Jiu-Jitsu, Santa Terezinha, Belo Horizonte.

## Como editar

Tudo que muda com frequência fica no bloco `CONFIG`, no fim do `index.html`:

- `whatsapp`: número do professor (só dígitos, com 55 + DDD)
- `schedule`: grade de horários (um item por aula: horário e turma); os nomes das turmas ficam em `turmas`
- `photos`: caminho das fotos dos cards e da galeria (ex.: `assets/turma-adulta.jpg`)

As frases do mascote ficam na lista `lines`, no mesmo arquivo.

## Deploy

Hospedado na Vercel como site estático. Cada push na `main` publica a nova versão.
