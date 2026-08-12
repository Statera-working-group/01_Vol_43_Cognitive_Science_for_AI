**Volume 43 Cognitive Science for AI**


# Chapter 11. Case Studies

##  

## 11.00 Case Study Overview

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

Case studies provide a practical bridge between cognitive science and artificial intelligence by examining how computational mechanisms resemble, approximate, or differ from human cognitive processes. Rather than treating AI concepts as isolated algorithms, a case-study approach places attention, memory, reasoning, retrieval, agency, error, and embodiment within concrete systems whose behavior can be observed and compared.

The purpose of these case studies is not to claim that artificial systems reproduce human cognition. Similar terminology can conceal fundamentally different mechanisms. Human attention emerges from biological perception, goals, memory, and limited cognitive resources, whereas attention in neural networks is a mathematical operation for weighting representations. Meaningful comparison therefore requires separating functional similarity from mechanistic equivalence.

Each case study can be understood through several complementary levels of analysis. At the behavioral level, the central question is what humans and AI systems can accomplish under comparable tasks. At the computational level, the focus shifts toward representations, information flow, optimization, and decision processes. At the cognitive level, the analysis asks whether observed behavior reflects comparable forms of memory, attention, reasoning, or adaptation.

Transformer attention and human attention provide a particularly useful example of this comparative method. Transformer attention dynamically assigns relevance among tokens or representations, enabling contextual information integration across sequences. Human attention also prioritizes information, but it is shaped by perception, goals, expectations, working-memory limits, emotion, and action. Their functional analogy is informative precisely because their mechanisms remain different.

Memory offers another important comparison. Human cognition includes sensory, working, episodic, semantic, and procedural forms of memory that interact across different timescales. AI systems distribute analogous functions across context windows, learned parameters, external databases, retrieval mechanisms, agent memory, and persistent state. Comparing these systems reveals both useful architectural correspondences and substantial differences in consolidation and experience.

Reasoning provides an especially challenging case because fluent outputs can create an impression of cognitive similarity. Chain-of-thought techniques expose intermediate textual steps that may improve performance on complex tasks, while human reasoning involves interacting processes such as working memory, mental models, inference, heuristics, metacognition, and uncertainty management. Observable reasoning traces therefore should not automatically be interpreted as direct representations of internal cognition.

Retrieval-Augmented Generation offers a useful engineering comparison with semantic memory. Human semantic memory supports access to accumulated conceptual knowledge without requiring conscious reconstruction of every learning episode. RAG systems retrieve relevant information from external stores and introduce it into the model\'s active context. The analogy clarifies how retrieval can extend limited internal state while also exposing differences in representation and grounding.

Agentic AI creates a broader comparison with cognitive architectures. Classical cognitive architectures attempt to integrate perception, memory, goals, reasoning, learning, and action within coordinated systems. Modern AI agents similarly combine language models with tools, retrieval, memory, planning, environmental observations, and feedback loops. Comparing these architectures helps identify which components are genuinely integrated and which remain loosely orchestrated modules.

Human error and model hallucination demonstrate why behavioral resemblance must be interpreted carefully. Humans can make errors because of incomplete knowledge, memory distortion, cognitive bias, limited attention, misleading context, or inappropriate heuristics. Generative models can produce unsupported outputs because probabilistic generation does not inherently guarantee factual grounding. Similar incorrect answers can therefore arise from very different underlying processes.

Robotics extends the comparison from abstract information processing to embodied cognition. An embodied agent must continuously connect perception, internal state, prediction, decision making, action, and environmental feedback. This perception-action loop makes cognition dependent on temporal continuity and physical consequences. Robotics therefore provides an important test of whether cognitive principles remain useful when intelligence must operate within a dynamic world.

The case studies also emphasize that cognition should be analyzed as an interacting system rather than as a collection of independent modules. Attention influences what enters working memory, memory affects reasoning, reasoning guides action, action changes future observations, and prediction connects present states with possible futures. AI architectures increasingly reproduce portions of this interaction through multimodal models, persistent memory, planning, tools, and world models.

A useful comparative framework must therefore consider capability, mechanism, representation, temporal behavior, resource constraints, learning, adaptation, and failure modes simultaneously. Two systems may achieve similar task accuracy while relying on completely different internal strategies. Conversely, systems with very different outward behavior may share useful computational principles. Case studies make these distinctions visible and discourage superficial one-to-one mappings between cognition and algorithms.

Experimental evidence is essential when evaluating such correspondences. Behavioral tasks, controlled perturbations, reaction patterns, error distributions, ablation studies, memory tests, attention analyses, and human-AI comparisons can reveal whether an apparent cognitive analogy has explanatory value. Reproducible experiments are particularly important because intuitive interpretations of complex AI behavior can easily exceed what observations actually demonstrate.

These comparisons also establish a practical connection between cognitive theory and AI engineering. Cognitive limitations suggest design requirements for interfaces, memory systems, reasoning workflows, uncertainty handling, and human oversight. Conversely, artificial systems provide computational environments in which hypotheses about attention, memory, reasoning, and coordinated cognition can be operationalized and tested, although computational success alone does not validate a psychological theory.

Across the chapter, the progression from attention and memory to reasoning, retrieval, agents, error, and embodiment gradually expands the unit of analysis. Early cases compare relatively focused mechanisms, while later cases examine integrated systems interacting with information, humans, tools, and physical environments. This progression reflects the broader movement from isolated cognitive functions toward architectures capable of maintaining coherent behavior over time.

Ultimately, these case studies provide a disciplined framework for learning from human cognition without assuming that artificial intelligence must imitate the human mind. Cognitive science supplies concepts, experiments, constraints, and organizational principles, while AI supplies computational models that can implement alternative solutions. Their comparison reveals where analogy is productive, where it breaks down, and where new architectures may emerge.

사례 연구(Case Studies)는 계산 메커니즘(Computational Mechanisms)이 인간의 인지 과정(Human Cognitive Processes)과 어떻게 유사하거나 근사하며, 또는 어떻게 다른지를 살펴봄으로써 인지과학(Cognitive Science)과 인공지능(Artificial Intelligence)을 실질적으로 연결하는 역할을 합니다. 사례 연구 접근법은 인공지능 개념을 개별 알고리즘으로만 다루지 않고 주의(Attention), 기억(Memory), 추론(Reasoning), 검색(Retrieval), 에이전시(Agency), 오류(Error), 체화(Embodiment)를 관찰하고 비교할 수 있는 구체적인 시스템 안에서 분석합니다.

이러한 사례 연구의 목적은 인공 시스템(Artificial Systems)이 인간의 인지(Human Cognition)를 그대로 재현한다고 주장하는 것이 아닙니다. 유사한 용어가 근본적으로 다른 메커니즘을 감출 수 있기 때문입니다. 인간의 주의(Human Attention)는 생물학적 지각(Biological Perception), 목표(Goals), 기억(Memory), 제한된 인지 자원(Cognitive Resources)에서 나타나는 반면, 신경망의 어텐션(Attention)은 표현(Representations)의 가중치를 조절하는 수학적 연산입니다. 따라서 의미 있는 비교를 위해서는 기능적 유사성(Functional Similarity)과 메커니즘적 동등성(Mechanistic Equivalence)을 구분해야 합니다.

각 사례 연구는 여러 상호보완적인 분석 수준(Levels of Analysis)을 통해 이해할 수 있습니다. 행동 수준(Behavioral Level)에서는 인간과 인공지능 시스템이 비교 가능한 과제에서 무엇을 수행할 수 있는지가 핵심 질문입니다. 계산 수준(Computational Level)에서는 표현(Representation), 정보 흐름(Information Flow), 최적화(Optimization), 의사결정 과정(Decision Processes)에 초점을 맞춥니다. 인지 수준(Cognitive Level)에서는 관찰된 행동이 유사한 형태의 기억, 주의, 추론 또는 적응(Adaptation)을 반영하는지를 분석합니다.

트랜스포머 어텐션(Transformer Attention)과 인간의 주의(Human Attention)는 이러한 비교 방법을 보여주는 특히 유용한 사례입니다. 트랜스포머 어텐션은 토큰(Token)이나 표현 사이의 관련성을 동적으로 할당하여 시퀀스(Sequence) 전체에서 문맥 정보를 통합합니다. 인간의 주의 역시 정보를 우선순위화하지만 지각(Perception), 목표, 기대(Expectations), 작업 기억(Working Memory)의 한계, 감정(Emotion), 행동(Action)의 영향을 받습니다. 따라서 두 시스템의 기능적 유사성은 유익하지만 그 메커니즘은 서로 다릅니다.

기억(Memory)은 또 다른 중요한 비교 영역을 제공합니다. 인간의 인지는 감각 기억(Sensory Memory), 작업 기억(Working Memory), 일화 기억(Episodic Memory), 의미 기억(Semantic Memory), 절차 기억(Procedural Memory)을 포함하며 이들은 서로 다른 시간 척도(Timescales)에서 상호작용합니다. 인공지능 시스템은 이와 유사한 기능을 컨텍스트 윈도(Context Window), 학습된 파라미터(Learned Parameters), 외부 데이터베이스(External Databases), 검색 메커니즘(Retrieval Mechanisms), 에이전트 기억(Agent Memory), 지속 상태(Persistent State)에 분산시킵니다. 이러한 비교는 유용한 구조적 대응 관계뿐 아니라 기억 공고화(Consolidation)와 경험(Experience) 측면의 중요한 차이도 보여줍니다.

추론(Reasoning)은 유창한 출력(Fluent Outputs)이 인지적 유사성에 대한 인상을 만들 수 있기 때문에 특히 어려운 비교 대상입니다. 사고의 연쇄(Chain-of-Thought) 기법은 복잡한 과제의 성능을 향상시킬 수 있는 중간 텍스트 단계(Intermediate Textual Steps)를 드러내는 반면, 인간의 추론은 작업 기억, 정신 모형(Mental Models), 추론(Inference), 휴리스틱(Heuristics), 메타인지(Metacognition), 불확실성 관리(Uncertainty Management)와 같은 상호작용하는 과정들을 포함합니다. 따라서 관찰 가능한 추론 과정(Reasoning Traces)을 내부 인지의 직접적인 표현으로 자동 해석해서는 안 됩니다.

검색 증강 생성(Retrieval-Augmented Generation, RAG)은 의미 기억(Semantic Memory)과 비교할 수 있는 유용한 공학적 사례입니다. 인간의 의미 기억은 모든 학습 경험을 의식적으로 재구성하지 않고도 축적된 개념적 지식(Conceptual Knowledge)에 접근할 수 있도록 합니다. RAG 시스템은 외부 저장소(External Stores)에서 관련 정보를 검색하고 이를 모델의 활성 컨텍스트(Active Context)에 제공합니다. 이러한 비유는 검색이 제한된 내부 상태(Internal State)를 어떻게 확장할 수 있는지를 설명하면서 표현과 그라운딩(Grounding)에서의 차이도 보여줍니다.

에이전틱 인공지능(Agentic AI)은 인지 아키텍처(Cognitive Architectures)와 더 광범위하게 비교할 수 있습니다. 고전적인 인지 아키텍처는 지각, 기억, 목표, 추론, 학습, 행동을 하나의 조정된 시스템으로 통합하려고 합니다. 현대의 인공지능 에이전트(AI Agents)도 언어 모델(Language Models)에 도구(Tools), 검색, 기억, 계획(Planning), 환경 관찰(Environmental Observations), 피드백 루프(Feedback Loops)를 결합합니다. 이러한 비교는 어떤 구성요소가 실제로 통합되어 있으며 어떤 요소가 느슨하게 조정된 모듈(Modules)에 머물러 있는지를 파악하는 데 도움을 줍니다.

인간 오류(Human Error)와 모델 환각(Model Hallucination)은 행동상의 유사성을 신중하게 해석해야 하는 이유를 보여줍니다. 인간은 불완전한 지식(Incomplete Knowledge), 기억 왜곡(Memory Distortion), 인지 편향(Cognitive Bias), 제한된 주의, 오도하는 문맥(Misleading Context), 부적절한 휴리스틱 때문에 오류를 범할 수 있습니다. 생성 모델(Generative Models)은 확률적 생성(Probabilistic Generation)이 본질적으로 사실적 근거(Factual Grounding)를 보장하지 않기 때문에 근거 없는 출력을 생성할 수 있습니다. 따라서 유사한 오답도 매우 다른 내부 과정에서 발생할 수 있습니다.

로보틱스(Robotics)는 추상적인 정보 처리에서 체화된 인지(Embodied Cognition)로 비교 범위를 확장합니다. 체화된 에이전트(Embodied Agent)는 지각, 내부 상태, 예측(Prediction), 의사결정(Decision Making), 행동, 환경 피드백(Environmental Feedback)을 지속적으로 연결해야 합니다. 이러한 지각-행동 루프(Perception-Action Loop)는 인지가 시간적 연속성(Temporal Continuity)과 물리적 결과(Physical Consequences)에 의존하도록 만듭니다. 따라서 로보틱스는 지능이 역동적인 현실 세계(Dynamic World)에서 작동해야 할 때 인지 원리가 여전히 유효한지를 검증하는 중요한 영역입니다.

사례 연구는 또한 인지를 독립적인 모듈들의 집합이 아니라 상호작용하는 시스템(Interacting System)으로 분석해야 한다는 점을 강조합니다. 주의는 작업 기억으로 들어오는 정보를 결정하고, 기억은 추론에 영향을 주며, 추론은 행동을 안내하고, 행동은 이후의 관찰을 변화시키며, 예측은 현재 상태와 가능한 미래를 연결합니다. 인공지능 아키텍처 역시 멀티모달 모델(Multimodal Models), 지속 기억(Persistent Memory), 계획, 도구, 월드 모델(World Models)을 통해 이러한 상호작용의 일부를 점차 구현하고 있습니다.

따라서 유용한 비교 프레임워크(Comparative Framework)는 능력(Capability), 메커니즘(Mechanism), 표현, 시간적 행동(Temporal Behavior), 자원 제약(Resource Constraints), 학습(Learning), 적응, 실패 모드(Failure Modes)를 동시에 고려해야 합니다. 두 시스템이 동일한 과제 정확도(Task Accuracy)를 달성하더라도 완전히 다른 내부 전략을 사용할 수 있습니다. 반대로 외형적으로 매우 다른 행동을 보이는 시스템들이 유용한 계산 원리(Computational Principles)를 공유할 수도 있습니다. 사례 연구는 이러한 차이를 드러내며 인지와 알고리즘 사이의 피상적인 일대일 대응을 피하도록 합니다.

이러한 대응 관계를 평가할 때는 실험적 증거(Experimental Evidence)가 필수적입니다. 행동 과제(Behavioral Tasks), 통제된 교란(Controlled Perturbations), 반응 패턴(Reaction Patterns), 오류 분포(Error Distributions), 절제 연구(Ablation Studies), 기억 검사(Memory Tests), 어텐션 분석(Attention Analysis), 인간-인공지능 비교(Human-AI Comparisons)는 겉으로 보이는 인지적 비유가 실제 설명력을 가지는지를 보여줄 수 있습니다. 복잡한 인공지능 행동에 대한 직관적인 해석은 실제 관찰 결과를 쉽게 넘어설 수 있기 때문에 재현 가능한 실험(Reproducible Experiments)이 특히 중요합니다.

이러한 비교는 인지 이론(Cognitive Theory)과 인공지능 공학(AI Engineering) 사이의 실질적인 연결도 형성합니다. 인지적 한계(Cognitive Limitations)는 인터페이스(Interfaces), 기억 시스템, 추론 워크플로(Reasoning Workflows), 불확실성 처리(Uncertainty Handling), 인간 감독(Human Oversight)의 설계 요구사항을 제시합니다. 반대로 인공 시스템은 주의, 기억, 추론, 통합된 인지(Coordinated Cognition)에 관한 가설을 계산적으로 구현하고 시험할 수 있는 환경을 제공하지만, 계산적 성공만으로 심리학적 이론(Psychological Theory)이 검증되는 것은 아닙니다.

이 장의 사례 연구는 주의와 기억에서 시작하여 추론, 검색, 에이전트, 오류, 체화로 진행하면서 분석 단위(Unit of Analysis)를 점진적으로 확장합니다. 초기 사례들은 비교적 집중된 개별 메커니즘을 비교하는 반면, 후반 사례들은 정보, 인간, 도구, 물리적 환경과 상호작용하는 통합 시스템(Integrated Systems)을 분석합니다. 이러한 진행 구조는 독립적인 인지 기능에서 시간에 걸쳐 일관된 행동(Coherent Behavior)을 유지할 수 있는 아키텍처로 발전하는 전체 흐름을 반영합니다.

