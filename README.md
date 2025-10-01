```mermaid
gantt
    title Sistema de Biblioteca Online
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m
    %% Diminuir espaçamento vertical entre tarefas
    barHeight 20
    %% Remover cor de fundo das seções
    sectionPlaneColor transparent

    section Planejamento
    Levantamento de requisitos  :a1, 2025-10-01, 5d
    Definição da arquitetura    :a2, after a1, 4d

    section Desenvolvimento
    Backend                     :b1, after a2, 10d
    Frontend                    :b2, after b1, 8d

    section Testes
    Testes unitários            :c1, after b2, 5d
    Testes de integração        :c2, after c1, 6d

    section Implantação
    Deploy em homologação       :d1, after c2, 3d
    Deploy em produção          :d2, after d1, 2d



```
