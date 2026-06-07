# TODO - Correção de mocks no Dashboard

- [x] Verificar e ajustar `src/pages/Dashboard.jsx` para parar de usar `MOCK` e buscar dados via API
- [x] Adicionar funções novas no `src/services/api.js` para buscar dados necessários do professor (perfil/stats/avisos/agenda)
- [x] Implementar chamadas `fetch` no `Dashboard.jsx` usando `token` do `AuthContext`
- [x] Remover `await` direto em JSX e usar estado (`useState`) + `useEffect`
- [x] Rodar o projeto (ex: `npm run dev`) e confirmar que os dados mudam após login