궁극적으로 이러한 사례 연구는 인공지능이 인간의 마음(Human Mind)을 그대로 모방해야 한다고 가정하지 않으면서도 인간 인지로부터 체계적으로 학습할 수 있는 프레임워크를 제공합니다. 인지과학은 개념(Concepts), 실험(Experiments), 제약조건(Constraints), 조직 원리(Organizational Principles)를 제공하고, 인공지능은 대안적인 해결책을 구현할 수 있는 계산 모델(Computational Models)을 제공합니다. 두 영역의 비교를 통해 어떤 비유가 생산적인지, 어디에서 그 비유가 한계를 보이는지, 그리고 어디에서 새로운 인공지능 아키텍처(New AI Architectures)가 등장할 수 있는지를 이해할 수 있습니다.

##  

## 11.01 Transformer Attention vs Human Attention [w/Code]

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

Transformer attention and human attention are often compared because both mechanisms prioritize information that is relevant to current processing. In transformers, attention assigns weights among tokens or representations so that some elements contribute more strongly to the next computation. Human attention similarly selects information, but it operates within a broader cognitive system involving perception, goals, memory, expectations, and action.

The similarity is primarily functional rather than mechanistic. Transformer attention is implemented through mathematical operations such as queries, keys, values, similarity scores, normalization, and weighted aggregation. Human attention emerges from interacting neural and cognitive processes distributed across the brain. Therefore, comparable selective behavior does not imply that transformers reproduce biological attention or conscious awareness.

Self-attention allows each token in a sequence to evaluate its relationship with other tokens and construct a context-sensitive representation. This mechanism enables transformers to capture dependencies that may span long textual or multimodal sequences. Human attention can also relate currently observed information to broader context, but it is constrained by working memory, perceptual capacity, prior knowledge, motivation, and task demands.

Multi-head attention further expands transformer processing by allowing several attention patterns to operate in parallel. Different heads may emphasize syntactic relations, positional dependencies, semantic associations, or other statistical structures learned during training. Human attention also supports multiple forms of selection, including spatial, feature-based, object-based, and goal-directed attention, although these processes are not equivalent to transformer heads.

Human attention is strongly influenced by competition for limited cognitive resources. When several stimuli or tasks demand processing simultaneously, performance may decline because attention must be allocated selectively. Transformers also operate under computational limitations, but their constraints are different. Sequence length, memory bandwidth, attention complexity, model size, and inference cost determine how much contextual information can be processed efficiently.

Another major difference concerns goals and control. Human attention can be influenced by deliberate intentions as well as automatically captured by salient events. Top-down processes prioritize information according to goals, while bottom-up processes respond to unexpected or prominent stimuli. Transformer attention does not independently possess goals in this cognitive sense; its weighting patterns are produced by learned representations, current inputs, architecture, and optimization.

Memory interacts continuously with human attention. Previous experiences, semantic knowledge, current working-memory contents, and expectations influence what receives attention and how information is interpreted. Transformer attention also depends on available context and learned parameters, but this relationship differs from biological memory. A model attends to representations inside its computational context rather than recalling experiences through human episodic or semantic memory systems.

Temporal behavior further distinguishes the two systems. Human attention unfolds continuously as perception, cognition, and action change over time. Attention can shift, persist, divide, recover after interruption, and become fatigued. Standard transformer attention is usually computed over a defined set of representations during a processing step. Temporal continuity must therefore be introduced through sequence context, recurrent interaction, memory modules, or agent architectures.

Attention weights are sometimes interpreted as explanations of model behavior, but this interpretation requires caution. A high attention score indicates computational weighting within a particular layer and head, not necessarily causal importance or human-like focus. Different attention patterns may produce similar outputs, and important information can also be transformed through residual pathways, feed-forward networks, embeddings, and interactions across multiple layers.

Experimental comparison should therefore examine behavior rather than rely only on visual similarity between attention maps. Human studies may measure reaction time, eye movements, task accuracy, distraction effects, memory performance, or attentional shifts. Transformer studies can analyze attention distributions, ablations, perturbations, representation changes, and task performance. Comparing these results can reveal functional correspondences without assuming biological equivalence.

The comparison becomes especially valuable when studying cognitive limitations. Humans may overlook information because of selective attention, overload, distraction, or limited working memory. Transformers may fail because relevant context receives insufficient weighting, information lies outside the context window, representations interfere, or learned correlations are misleading. Similar errors may therefore appear at the behavioral level while originating from fundamentally different mechanisms.

From an AI design perspective, human attention suggests useful principles such as selective processing, resource allocation, hierarchical focus, context-sensitive prioritization, and interaction between perception and memory. Transformer attention provides a computational realization of selective information integration, but it represents only one possible engineering solution. Cognitive science can inspire broader architectures that combine attention with memory, goals, uncertainty, and action.

The most productive comparison treats transformer attention as an engineered information-selection mechanism and human attention as a complex cognitive function embedded within an adaptive organism. Their similarities help explain why selective processing is useful for intelligent systems, while their differences reveal important gaps in current AI. Understanding both sides can guide the development of more efficient, context-aware, adaptive, and cognitively informed AI architectures.

트랜스포머 어텐션(Transformer Attention)과 인간의 주의(Human Attention)는 두 메커니즘 모두 현재 처리 과정에서 관련성이 높은 정보에 우선순위를 부여한다는 점에서 자주 비교됩니다. 트랜스포머(Transformer)에서 어텐션은 토큰(Token)이나 표현(Representation) 사이에 가중치를 할당하여 특정 요소가 다음 계산 과정에 더 강하게 기여하도록 합니다. 인간의 주의도 정보를 선택하지만 지각(Perception), 목표(Goals), 기억(Memory), 기대(Expectations), 행동(Action)이 결합된 더 광범위한 인지 시스템(Cognitive System) 안에서 작동합니다.

두 시스템의 유사성은 주로 메커니즘적(Mechanistic)이라기보다 기능적(Functional)입니다. 트랜스포머 어텐션은 쿼리(Query), 키(Key), 값(Value), 유사도 점수(Similarity Scores), 정규화(Normalization), 가중 집계(Weighted Aggregation)와 같은 수학적 연산으로 구현됩니다. 인간의 주의는 뇌 전체에 분산된 신경 및 인지 과정(Neural and Cognitive Processes)의 상호작용으로 발생합니다. 따라서 유사한 선택적 행동(Selective Behavior)이 나타난다고 해서 트랜스포머가 생물학적 주의(Biological Attention)나 의식적 자각(Conscious Awareness)을 재현한다는 의미는 아닙니다.

셀프 어텐션(Self-Attention)은 시퀀스(Sequence)의 각 토큰이 다른 토큰과의 관계를 평가하고 문맥에 민감한 표현(Context-Sensitive Representation)을 구성하도록 합니다. 이러한 메커니즘을 통해 트랜스포머는 긴 텍스트 또는 멀티모달 시퀀스(Multimodal Sequence)에 걸친 의존 관계(Dependencies)를 포착할 수 있습니다. 인간의 주의 역시 현재 관찰되는 정보를 더 넓은 문맥과 연결할 수 있지만 작업 기억(Working Memory), 지각 능력(Perceptual Capacity), 사전 지식(Prior Knowledge), 동기(Motivation), 과제 요구사항(Task Demands)의 제약을 받습니다.

멀티헤드 어텐션(Multi-Head Attention)은 여러 어텐션 패턴(Attention Patterns)이 병렬로 작동하도록 하여 트랜스포머의 처리 능력을 더욱 확장합니다. 서로 다른 헤드(Head)는 구문적 관계(Syntactic Relations), 위치적 의존성(Positional Dependencies), 의미적 연관성(Semantic Associations), 또는 학습 과정에서 습득한 다른 통계적 구조(Statistical Structures)를 강조할 수 있습니다. 인간의 주의 역시 공간 기반 주의(Spatial Attention), 특징 기반 주의(Feature-Based Attention), 객체 기반 주의(Object-Based Attention), 목표 지향적 주의(Goal-Directed Attention) 등 다양한 형태의 선택을 지원하지만 이러한 과정이 트랜스포머의 어텐션 헤드와 동일한 것은 아닙니다.

인간의 주의는 제한된 인지 자원(Limited Cognitive Resources)을 둘러싼 경쟁의 영향을 크게 받습니다. 여러 자극이나 과제가 동시에 처리를 요구하면 주의를 선택적으로 배분해야 하기 때문에 수행 성능이 저하될 수 있습니다. 트랜스포머 역시 계산 자원(Computational Resources)의 한계를 가지지만 그 제약의 성격은 다릅니다. 시퀀스 길이(Sequence Length), 메모리 대역폭(Memory Bandwidth), 어텐션 복잡도(Attention Complexity), 모델 크기(Model Size), 추론 비용(Inference Cost)이 얼마나 많은 문맥 정보를 효율적으로 처리할 수 있는지를 결정합니다.

또 다른 중요한 차이는 목표(Goals)와 제어(Control)에 있습니다. 인간의 주의는 의도적인 목적에 의해 영향을 받을 수도 있으며 동시에 두드러진 사건(Salient Events)에 의해 자동으로 포착될 수도 있습니다. 하향식 과정(Top-Down Processes)은 목표에 따라 정보의 우선순위를 결정하고, 상향식 과정(Bottom-Up Processes)은 예상하지 못했거나 두드러진 자극에 반응합니다. 트랜스포머 어텐션은 이러한 인지적 의미에서 독립적인 목표를 가지지 않으며, 그 가중치 패턴은 학습된 표현, 현재 입력(Current Inputs), 아키텍처(Architecture), 최적화(Optimization)에 의해 생성됩니다.

기억(Memory)은 인간의 주의와 지속적으로 상호작용합니다. 이전 경험(Previous Experiences), 의미 지식(Semantic Knowledge), 현재 작업 기억의 내용, 기대는 무엇에 주의를 기울일지와 정보를 어떻게 해석할지에 영향을 줍니다. 트랜스포머 어텐션 역시 사용 가능한 컨텍스트(Context)와 학습된 파라미터(Learned Parameters)에 의존하지만 이러한 관계는 생물학적 기억과 다릅니다. 모델은 인간의 일화 기억(Episodic Memory)이나 의미 기억 시스템을 통해 경험을 회상하는 것이 아니라 계산 컨텍스트(Computational Context) 내부의 표현에 어텐션을 적용합니다.

시간적 행동(Temporal Behavior)은 두 시스템을 더욱 명확하게 구분합니다. 인간의 주의는 지각, 인지, 행동이 시간에 따라 변화하면서 지속적으로 전개됩니다. 주의는 이동하거나 유지되고, 분할되거나 방해 이후 회복될 수 있으며 피로(Fatigue)의 영향을 받을 수도 있습니다. 표준 트랜스포머 어텐션은 일반적으로 하나의 처리 단계에서 정의된 표현 집합을 대상으로 계산됩니다. 따라서 시간적 연속성(Temporal Continuity)을 구현하려면 시퀀스 컨텍스트(Sequence Context), 반복적 상호작용(Recurrent Interaction), 메모리 모듈(Memory Modules), 에이전트 아키텍처(Agent Architectures) 등을 추가해야 합니다.

어텐션 가중치(Attention Weights)는 때때로 모델 행동(Model Behavior)을 설명하는 수단으로 해석되지만 이러한 해석에는 주의가 필요합니다. 높은 어텐션 점수(Attention Score)는 특정 레이어(Layer)와 헤드에서의 계산적 가중치를 나타낼 뿐 반드시 인과적 중요성(Causal Importance)이나 인간과 같은 집중을 의미하지는 않습니다. 서로 다른 어텐션 패턴이 유사한 출력을 생성할 수 있으며 중요한 정보는 잔차 경로(Residual Pathways), 피드포워드 네트워크(Feed-Forward Networks), 임베딩(Embeddings), 여러 레이어 사이의 상호작용을 통해서도 변환될 수 있습니다.

따라서 실험적 비교(Experimental Comparison)는 단순히 어텐션 맵(Attention Maps)의 시각적 유사성에 의존하기보다 행동을 조사해야 합니다. 인간 연구에서는 반응 시간(Reaction Time), 안구 움직임(Eye Movements), 과제 정확도(Task Accuracy), 주의 분산 효과(Distraction Effects), 기억 성능(Memory Performance), 주의 전환(Attentional Shifts)을 측정할 수 있습니다. 트랜스포머 연구에서는 어텐션 분포(Attention Distributions), 절제 실험(Ablations), 교란(Perturbations), 표현 변화(Representation Changes), 과제 성능을 분석할 수 있습니다. 이러한 결과의 비교를 통해 생물학적 동등성을 가정하지 않고도 기능적 대응 관계(Functional Correspondences)를 발견할 수 있습니다.

이러한 비교는 인지적 한계(Cognitive Limitations)를 연구할 때 특히 유용합니다. 인간은 선택적 주의(Selective Attention), 과부하(Overload), 주의 분산(Distraction), 제한된 작업 기억으로 인해 정보를 놓칠 수 있습니다. 트랜스포머는 관련 컨텍스트에 충분한 가중치가 부여되지 않거나 정보가 컨텍스트 윈도(Context Window) 밖에 존재하거나 표현 간 간섭(Representation Interference)이 발생하거나 학습된 상관관계(Learned Correlations)가 잘못된 방향으로 작용하여 실패할 수 있습니다. 따라서 행동 수준에서는 유사한 오류가 나타나더라도 그 원인이 되는 메커니즘은 근본적으로 다를 수 있습니다.

인공지능 설계(AI Design)의 관점에서 인간의 주의는 선택적 처리(Selective Processing), 자원 할당(Resource Allocation), 계층적 집중(Hierarchical Focus), 문맥 기반 우선순위화(Context-Sensitive Prioritization), 지각과 기억의 상호작용과 같은 유용한 원리를 제시합니다. 트랜스포머 어텐션은 선택적인 정보 통합(Selective Information Integration)을 계산적으로 구현하지만 이는 가능한 공학적 해결책 가운데 하나일 뿐입니다. 인지과학은 어텐션을 기억, 목표, 불확실성(Uncertainty), 행동과 결합하는 더욱 광범위한 인공지능 아키텍처를 설계하는 데 영감을 제공할 수 있습니다.

가장 생산적인 비교 방법은 트랜스포머 어텐션을 공학적으로 설계된 정보 선택 메커니즘(Engineered Information-Selection Mechanism)으로 이해하고, 인간의 주의를 적응하는 유기체(Adaptive Organism) 안에 내재된 복잡한 인지 기능(Complex Cognitive Function)으로 이해하는 것입니다. 두 시스템의 유사성은 선택적 정보 처리가 지능형 시스템(Intelligent Systems)에 왜 유용한지를 설명하며, 두 시스템의 차이는 현재 인공지능이 가진 중요한 한계를 보여줍니다. 양쪽을 함께 이해하는 것은 더욱 효율적이고 문맥을 인식하며 적응 가능하고 인지과학적 원리를 반영하는 인공지능 아키텍처(Cognitively Informed AI Architectures)를 개발하는 데 중요한 기반을 제공합니다.

##  

## 11.02 LLM Memory vs Human Memory [w/Code]

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

Large language model memory and human memory are often compared because both support the use of past information to influence present behavior. However, the resemblance is mainly functional. Human memory emerges from biological processes that encode, consolidate, retrieve, reconstruct, and sometimes forget experiences. LLM memory is distributed across model parameters, context windows, retrieval systems, external storage, and persistent agent states.

Human memory is not a single storage mechanism but a collection of interacting systems. Sensory memory briefly preserves incoming perceptual information, working memory maintains information needed for current reasoning, episodic memory stores personally experienced events, semantic memory represents concepts and knowledge, and procedural memory supports learned skills. These systems operate over different timescales and contribute differently to cognition.

An LLM does not naturally possess these biological memory systems. Information acquired during training is primarily embedded statistically in model parameters, where patterns learned from large datasets influence future predictions. This parameter-based knowledge is sometimes compared with long-term semantic memory because it supports access to general information, but the analogy is limited because the model does not retrieve stored experiences in the same way humans do.

The context window provides another memory-like mechanism. Tokens from the current interaction remain available to the model and can influence later outputs through attention. This resembles working memory at a functional level because temporarily available information supports ongoing processing. However, a context window is an explicit computational buffer, whereas human working memory is dynamically controlled, capacity-limited, and deeply integrated with attention, goals, perception, and long-term memory.

Human episodic memory contains records of events associated with temporal, spatial, perceptual, and contextual information. Recollection can involve reconstructing what happened, where it occurred, and how different experiences relate to one another. Standard LLMs do not inherently maintain autobiographical episodes. Persistent agent systems can approximate episodic functionality by storing interaction histories, observations, actions, timestamps, and summaries in external memory structures.

