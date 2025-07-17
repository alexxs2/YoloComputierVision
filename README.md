# Yolo Computier Vision
Durante este desafio, aprofundei-me nos três principais tipos de tarefas de visão computacional em deep learning: classificação, detecção e segmentação, focando, neste caso, na detecção de objetos. Para isso, elaborei todo o pipeline “do zero”:

- **Coleta de dados:** selecionei manualmente 406 imagens (203 de cães e 203 de gatos) no Google Imagens, seguindo boas práticas de diversidade (raças, cores, tamanhos, sexos, ângulos e poses distintas).

- **Anotação:** utilizei a plataforma CVAT para delimitar, em cada imagem, o objeto de interesse (cão ou gato) dentro de caixas delimitadoras, garantindo consistência e qualidade das marcações.

- **Divisão dos conjuntos:** reservei 15 % do total (64 imagens: 32 cães e 32 gatos) para validação e utilizei as 342 imagens restantes para treinamento.

- **Treinamento:** escolhi o modelo YOLOv8n, configurando-o para 10 000 épocas de treinamento com hiperparâmetros padrão do framework Ultralytics.

- **Avaliação prática:** após concluir o treinamento, apliquei os pesos finais em vídeos contendo cães e gatos para verificar a precisão e a robustez do detector em condições reais.

Com este projeto, consolidei minhas habilidades de pré‑processamento de dados, anotação de imagens e fine‑tuning de modelos de detecção em deep learning, além de entender na prática a importância de cada etapa do fluxo de trabalho para obter resultados confiáveis.
