# GeoBusca CEP

Atividade Guiada: Integração com APIs.

Aplicação React criada com Vite para:
- buscar um endereço por CEP usando ViaCEP;
- converter o endereço em coordenadas com OpenCage;
- exibir a localização em mapa com React Leaflet / OpenStreetMap;
- salvar, editar, selecionar e remover endereços favoritos no `localStorage`.

## Como executar

1. Instale as dependências:

```bash
npm install
```

2. Copie `.env.example` para `.env` e substitua o valor da chave:

```env
VITE_OPENCAGE_API_KEY=SUA_CHAVE_AQUI
```

3. Rode o projeto:

```bash
npm run dev
```

## Repositório solicitado na atividade

`atividade-guiada-aula-05-frameworks-1`

> Observação: o arquivo `.env` não deve ser enviado ao GitHub. Envie o `.env.example`.