Semantic memory offers one of the strongest functional parallels between humans and language models. Humans accumulate conceptual knowledge that can be accessed independently of the original learning episode. LLM parameters also encode distributed statistical relationships among words, concepts, facts, and patterns. Yet human semantic memory is grounded in lifelong perception and action, while language models may acquire much of their knowledge from symbolic or multimodal training data.

Retrieval-Augmented Generation extends LLM memory beyond internal parameters. A system can search vector databases, documents, knowledge bases, or other external repositories and insert relevant information into the active context. This architecture resembles memory retrieval because stored knowledge becomes available when needed. Nevertheless, retrieval quality depends on indexing, embeddings, similarity functions, query formulation, ranking, and the reliability of the external information source.

Human memory retrieval is strongly cue-dependent. A smell, location, word, emotional state, or current goal can activate related memories through associative processes. Retrieval in AI systems is also dependent on cues, but these cues are computationally represented through queries, embeddings, keys, metadata, or symbolic conditions. This similarity is useful for engineering, yet it does not imply that artificial retrieval reproduces the biological processes responsible for human remembering.

Forgetting also differs significantly between humans and LLM systems. Human forgetting can result from decay, interference, retrieval failure, reconstruction, changing context, or adaptive suppression of irrelevant information. Model parameters generally do not forget individual training examples through ordinary inference. Instead, information may become inaccessible, overwritten during further training, removed through editing, or excluded because it falls outside the current context or retrieval process.

Memory consolidation is another important distinction. Human memory changes after learning as experiences are stabilized, reorganized, integrated with prior knowledge, and sometimes replayed during rest or sleep. Artificial systems can implement analogous processes through replay buffers, periodic summarization, fine-tuning, continual learning, parameter updates, or memory compression. These mechanisms are engineered approximations rather than direct equivalents of biological consolidation.

Reconstruction is central to human remembering. People do not always retrieve exact copies of past events; instead, memory can be rebuilt from fragments, expectations, semantic knowledge, and current context. LLM generation is also reconstructive in a broad computational sense because outputs are generated from learned distributions rather than copied from a dedicated memory record. This similarity partly explains why fluent recall does not necessarily guarantee factual accuracy.

Memory errors therefore arise differently in humans and language models. Humans may confuse events, distort details, forget sources, or incorporate expectations into remembered experiences. LLMs may hallucinate unsupported information, merge related patterns incorrectly, retrieve irrelevant documents, or generate plausible but false continuations. Similar behavioral failures can emerge even though the underlying mechanisms of error are fundamentally different.

Agentic AI systems increasingly combine multiple memory layers to support longer-term behavior. Short-term context can maintain immediate state, external episodic stores can preserve previous interactions, vector databases can provide semantic retrieval, and structured records can maintain goals, plans, tools, or environmental state. This modular organization resembles the idea that intelligent behavior benefits from multiple specialized memory systems rather than a single uniform store.

Temporal state persistence is especially important for AI agents and embodied systems. A capable agent must remember what it observed, what actions it performed, what goals remain unfinished, and how the environment has changed. Human cognition performs this integration naturally across perception, memory, reasoning, and action. Artificial systems usually require explicit mechanisms for state tracking, memory selection, retrieval, summarization, and updating to achieve comparable continuity.

The most useful comparison therefore treats human memory as an adaptive biological system and LLM memory as a collection of computational mechanisms serving similar information-preservation functions. Human memory integrates experience, meaning, embodiment, emotion, and action, whereas LLM memory relies on parameters, context, retrieval, and external storage. Their comparison reveals valuable design principles while also clarifying where current AI remains fundamentally different from human cognition.

대규모 언어 모델 기억(Large Language Model Memory)과 인간 기억(Human Memory)은 모두 과거의 정보를 활용하여 현재의 행동에 영향을 준다는 점에서 자주 비교됩니다. 그러나 이러한 유사성은 주로 기능적(Functional)입니다. 인간 기억은 경험을 부호화(Encoding), 공고화(Consolidation), 검색(Retrieval), 재구성(Reconstruction)하고 때로는 망각(Forgetting)하는 생물학적 과정에서 발생합니다. 반면 LLM 기억은 모델 파라미터(Model Parameters), 컨텍스트 윈도(Context Windows), 검색 시스템(Retrieval Systems), 외부 저장소(External Storage), 지속적인 에이전트 상태(Persistent Agent States)에 분산되어 있습니다.

인간 기억은 하나의 저장 메커니즘(Storage Mechanism)이 아니라 서로 상호작용하는 여러 시스템의 집합입니다. 감각 기억(Sensory Memory)은 입력되는 지각 정보를 짧은 시간 동안 유지하고, 작업 기억(Working Memory)은 현재의 추론에 필요한 정보를 유지하며, 일화 기억(Episodic Memory)은 개인적으로 경험한 사건을 저장합니다. 의미 기억(Semantic Memory)은 개념과 지식을 표현하고, 절차 기억(Procedural Memory)은 학습된 기술을 지원합니다. 이러한 시스템은 서로 다른 시간 척도(Timescales)에서 작동하며 인지에 서로 다른 방식으로 기여합니다.

LLM은 이러한 생물학적 기억 시스템(Biological Memory Systems)을 자연적으로 가지고 있지 않습니다. 학습 과정에서 습득된 정보는 주로 모델 파라미터에 통계적으로 내재되며, 대규모 데이터셋에서 학습한 패턴이 이후의 예측(Prediction)에 영향을 줍니다. 이러한 파라미터 기반 지식(Parameter-Based Knowledge)은 일반적인 정보에 접근할 수 있다는 점에서 장기 의미 기억(Long-Term Semantic Memory)과 비교되기도 하지만, 모델이 인간과 동일한 방식으로 저장된 경험을 검색하는 것은 아니기 때문에 이러한 비유에는 한계가 있습니다.

컨텍스트 윈도(Context Window)는 또 다른 기억 유사 메커니즘(Memory-Like Mechanism)을 제공합니다. 현재 상호작용의 토큰(Token)은 모델이 사용할 수 있는 상태로 유지되며 어텐션(Attention)을 통해 이후의 출력에 영향을 줄 수 있습니다. 이는 일시적으로 사용 가능한 정보가 현재의 처리를 지원한다는 점에서 기능적으로 작업 기억과 유사합니다. 그러나 컨텍스트 윈도는 명시적인 계산 버퍼(Computational Buffer)인 반면, 인간의 작업 기억은 동적으로 제어되고 용량이 제한되며 주의, 목표, 지각, 장기 기억(Long-Term Memory)과 깊이 통합되어 있습니다.

인간의 일화 기억(Episodic Memory)은 시간적, 공간적, 지각적, 문맥적 정보와 연결된 사건의 기록을 포함합니다. 회상(Recollection)은 무엇이 발생했는지, 어디에서 발생했는지, 그리고 서로 다른 경험이 어떻게 연결되는지를 재구성하는 과정을 포함할 수 있습니다. 표준 LLM은 본질적으로 자전적 일화(Autobiographical Episodes)를 지속적으로 유지하지 않습니다. 그러나 지속형 에이전트 시스템(Persistent Agent Systems)은 상호작용 기록, 관찰(Observations), 행동(Actions), 타임스탬프(Timestamps), 요약(Summaries)을 외부 기억 구조에 저장하여 일화적 기능을 근사할 수 있습니다.

의미 기억(Semantic Memory)은 인간과 언어 모델 사이에서 가장 강력한 기능적 유사성을 보여주는 영역 가운데 하나입니다. 인간은 원래의 학습 경험과 독립적으로 접근할 수 있는 개념적 지식(Conceptual Knowledge)을 축적합니다. LLM의 파라미터 역시 단어, 개념, 사실, 패턴 사이의 분산된 통계적 관계(Distributed Statistical Relationships)를 부호화합니다. 그러나 인간의 의미 기억은 평생에 걸친 지각과 행동에 기반하는 반면, 언어 모델은 주로 기호적(Symbolic) 또는 멀티모달 학습 데이터(Multimodal Training Data)를 통해 지식을 습득할 수 있습니다.

검색 증강 생성(Retrieval-Augmented Generation, RAG)은 LLM의 기억을 내부 파라미터의 범위를 넘어 확장합니다. 시스템은 벡터 데이터베이스(Vector Databases), 문서(Documents), 지식 베이스(Knowledge Bases), 기타 외부 저장소를 검색하여 관련 정보를 활성 컨텍스트(Active Context)에 삽입할 수 있습니다. 이러한 아키텍처는 필요한 시점에 저장된 지식을 사용할 수 있다는 점에서 기억 검색(Memory Retrieval)과 유사합니다. 그러나 검색 품질은 인덱싱(Indexing), 임베딩(Embeddings), 유사도 함수(Similarity Functions), 질의 구성(Query Formulation), 순위화(Ranking), 외부 정보원의 신뢰성에 따라 달라집니다.

인간의 기억 검색은 단서 의존적(Cue-Dependent)인 특성이 강합니다. 냄새, 장소, 단어, 감정 상태(Emotional State), 현재의 목표 등이 연상 과정(Associative Processes)을 통해 관련 기억을 활성화할 수 있습니다. 인공지능 시스템의 검색 역시 단서에 의존하지만 이러한 단서는 쿼리(Queries), 임베딩, 키(Keys), 메타데이터(Metadata), 기호적 조건(Symbolic Conditions) 등을 통해 계산적으로 표현됩니다. 이러한 유사성은 공학적으로 유용하지만 인공 검색이 인간의 기억을 담당하는 생물학적 과정을 그대로 재현한다는 의미는 아닙니다.

망각(Forgetting) 역시 인간과 LLM 시스템에서 상당히 다르게 나타납니다. 인간의 망각은 쇠퇴(Decay), 간섭(Interference), 검색 실패(Retrieval Failure), 재구성, 문맥 변화(Changing Context), 관련성이 낮은 정보를 적응적으로 억제하는 과정에서 발생할 수 있습니다. 일반적인 추론(Inference) 과정에서 모델 파라미터가 개별 학습 사례를 직접 망각하는 것은 아닙니다. 대신 정보가 접근하기 어려워지거나 추가 학습 과정에서 덮어쓰이거나, 모델 편집(Model Editing)을 통해 제거되거나, 현재 컨텍스트 또는 검색 과정에서 제외될 수 있습니다.

기억 공고화(Memory Consolidation)는 또 다른 중요한 차이를 보여줍니다. 인간의 기억은 학습 이후 경험이 안정화되고, 재구성되며, 기존 지식과 통합되고, 때로는 휴식이나 수면 과정에서 재생(Replay)되면서 변화합니다. 인공 시스템에서는 리플레이 버퍼(Replay Buffers), 주기적 요약(Periodic Summarization), 미세조정(Fine-Tuning), 지속 학습(Continual Learning), 파라미터 업데이트(Parameter Updates), 기억 압축(Memory Compression)을 통해 이와 유사한 과정을 구현할 수 있습니다. 그러나 이러한 메커니즘은 생물학적 공고화의 직접적인 등가물이 아니라 공학적으로 설계된 근사 방법입니다.

재구성(Reconstruction)은 인간의 기억에서 핵심적인 특징입니다. 사람은 과거 사건을 항상 정확한 복사본으로 검색하는 것이 아니라 기억의 일부, 기대, 의미 지식, 현재의 문맥을 이용하여 기억을 다시 구성할 수 있습니다. LLM의 생성(Generation) 역시 전용 기억 기록을 그대로 복사하는 것이 아니라 학습된 분포(Learned Distributions)를 기반으로 출력을 생성한다는 점에서 넓은 계산적 의미에서 재구성적이라고 볼 수 있습니다. 이러한 유사성은 유창한 회상(Fluent Recall)이 반드시 사실적 정확성(Factual Accuracy)을 보장하지 않는 이유를 부분적으로 설명합니다.

따라서 기억 오류(Memory Errors)는 인간과 언어 모델에서 서로 다른 방식으로 발생합니다. 인간은 사건을 혼동하거나 세부 내용을 왜곡하고, 정보의 출처를 잊거나, 기대를 기억된 경험에 포함시킬 수 있습니다. LLM은 근거 없는 정보를 환각(Hallucination)하거나 관련된 패턴을 잘못 결합하고, 부적절한 문서를 검색하거나, 그럴듯하지만 잘못된 문장을 생성할 수 있습니다. 행동 수준(Behavioral Level)에서 유사한 실패가 나타날 수 있지만 그 오류를 발생시키는 내부 메커니즘은 근본적으로 다릅니다.

에이전틱 인공지능 시스템(Agentic AI Systems)은 장기간의 행동을 지원하기 위해 점차 여러 기억 계층(Memory Layers)을 결합하고 있습니다. 단기 컨텍스트(Short-Term Context)는 즉각적인 상태를 유지하고, 외부 일화 저장소(External Episodic Stores)는 이전 상호작용을 보존하며, 벡터 데이터베이스는 의미적 검색(Semantic Retrieval)을 제공합니다. 또한 구조화된 기록(Structured Records)은 목표, 계획(Plans), 도구(Tools), 환경 상태(Environmental State)를 유지할 수 있습니다. 이러한 모듈식 구성(Modular Organization)은 지능적 행동이 하나의 균일한 저장소보다 여러 전문화된 기억 시스템의 도움을 받을 수 있다는 개념과 유사합니다.

시간적 상태 지속성(Temporal State Persistence)은 인공지능 에이전트와 체화된 시스템(Embodied Systems)에서 특히 중요합니다. 유능한 에이전트는 무엇을 관찰했는지, 어떤 행동을 수행했는지, 어떤 목표가 아직 완료되지 않았는지, 그리고 환경이 어떻게 변화했는지를 기억해야 합니다. 인간의 인지는 지각, 기억, 추론, 행동에 걸쳐 이러한 정보를 자연스럽게 통합합니다. 인공 시스템이 이와 유사한 연속성(Continuity)을 구현하려면 일반적으로 상태 추적(State Tracking), 기억 선택(Memory Selection), 검색, 요약, 업데이트를 위한 명시적인 메커니즘이 필요합니다.

따라서 가장 유용한 비교 방법은 인간 기억을 적응적인 생물학적 시스템(Adaptive Biological System)으로 이해하고, LLM 기억을 유사한 정보 보존 기능(Information-Preservation Functions)을 수행하는 여러 계산 메커니즘(Computational Mechanisms)의 집합으로 이해하는 것입니다. 인간 기억은 경험, 의미(Meaning), 체화(Embodiment), 감정(Emotion), 행동을 통합하는 반면, LLM 기억은 파라미터, 컨텍스트, 검색, 외부 저장소에 의존합니다. 두 시스템의 비교는 유용한 설계 원리(Design Principles)를 발견하게 하는 동시에 현재 인공지능이 인간 인지와 근본적으로 다른 부분을 명확하게 보여줍니다.

##  

## 11.03 Chain of Thought vs Human Reasoning [w/Code]

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

Chain-of-Thought reasoning and human reasoning are often compared because both can express problem solving as a sequence of intermediate steps. A language model may decompose a question, generate intermediate propositions, evaluate possible relationships, and produce a final answer. Humans can also reason through sequential steps, but human reasoning arises from a broader cognitive system involving perception, memory, goals, knowledge, emotion, and metacognition.

Chain-of-Thought, commonly abbreviated as CoT, is a prompting and reasoning approach in which intermediate textual steps are generated before or alongside an answer. Instead of mapping a complex problem directly to a conclusion, the model can represent useful intermediate relationships within its generated sequence. This additional computational trajectory can improve performance on tasks involving arithmetic, logic, planning, and multi-step inference.

The apparent similarity between CoT and human reasoning should not be interpreted as mechanistic equivalence. Human reasoning involves neural processes whose internal operations are not simply sentences spoken internally. Language, imagery, concepts, spatial representations, memories, emotions, and implicit associations can all participate in reasoning. CoT, by contrast, represents reasoning-related computation through generated tokens and learned statistical relationships among representations.

Human reasoning is commonly described through multiple forms of inference. Deductive reasoning derives conclusions from premises, inductive reasoning generalizes from observations, abductive reasoning searches for plausible explanations, and analogical reasoning transfers relational structures between situations. Humans also use causal reasoning and planning. Language models can exhibit behavior corresponding to these forms, although success varies substantially with task structure, training, prompting, and available context.

Working memory plays a central role in human reasoning because intermediate information must often remain accessible while a problem is being solved. People maintain assumptions, partial results, goals, and constraints while shifting attention among them. CoT provides an artificial functional analogue by placing intermediate information into the generated context, where subsequent tokens can condition on previous reasoning steps and preserve a temporary computational trajectory.

