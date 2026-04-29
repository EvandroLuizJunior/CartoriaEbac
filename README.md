<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=1E90FF&height=120&section=header"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=1E90FF&size=35&center=true&vCenter=true&width=1000&lines=HELLO,+My+name+is+Evandro+Junior;I'm+21+years+old;I'm+from+Brazil;Forming+Data+Scientist;Be+Welcome!+:%29)](https://git.io/typing-svg)


# modulo1
Atividade módulo 1 curso EBAC - TI Básico

## Ideia de evolução: aplicativo para leitura de dutos em DWG

Se você já tem códigos base e quer evoluir para um app que leia sistemas de dutos em `.dwg`, este é um caminho prático:

1. **Escolher stack**
   - Backend: `Python` (rápido para prototipar) ou `C#/.NET` (forte no desktop).
   - Frontend: `Qt`, `Electron` ou web app (`React` + API).

2. **Ler arquivos DWG**
   - Em geral, use biblioteca especializada (ex.: conversão DWG -> DXF para processamento).
   - Extraia entidades relevantes: `LINE`, `LWPOLYLINE`, `POLYLINE`, `BLOCK`, `TEXT`.

3. **Modelar a rede de dutos**
   - Converter geometria em grafo:
     - nós = conexões/interseções
     - arestas = trechos de duto
   - Calcular:
     - comprimento total
     - diâmetros por trecho
     - perdas estimadas (quando houver dados técnicos)

4. **Validações automáticas úteis**
   - trechos desconectados
   - loops inesperados
   - colisões / sobreposições
   - inconsistência de layer/padrão de desenho

5. **Saída do app**
   - relatório CSV/PDF
   - visualização com destaque de erros
   - exportação para DXF/JSON para integração com outros sistemas

## Próximo passo recomendado

Se quiser, posso te ajudar a montar um **MVP em etapas** usando seus códigos base:
- Etapa 1: importar DWG/DXF e listar entidades.
- Etapa 2: reconstruir conectividade dos dutos.
- Etapa 3: gerar relatório técnico automático.

