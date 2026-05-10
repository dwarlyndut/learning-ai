# Roadmap · Aprender IA con foco en Big Tech

> Mapa vivo de los temas a cubrir. Marca con `[x]` lo que vas cubriendo.
> Cualquiera puede agregar temas nuevos. El orden es sugerido, no obligatorio.

**Niveles de prioridad:**
- 🔴 **Fundacional** — sin esto no se construye lo siguiente
- 🟡 **Importante** — necesario para roles técnicos en IA
- 🔵 **Avanzado** — diferenciador para big tech

---

## 1. Fundamentos matemáticos y de programación

- [ ] 🔴 Python a nivel intermedio (decoradores, generadores, type hints)
- [ ] 🔴 NumPy y operaciones vectorizadas
- [ ] 🔴 Pandas para manipulación de datos
- [ ] 🔴 Álgebra lineal aplicada (vectores, matrices, descomposición)
- [ ] 🟡 Cálculo: derivadas parciales, gradiente, regla de la cadena
- [ ] 🟡 Probabilidad y estadística: distribuciones, Bayes, MLE
- [ ] 🔵 Optimización: convexidad, métodos de descenso

## 2. Machine Learning clásico

- [ ] 🔴 Tipos de aprendizaje: supervisado, no supervisado, refuerzo
- [ ] 🔴 Regresión lineal y logística (entender la matemática, no solo usar sklearn)
- [ ] 🔴 Funciones de pérdida y descenso de gradiente
- [ ] 🔴 Overfitting, regularización (L1, L2), validación cruzada
- [ ] 🟡 Árboles de decisión, random forests, gradient boosting (XGBoost)
- [ ] 🟡 SVM, k-means, PCA
- [ ] 🟡 Métricas: accuracy, precision, recall, F1, AUC-ROC, confusion matrix
- [ ] 🔵 Bias-variance tradeoff a nivel teórico

## 3. Deep Learning

- [ ] 🔴 Perceptrón y redes neuronales feedforward
- [ ] 🔴 Backpropagation (entender cómo funciona, no solo usarlo)
- [ ] 🔴 Activaciones: ReLU, sigmoid, tanh, softmax
- [ ] 🟡 CNNs y aplicaciones en visión
- [ ] 🟡 RNNs, LSTM, GRU
- [ ] 🟡 Regularización en deep: dropout, batch normalization
- [ ] 🟡 PyTorch a nivel funcional (preferencia industria)
- [ ] 🔵 TensorFlow/JAX a nivel básico
- [ ] 🔵 Custom training loops, autograd interno

## 4. Transformers y LLMs

- [ ] 🔴 Mecanismo de atención (entenderlo a nivel matemático)
- [ ] 🔴 Arquitectura transformer: encoder, decoder, encoder-decoder
- [ ] 🔴 Self-attention vs cross-attention
- [ ] 🟡 Tokenización (BPE, WordPiece, SentencePiece)
- [ ] 🟡 Embeddings y posicional encoding
- [ ] 🟡 GPT vs BERT vs T5: diferencias arquitectónicas
- [ ] 🟡 Fine-tuning vs prompt-tuning vs LoRA
- [ ] 🔵 RLHF y constitutional AI
- [ ] 🔵 Mixture of Experts (MoE)
- [ ] 🔵 Long-context techniques (RoPE, ALiBi)

## 5. LLM Engineering aplicado

- [ ] 🔴 Prompt engineering: CoT, few-shot, role prompting
- [ ] 🔴 Uso de APIs (Anthropic, OpenAI) a nivel productivo
- [ ] 🟡 RAG (Retrieval Augmented Generation) end-to-end
- [ ] 🟡 Vector databases (pgvector, Pinecone, Weaviate)
- [ ] 🟡 Embeddings models: cuándo usar cada uno
- [ ] 🟡 Agentes: tool use, function calling, ReAct
- [ ] 🔵 MCP (Model Context Protocol)
- [ ] 🔵 Evaluación de LLMs: benchmarks, evals custom
- [ ] 🔵 Cost optimization en producción

## 6. MLOps y producción

- [ ] 🟡 Experimentación: MLflow, Weights & Biases
- [ ] 🟡 Versionado de modelos y datos (DVC)
- [ ] 🟡 Serving: FastAPI, vLLM, TGI
- [ ] 🟡 Containerización: Docker básico
- [ ] 🔵 Kubernetes para ML workloads
- [ ] 🔵 Distributed training (DDP, FSDP)
- [ ] 🔵 Monitoring: drift, performance, costs

## 7. System Design para roles ML

- [ ] 🔴 Diseñar un recommender system end-to-end
- [ ] 🔴 Diseñar un sistema de búsqueda semántica
- [ ] 🟡 Diseñar pipeline de datos para entrenar un modelo
- [ ] 🟡 Diseñar sistema de moderación con LLM
- [ ] 🔵 Diseñar plataforma multi-tenant de inferencia
- [ ] 🔵 Trade-offs: latencia vs throughput, costo vs calidad

## 8. Papers fundamentales

> Esta sección la va llenando el mentor con lo que considere crítico leer.

- [ ] *(Pendiente: M agrega papers prioritarios)*

## 9. Proyectos prácticos

> Tener proyectos en GitHub vale más que cualquier curso para big tech.

- [ ] Proyecto end-to-end: data → modelo → API → demo
- [ ] *(Más proyectos por definir con M)*

## 10. Soft skills técnicos para entrevistas

- [ ] 🔴 Explicar conceptos técnicos en inglés con claridad
- [ ] 🟡 System design interviews (formato big tech)
- [ ] 🟡 ML coding interviews (implementar algos desde cero)
- [ ] 🔵 Behavioral interviews estilo Amazon (STAR method)

---

## Notas

**[D]** Empiezo por fundamentos matemáticos + ML clásico antes de saltar a transformers.

**[M]** *(Pendiente: M agrega su recomendación de orden)*

---

*Última actualización: ver historial de Git*