This externalized intermediate representation can be particularly useful for decomposition. A difficult problem may be separated into smaller subproblems whose outputs become inputs to later stages. Human problem solvers similarly use decomposition, notes, diagrams, equations, or verbal rehearsal to reduce cognitive load. In LLM systems, decomposition can extend beyond a single CoT sequence through planners, tools, search procedures, external memory, and specialized reasoning modules.

Human reasoning is not always deliberate or sequential. Many judgments occur rapidly through learned patterns, heuristics, intuition, and automatic processes, while other problems require slower and more controlled reasoning. This distinction is often associated with dual-process theories of cognition. LLM behavior can also vary between direct responses and extended inference procedures, but this computational distinction should not automatically be identified with human intuitive and deliberative cognitive systems.

Metacognition provides another important difference. Humans can sometimes evaluate their own uncertainty, recognize confusion, reconsider assumptions, change strategies, and decide that additional information is necessary. LLM reasoning systems can approximate some of these functions through self-evaluation, critique, verification, reflection, or iterative generation. However, these procedures are engineered computational loops and should not automatically be interpreted as human-like self-awareness.

The reliability of a reasoning trace also requires careful interpretation. A coherent sequence of intermediate statements may lead to an incorrect conclusion, while a correct answer may sometimes be accompanied by an imperfect explanation. Generated reasoning can contain unsupported assumptions, arithmetic errors, invalid logical transitions, or post-hoc rationalizations. Consequently, the apparent plausibility of a textual reasoning chain is not sufficient evidence that the underlying computation is correct.

Human reasoning is similarly fallible, but its characteristic failures arise from cognitive mechanisms such as confirmation bias, anchoring, availability, framing effects, limited working memory, and inappropriate heuristics. LLMs may instead fail because of misleading statistical associations, inadequate context, representation errors, weak decomposition, accumulated generation errors, or unreliable intermediate steps. Similar incorrect conclusions can therefore originate from substantially different mechanisms.

Reasoning performance can be improved by introducing mechanisms that evaluate alternatives rather than committing immediately to one trajectory. AI systems may generate multiple candidate solutions, compare intermediate states, search among possible reasoning paths, use external tools, retrieve relevant evidence, or verify calculations. These approaches broaden reasoning beyond a single linear CoT and move toward architectures in which generation, evaluation, search, memory, and feedback interact.

Human reasoning also depends strongly on knowledge and grounding. People reason using concepts acquired through language, perception, social interaction, physical experience, and repeated action in the world. Language models acquire structured statistical knowledge from training data and may additionally receive multimodal inputs, retrieved documents, tool outputs, or environmental observations. Similar reasoning performance therefore does not imply equivalent experiential foundations or representations.

Experimental comparison should focus on observable capabilities and failure patterns rather than assuming that generated text directly reveals internal cognition. Researchers can compare accuracy, response consistency, sensitivity to problem formulation, intermediate errors, transfer across tasks, uncertainty calibration, and performance under limited information. Controlled perturbations and ablation studies can further reveal which contextual or computational components contribute to successful reasoning.

For AI engineering, the comparison with human reasoning suggests several useful principles: decompose complex problems, preserve relevant intermediate state, evaluate alternative hypotheses, verify uncertain conclusions, integrate external knowledge, and revise decisions when evidence changes. These principles can be implemented through CoT, retrieval, tool use, search, memory, planning, self-evaluation, or combinations of several mechanisms rather than relying on one reasoning technique alone.

The most useful interpretation is therefore that Chain-of-Thought provides a computational method for organizing intermediate reasoning-related information, while human reasoning is a multidimensional cognitive process embedded within memory, perception, goals, experience, and action. Comparing them helps identify functional similarities without confusing textual reasoning traces with human thought, and it provides a foundation for designing more robust reasoning-aware AI systems.

사고의 연쇄(Chain-of-Thought) 추론과 인간 추론(Human Reasoning)은 모두 문제 해결 과정을 일련의 중간 단계(Intermediate Steps)로 표현할 수 있다는 점에서 자주 비교됩니다. 언어 모델(Language Model)은 질문을 분해하고, 중간 명제(Intermediate Propositions)를 생성하며, 가능한 관계를 평가한 후 최종 답변을 생성할 수 있습니다. 인간 역시 순차적인 단계를 통해 추론할 수 있지만, 인간의 추론은 지각(Perception), 기억(Memory), 목표(Goals), 지식(Knowledge), 감정(Emotion), 메타인지(Metacognition)를 포함하는 더 광범위한 인지 시스템(Cognitive System)에서 발생합니다.

일반적으로 CoT로 약칭되는 사고의 연쇄(Chain-of-Thought)는 답변을 생성하기 전이나 답변과 함께 중간의 텍스트 단계(Intermediate Textual Steps)를 생성하는 프롬프팅 및 추론 접근법(Prompting and Reasoning Approach)입니다. 복잡한 문제를 직접 결론으로 연결하는 대신 모델은 생성 시퀀스(Generated Sequence) 안에서 유용한 중간 관계를 표현할 수 있습니다. 이러한 추가적인 계산 경로(Computational Trajectory)는 산술(Arithmetic), 논리(Logic), 계획(Planning), 다단계 추론(Multi-Step Inference)이 필요한 과제의 성능을 향상시킬 수 있습니다.

CoT와 인간 추론 사이에서 나타나는 외형적 유사성을 메커니즘적 동등성(Mechanistic Equivalence)으로 해석해서는 안 됩니다. 인간의 추론에는 내부 연산이 단순히 머릿속에서 발화되는 문장으로만 이루어지지 않는 신경 과정(Neural Processes)이 관여합니다. 언어(Language), 심상(Imagery), 개념(Concepts), 공간적 표현(Spatial Representations), 기억, 감정, 암묵적 연상(Implicit Associations)이 모두 추론에 참여할 수 있습니다. 반면 CoT는 생성된 토큰(Generated Tokens)과 표현 사이에서 학습된 통계적 관계(Statistical Relationships)를 통해 추론 관련 계산을 표현합니다.

인간의 추론은 일반적으로 여러 형태의 추론 방식(Inference)으로 설명됩니다. 연역적 추론(Deductive Reasoning)은 전제(Premises)에서 결론을 도출하고, 귀납적 추론(Inductive Reasoning)은 관찰 결과로부터 일반화하며, 귀추적 추론(Abductive Reasoning)은 가능한 설명을 탐색하고, 유추적 추론(Analogical Reasoning)은 상황 사이의 관계적 구조(Relational Structures)를 전이합니다. 인간은 또한 인과 추론(Causal Reasoning)과 계획을 사용합니다. 언어 모델 역시 이러한 형태에 대응하는 행동을 보일 수 있지만 성공 수준은 과제 구조(Task Structure), 학습(Training), 프롬프팅(Prompting), 사용 가능한 컨텍스트(Context)에 따라 크게 달라집니다.

작업 기억(Working Memory)은 문제를 해결하는 동안 중간 정보를 접근 가능한 상태로 유지해야 하기 때문에 인간의 추론에서 핵심적인 역할을 합니다. 사람은 가정(Assumptions), 부분적인 결과(Partial Results), 목표, 제약조건(Constraints)을 유지하면서 이들 사이에서 주의를 전환합니다. CoT는 중간 정보를 생성된 컨텍스트에 배치함으로써 이러한 기능에 대한 인공적인 기능적 유사체(Functional Analogue)를 제공합니다. 이후 토큰은 이전 추론 단계에 조건화될 수 있으며 일시적인 계산 경로를 유지할 수 있습니다.

이렇게 외부화된 중간 표현(Externalized Intermediate Representation)은 특히 문제 분해(Decomposition)에 유용할 수 있습니다. 어려운 문제를 여러 개의 작은 하위 문제(Subproblems)로 나누고 각각의 결과를 이후 단계의 입력으로 사용할 수 있습니다. 인간의 문제 해결자도 인지 부하(Cognitive Load)를 줄이기 위해 문제 분해, 메모(Notes), 다이어그램(Diagrams), 방정식(Equations), 언어적 반복(Verbal Rehearsal)을 사용합니다. LLM 시스템에서는 계획기(Planners), 도구(Tools), 탐색 절차(Search Procedures), 외부 기억(External Memory), 전문화된 추론 모듈(Specialized Reasoning Modules)을 통해 단일 CoT 시퀀스를 넘어 문제 분해를 확장할 수 있습니다.

인간의 추론이 항상 의도적이거나 순차적인 것은 아닙니다. 많은 판단은 학습된 패턴(Learned Patterns), 휴리스틱(Heuristics), 직관(Intuition), 자동적 과정(Automatic Processes)을 통해 빠르게 이루어지는 반면, 일부 문제는 더 느리고 통제된 추론(Controlled Reasoning)을 요구합니다. 이러한 구분은 흔히 인지과학의 이중 과정 이론(Dual-Process Theories)과 관련됩니다. LLM의 행동 역시 직접적인 응답과 확장된 추론 절차(Extended Inference Procedures) 사이에서 달라질 수 있지만 이러한 계산적 차이를 인간의 직관적 및 숙고적 인지 시스템과 자동으로 동일시해서는 안 됩니다.

메타인지(Metacognition)는 또 하나의 중요한 차이를 보여줍니다. 인간은 자신의 불확실성(Uncertainty)을 평가하고, 혼란을 인식하며, 가정을 다시 검토하고, 전략을 변경하며, 추가 정보가 필요하다고 판단할 수 있습니다. LLM 추론 시스템은 자기 평가(Self-Evaluation), 비평(Critique), 검증(Verification), 성찰(Reflection), 반복적 생성(Iterative Generation)을 통해 이러한 기능의 일부를 근사할 수 있습니다. 그러나 이러한 절차는 공학적으로 설계된 계산 루프(Computational Loops)이며 인간과 같은 자기 인식(Self-Awareness)으로 자동 해석해서는 안 됩니다.

추론 과정(Reasoning Trace)의 신뢰성 역시 신중하게 해석해야 합니다. 일관성 있어 보이는 중간 진술의 연속이 잘못된 결론으로 이어질 수 있으며, 반대로 올바른 답변에 불완전한 설명이 동반되는 경우도 있습니다. 생성된 추론에는 근거 없는 가정(Unsupported Assumptions), 산술 오류(Arithmetic Errors), 잘못된 논리적 전환(Invalid Logical Transitions), 사후 합리화(Post-Hoc Rationalizations)가 포함될 수 있습니다. 따라서 텍스트 추론 연쇄(Textual Reasoning Chain)가 그럴듯하게 보인다는 사실만으로 내부 계산이 올바르다는 충분한 증거가 되지는 않습니다.

인간의 추론 역시 오류를 일으킬 수 있지만 대표적인 실패는 확증 편향(Confirmation Bias), 앵커링(Anchoring), 가용성 편향(Availability), 프레이밍 효과(Framing Effects), 제한된 작업 기억, 부적절한 휴리스틱과 같은 인지 메커니즘에서 발생합니다. 반면 LLM은 잘못된 통계적 연관성(Misleading Statistical Associations), 불충분한 컨텍스트(Inadequate Context), 표현 오류(Representation Errors), 불완전한 문제 분해(Weak Decomposition), 누적된 생성 오류(Accumulated Generation Errors), 신뢰할 수 없는 중간 단계 때문에 실패할 수 있습니다. 따라서 유사한 오답이라도 상당히 다른 메커니즘에서 발생할 수 있습니다.

하나의 추론 경로에 즉시 의존하지 않고 여러 대안을 평가하는 메커니즘을 도입하면 추론 성능(Reasoning Performance)을 향상시킬 수 있습니다. 인공지능 시스템은 여러 후보 해결책(Candidate Solutions)을 생성하고, 중간 상태(Intermediate States)를 비교하며, 가능한 추론 경로를 탐색하고, 외부 도구를 사용하거나 관련 증거를 검색하며 계산 결과를 검증할 수 있습니다. 이러한 접근법은 추론을 하나의 선형적인 CoT에서 확장하여 생성(Generation), 평가(Evaluation), 탐색(Search), 기억, 피드백(Feedback)이 상호작용하는 아키텍처로 발전시킵니다.

인간의 추론은 지식과 그라운딩(Grounding)에도 크게 의존합니다. 사람은 언어, 지각, 사회적 상호작용(Social Interaction), 물리적 경험(Physical Experience), 현실 세계에서의 반복적인 행동을 통해 습득한 개념을 사용하여 추론합니다. 언어 모델은 학습 데이터로부터 구조화된 통계적 지식(Structured Statistical Knowledge)을 습득하며 추가적으로 멀티모달 입력(Multimodal Inputs), 검색된 문서(Retrieved Documents), 도구 출력(Tool Outputs), 환경 관찰(Environmental Observations)을 제공받을 수 있습니다. 따라서 유사한 추론 성능이 나타나더라도 동일한 경험적 기반(Experiential Foundations)이나 표현을 가지고 있다는 의미는 아닙니다.

실험적 비교(Experimental Comparison)는 생성된 텍스트가 내부 인지를 직접적으로 보여준다고 가정하기보다 관찰 가능한 능력(Observable Capabilities)과 실패 패턴(Failure Patterns)에 초점을 맞추어야 합니다. 연구자는 정확도(Accuracy), 응답 일관성(Response Consistency), 문제 표현 방식에 대한 민감도, 중간 오류(Intermediate Errors), 과제 간 전이(Transfer Across Tasks), 불확실성 보정(Uncertainty Calibration), 제한된 정보에서의 성능을 비교할 수 있습니다. 통제된 교란(Controlled Perturbations)과 절제 연구(Ablation Studies)를 통해 어떤 문맥적 또는 계산적 구성요소가 성공적인 추론에 기여하는지도 분석할 수 있습니다.

인공지능 공학(AI Engineering)의 관점에서 인간 추론과의 비교는 복잡한 문제를 분해하고, 관련된 중간 상태를 유지하며, 대안 가설(Alternative Hypotheses)을 평가하고, 불확실한 결론을 검증하며, 외부 지식(External Knowledge)을 통합하고, 증거가 변경되면 결정을 수정해야 한다는 유용한 원리를 제시합니다. 이러한 원리는 하나의 추론 기법에만 의존하지 않고 CoT, 검색(Retrieval), 도구 사용(Tool Use), 탐색, 기억, 계획, 자기 평가 또는 여러 메커니즘의 조합을 통해 구현할 수 있습니다.

따라서 가장 유용한 해석은 사고의 연쇄(Chain-of-Thought)를 추론과 관련된 중간 정보를 구성하기 위한 계산적 방법(Computational Method)으로 이해하고, 인간 추론을 기억, 지각, 목표, 경험, 행동에 내재된 다차원적 인지 과정(Multidimensional Cognitive Process)으로 이해하는 것입니다. 두 시스템을 비교하면 텍스트 형태의 추론 과정(Textual Reasoning Traces)을 인간의 사고(Human Thought)와 혼동하지 않으면서 기능적 유사성을 파악할 수 있으며, 더욱 견고하고 추론 능력을 고려한 인공지능 시스템(Reasoning-Aware AI Systems)을 설계하기 위한 기반을 마련할 수 있습니다.

##  

## 11.04 RAG vs Semantic Memory [w/Code]

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

Retrieval-Augmented Generation, or RAG, and human semantic memory are often compared because both allow an intelligent system to access previously acquired knowledge when responding to a current task. RAG retrieves relevant information from external sources and places it into the model's active context, while semantic memory allows humans to access concepts, facts, meanings, and relationships accumulated across experience.

Human semantic memory is part of long-term memory and differs from episodic memory because it stores generalized knowledge rather than records of specific personal events. A person may know that water freezes near zero degrees Celsius without remembering when that fact was first learned. Semantic memory therefore supports stable conceptual knowledge that can be reused across many different situations and reasoning tasks.

RAG provides a computational mechanism that performs a somewhat similar function by separating stored knowledge from the language model's internal parameters. Documents, knowledge bases, databases, or other repositories can be indexed and searched when needed. Retrieved information is inserted into the context window so that the model can condition its generation on relevant external evidence rather than relying only on parametric knowledge.

The similarity between RAG and semantic memory is mainly functional rather than mechanistic. Human semantic knowledge is represented through distributed neural systems shaped by perception, language, action, education, and social experience. RAG instead depends on engineered components such as document segmentation, embeddings, indexes, similarity search, ranking, query generation, and context construction. Similar information-access behavior therefore arises from fundamentally different mechanisms.

Retrieval cues are important in both systems. Human semantic memory may be activated by words, concepts, questions, goals, or associations that bring related knowledge into awareness. In RAG systems, the user query or an automatically generated search query is converted into a computational representation used to retrieve matching information. The usefulness of retrieval depends strongly on whether the query activates the appropriate knowledge.

