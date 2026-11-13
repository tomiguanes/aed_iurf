# Preferencias pedagógicas y notas de trabajo

## Preferencias de enseñanza del estudiante
1. **Prosa continua, coherente y cohesiva**: En primera instancia, nunca explicar mediante listas, viñetas (ítems) ni gráficos. Toda explicación conceptual debe ser redactada en texto lineal, hilvanando las ideas de manera fluida para conectar el porqué detrás de cada concepto y cómo se fundamentan unos temas sobre otros.
2. **Método socrático estricto**: Avanzar mediante un diálogo de idas y vueltas con preguntas abiertas. No ofrecer opciones múltiples ni pistas que regalen la respuesta; el estudiante debe redactar la respuesta completa con sus propias palabras tal como le salga, y a partir de esa producción se pule y afina la precisión conceptual y formal.
3. **Alineación total con la cátedra del Prof. Mariano Fritz**:
   - Usar las definiciones exactas de la cátedra: por ejemplo, $O(g(n)) = \{f(n) : \exists c, n_0 \in \mathbb{R}^+ \text{ tales que } 0 \le f(n) \le c g(n), \forall n \ge n_0\}$.
   - En las refutaciones de pertenencia (ej. puntos 1 de [parciales.pdf](file:///home/antigravity/tomiguanes/aed_iurf/parciales.pdf)), usar la demostración por reducción al absurdo tal como se registró en [2026-06-19_-_Analisis_algoritmos.docx](file:///home/antigravity/tomiguanes/aed_iurf/2026-06-19_-_Analisis_algoritmos.docx) (suponer que existen $c, n_0 \in \mathbb{R}^+$, despejar hasta llegar a que una función creciente queda acotada por la constante $c$ para todo $n \ge n_0$, lo cual es un absurdo).
   - En la resolución de recurrencias, emplear el método de sustitución iterativa en función del paso $k$ y despeje del caso base ($n - k = 1$ o $n / 2^k = 1$), tal como se ve en [analisis_algoritmos_recursivos.docx](file:///home/antigravity/tomiguanes/aed_iurf/analisis_algoritmos_recursivos.docx).
   - Adaptar el uso de la skill `/teach` para que priorice este intercambio conversacional en prosa y socrático por encima de cuestionarios multiple-choice.