Association also provides an important point of comparison. Human semantic knowledge is organized through networks of related concepts, allowing one idea to activate related ideas through meaning and prior learning. Vector-based RAG approximates this behavior by mapping text into embedding spaces where semantically related items may appear near one another. Similarity in embedding space, however, is a mathematical approximation rather than a direct model of human conceptual organization.

Human semantic memory usually contains abstracted knowledge that has been integrated across many experiences. Repeated encounters with objects, language, categories, and relationships gradually support stable concepts that are not tied to one source document. RAG systems often preserve information in explicit external records, meaning that retrieval may return passages, chunks, or structured entries whose content remains closely associated with particular documents or databases.

Knowledge updating also differs substantially. Human semantic memory changes gradually as new experiences modify existing concepts, correct misconceptions, or introduce new relationships. RAG systems can update more directly by adding, deleting, or replacing external documents without retraining the underlying language model. This modularity is one of the major engineering advantages of retrieval-based architectures when knowledge changes frequently.

RAG can also improve traceability because retrieved passages can provide explicit evidence for generated answers. Human semantic memory often does not preserve a reliable record of where a fact originally came from, producing source-memory errors even when the knowledge itself is correct. In contrast, a well-designed RAG system can retain document identifiers, metadata, timestamps, or citations that help users inspect the origin of retrieved information.

However, retrieval does not guarantee correctness. A RAG system may retrieve irrelevant documents, miss important evidence, select outdated information, rank weak matches too highly, or provide context that the language model interprets incorrectly. Human semantic memory can also produce errors through incomplete knowledge, interference, conceptual confusion, outdated beliefs, or distorted associations. Similar failures may therefore appear despite different underlying causes.

The context window creates another important distinction. Retrieved information must normally be inserted into a limited active context before an LLM can use it effectively. Human semantic memory does not operate through a fixed textual context window, although attention and working memory constrain how much retrieved knowledge can be actively manipulated at once. RAG therefore separates long-term external storage from limited short-term computational access.

Advanced RAG architectures increasingly incorporate multiple retrieval stages, query rewriting, reranking, metadata filtering, knowledge graphs, memory stores, and iterative search. These mechanisms move RAG beyond simple nearest-neighbor retrieval toward more structured knowledge access. Human semantic retrieval is likewise influenced by context, goals, associations, and prior activation, suggesting that intelligent retrieval benefits from dynamic control rather than one-shot lookup.

For agentic AI, RAG can function as one layer within a larger memory architecture. Immediate context can represent short-term state, external interaction histories can approximate episodic memory, and retrieval systems can provide semantic knowledge. Structured databases may maintain goals, tools, plans, or world state. Combining these layers allows artificial agents to maintain more persistent and context-sensitive behavior across extended tasks.

The comparison between RAG and semantic memory also highlights the importance of grounding. Human concepts are shaped by embodied perception, communication, social interaction, and repeated encounters with the world. RAG can ground language-model outputs in external records, but those records remain computational representations. Multimodal retrieval, tool use, and environmental interaction can broaden this grounding, yet they still differ from human lived experience.

The most useful interpretation is therefore that RAG provides an engineered retrieval mechanism that performs some functions analogous to semantic memory without reproducing human memory itself. Both systems support access to stored knowledge, cue-dependent retrieval, and context-sensitive reasoning, but they differ in representation, learning, updating, grounding, and failure modes. Their comparison offers useful principles for designing more reliable knowledge-aware AI systems.

검색 증강 생성(Retrieval-Augmented Generation, RAG)과 인간의 의미 기억(Human Semantic Memory)은 모두 지능형 시스템(Intelligent System)이 현재의 과제에 대응할 때 이전에 습득한 지식에 접근할 수 있도록 한다는 점에서 자주 비교됩니다. RAG는 외부 정보원(External Sources)에서 관련 정보를 검색하여 모델의 활성 컨텍스트(Active Context)에 제공하는 반면, 의미 기억은 인간이 경험을 통해 축적한 개념(Concepts), 사실(Facts), 의미(Meanings), 관계(Relationships)에 접근할 수 있도록 합니다.

인간의 의미 기억(Semantic Memory)은 장기 기억(Long-Term Memory)의 일부이며 특정한 개인적 사건의 기록보다 일반화된 지식(Generalized Knowledge)을 저장한다는 점에서 일화 기억(Episodic Memory)과 구별됩니다. 사람은 어떤 시점에 그 사실을 처음 배웠는지를 기억하지 못하더라도 물이 섭씨 약 0도에서 언다는 사실을 알고 있을 수 있습니다. 따라서 의미 기억은 다양한 상황과 추론 과제에서 반복적으로 활용할 수 있는 안정적인 개념적 지식(Conceptual Knowledge)을 지원합니다.

RAG는 저장된 지식(Stored Knowledge)을 언어 모델의 내부 파라미터(Internal Parameters)와 분리함으로써 이와 어느 정도 유사한 기능을 수행하는 계산 메커니즘(Computational Mechanism)을 제공합니다. 문서(Documents), 지식 베이스(Knowledge Bases), 데이터베이스(Databases), 기타 저장소를 인덱싱(Indexing)하고 필요할 때 검색할 수 있습니다. 검색된 정보는 컨텍스트 윈도(Context Window)에 삽입되어 모델이 파라미터 지식(Parametric Knowledge)에만 의존하지 않고 관련된 외부 증거(External Evidence)를 기반으로 출력을 생성할 수 있도록 합니다.

RAG와 의미 기억의 유사성은 메커니즘적(Mechanistic)이라기보다 주로 기능적(Functional)입니다. 인간의 의미 지식(Semantic Knowledge)은 지각(Perception), 언어(Language), 행동(Action), 교육(Education), 사회적 경험(Social Experience)에 의해 형성되는 분산된 신경 시스템(Distributed Neural Systems)을 통해 표현됩니다. 반면 RAG는 문서 분할(Document Segmentation), 임베딩(Embeddings), 인덱스(Indexes), 유사도 검색(Similarity Search), 순위화(Ranking), 쿼리 생성(Query Generation), 컨텍스트 구성(Context Construction)과 같은 공학적으로 설계된 구성요소에 의존합니다. 따라서 유사한 정보 접근 행동은 근본적으로 다른 메커니즘에서 발생합니다.

검색 단서(Retrieval Cues)는 두 시스템 모두에서 중요합니다. 인간의 의미 기억은 단어, 개념, 질문, 목표 또는 연상(Associations)에 의해 활성화되어 관련 지식이 의식적으로 접근 가능한 상태가 될 수 있습니다. RAG 시스템에서는 사용자 질의(User Query) 또는 자동으로 생성된 검색 질의가 계산적 표현(Computational Representation)으로 변환되고 이를 이용하여 일치하는 정보를 검색합니다. 검색의 유용성은 질의가 적절한 지식을 얼마나 정확하게 활성화하는지에 크게 좌우됩니다.

연상(Association) 역시 중요한 비교 지점을 제공합니다. 인간의 의미 지식은 서로 관련된 개념들의 네트워크(Networks of Related Concepts)를 통해 구성되며, 하나의 아이디어가 의미와 이전 학습을 통해 관련된 다른 아이디어를 활성화할 수 있습니다. 벡터 기반 RAG(Vector-Based RAG)는 텍스트를 임베딩 공간(Embedding Space)에 매핑하여 의미적으로 관련된 항목들이 서로 가까운 위치에 나타나도록 함으로써 이러한 행동을 근사합니다. 그러나 임베딩 공간에서의 유사성은 인간의 개념 조직(Conceptual Organization)을 직접적으로 구현한 것이 아니라 수학적으로 근사한 것입니다.

인간의 의미 기억은 일반적으로 여러 경험에 걸쳐 통합된 추상화된 지식(Abstracted Knowledge)을 포함합니다. 객체, 언어, 범주(Categories), 관계를 반복적으로 경험하면서 특정한 하나의 정보원에 종속되지 않는 안정적인 개념이 점진적으로 형성됩니다. 반면 RAG 시스템은 정보를 명시적인 외부 기록(Explicit External Records)으로 보존하는 경우가 많기 때문에 검색 결과는 특정 문서나 데이터베이스와 밀접하게 연결된 구절(Passages), 청크(Chunks), 구조화된 항목(Structured Entries)의 형태로 반환될 수 있습니다.

지식 업데이트(Knowledge Updating) 방식에서도 상당한 차이가 존재합니다. 인간의 의미 기억은 새로운 경험이 기존 개념을 수정하고, 잘못된 이해를 교정하며, 새로운 관계를 추가하면서 점진적으로 변화합니다. RAG 시스템에서는 기반 언어 모델(Underlying Language Model)을 다시 학습하지 않고도 외부 문서를 추가하거나 삭제하고 교체함으로써 지식을 보다 직접적으로 업데이트할 수 있습니다. 이러한 모듈성(Modularity)은 지식이 자주 변화하는 환경에서 검색 기반 아키텍처(Retrieval-Based Architectures)가 제공하는 중요한 공학적 장점 가운데 하나입니다.

RAG는 검색된 구절이 생성된 답변의 명시적인 증거(Explicit Evidence)를 제공할 수 있기 때문에 추적 가능성(Traceability)을 향상시킬 수도 있습니다. 인간의 의미 기억은 어떤 사실을 처음 어디에서 습득했는지에 대한 신뢰할 수 있는 기록을 항상 유지하지 않기 때문에 지식 자체는 정확하더라도 출처 기억 오류(Source-Memory Errors)가 발생할 수 있습니다. 반면 잘 설계된 RAG 시스템은 문서 식별자(Document Identifiers), 메타데이터(Metadata), 타임스탬프(Timestamps), 인용(Citations)을 유지하여 사용자가 검색된 정보의 출처를 확인할 수 있도록 할 수 있습니다.

그러나 검색(Retrieval)이 정확성을 보장하는 것은 아닙니다. RAG 시스템은 관련성이 낮은 문서를 검색하거나 중요한 증거를 놓칠 수 있으며, 오래된 정보(Outdated Information)를 선택하거나 관련성이 낮은 결과의 순위를 지나치게 높게 평가하거나, 언어 모델이 검색된 컨텍스트를 잘못 해석할 수도 있습니다. 인간의 의미 기억 역시 불완전한 지식(Incomplete Knowledge), 간섭(Interference), 개념적 혼동(Conceptual Confusion), 오래된 믿음(Outdated Beliefs), 왜곡된 연상(Distorted Associations)으로 인해 오류를 발생시킬 수 있습니다. 따라서 서로 다른 내부 원인에도 불구하고 유사한 실패가 나타날 수 있습니다.

컨텍스트 윈도(Context Window)는 또 다른 중요한 차이를 만들어냅니다. 검색된 정보는 일반적으로 LLM이 효과적으로 활용할 수 있도록 제한된 활성 컨텍스트에 삽입되어야 합니다. 인간의 의미 기억은 고정된 텍스트 컨텍스트 윈도를 통해 작동하지 않지만 주의(Attention)와 작업 기억(Working Memory)은 한 번에 능동적으로 처리할 수 있는 지식의 양을 제한합니다. 따라서 RAG는 장기적인 외부 저장(Long-Term External Storage)과 제한된 단기 계산 접근(Short-Term Computational Access)을 명확하게 분리합니다.

고급 RAG 아키텍처(Advanced RAG Architectures)는 점차 다단계 검색(Multi-Stage Retrieval), 쿼리 재작성(Query Rewriting), 재순위화(Reranking), 메타데이터 필터링(Metadata Filtering), 지식 그래프(Knowledge Graphs), 메모리 저장소(Memory Stores), 반복적 검색(Iterative Search)을 통합하고 있습니다. 이러한 메커니즘은 RAG를 단순한 최근접 이웃 검색(Nearest-Neighbor Retrieval)에서 보다 구조화된 지식 접근(Structured Knowledge Access) 방식으로 확장합니다. 인간의 의미 검색 역시 문맥, 목표, 연상, 이전 활성화(Prior Activation)의 영향을 받기 때문에 지능적인 검색에는 단발성 조회(One-Shot Lookup)보다 동적인 제어(Dynamic Control)가 중요하다는 점을 보여줍니다.

에이전틱 인공지능(Agentic AI)에서 RAG는 더 큰 기억 아키텍처(Memory Architecture)를 구성하는 하나의 계층으로 기능할 수 있습니다. 즉각적인 컨텍스트는 단기 상태(Short-Term State)를 표현하고, 외부 상호작용 기록(External Interaction Histories)은 일화 기억을 근사하며, 검색 시스템은 의미 지식을 제공할 수 있습니다. 구조화된 데이터베이스는 목표(Goals), 도구(Tools), 계획(Plans), 월드 상태(World State)를 유지할 수도 있습니다. 이러한 계층을 결합하면 인공 에이전트(Artificial Agents)가 장시간에 걸친 과제에서도 더욱 지속적이고 문맥에 민감한 행동(Context-Sensitive Behavior)을 유지할 수 있습니다.

RAG와 의미 기억의 비교는 그라운딩(Grounding)의 중요성도 보여줍니다. 인간의 개념은 체화된 지각(Embodied Perception), 의사소통(Communication), 사회적 상호작용, 현실 세계와의 반복적인 접촉을 통해 형성됩니다. RAG는 언어 모델의 출력을 외부 기록에 근거하도록 만들 수 있지만 이러한 기록 역시 계산적 표현입니다. 멀티모달 검색(Multimodal Retrieval), 도구 사용(Tool Use), 환경과의 상호작용(Environmental Interaction)은 이러한 그라운딩을 확장할 수 있지만 여전히 인간의 실제 경험(Lived Experience)과는 차이가 있습니다.

따라서 가장 유용한 해석은 RAG를 인간의 기억 자체를 재현하지 않으면서 의미 기억과 유사한 일부 기능을 수행하는 공학적으로 설계된 검색 메커니즘(Engineered Retrieval Mechanism)으로 이해하는 것입니다. 두 시스템 모두 저장된 지식에 대한 접근, 단서 의존적 검색(Cue-Dependent Retrieval), 문맥에 민감한 추론(Context-Sensitive Reasoning)을 지원하지만 표현(Representation), 학습(Learning), 업데이트(Updating), 그라운딩, 실패 모드(Failure Modes)에서는 차이가 있습니다. 이러한 비교는 보다 신뢰할 수 있는 지식 인식 인공지능 시스템(Knowledge-Aware AI Systems)을 설계하기 위한 유용한 원리를 제공합니다.

##  

## 11.05 Agents vs Cognitive Architectures [w/Code]

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

Modern AI agents and classical cognitive architectures are often compared because both attempt to coordinate multiple capabilities into systems that can perceive information, maintain state, pursue goals, reason about alternatives, and select actions. AI agents typically combine language models with tools, memory, planning, retrieval, and environmental feedback, while cognitive architectures were developed to model how integrated human-like cognition may emerge from interacting functional components.

A cognitive architecture is more than a collection of independent algorithms. Frameworks such as SOAR, ACT-R, CLARION, LIDA, and related approaches define organized mechanisms for memory, attention, learning, reasoning, goal management, and action selection. Their purpose is often explanatory as well as computational: they attempt to describe recurring structural principles of cognition rather than merely optimize performance on one task.

Modern AI agents are usually engineered from a different starting point. A foundation model or large language model often serves as the central reasoning and language component, while external modules provide retrieval, tool execution, planning, memory, perception, or control. The resulting system can interact with software services, documents, databases, simulated environments, or physical robots, enabling behavior that extends beyond a single model invocation.

The functional similarity between agents and cognitive architectures is strongest at the system level. Both approaches recognize that intelligent behavior requires coordination among specialized functions. Perception provides information, memory preserves relevant state, goals determine priorities, reasoning evaluates alternatives, and action changes the environment. Intelligence therefore emerges not from one isolated capability but from repeated interaction among multiple processes over time.

Their internal organization, however, can differ substantially. Cognitive architectures often specify explicit modules and control rules derived from theories of cognition. An AI agent may instead rely on prompts, model outputs, tool APIs, vector stores, planners, and orchestration logic. The architecture may be highly modular, but its components are usually selected for engineering effectiveness rather than for direct correspondence with psychological or neurological mechanisms.

Memory illustrates this contrast clearly. Cognitive architectures commonly distinguish working memory, declarative memory, procedural knowledge, and other specialized stores. Agentic AI may implement short-term context, vector databases, episodic interaction logs, structured state, and persistent profiles. These mechanisms can perform analogous roles, but the representations, updating processes, retrieval rules, and failure modes are often fundamentally different.

Goal management is another shared requirement. Cognitive architectures often maintain explicit goals, subgoals, production rules, or activation structures that determine what processing occurs next. AI agents can maintain objectives in prompts, plans, task graphs, state machines, or external memory. Complex tasks may be decomposed into subtasks, monitored for completion, and revised when tools fail or new information changes the situation.

Planning also reveals both similarity and difference. Classical cognitive systems may combine symbolic search, production systems, or procedural knowledge to determine actions. Contemporary agents frequently ask language models to propose plans, generate steps, select tools, or revise strategies. More advanced systems can incorporate explicit search, simulation, world models, constraint solvers, or reinforcement-learning policies rather than relying entirely on linguistic planning.

Action selection is central to both architectures because cognition becomes operational only when a system chooses what to do next. A cognitive architecture may use conflict resolution, activation levels, utility estimates, or procedural rules. An AI agent may select among API calls, retrieval operations, messages, code execution, navigation commands, or physical actions based on model outputs and external control logic.

Feedback closes the cognitive loop. After an action is performed, the resulting observation can update memory, alter beliefs, modify the plan, or change the next action. This perceive-reason-act-update cycle appears in both cognitive architectures and agentic AI. Persistent behavior requires repeated state transitions rather than a single input-output transformation, which is why temporal continuity is a defining property of both system types.

Learning introduces a major difference in many current implementations. Cognitive architectures often include explicit theories of skill acquisition, reinforcement, chunking, activation change, or memory adaptation. Many deployed AI agents use a largely fixed pretrained model during operation and adapt primarily through context, retrieval, or stored interaction history. Continual learning can be added, but it is often separated from real-time agent execution.

Metacognitive functions provide another useful comparison. Human-inspired architectures may include monitoring of goals, conflicts, uncertainty, or cognitive control. AI agents can approximate similar functions through self-evaluation, reflection, critic modules, verification stages, or supervisory agents. These mechanisms can detect failures and trigger replanning, although they remain engineered control processes rather than evidence of human-like self-awareness.

The comparison becomes especially interesting in multi-agent systems. Human cognition coordinates many functional processes within one organism, while agentic AI can distribute capabilities across several specialized agents. One agent may plan, another retrieve evidence, another execute tools, and another evaluate results. This distributed arrangement can increase modularity and parallelism, although coordination overhead and inconsistent internal state can introduce new failure modes.

Embodied agents bring the comparison even closer to cognitive architecture research because perception and action must operate continuously in a physical environment. A robot may integrate cameras, LiDAR, proprioception, world models, memory, planning, and control while pursuing goals under uncertainty. In such systems, cognition cannot be separated cleanly from timing, embodiment, environmental dynamics, and the consequences of physical action.

Evaluation should therefore consider architecture-level behavior rather than isolated benchmark accuracy. Important questions include whether the system maintains coherent goals, preserves relevant state, recovers from failed actions, adapts to changing conditions, selects appropriate tools, manages uncertainty, and avoids repeating errors. Cognitive architectures provide useful concepts for evaluating these properties because they emphasize integrated behavior across time.

For AI engineering, cognitive architectures offer organizational principles that can guide agent design without requiring literal imitation of the human mind. Specialized memory, explicit state representation, hierarchical goals, controlled attention, planning, feedback, learning, and metacognitive monitoring can all improve robustness. Modern foundation models can then serve as flexible components within broader architectures rather than being treated as complete cognitive systems by themselves.

The most useful interpretation is therefore that cognitive architectures provide theories and structural models of integrated cognition, while AI agents provide engineered systems for coordinated goal-directed computation and action. Their comparison reveals substantial functional overlap but different origins, representations, and design objectives. Combining insights from both can support more persistent, adaptive, interpretable, and cognitively organized artificial agents.

현대의 인공지능 에이전트(AI Agents)와 고전적인 인지 아키텍처(Cognitive Architectures)는 모두 여러 능력을 조정하여 정보를 지각하고, 상태를 유지하며, 목표를 추구하고, 대안을 추론하며, 행동을 선택할 수 있는 시스템을 구현하려 한다는 점에서 자주 비교됩니다. AI 에이전트는 일반적으로 언어 모델(Language Models)에 도구(Tools), 기억(Memory), 계획(Planning), 검색(Retrieval), 환경 피드백(Environmental Feedback)을 결합하는 반면, 인지 아키텍처는 상호작용하는 기능적 구성요소를 통해 통합된 인간형 인지(Human-Like Cognition)가 어떻게 나타날 수 있는지를 모델링하기 위해 개발되었습니다.

인지 아키텍처(Cognitive Architecture)는 단순히 독립적인 알고리즘들을 모아 놓은 것 이상의 의미를 가집니다. SOAR, ACT-R, CLARION, LIDA와 같은 프레임워크는 기억, 주의(Attention), 학습(Learning), 추론(Reasoning), 목표 관리(Goal Management), 행동 선택(Action Selection)을 위한 체계적인 메커니즘을 정의합니다. 이러한 아키텍처의 목적은 계산적일 뿐만 아니라 설명적이기도 하며, 하나의 과제 성능만 최적화하기보다 인지의 반복적인 구조적 원리(Structural Principles)를 설명하려고 합니다.

현대의 AI 에이전트는 일반적으로 이와 다른 출발점에서 공학적으로 설계됩니다. 파운데이션 모델(Foundation Model) 또는 대규모 언어 모델(Large Language Model)이 핵심 추론 및 언어 구성요소로 사용되는 경우가 많으며, 외부 모듈(External Modules)이 검색, 도구 실행(Tool Execution), 계획, 기억, 지각(Perception), 제어(Control)를 제공합니다. 이렇게 구성된 시스템은 소프트웨어 서비스, 문서, 데이터베이스, 시뮬레이션 환경(Simulated Environments), 물리적 로봇(Physical Robots)과 상호작용할 수 있어 단일 모델 호출을 넘어서는 행동을 수행할 수 있습니다.

에이전트와 인지 아키텍처 사이의 기능적 유사성(Functional Similarity)은 시스템 수준(System Level)에서 가장 분명하게 나타납니다. 두 접근법 모두 지능적 행동(Intelligent Behavior)을 위해 전문화된 기능 사이의 조정이 필요하다는 점을 인식합니다. 지각은 정보를 제공하고, 기억은 관련 상태를 보존하며, 목표는 우선순위를 결정하고, 추론은 대안을 평가하며, 행동은 환경을 변화시킵니다. 따라서 지능은 하나의 고립된 능력이 아니라 시간에 따라 여러 과정이 반복적으로 상호작용하면서 나타납니다.

그러나 두 시스템의 내부 구성(Internal Organization)은 상당히 다를 수 있습니다. 인지 아키텍처는 흔히 인지 이론(Cognitive Theories)에서 도출된 명시적인 모듈(Explicit Modules)과 제어 규칙(Control Rules)을 정의합니다. 반면 AI 에이전트는 프롬프트(Prompts), 모델 출력(Model Outputs), 도구 API(Tool APIs), 벡터 저장소(Vector Stores), 계획기(Planners), 오케스트레이션 로직(Orchestration Logic)에 의존할 수 있습니다. 이러한 구조 역시 높은 모듈성을 가질 수 있지만 구성요소는 심리학적 또는 신경학적 메커니즘과의 직접적인 대응보다는 공학적 효과를 기준으로 선택되는 경우가 많습니다.

기억(Memory)은 이러한 차이를 명확하게 보여줍니다. 인지 아키텍처는 일반적으로 작업 기억(Working Memory), 선언적 기억(Declarative Memory), 절차적 지식(Procedural Knowledge), 기타 전문화된 저장소를 구분합니다. 에이전틱 인공지능(Agentic AI)은 단기 컨텍스트(Short-Term Context), 벡터 데이터베이스(Vector Databases), 일화적 상호작용 로그(Episodic Interaction Logs), 구조화된 상태(Structured State), 지속 프로파일(Persistent Profiles)을 구현할 수 있습니다. 이들은 유사한 역할을 수행할 수 있지만 표현 방식, 업데이트 과정, 검색 규칙(Retrieval Rules), 실패 모드(Failure Modes)는 근본적으로 다를 수 있습니다.

목표 관리(Goal Management)는 두 시스템이 공유하는 또 하나의 핵심 요구사항입니다. 인지 아키텍처는 흔히 명시적인 목표, 하위 목표(Subgoals), 생성 규칙(Production Rules), 활성화 구조(Activation Structures)를 유지하여 다음에 어떤 처리가 수행될지를 결정합니다. AI 에이전트는 프롬프트, 계획, 태스크 그래프(Task Graphs), 상태 머신(State Machines), 외부 기억에 목표를 유지할 수 있습니다. 복잡한 과제는 하위 과제(Subtasks)로 분해되고 완료 여부를 추적할 수 있으며, 도구가 실패하거나 새로운 정보에 의해 상황이 변하면 계획을 수정할 수 있습니다.

계획(Planning) 역시 유사성과 차이를 동시에 보여줍니다. 고전적인 인지 시스템은 행동을 결정하기 위해 기호적 탐색(Symbolic Search), 생성 시스템(Production Systems), 절차적 지식 등을 결합할 수 있습니다. 현대의 에이전트는 언어 모델을 이용하여 계획을 제안하고, 단계를 생성하며, 도구를 선택하거나 전략을 수정하는 경우가 많습니다. 더욱 발전된 시스템은 언어적 계획에만 의존하지 않고 명시적 탐색(Explicit Search), 시뮬레이션(Simulation), 월드 모델(World Models), 제약조건 해결기(Constraint Solvers), 강화학습 정책(Reinforcement-Learning Policies)을 통합할 수 있습니다.

행동 선택(Action Selection)은 두 아키텍처 모두에서 핵심적입니다. 시스템이 다음에 무엇을 수행할 것인지 결정해야만 인지가 실제 행동으로 이어질 수 있기 때문입니다. 인지 아키텍처는 충돌 해결(Conflict Resolution), 활성화 수준(Activation Levels), 효용 추정(Utility Estimates), 절차적 규칙(Procedural Rules)을 사용할 수 있습니다. AI 에이전트는 모델 출력과 외부 제어 로직을 기반으로 API 호출, 검색 작업, 메시지, 코드 실행(Code Execution), 내비게이션 명령(Navigation Commands), 물리적 행동 가운데 하나를 선택할 수 있습니다.

피드백(Feedback)은 인지 루프(Cognitive Loop)를 완성합니다. 행동이 수행된 이후 그 결과로 얻어진 관찰(Observation)은 기억을 업데이트하고, 믿음(Beliefs)을 변경하며, 계획을 수정하거나 다음 행동을 변화시킬 수 있습니다. 이러한 지각-추론-행동-업데이트(Perceive-Reason-Act-Update) 순환은 인지 아키텍처와 에이전틱 AI 모두에서 나타납니다. 지속적인 행동(Persistent Behavior)을 구현하려면 단일 입력-출력 변환보다 반복적인 상태 전이(State Transitions)가 필요하며, 이러한 시간적 연속성(Temporal Continuity)은 두 시스템 유형의 중요한 특징입니다.

학습(Learning)은 현재의 많은 구현에서 중요한 차이를 만들어냅니다. 인지 아키텍처는 기술 습득(Skill Acquisition), 강화(Reinforcement), 청킹(Chunking), 활성화 변화(Activation Change), 기억 적응(Memory Adaptation)에 관한 명시적인 이론을 포함하는 경우가 많습니다. 반면 현재 배포되는 많은 AI 에이전트는 작동 중에 사전학습된 모델(Pretrained Model)을 대부분 고정한 상태로 사용하며, 컨텍스트, 검색, 저장된 상호작용 기록을 통해 주로 적응합니다. 지속 학습(Continual Learning)을 추가할 수 있지만 일반적으로 실시간 에이전트 실행(Real-Time Agent Execution)과 분리되어 구현됩니다.

메타인지 기능(Metacognitive Functions)은 또 하나의 유용한 비교 지점을 제공합니다. 인간의 인지에서 영감을 받은 아키텍처는 목표, 충돌(Conflicts), 불확실성(Uncertainty), 인지적 제어(Cognitive Control)를 모니터링하는 기능을 포함할 수 있습니다. AI 에이전트는 자기 평가(Self-Evaluation), 성찰(Reflection), 비평 모듈(Critic Modules), 검증 단계(Verification Stages), 감독 에이전트(Supervisory Agents)를 통해 유사한 기능을 근사할 수 있습니다. 이러한 메커니즘은 실패를 탐지하고 재계획(Replanning)을 유도할 수 있지만 인간과 같은 자기 인식(Self-Awareness)의 증거라기보다 공학적으로 설계된 제어 과정으로 이해해야 합니다.

다중 에이전트 시스템(Multi-Agent Systems)에서는 이러한 비교가 더욱 흥미로워집니다. 인간의 인지는 하나의 유기체 안에서 여러 기능적 과정을 조정하지만 에이전틱 AI는 여러 전문화된 에이전트에 능력을 분산할 수 있습니다. 하나의 에이전트는 계획을 담당하고, 다른 에이전트는 증거를 검색하며, 또 다른 에이전트는 도구를 실행하고, 별도의 에이전트가 결과를 평가할 수 있습니다. 이러한 분산 구조(Distributed Arrangement)는 모듈성과 병렬성(Parallelism)을 높일 수 있지만 조정 오버헤드(Coordination Overhead)와 일관되지 않은 내부 상태(Inconsistent Internal State)라는 새로운 실패 가능성을 만들 수 있습니다.

체화된 에이전트(Embodied Agents)는 지각과 행동이 물리적 환경에서 지속적으로 작동해야 하기 때문에 인지 아키텍처 연구와의 비교를 더욱 직접적으로 만듭니다. 로봇은 불확실성 아래에서 목표를 수행하면서 카메라(Cameras), 라이다(LiDAR), 고유수용감각(Proprioception), 월드 모델, 기억, 계획, 제어를 통합할 수 있습니다. 이러한 시스템에서 인지는 타이밍(Timing), 체화(Embodiment), 환경 역학(Environmental Dynamics), 물리적 행동의 결과와 명확하게 분리될 수 없습니다.

따라서 평가는 개별 벤치마크 정확도(Benchmark Accuracy)보다 아키텍처 수준의 행동(Architecture-Level Behavior)을 고려해야 합니다. 중요한 평가 요소에는 시스템이 일관된 목표(Coherent Goals)를 유지하는지, 관련 상태를 보존하는지, 실패한 행동에서 회복하는지, 변화하는 조건에 적응하는지, 적절한 도구를 선택하는지, 불확실성을 관리하는지, 동일한 오류의 반복을 방지하는지가 포함됩니다. 인지 아키텍처는 시간에 걸친 통합적 행동(Integrated Behavior)을 강조하기 때문에 이러한 특성을 평가하는 데 유용한 개념을 제공합니다.

인공지능 공학(AI Engineering)의 관점에서 인지 아키텍처는 인간의 마음(Human Mind)을 문자 그대로 모방하지 않으면서도 에이전트 설계를 안내할 수 있는 조직 원리(Organizational Principles)를 제공합니다. 전문화된 기억(Specialized Memory), 명시적인 상태 표현(Explicit State Representation), 계층적 목표(Hierarchical Goals), 통제된 주의(Controlled Attention), 계획, 피드백, 학습, 메타인지적 모니터링(Metacognitive Monitoring)은 모두 시스템의 견고성(Robustness)을 향상시킬 수 있습니다. 현대의 파운데이션 모델은 그 자체를 완전한 인지 시스템으로 간주하기보다 이러한 광범위한 아키텍처 내부에서 유연한 구성요소로 활용할 수 있습니다.

따라서 가장 유용한 해석은 인지 아키텍처를 통합된 인지(Integrated Cognition)에 관한 이론과 구조적 모델(Structural Models)을 제공하는 체계로 이해하고, AI 에이전트를 목표 지향적인 계산과 행동(Goal-Directed Computation and Action)을 조정하기 위해 공학적으로 설계된 시스템으로 이해하는 것입니다. 두 시스템의 비교는 상당한 기능적 중첩(Functional Overlap)을 보여주는 동시에 서로 다른 기원(Origins), 표현(Representations), 설계 목표(Design Objectives)를 드러냅니다. 두 접근법의 통찰을 결합하면 더욱 지속적이고(Persistent), 적응적이며(Adaptive), 해석 가능하고(Interpretable), 인지적으로 조직된 인공 에이전트(Cognitively Organized Artificial Agents)를 설계하는 데 도움이 될 수 있습니다.

##  

## 11.06 Human Error vs Model Hallucination [w/Code]

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

Human error and model hallucination are often compared because both can produce outputs that are inaccurate, incomplete, misleading, or inconsistent with available evidence. At the behavioral level, a person and an AI model may confidently provide the same incorrect answer. However, the mechanisms producing these failures are fundamentally different, making it important to distinguish observable similarity from cognitive or computational equivalence.

Human error emerges from the limitations and adaptive characteristics of biological cognition. People operate with finite attention, working memory, knowledge, time, and perceptual capacity. Errors may result from forgetting, distraction, fatigue, misunderstanding, cognitive bias, incorrect assumptions, or inappropriate heuristics. In many situations, these mechanisms trade perfect accuracy for speed, efficiency, and the ability to make decisions under uncertainty.

Model hallucination refers broadly to generated content that appears plausible but is unsupported, inconsistent with evidence, or factually incorrect. A language model generates outputs by predicting tokens from learned statistical patterns and the available context. Unless additional mechanisms provide grounding or verification, fluent generation does not inherently guarantee factual correctness, source reliability, logical validity, or consistency with the external world.

Human memory is reconstructive rather than a perfect recording system, which creates an important source of error. People may combine fragments of actual experiences with expectations, semantic knowledge, later information, or contextual assumptions. This can produce distorted recollections or source-memory errors. Model hallucination can appear similarly reconstructive, but it arises from generative computation over learned representations rather than biological recollection.

Cognitive biases provide another major source of human error. Confirmation bias can favor evidence consistent with existing beliefs, anchoring can make initial information disproportionately influential, and availability can cause easily recalled examples to affect judgment. Models do not necessarily possess these human biases in the same psychological sense, but training distributions, prompts, context ordering, and learned correlations can create systematic response tendencies that resemble biased behavior.

Knowledge limitations affect both humans and models in different ways. A person may recognize that information is missing and explicitly say that they do not know, although confidence can also exceed actual knowledge. A language model may generate a plausible continuation even when reliable information is unavailable. This creates a calibration problem in which linguistic confidence, factual accuracy, and the model\'s actual evidential support may not correspond closely.

Context also plays a critical role in both forms of failure. Humans may misunderstand ambiguous instructions, overlook important details, or interpret information according to previous expectations. Models can likewise be sensitive to prompt wording, irrelevant context, conflicting instructions, missing evidence, and the ordering of information. Small contextual changes can therefore alter conclusions even when the underlying task appears essentially unchanged.

Human errors can sometimes be detected through metacognition. A person may experience uncertainty, reconsider an assumption, search for additional evidence, ask another person, or verify a calculation. AI systems can implement functionally similar procedures through uncertainty estimation, self-evaluation, critique, retrieval, external tools, multiple candidate generation, or verification models. These mechanisms can reduce errors without implying human-like awareness of being wrong.

Hallucination becomes particularly important when language models interact with external knowledge systems. Retrieval-Augmented Generation can provide documents that ground an answer in relevant evidence, but retrieval itself can fail. The system may select irrelevant, outdated, incomplete, or contradictory information. Consequently, reliable AI requires evaluation of both the generation process and the quality, provenance, and relevance of the information supplied to it.

Tool use provides another method for reducing model errors. Calculators can verify arithmetic, databases can provide structured records, search systems can retrieve current information, and specialized software can perform deterministic operations. Humans similarly rely on notebooks, instruments, references, computers, and other people to extend cognition. In both cases, external resources can improve reliability when they are selected appropriately and their outputs are interpreted correctly.

Error propagation is especially important in multi-step reasoning. A small incorrect assumption early in a human reasoning process can influence every later conclusion. Chain-of-Thought and agentic AI systems face a comparable computational problem because an incorrect intermediate result can become context for subsequent steps. Verification at intermediate stages can therefore be more effective than checking only the final answer after a long reasoning sequence has already developed.

The consequences of errors depend strongly on the environment in which they occur. An incorrect answer in casual conversation may have little impact, while errors in medicine, engineering, finance, transportation, or robotic control can create significant risks. Human-AI systems therefore require reliability mechanisms proportional to the consequences of failure, including validation, uncertainty handling, evidence tracking, redundancy, supervision, and safe fallback behavior.

Embodied AI makes this distinction particularly important because hallucination can move from information generation into physical action. A robot that incorrectly estimates an object\'s location, misunderstands an instruction, or constructs an inaccurate world state may choose an unsafe action. Physical AI therefore requires grounding through sensors, state estimation, world models, constraints, feedback, and continuous verification rather than relying solely on linguistic plausibility.

Human-machine collaboration can reduce some errors when the strengths and weaknesses of each participant are understood. Humans can contribute contextual judgment, responsibility, experiential knowledge, and flexible interpretation, while AI systems can process large information spaces, maintain consistent procedures, and perform repeated checks. However, humans may also overtrust automated outputs, creating automation bias when apparently authoritative AI responses are accepted without sufficient verification.

Evaluation should therefore examine more than simple error rates. Important dimensions include the type of error, confidence associated with the error, consistency across repeated trials, sensitivity to context, ability to recognize uncertainty, availability of supporting evidence, and capacity to recover after failure. Comparing these characteristics provides a richer understanding of reliability than merely asking whether humans or models produce more correct answers.

The most useful interpretation is that human error and model hallucination are distinct failure phenomena that can sometimes produce superficially similar outcomes. Human errors emerge from biological cognition, experience, memory, attention, and heuristics, whereas hallucinations emerge from generative computation, learned distributions, contextual limitations, and insufficient grounding. Understanding these differences supports the design of AI systems that verify evidence, manage uncertainty, detect failures, and cooperate effectively with human judgment.

인간 오류(Human Error)와 모델 환각(Model Hallucination)은 모두 부정확하거나 불완전하고, 오해를 유발하거나, 이용 가능한 증거와 일치하지 않는 출력을 만들어낼 수 있다는 점에서 자주 비교됩니다. 행동 수준(Behavioral Level)에서는 사람과 인공지능 모델이 동일한 잘못된 답을 자신 있게 제시할 수도 있습니다. 그러나 이러한 실패를 만들어내는 메커니즘은 근본적으로 다르기 때문에 관찰 가능한 유사성과 인지적 또는 계산적 동등성(Cognitive or Computational Equivalence)을 구분하는 것이 중요합니다.

인간 오류는 생물학적 인지(Biological Cognition)의 한계와 적응적 특성에서 발생합니다. 사람은 제한된 주의(Attention), 작업 기억(Working Memory), 지식(Knowledge), 시간(Time), 지각 능력(Perceptual Capacity)을 가지고 행동합니다. 오류는 망각(Forgetting), 주의 분산(Distraction), 피로(Fatigue), 오해(Misunderstanding), 인지 편향(Cognitive Bias), 잘못된 가정(Incorrect Assumptions), 부적절한 휴리스틱(Inappropriate Heuristics) 때문에 발생할 수 있습니다. 많은 상황에서 이러한 메커니즘은 완벽한 정확성보다 속도, 효율성, 불확실성 아래에서의 의사결정 능력을 우선시하는 절충을 만들어냅니다.

모델 환각(Model Hallucination)은 일반적으로 그럴듯하게 보이지만 근거가 없거나, 이용 가능한 증거와 일치하지 않거나, 사실적으로 잘못된 생성 콘텐츠(Generated Content)를 의미합니다. 언어 모델(Language Model)은 학습된 통계적 패턴(Statistical Patterns)과 현재 컨텍스트(Context)를 기반으로 다음 토큰을 예측하여 출력을 생성합니다. 추가적인 그라운딩(Grounding)이나 검증(Verification) 메커니즘이 없다면 유창한 생성 자체가 사실적 정확성(Factual Correctness), 출처 신뢰성(Source Reliability), 논리적 타당성(Logical Validity), 외부 세계와의 일관성을 자동으로 보장하지는 않습니다.

인간의 기억(Human Memory)은 완벽한 기록 시스템이 아니라 재구성적(Reconstructive)이기 때문에 중요한 오류 원인이 됩니다. 사람은 실제 경험의 일부를 기대(Expectations), 의미 지식(Semantic Knowledge), 이후에 접한 정보(Later Information), 문맥적 가정(Contextual Assumptions)과 결합할 수 있습니다. 이로 인해 왜곡된 회상(Distorted Recollections)이나 출처 기억 오류(Source-Memory Errors)가 발생할 수 있습니다. 모델 환각도 외형상 재구성적으로 보일 수 있지만 이는 생물학적 회상이 아니라 학습된 표현(Learned Representations)에 대한 생성 계산(Generative Computation)에서 발생합니다.

인지 편향(Cognitive Biases)은 인간 오류의 또 다른 중요한 원인입니다. 확증 편향(Confirmation Bias)은 기존 믿음과 일치하는 증거를 더 선호하게 만들 수 있고, 앵커링(Anchoring)은 초기 정보에 지나치게 큰 영향을 받게 할 수 있으며, 가용성 편향(Availability)은 쉽게 떠오르는 사례가 판단에 과도한 영향을 미치게 할 수 있습니다. 모델이 이러한 인간 편향을 동일한 심리적 의미로 가지는 것은 아니지만 학습 데이터 분포(Training Distributions), 프롬프트(Prompts), 컨텍스트 순서(Context Ordering), 학습된 상관관계(Learned Correlations)는 편향된 행동과 유사한 체계적 응답 경향을 만들 수 있습니다.

지식의 한계(Knowledge Limitations)는 인간과 모델 모두에 영향을 주지만 방식은 다릅니다. 사람은 정보가 부족하다는 사실을 인식하고 모른다고 명시적으로 말할 수 있지만, 실제 지식보다 자신감이 과도한 경우도 있습니다. 반면 언어 모델은 신뢰할 수 있는 정보가 부족하더라도 그럴듯한 이어쓰기(Plausible Continuation)를 생성할 수 있습니다. 이로 인해 언어적 자신감(Linguistic Confidence), 사실적 정확성, 실제 증거 수준(Evidential Support)이 서로 일치하지 않는 보정 문제(Calibration Problem)가 발생할 수 있습니다.

컨텍스트(Context) 역시 두 형태의 실패 모두에서 중요한 역할을 합니다. 인간은 모호한 지시를 잘못 이해하거나, 중요한 세부사항을 놓치거나, 기존 기대에 따라 정보를 해석할 수 있습니다. 모델도 프롬프트 표현(Prompt Wording), 관련성이 낮은 컨텍스트(Irrelevant Context), 상충하는 지시(Conflicting Instructions), 누락된 증거(Missing Evidence), 정보의 순서에 민감할 수 있습니다. 따라서 기초적인 과제가 같아 보이더라도 작은 문맥 변화가 결론을 바꿀 수 있습니다.

인간의 오류는 때때로 메타인지(Metacognition)를 통해 탐지될 수 있습니다. 사람은 불확실성을 느끼고, 가정을 다시 검토하며, 추가 증거를 찾거나, 다른 사람에게 묻거나, 계산을 검증할 수 있습니다. 인공지능 시스템은 불확실성 추정(Uncertainty Estimation), 자기 평가(Self-Evaluation), 비평(Critique), 검색(Retrieval), 외부 도구(External Tools), 다중 후보 생성(Multiple Candidate Generation), 검증 모델(Verification Models)을 통해 기능적으로 유사한 절차를 구현할 수 있습니다. 이러한 메커니즘은 오류를 줄일 수 있지만 인간과 같은 자기 인식(Self-Awareness)을 의미하지는 않습니다.

환각은 언어 모델이 외부 지식 시스템(External Knowledge Systems)과 결합될 때 특히 중요해집니다. 검색 증강 생성(Retrieval-Augmented Generation, RAG)은 관련 문서를 제공하여 답변을 외부 증거에 근거하도록 할 수 있지만 검색 자체도 실패할 수 있습니다. 시스템은 관련성이 낮거나 오래되었거나, 불완전하거나, 서로 모순되는 정보를 선택할 수 있습니다. 따라서 신뢰할 수 있는 인공지능을 위해서는 생성 과정뿐 아니라 제공된 정보의 품질(Quality), 출처(Provenance), 관련성(Relevance)도 함께 평가해야 합니다.

도구 사용(Tool Use)은 모델 오류를 줄이는 또 다른 방법을 제공합니다. 계산기(Calculators)는 산술을 검증할 수 있고, 데이터베이스(Databases)는 구조화된 기록을 제공하며, 검색 시스템(Search Systems)은 최신 정보를 찾을 수 있고, 전문 소프트웨어(Specialized Software)는 결정론적 연산(Deterministic Operations)을 수행할 수 있습니다. 인간 역시 노트, 계측기(Instruments), 참고자료(References), 컴퓨터, 다른 사람을 활용하여 인지 능력을 확장합니다. 두 경우 모두 외부 자원이 적절히 선택되고 결과가 올바르게 해석될 때 신뢰성이 향상될 수 있습니다.

오류 전파(Error Propagation)는 다단계 추론(Multi-Step Reasoning)에서 특히 중요합니다. 인간의 추론 과정 초기에 발생한 작은 잘못된 가정이 이후 모든 결론에 영향을 줄 수 있습니다. 사고의 연쇄(Chain-of-Thought)와 에이전틱 인공지능(Agentic AI) 시스템도 유사한 계산적 문제를 가지며, 잘못된 중간 결과가 이후 단계의 컨텍스트로 사용될 수 있습니다. 따라서 긴 추론 과정이 끝난 후 최종 답만 확인하는 것보다 중간 단계에서 검증하는 것이 더 효과적일 수 있습니다.

오류의 결과는 발생하는 환경(Environment)에 따라 크게 달라집니다. 일상적인 대화에서의 잘못된 답변은 영향이 작을 수 있지만 의료(Medicine), 공학(Engineering), 금융(Finance), 교통(Transportation), 로봇 제어(Robotic Control)에서의 오류는 심각한 위험을 만들 수 있습니다. 따라서 인간-인공지능 시스템(Human-AI Systems)은 실패의 결과에 비례하여 검증(Validation), 불확실성 처리(Uncertainty Handling), 증거 추적(Evidence Tracking), 중복성(Redundancy), 감독(Supervision), 안전한 대체 동작(Safe Fallback Behavior)을 포함해야 합니다.

체화 인공지능(Embodied AI)에서는 이러한 구분이 더욱 중요해집니다. 환각이 정보 생성 수준을 넘어 물리적 행동(Physical Action)으로 연결될 수 있기 때문입니다. 로봇이 물체의 위치를 잘못 추정하거나, 지시를 잘못 이해하거나, 부정확한 월드 상태(World State)를 구성하면 위험한 행동을 선택할 수 있습니다. 따라서 피지컬 AI(Physical AI)는 언어적 그럴듯함에만 의존해서는 안 되며 센서(Sensors), 상태 추정(State Estimation), 월드 모델(World Models), 제약조건(Constraints), 피드백, 지속적 검증(Continuous Verification)을 통해 현실 세계에 근거해야 합니다.

인간-기계 협업(Human-Machine Collaboration)은 각 참여자의 강점과 약점을 이해할 때 일부 오류를 줄일 수 있습니다. 인간은 문맥적 판단(Contextual Judgment), 책임(Responsibility), 경험적 지식(Experiential Knowledge), 유연한 해석(Flexible Interpretation)을 제공할 수 있고, 인공지능 시스템은 대규모 정보 공간을 처리하고, 일관된 절차를 유지하며, 반복적인 검사를 수행할 수 있습니다. 그러나 인간이 자동화된 출력을 과도하게 신뢰하면 권위 있어 보이는 인공지능 응답을 충분한 검증 없이 받아들이는 자동화 편향(Automation Bias)이 발생할 수 있습니다.

따라서 평가는 단순한 오류율(Error Rate)만 조사해서는 충분하지 않습니다. 중요한 평가 차원에는 오류의 유형(Type of Error), 오류와 함께 나타나는 신뢰도(Confidence), 반복 시험에서의 일관성(Consistency), 컨텍스트 변화에 대한 민감도(Sensitivity to Context), 불확실성을 인식하는 능력, 지원 증거(Supporting Evidence)의 존재 여부, 실패 이후 회복할 수 있는 능력이 포함됩니다. 이러한 특성을 비교하면 인간과 모델 가운데 누가 더 많은 정답을 내는지만 비교하는 것보다 신뢰성(Reliability)을 훨씬 풍부하게 이해할 수 있습니다.

가장 유용한 해석은 인간 오류와 모델 환각을 표면적으로 유사한 결과를 만들 수 있지만 서로 다른 실패 현상(Distinct Failure Phenomena)으로 이해하는 것입니다. 인간 오류는 생물학적 인지, 경험, 기억, 주의, 휴리스틱에서 발생하는 반면 모델 환각은 생성 계산, 학습된 분포(Learned Distributions), 문맥적 한계(Contextual Limitations), 불충분한 그라운딩(Insufficient Grounding)에서 발생합니다. 이러한 차이를 이해하면 증거를 검증하고, 불확실성을 관리하며, 실패를 탐지하고, 인간의 판단과 효과적으로 협력하는 인공지능 시스템을 설계하는 데 도움이 됩니다.

##  

## 11.07 Robotics and Embodied Cognition [w/Code]

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

Robotics provides one of the clearest practical settings for studying embodied cognition because a robot must connect perception, internal processing, and physical action within a continuously changing environment. Embodied cognition argues that intelligence cannot be understood only as abstract computation inside an agent. Cognitive behavior emerges through ongoing interaction among the body, sensory systems, actions, and the surrounding world.

Traditional approaches to intelligence often describe cognition as a sequence in which information enters a system, internal representations are processed, and an output is produced. Embodied cognition challenges this separation between cognition and physical interaction. Human intelligence develops through active engagement with objects, spaces, tools, and other people, suggesting that knowledge is shaped by what an embodied agent can perceive and do.

The perception-action loop is therefore central to embodied cognition. Perception guides action, while action changes the environment and generates new sensory information. A robot approaching an object, for example, receives different visual, spatial, and tactile information as it moves. Intelligence develops through repeated cycles of sensing, interpretation, action, observation, and adaptation rather than through isolated processing of static inputs.

The physical structure of an agent also influences the kinds of knowledge it can acquire. Humans possess hands for dexterous manipulation, binocular vision for depth perception, and locomotion capabilities that determine how they explore environments. Robots likewise differ according to their cameras, LiDAR, tactile sensors, manipulators, wheels, legs, joints, and actuators. Different embodiments create different opportunities for learning and interaction.

This relationship between body and cognition is closely connected to the concept of affordances. An environment does not simply contain objects with fixed descriptions; it presents possibilities for action relative to the capabilities of an agent. A surface may support walking for one robot but not another, while an object may be graspable by one manipulator but inaccessible to another. Perception therefore becomes closely linked to possible actions.

Situated cognition extends this perspective by emphasizing that intelligent behavior depends on the context in which an agent operates. Cognitive processing can make use of environmental structures, tools, landmarks, external memory, and other agents rather than representing everything internally. A navigation robot using environmental markers, for example, incorporates features of the external world into its broader problem-solving process.

Robotics makes these ideas operational through sensors and actuators. Cameras provide visual observations, LiDAR measures spatial structure, IMUs estimate motion, tactile and force sensors capture physical contact, and microphones provide acoustic information. Motors, wheels, legs, and manipulators allow the robot to intervene in the environment. These components establish the physical interface through which perception and action become connected.

Grounded intelligence emerges when internal representations become systematically connected with sensory experience and physical consequences. The concept of grasping, for example, involves more than a linguistic definition. For an embodied robot, it can involve object geometry, relative pose, approach trajectory, gripper configuration, contact, force, stability, and task success. Repeated interaction connects abstract representations with actionable physical knowledge.

Learning through interaction provides information that passive observation alone may not reveal. A robot can move around an object to resolve visual ambiguity, touch a surface to estimate physical properties, manipulate an object to test its mobility, or repeat an action to estimate its consequences. Action therefore becomes a mechanism for acquiring information, making exploration an active component of perception, learning, and reasoning.

Embodied cognition also provides a useful foundation for understanding world models. Through repeated interaction, an agent can learn predictive relationships between states, actions, and outcomes. Such representations can capture expectations about object motion, contact, spatial change, or environmental dynamics. A world model can then support prediction, simulation, planning, and decision making by estimating possible consequences before physical actions are executed.

Memory gives these interactions temporal continuity. A robot operating in a changing environment must retain information about previous observations, actions, locations, objects, failures, and goals. Current perception becomes more useful when interpreted in relation to past experience. Embodied intelligence therefore benefits from architectures that connect perception, memory, prediction, planning, and control across multiple timescales.

Adaptive behavior emerges when feedback changes future decisions. If a grasp fails, a robot may alter its approach angle or force. If a planned route becomes blocked, it may update its environmental representation and select another path. These feedback-driven adjustments demonstrate why embodied cognition is fundamentally dynamic: intelligence involves maintaining effective interaction as both the agent and the environment change.

Large language models and foundation models can become components of embodied systems by providing semantic knowledge, language understanding, reasoning, or high-level planning. However, language alone does not provide direct physical experience. Embodied AI therefore seeks to connect symbolic and linguistic representations with perception, world models, memory, action, and feedback so that abstract knowledge can participate in physically grounded behavior.

Robotics also exposes the importance of uncertainty and physical consequences. Sensor measurements can be noisy, objects can move unexpectedly, surfaces can vary, and actions can fail. Unlike purely digital tasks, an incorrect decision may alter the physical state of the environment and cannot always be reversed. Reliable embodied systems therefore require continuous state estimation, feedback, adaptation, and constraints on potentially unsafe actions.

The connection between robotics and embodied cognition consequently extends beyond building machines that imitate human behavior. It provides a framework for understanding intelligence as an adaptive process distributed across perception, internal representations, bodily capabilities, action, and environmental structure. Sensorimotor intelligence, grounded learning, physical interaction, adaptive behavior, and integrated architectures become complementary parts of the same framework.

The broader implication is that increasingly capable artificial intelligence may require more than processing larger quantities of abstract information. Physical or simulated embodiment can provide opportunities to acquire knowledge through exploration, intervention, feedback, and consequences. Robotics therefore serves as both an engineering domain and an experimental platform for investigating how perception, action, memory, prediction, and learning can combine into more grounded and adaptive forms of intelligence.

로보틱스(Robotics)는 로봇이 지속적으로 변화하는 환경 안에서 지각(Perception), 내부 처리(Internal Processing), 물리적 행동(Physical Action)을 연결해야 하기 때문에 체화된 인지(Embodied Cognition)를 연구할 수 있는 가장 명확하고 실용적인 분야 가운데 하나입니다. 체화된 인지는 지능(Intelligence)을 에이전트 내부에서 수행되는 추상적인 계산(Abstract Computation)만으로 이해할 수 없다고 봅니다. 인지적 행동(Cognitive Behavior)은 신체(Body), 감각 시스템(Sensory Systems), 행동(Actions), 주변 세계(Surrounding World) 사이의 지속적인 상호작용을 통해 나타납니다.

전통적인 지능 접근법(Traditional Approaches to Intelligence)은 흔히 정보가 시스템에 입력되고, 내부 표현(Internal Representations)이 처리된 다음, 출력(Output)이 생성되는 일련의 과정으로 인지를 설명합니다. 체화된 인지는 인지와 물리적 상호작용(Physical Interaction)을 이렇게 분리하는 관점에 문제를 제기합니다. 인간의 지능은 객체(Objects), 공간(Spaces), 도구(Tools), 다른 사람들과 능동적으로 상호작용하면서 발달하며, 이는 지식(Knowledge)이 체화된 에이전트가 무엇을 지각하고 행동할 수 있는지에 의해 형성된다는 것을 보여줍니다.

따라서 지각-행동 루프(Perception-Action Loop)는 체화된 인지의 핵심입니다. 지각은 행동을 안내하고, 행동은 환경을 변화시키면서 새로운 감각 정보(Sensory Information)를 만들어냅니다. 예를 들어 로봇이 객체에 접근하면 이동 과정에서 서로 다른 시각적, 공간적, 촉각적 정보(Visual, Spatial, and Tactile Information)를 얻게 됩니다. 지능은 정적인 입력을 독립적으로 처리하는 것이 아니라 감지(Sensing), 해석(Interpretation), 행동, 관찰(Observation), 적응(Adaptation)의 반복적인 순환을 통해 발달합니다.

에이전트의 물리적 구조(Physical Structure) 역시 어떤 종류의 지식을 습득할 수 있는지에 영향을 줍니다. 인간은 정교한 조작(Dexterous Manipulation)을 위한 손, 깊이 지각(Depth Perception)을 위한 양안 시각(Binocular Vision), 환경을 탐색하는 방식을 결정하는 이동 능력(Locomotion Capabilities)을 가지고 있습니다. 로봇 역시 카메라(Cameras), 라이다(LiDAR), 촉각 센서(Tactile Sensors), 매니퓰레이터(Manipulators), 바퀴(Wheels), 다리(Legs), 관절(Joints), 액추에이터(Actuators)의 구성에 따라 서로 다른 체화 특성을 가지며, 이러한 차이는 학습과 상호작용의 가능성을 변화시킵니다.

신체와 인지의 이러한 관계는 행동유도성(Affordances)이라는 개념과 밀접하게 연결됩니다. 환경은 단순히 고정된 속성을 가진 객체들로 구성되는 것이 아니라 특정 에이전트의 능력에 따라 가능한 행동의 기회(Possibilities for Action)를 제공합니다. 어떤 표면은 한 로봇에게는 이동 가능한 공간이지만 다른 로봇에게는 그렇지 않을 수 있으며, 어떤 객체는 특정 매니퓰레이터로는 파지(Grasp)할 수 있지만 다른 매니퓰레이터로는 접근하기 어려울 수 있습니다. 따라서 지각은 가능한 행동과 밀접하게 연결됩니다.

상황적 인지(Situated Cognition)는 지능적 행동이 에이전트가 작동하는 구체적인 맥락(Context)에 의존한다는 점을 강조함으로써 이러한 관점을 확장합니다. 인지 처리는 모든 것을 내부적으로 표현하는 대신 환경 구조(Environmental Structures), 도구, 랜드마크(Landmarks), 외부 기억(External Memory), 다른 에이전트를 활용할 수 있습니다. 예를 들어 환경 표식을 이용하여 이동하는 로봇은 외부 세계의 특징을 자신의 광범위한 문제 해결 과정(Problem-Solving Process)에 통합하여 활용합니다.

로보틱스는 센서(Sensors)와 액추에이터(Actuators)를 통해 이러한 개념을 실제 시스템으로 구현합니다. 카메라는 시각적 관찰(Visual Observations)을 제공하고, 라이다는 공간 구조(Spatial Structure)를 측정하며, 관성측정장치(Inertial Measurement Unit, IMU)는 움직임을 추정합니다. 촉각 및 힘 센서(Tactile and Force Sensors)는 물리적 접촉을 측정하고, 마이크(Microphones)는 음향 정보를 제공합니다. 모터(Motors), 바퀴, 다리, 매니퓰레이터는 로봇이 환경에 직접 개입할 수 있도록 하며, 이러한 구성요소는 지각과 행동을 연결하는 물리적 인터페이스(Physical Interface)를 형성합니다.

그라운딩된 지능(Grounded Intelligence)은 내부 표현이 감각 경험(Sensory Experience)과 물리적 결과(Physical Consequences)에 체계적으로 연결될 때 형성됩니다. 예를 들어 파지(Grasping)라는 개념은 단순한 언어적 정의 이상의 의미를 가집니다. 체화된 로봇에게 파지는 객체 형상(Object Geometry), 상대 자세(Relative Pose), 접근 궤적(Approach Trajectory), 그리퍼 구성(Gripper Configuration), 접촉(Contact), 힘(Force), 안정성(Stability), 작업 성공(Task Success)을 포함할 수 있습니다. 반복적인 상호작용은 추상적인 표현을 실제 행동 가능한 물리적 지식(Actionable Physical Knowledge)과 연결합니다.

상호작용을 통한 학습(Learning through Interaction)은 수동적인 관찰(Passive Observation)만으로는 얻기 어려운 정보를 제공합니다. 로봇은 시각적 모호성(Visual Ambiguity)을 해결하기 위해 객체 주변을 이동할 수 있고, 표면의 물리적 특성을 추정하기 위해 접촉할 수 있으며, 객체를 조작하여 이동 가능성을 확인하거나 행동의 결과를 추정하기 위해 같은 동작을 반복할 수 있습니다. 따라서 행동은 정보를 획득하는 하나의 메커니즘이 되며, 탐색(Exploration)은 지각, 학습, 추론(Reasoning)의 능동적인 구성요소가 됩니다.

체화된 인지는 월드 모델(World Models)을 이해하기 위한 유용한 기반도 제공합니다. 반복적인 상호작용을 통해 에이전트는 상태(State), 행동(Action), 결과(Outcome) 사이의 예측 관계(Predictive Relationships)를 학습할 수 있습니다. 이러한 표현은 객체의 움직임, 접촉, 공간적 변화, 환경 동역학(Environmental Dynamics)에 대한 예측을 포함할 수 있습니다. 월드 모델은 실제 물리적 행동을 실행하기 전에 가능한 결과를 추정함으로써 예측(Prediction), 시뮬레이션(Simulation), 계획(Planning), 의사결정(Decision Making)을 지원할 수 있습니다.

기억(Memory)은 이러한 상호작용에 시간적 연속성(Temporal Continuity)을 제공합니다. 변화하는 환경에서 작동하는 로봇은 이전의 관찰, 행동, 위치(Locations), 객체, 실패(Failures), 목표(Goals)에 관한 정보를 유지해야 합니다. 현재의 지각은 과거의 경험과 연결하여 해석될 때 더욱 유용해집니다. 따라서 체화된 지능(Embodied Intelligence)은 여러 시간 척도(Timescales)에 걸쳐 지각, 기억, 예측, 계획, 제어(Control)를 연결하는 아키텍처를 통해 향상될 수 있습니다.

적응적 행동(Adaptive Behavior)은 피드백(Feedback)이 이후의 의사결정을 변화시킬 때 나타납니다. 파지가 실패하면 로봇은 접근 각도(Approach Angle)나 힘을 변경할 수 있습니다. 계획된 경로가 차단되면 환경 표현(Environmental Representation)을 업데이트하고 다른 경로를 선택할 수 있습니다. 이러한 피드백 기반 조정(Feedback-Driven Adjustments)은 체화된 인지가 근본적으로 동적(Dynamic)이라는 점을 보여줍니다. 즉, 지능은 에이전트와 환경이 모두 변화하는 상황에서도 효과적인 상호작용을 지속적으로 유지하는 과정입니다.

대규모 언어 모델(Large Language Models)과 파운데이션 모델(Foundation Models)은 의미 지식(Semantic Knowledge), 언어 이해(Language Understanding), 추론, 고수준 계획(High-Level Planning)을 제공함으로써 체화된 시스템(Embodied Systems)의 구성요소가 될 수 있습니다. 그러나 언어만으로 직접적인 물리적 경험(Physical Experience)을 제공할 수는 없습니다. 따라서 체화 인공지능(Embodied AI)은 기호적 및 언어적 표현(Symbolic and Linguistic Representations)을 지각, 월드 모델, 기억, 행동, 피드백과 연결하여 추상적인 지식이 물리적으로 그라운딩된 행동(Physically Grounded Behavior)에 참여하도록 하는 것을 목표로 합니다.

로보틱스는 불확실성(Uncertainty)과 물리적 결과의 중요성도 명확하게 보여줍니다. 센서 측정에는 잡음(Noise)이 포함될 수 있고, 객체가 예상하지 못하게 움직일 수 있으며, 표면의 특성이 달라질 수 있고, 행동이 실패할 수도 있습니다. 순수한 디지털 과제와 달리 잘못된 의사결정은 환경의 물리적 상태(Physical State)를 실제로 변화시킬 수 있으며 항상 원래 상태로 되돌릴 수 있는 것도 아닙니다. 따라서 신뢰할 수 있는 체화 시스템은 지속적인 상태 추정(State Estimation), 피드백, 적응, 잠재적으로 위험한 행동을 제한하는 제약조건(Constraints)을 필요로 합니다.

따라서 로보틱스와 체화된 인지의 연결은 단순히 인간의 행동을 모방하는 기계를 만드는 것을 넘어섭니다. 이는 지능을 지각, 내부 표현, 신체적 능력(Bodily Capabilities), 행동, 환경 구조 전반에 분산된 적응적 과정(Adaptive Process)으로 이해하기 위한 프레임워크를 제공합니다. 감각운동 지능(Sensorimotor Intelligence), 그라운딩된 학습(Grounded Learning), 물리적 상호작용, 적응적 행동, 통합 아키텍처(Integrated Architectures)는 이러한 관점에서 하나의 체계를 구성하는 상호보완적인 요소가 됩니다.

더 넓은 관점에서 보면 점점 더 발전하는 인공지능을 구현하기 위해서는 단순히 더 많은 양의 추상적 정보(Abstract Information)를 처리하는 것만으로는 충분하지 않을 수 있습니다. 물리적 또는 시뮬레이션 기반 체화(Physical or Simulated Embodiment)는 탐색, 개입(Intervention), 피드백, 행동의 결과를 통해 지식을 습득할 수 있는 기회를 제공합니다. 따라서 로보틱스는 공학적 응용 분야인 동시에 지각, 행동, 기억, 예측, 학습이 어떻게 결합되어 더욱 그라운딩되고 적응적인 형태의 지능(Grounded and Adaptive Intelligence)을 형성할 수 있는지를 연구하기 위한 실험적 플랫폼(Experimental Platform)의 역할을 합니다.
