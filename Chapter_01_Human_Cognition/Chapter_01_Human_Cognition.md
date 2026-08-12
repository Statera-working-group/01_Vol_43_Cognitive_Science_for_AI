**Volume 43 Cognitive Science for AI**


# Chapter 01. Human Cognition

##  

## 01.00 Overview of Cognitive Science

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

Cognitive science is the interdisciplinary study of how intelligent systems acquire information, transform it into internal representations, use those representations to guide behavior, and adapt through experience. It investigates perception, attention, memory, learning, language, reasoning, decision making, problem solving, and action as interconnected processes rather than isolated abilities.

The field emerged from the recognition that intelligence cannot be adequately explained from a single disciplinary perspective. Psychology contributes experimental models of behavior and mental processes, neuroscience investigates their biological mechanisms, linguistics studies language and meaning, philosophy examines knowledge and mind, while computer science provides computational models capable of implementing and testing theories of cognition.

A central idea in cognitive science is that observable behavior results from internal information-processing mechanisms. Sensory signals are not simply recorded and reproduced. They are selected, organized, interpreted, combined with prior knowledge, and transformed into representations that support prediction and action. Cognition therefore involves continuous interaction between incoming evidence and internally maintained models.

Perception provides one of the clearest examples of this constructive process. Visual, auditory, tactile, and other sensory signals are incomplete and frequently ambiguous, yet humans normally perceive coherent objects, events, spatial relationships, and situations. Cognitive systems resolve this ambiguity by combining sensory evidence with context, expectations, learned regularities, memory, and task-dependent attention.

Attention determines which information receives limited computational and cognitive resources. Because an intelligent organism cannot process every available stimulus with equal depth, attention performs selection, prioritization, and resource allocation. This principle is important for AI because practical systems must similarly determine which tokens, image regions, memories, sensor streams, objects, or candidate actions deserve greater processing.

Memory allows cognition to extend beyond the immediate present. Sensory memory briefly preserves incoming information, working memory maintains information needed for current operations, and long-term memory supports knowledge accumulated across extended experience. Episodic, semantic, and procedural forms of memory further distinguish remembered experiences, generalized knowledge, and learned skills that influence future behavior.

Learning changes internal representations and behavior through experience. Cognitive science examines learning through association, reinforcement, observation, instruction, abstraction, analogy, and repeated interaction with the environment. Human learning is particularly important for AI because people often acquire useful concepts from relatively limited data while transferring previous knowledge to unfamiliar situations and continuously integrating new information.

Reasoning transforms available representations into conclusions, predictions, explanations, or plans. Deductive reasoning derives consequences from rules, inductive reasoning identifies broader regularities from observations, and abductive reasoning searches for plausible explanations. Human reasoning also relies heavily on heuristics, analogy, prior knowledge, uncertainty estimation, and contextual judgment rather than purely formal logical operations.

Problem solving combines representation, search, reasoning, memory, and action selection. A problem can become easier or harder depending on how its states, constraints, goals, and possible operations are represented internally. Humans rarely explore all possible alternatives exhaustively; instead, they use experience, abstraction, decomposition, heuristics, and intermediate goals to restrict the search space and concentrate computation on promising possibilities.

Decision making concerns the selection of actions when multiple alternatives are available. Decisions may depend on expected reward, uncertainty, risk, previous experience, social context, emotional state, and long-term objectives. Cognitive research shows that human decisions are neither perfectly rational nor completely arbitrary, motivating computational models that combine bounded rationality, value estimation, heuristics, and adaptive control.

Language introduces a powerful mechanism for representing and communicating concepts beyond immediate sensory experience. Words and sentences allow humans to describe objects, relations, intentions, hypothetical situations, rules, and abstract ideas. Language is closely connected with memory, conceptual knowledge, reasoning, social interaction, and planning, although cognitive science continues to investigate how linguistic and nonlinguistic representations interact.

Concept formation enables intelligent systems to organize diverse experiences into reusable categories. Humans recognize that different observations may correspond to the same underlying object, property, relation, or event despite variations in appearance and context. Such abstraction supports generalization because knowledge learned from one instance can be applied to other situations sharing relevant structural or semantic characteristics.

Cognitive representations can take several forms, including symbolic structures, distributed patterns, spatial models, conceptual networks, probabilistic beliefs, and sensorimotor states. Different cognitive theories emphasize different representational mechanisms. For AI, this diversity suggests that intelligence may require multiple complementary representations rather than assuming that every cognitive function should operate through a single universal format.

The relationship between symbolic processing and distributed representation has been especially influential. Classical cognitive theories often describe cognition through explicit symbols, rules, and structured operations, while connectionist theories explain cognition through distributed activity across networks of simple processing units. Modern AI increasingly combines these perspectives through neural representations, structured reasoning, external tools, and explicit memory systems.

Cognition is also inherently temporal. Intelligent behavior depends not only on understanding the current state but also on remembering previous states and anticipating possible future states. Humans continuously integrate information over different time scales, ranging from milliseconds of sensory processing to years of accumulated knowledge. This temporal integration provides an important foundation for sequential prediction, planning, and world modeling.

Prediction is therefore closely connected with cognition. An intelligent agent benefits from anticipating what sensory input, environmental change, or behavioral consequence is likely to occur next. Prediction allows discrepancies between expectation and observation to become informative learning signals. This perspective connects cognitive science with predictive processing, generative modeling, model-based reinforcement learning, and modern computational world models.

Cognition should not be understood as a purely passive process occurring independently of action. Perception influences action, action changes the environment, and the resulting sensory consequences provide new evidence for perception and learning. This perception-action loop is especially important in embodied intelligence, where an agent must continuously coordinate sensing, prediction, planning, control, and physical interaction.

Embodied cognition extends this idea by emphasizing that intelligence develops through interaction between the brain, body, environment, and task. Physical structure constrains possible actions, while actions determine which information becomes available to perception. For robotics and Physical AI, this means that cognition cannot always be separated cleanly from morphology, sensor configuration, motor capability, environmental dynamics, and real-time control.

Social cognition adds another dimension to intelligence. Humans interpret facial expressions, gestures, intentions, beliefs, goals, emotions, and social relationships while predicting the behavior of other agents. These capabilities enable cooperation, communication, imitation, teaching, and coordinated action. AI systems interacting with humans increasingly require corresponding mechanisms for intent estimation, perspective taking, communication, and adaptive collaboration.

Metacognition refers to cognition about one\'s own cognitive processes. Humans can sometimes estimate whether they know something, recognize uncertainty, detect errors, reconsider strategies, and allocate additional effort when confidence is low. Comparable capabilities are valuable for AI systems because an intelligent agent should ideally distinguish reliable conclusions from uncertain ones and determine when additional evidence or external assistance is required.

Cognitive science also emphasizes that intelligence operates under constraints. Human working memory is limited, attention is selective, decisions must often be made before all information is available, and computation consumes biological resources. Rather than making cognition ineffective, these constraints encourage efficient strategies such as abstraction, chunking, selective retrieval, hierarchical planning, and approximate reasoning.

This concept of bounded cognition provides a useful contrast with approaches that equate intelligence primarily with increasing computational scale. Human intelligence demonstrates that capable behavior can emerge from selective computation, reusable representations, specialized subsystems, memory, prediction, and adaptive resource allocation. Cognitive science therefore offers principles for designing AI systems that seek efficiency as well as raw computational capacity.

Cognitive architectures attempt to integrate these mechanisms into unified models of intelligent behavior. Instead of modeling perception, memory, reasoning, and action independently, a cognitive architecture specifies how information moves between functional components and how those components cooperate over time. Such architectures provide conceptual precedents for modern AI agents combining foundation models, memory, planning, tools, and environmental interaction.

However, cognitive science should not be treated as a direct engineering blueprint for artificial intelligence. A psychological theory may explain human behavior without specifying an optimal computational implementation, and a successful AI mechanism does not necessarily reproduce human cognition. The productive objective is to identify computational principles that can inspire artificial systems while preserving the distinction between biological explanation and engineering design.

Experimental methods are consequently essential to the field. Researchers use behavioral measurements such as accuracy, reaction time, recall, eye movement, choice patterns, and error distributions to infer underlying cognitive processes. Computational models can then generate predictions that are compared with observations, creating an iterative relationship among theoretical hypotheses, experimental evidence, mathematical models, and simulation.

For AI research, this methodology provides an important lesson: intelligence should be evaluated through behavioral capabilities and failure patterns rather than model size alone. Controlled experiments can reveal whether a system truly generalizes, remembers relevant information, reasons compositionally, adapts to changing conditions, manages uncertainty, or merely exploits statistical regularities contained in its training distribution.

Modern foundation models create new opportunities for interaction between AI and cognitive science. Large language models, multimodal models, generative models, and autonomous agents exhibit behaviors involving representation, contextual learning, retrieval, reasoning, planning, and tool use. These systems provide computational platforms for testing cognitive hypotheses while cognitive theories provide frameworks for analyzing their capabilities and limitations.

At the same time, major differences remain between current AI and human cognition. Humans learn continuously from multimodal embodied experience, maintain persistent goals and memories, operate with limited energy, adapt rapidly to changing environments, and integrate perception with physical and social interaction. Many AI systems instead depend on large offline datasets, fixed training phases, external memory mechanisms, and narrowly defined deployment conditions.

These differences make cognitive science particularly relevant to the development of more general AI systems. Research on working memory can inform context management, studies of attention can inspire selective computation, human learning can motivate continual and few-shot adaptation, cognitive control can influence agent architectures, and research on mental simulation can contribute to planning and predictive world models.

The relationship becomes even more significant for embodied AI and robotics. A robot operating in the physical world must interpret uncertain sensory information, remember relevant events, recognize objects and situations, predict environmental dynamics, choose goals, plan actions, detect failures, and adapt its behavior. These requirements closely correspond to the integrated cognitive functions studied across cognitive science.

World models provide an especially important bridge between cognitive science and modern Physical AI. An internal model can represent entities, relationships, dynamics, uncertainty, and possible future consequences of actions. Rather than reacting only to current observations, an agent equipped with such representations can mentally evaluate alternative futures and select actions according to predicted outcomes before executing them physically.

A complete cognitive perspective therefore moves beyond the simple sequence of perception followed by decision and action. Intelligent behavior emerges from recurrent interaction among perception, attention, memory, representation, learning, prediction, reasoning, planning, decision making, and action. Each process influences the others, creating a continuously updated internal state that connects past experience, present observation, and anticipated futures.

From an AI engineering perspective, cognitive science is valuable not because artificial systems must imitate every detail of human cognition, but because it provides a structured vocabulary for identifying missing capabilities. When an AI system fails, the problem may involve perception, memory, representation, attention, reasoning, uncertainty, planning, adaptation, or coordination among these functions rather than insufficient model capacity alone.

The broader objective is to understand intelligence as an integrated adaptive system. Cognitive science provides theories and experimental evidence about how such integration occurs in humans, while AI provides computational mechanisms for constructing and testing alternative forms of intelligence. Their interaction creates a foundation for increasingly capable agents that can learn, predict, reason, remember, communicate, and act within complex environments.

인지과학(Cognitive Science)은 지능 시스템(Intelligent Systems)이 정보를 획득하고, 이를 내부 표현(Internal Representations)으로 변환하며, 이러한 표현을 활용하여 행동(Behavior)을 유도하고, 경험(Experience)을 통해 적응하는 방식을 연구하는 학제간 분야(Interdisciplinary Field)입니다. 인지과학은 지각(Perception), 주의(Attention), 기억(Memory), 학습(Learning), 언어(Language), 추론(Reasoning), 의사결정(Decision Making), 문제 해결(Problem Solving), 행동(Action)을 서로 분리된 능력이 아니라 상호 연결된 과정으로 연구합니다.

인지과학(Cognitive Science)은 지능(Intelligence)을 하나의 학문적 관점만으로 충분히 설명하기 어렵다는 인식에서 발전했습니다. 심리학(Psychology)은 행동과 정신 과정(Mental Processes)에 대한 실험적 모델을 제공하고, 신경과학(Neuroscience)은 그 생물학적 메커니즘(Biological Mechanisms)을 연구하며, 언어학(Linguistics)은 언어와 의미를 연구합니다. 철학(Philosophy)은 지식과 마음을 탐구하고, 컴퓨터 과학(Computer Science)은 인지 이론을 구현하고 검증할 수 있는 계산 모델(Computational Models)을 제공합니다.

인지과학(Cognitive Science)의 핵심 개념 가운데 하나는 관찰 가능한 행동(Observable Behavior)이 내부 정보 처리 메커니즘(Internal Information-Processing Mechanisms)의 결과라는 것입니다. 감각 신호(Sensory Signals)는 단순히 기록되고 재생되는 것이 아니라 선택되고, 조직되고, 해석되며, 기존 지식(Prior Knowledge)과 결합되어 예측(Prediction)과 행동(Action)을 지원하는 표현(Representations)으로 변환됩니다. 따라서 인지(Cognition)는 입력되는 증거와 내부적으로 유지되는 모델 사이의 지속적인 상호작용을 포함합니다.

지각(Perception)은 이러한 구성적 과정(Constructive Process)을 가장 명확하게 보여주는 사례 가운데 하나입니다. 시각(Visual), 청각(Auditory), 촉각(Tactile) 및 기타 감각 신호는 불완전하고 모호한 경우가 많지만, 인간은 일반적으로 일관된 객체(Objects), 사건(Events), 공간적 관계(Spatial Relationships), 상황(Situations)을 인식합니다. 인지 시스템은 감각적 증거를 문맥(Context), 기대(Expectations), 학습된 규칙성(Learned Regularities), 기억(Memory), 작업 의존적 주의(Task-Dependent Attention)와 결합하여 이러한 모호성을 해결합니다.

주의(Attention)는 제한된 계산 및 인지 자원(Computational and Cognitive Resources)을 어떤 정보에 할당할 것인지를 결정합니다. 지능을 가진 유기체는 이용 가능한 모든 자극을 동일한 깊이로 처리할 수 없기 때문에, 주의는 선택(Selection), 우선순위 결정(Prioritization), 자원 할당(Resource Allocation)의 역할을 수행합니다. 이러한 원리는 실제 AI 시스템이 어떤 토큰(Tokens), 이미지 영역(Image Regions), 기억(Memories), 센서 스트림(Sensor Streams), 객체(Objects), 후보 행동(Candidate Actions)에 더 많은 처리 자원을 할당할지를 결정해야 한다는 점에서도 중요합니다.

기억(Memory)은 인지(Cognition)가 즉각적인 현재 순간을 넘어 작동할 수 있도록 합니다. 감각 기억(Sensory Memory)은 입력되는 정보를 매우 짧은 시간 동안 보존하고, 작업 기억(Working Memory)은 현재 수행 중인 연산에 필요한 정보를 유지하며, 장기 기억(Long-Term Memory)은 장기간의 경험을 통해 축적된 지식을 지원합니다. 일화 기억(Episodic Memory), 의미 기억(Semantic Memory), 절차 기억(Procedural Memory)은 각각 기억된 경험, 일반화된 지식, 학습된 기술을 구분하며 미래 행동에 영향을 미칩니다.

학습(Learning)은 경험(Experience)을 통해 내부 표현과 행동을 변화시키는 과정입니다. 인지과학은 연합(Association), 강화(Reinforcement), 관찰(Observation), 교육(Instruction), 추상화(Abstraction), 유추(Analogy), 환경과의 반복적인 상호작용을 통한 학습을 연구합니다. 인간 학습은 비교적 제한된 데이터만으로도 유용한 개념을 습득하고, 기존 지식을 새로운 상황으로 전이(Transfer)하며, 새로운 정보를 지속적으로 통합한다는 점에서 AI 연구에 특히 중요합니다.

추론(Reasoning)은 이용 가능한 표현을 결론(Conclusions), 예측(Predictions), 설명(Explanations), 계획(Plans)으로 변환합니다. 연역적 추론(Deductive Reasoning)은 규칙으로부터 결과를 도출하고, 귀납적 추론(Inductive Reasoning)은 관찰로부터 보다 일반적인 규칙성을 발견하며, 가설적 추론(Abductive Reasoning)은 관찰된 현상에 대한 타당한 설명을 탐색합니다. 인간의 추론은 순수한 형식 논리 연산뿐 아니라 휴리스틱(Heuristics), 유추(Analogy), 사전 지식(Prior Knowledge), 불확실성 추정(Uncertainty Estimation), 문맥적 판단(Contextual Judgment)에 크게 의존합니다.

문제 해결(Problem Solving)은 표현(Representation), 탐색(Search), 추론(Reasoning), 기억(Memory), 행동 선택(Action Selection)을 결합합니다. 문제의 상태(States), 제약조건(Constraints), 목표(Goals), 가능한 연산(Possible Operations)을 내부적으로 어떻게 표현하는가에 따라 문제 해결의 난이도가 크게 달라질 수 있습니다. 인간은 일반적으로 모든 가능한 대안을 완전 탐색하지 않고 경험, 추상화, 분해(Decomposition), 휴리스틱, 중간 목표(Intermediate Goals)를 활용하여 탐색 공간(Search Space)을 제한하고 유망한 가능성에 계산 자원을 집중합니다.

의사결정(Decision Making)은 여러 대안이 존재할 때 행동을 선택하는 과정과 관련됩니다. 의사결정은 기대 보상(Expected Reward), 불확실성(Uncertainty), 위험(Risk), 이전 경험(Previous Experience), 사회적 맥락(Social Context), 감정 상태(Emotional State), 장기 목표(Long-Term Objectives)의 영향을 받을 수 있습니다. 인지 연구는 인간의 결정이 완전히 합리적이지도, 완전히 임의적이지도 않다는 것을 보여주며, 제한된 합리성(Bounded Rationality), 가치 추정(Value Estimation), 휴리스틱, 적응형 제어(Adaptive Control)를 결합하는 계산 모델의 필요성을 제시합니다.

언어(Language)는 즉각적인 감각 경험을 넘어서는 개념을 표현하고 전달할 수 있는 강력한 메커니즘을 제공합니다. 단어와 문장을 통해 인간은 객체, 관계(Relations), 의도(Intentions), 가상 상황(Hypothetical Situations), 규칙(Rules), 추상적 개념(Abstract Ideas)을 설명할 수 있습니다. 언어는 기억, 개념적 지식(Conceptual Knowledge), 추론, 사회적 상호작용(Social Interaction), 계획과 밀접하게 연결되어 있지만, 언어적 표현과 비언어적 표현(Nonlinguistic Representations)이 어떻게 상호작용하는지는 여전히 중요한 연구 주제입니다.

개념 형성(Concept Formation)은 지능 시스템이 다양한 경험을 재사용 가능한 범주(Categories)로 조직할 수 있도록 합니다. 인간은 외형과 문맥이 달라지더라도 서로 다른 관찰이 동일한 기본 객체, 속성(Property), 관계(Relation), 사건(Event)에 해당할 수 있음을 인식합니다. 이러한 추상화(Abstraction)는 하나의 사례에서 학습된 지식을 관련된 구조적 또는 의미적 특성을 공유하는 다른 상황에 적용할 수 있게 하므로 일반화(Generalization)를 지원합니다.

인지 표현(Cognitive Representations)은 기호 구조(Symbolic Structures), 분산 패턴(Distributed Patterns), 공간 모델(Spatial Models), 개념 네트워크(Conceptual Networks), 확률적 믿음(Probabilistic Beliefs), 감각운동 상태(Sensorimotor States) 등 여러 형태를 가질 수 있습니다. 서로 다른 인지 이론은 서로 다른 표현 메커니즘을 강조합니다. AI 관점에서 이러한 다양성은 모든 인지 기능이 하나의 보편적 표현 형식만으로 작동하기보다는 여러 상호보완적 표현을 필요로 할 가능성을 시사합니다.

기호 처리(Symbolic Processing)와 분산 표현(Distributed Representation)의 관계는 특히 큰 영향을 미쳐 왔습니다. 고전적 인지 이론(Classical Cognitive Theories)은 명시적인 기호(Symbols), 규칙(Rules), 구조화된 연산을 통해 인지를 설명하는 경우가 많으며, 연결주의 이론(Connectionist Theories)은 단순한 처리 단위들로 구성된 네트워크 전체에 분산된 활동을 통해 인지를 설명합니다. 현대 AI는 신경 표현(Neural Representations), 구조화된 추론(Structured Reasoning), 외부 도구(External Tools), 명시적 기억 시스템(Explicit Memory Systems)을 통해 이러한 관점을 점차 결합하고 있습니다.

인지(Cognition)는 본질적으로 시간적(Temporal)이기도 합니다. 지능적 행동은 현재 상태를 이해하는 것뿐만 아니라 이전 상태를 기억하고 가능한 미래 상태를 예상하는 능력에 의존합니다. 인간은 수 밀리초의 감각 처리부터 수년에 걸쳐 축적된 지식까지 서로 다른 시간 규모(Time Scales)의 정보를 지속적으로 통합합니다. 이러한 시간적 통합(Temporal Integration)은 순차적 예측(Sequential Prediction), 계획(Planning), 월드 모델링(World Modeling)의 중요한 기반을 제공합니다.

따라서 예측(Prediction)은 인지와 밀접하게 연결됩니다. 지능형 에이전트(Intelligent Agent)는 다음에 발생할 가능성이 높은 감각 입력, 환경 변화(Environmental Change), 행동 결과(Behavioral Consequence)를 예상함으로써 이점을 얻을 수 있습니다. 예측은 기대와 실제 관찰 사이의 차이를 유용한 학습 신호(Learning Signal)로 사용할 수 있게 합니다. 이러한 관점은 인지과학을 예측 처리(Predictive Processing), 생성 모델링(Generative Modeling), 모델 기반 강화학습(Model-Based Reinforcement Learning), 현대적 계산 월드 모델(Computational World Models)과 연결합니다.

인지(Cognition)는 행동과 독립적으로 발생하는 순수하게 수동적인 과정으로 이해해서는 안 됩니다. 지각은 행동에 영향을 미치고, 행동은 환경을 변화시키며, 그 결과 발생하는 감각적 결과(Sensory Consequences)는 지각과 학습에 새로운 증거를 제공합니다. 이러한 지각-행동 루프(Perception-Action Loop)는 에이전트가 감지(Sensing), 예측, 계획, 제어(Control), 물리적 상호작용(Physical Interaction)을 지속적으로 조정해야 하는 체화 지능(Embodied Intelligence)에서 특히 중요합니다.

체화 인지(Embodied Cognition)는 지능이 뇌(Brain), 신체(Body), 환경(Environment), 작업(Task)의 상호작용을 통해 발전한다는 점을 강조합니다. 물리적 구조(Physical Structure)는 가능한 행동을 제한하고, 행동은 지각에 어떤 정보가 제공되는지를 결정합니다. 로보틱스(Robotics)와 피지컬 AI(Physical AI)의 관점에서 이는 인지가 형태학(Morphology), 센서 구성(Sensor Configuration), 운동 능력(Motor Capability), 환경 동역학(Environmental Dynamics), 실시간 제어(Real-Time Control)와 항상 명확하게 분리될 수 없다는 것을 의미합니다.

사회적 인지(Social Cognition)는 지능에 또 다른 차원을 추가합니다. 인간은 다른 에이전트의 행동을 예측하면서 얼굴 표정(Facial Expressions), 몸짓(Gestures), 의도(Intentions), 믿음(Beliefs), 목표(Goals), 감정(Emotions), 사회적 관계(Social Relationships)를 해석합니다. 이러한 능력은 협력(Cooperation), 의사소통(Communication), 모방(Imitation), 교육(Teaching), 협조적 행동(Coordinated Action)을 가능하게 합니다. 인간과 상호작용하는 AI 시스템 역시 의도 추정(Intent Estimation), 관점 취하기(Perspective Taking), 의사소통, 적응형 협업(Adaptive Collaboration)을 위한 대응 메커니즘을 점차 필요로 합니다.

메타인지(Metacognition)는 자신의 인지 과정 자체에 대한 인지를 의미합니다. 인간은 자신이 어떤 내용을 알고 있는지 평가하고, 불확실성을 인식하며, 오류를 감지하고, 전략을 재검토하며, 신뢰도(Confidence)가 낮을 경우 추가적인 노력을 할당할 수 있습니다. 이와 유사한 능력은 AI 시스템에도 중요합니다. 지능형 에이전트는 신뢰할 수 있는 결론과 불확실한 결론을 구분하고, 언제 추가 증거나 외부 지원(External Assistance)이 필요한지를 판단할 수 있어야 합니다.

인지과학은 또한 지능이 여러 제약조건(Constraints) 아래에서 작동한다는 점을 강조합니다. 인간의 작업 기억은 제한적이고, 주의는 선택적이며, 모든 정보를 확보하기 전에 결정을 내려야 하는 경우가 많고, 계산에는 생물학적 자원(Biological Resources)이 소비됩니다. 이러한 제약은 인지를 비효율적으로 만드는 대신 추상화, 청킹(Chunking), 선택적 검색(Selective Retrieval), 계층적 계획(Hierarchical Planning), 근사 추론(Approximate Reasoning)과 같은 효율적인 전략을 촉진합니다.

이러한 제한된 인지(Bounded Cognition)의 개념은 지능을 주로 계산 규모(Computational Scale)의 증가와 동일시하는 접근법과 중요한 대비를 이룹니다. 인간 지능은 선택적 계산(Selective Computation), 재사용 가능한 표현(Reusable Representations), 전문화된 하위 시스템(Specialized Subsystems), 기억, 예측, 적응형 자원 할당을 통해 높은 수준의 행동이 나타날 수 있음을 보여줍니다. 따라서 인지과학은 단순한 계산 능력뿐 아니라 효율성을 추구하는 AI 시스템 설계에도 중요한 원리를 제공합니다.

인지 아키텍처(Cognitive Architectures)는 이러한 메커니즘들을 통합하여 지능적 행동의 통합 모델(Unified Models)을 구축하려고 합니다. 지각, 기억, 추론, 행동을 각각 독립적으로 모델링하는 대신, 인지 아키텍처는 기능적 구성요소(Functional Components) 사이에서 정보가 어떻게 이동하며 이러한 구성요소가 시간에 따라 어떻게 협력하는지를 정의합니다. 이러한 아키텍처는 파운데이션 모델(Foundation Models), 기억, 계획, 도구(Tools), 환경 상호작용을 결합하는 현대 AI 에이전트(AI Agents)의 개념적 선행 사례를 제공합니다.

그러나 인지과학(Cognitive Science)을 인공지능(Artificial Intelligence)을 위한 직접적인 공학 설계도(Engineering Blueprint)로 이해해서는 안 됩니다. 심리학적 이론은 최적의 계산 구현을 제시하지 않으면서 인간 행동을 설명할 수 있으며, 성공적인 AI 메커니즘이 반드시 인간의 인지를 그대로 재현하는 것도 아닙니다. 생산적인 목표는 생물학적 설명(Biological Explanation)과 공학적 설계(Engineering Design)의 차이를 유지하면서 인공 시스템에 영감을 제공할 수 있는 계산 원리(Computational Principles)를 발견하는 것입니다.

따라서 실험 방법(Experimental Methods)은 인지과학에서 필수적입니다. 연구자들은 정확도(Accuracy), 반응 시간(Reaction Time), 회상(Recall), 안구 움직임(Eye Movement), 선택 패턴(Choice Patterns), 오류 분포(Error Distributions)와 같은 행동 측정치를 사용하여 그 이면의 인지 과정을 추론합니다. 이후 계산 모델은 관찰 결과와 비교할 수 있는 예측을 생성하며, 이를 통해 이론적 가설(Theoretical Hypotheses), 실험적 증거(Experimental Evidence), 수학적 모델(Mathematical Models), 시뮬레이션(Simulation) 사이에 반복적인 관계가 형성됩니다.

AI 연구 관점에서 이러한 방법론은 중요한 교훈을 제공합니다. 지능은 모델 크기(Model Size)만으로 평가하는 것이 아니라 행동 능력(Behavioral Capabilities)과 실패 패턴(Failure Patterns)을 통해 평가해야 합니다. 통제된 실험(Controlled Experiments)을 통해 시스템이 실제로 일반화하고, 관련 정보를 기억하며, 조합적 추론(Compositional Reasoning)을 수행하고, 변화하는 조건에 적응하며, 불확실성을 관리하는지 또는 단순히 학습 데이터 분포에 포함된 통계적 규칙성을 이용하는지를 확인할 수 있습니다.

현대 파운데이션 모델(Foundation Models)은 AI와 인지과학 사이의 상호작용을 위한 새로운 가능성을 제공합니다. 대규모 언어 모델(Large Language Models), 멀티모달 모델(Multimodal Models), 생성 모델(Generative Models), 자율 에이전트(Autonomous Agents)는 표현, 문맥 학습(Contextual Learning), 검색(Retrieval), 추론, 계획, 도구 사용(Tool Use)과 관련된 행동을 보여줍니다. 이러한 시스템은 인지 가설을 검증할 수 있는 계산 플랫폼을 제공하는 동시에, 인지 이론은 이러한 시스템의 능력과 한계를 분석하기 위한 프레임워크를 제공합니다.

동시에 현재의 AI와 인간 인지 사이에는 여전히 중요한 차이가 존재합니다. 인간은 멀티모달 체화 경험(Multimodal Embodied Experience)을 통해 지속적으로 학습하고, 지속적인 목표와 기억을 유지하며, 제한된 에너지로 작동하고, 변화하는 환경에 빠르게 적응하며, 지각을 물리적·사회적 상호작용과 통합합니다. 반면 많은 AI 시스템은 대규모 오프라인 데이터셋(Offline Datasets), 고정된 학습 단계(Fixed Training Phases), 외부 기억 메커니즘(External Memory Mechanisms), 제한적으로 정의된 배포 조건(Deployment Conditions)에 의존합니다.

이러한 차이는 보다 일반적인 AI 시스템을 개발하는 과정에서 인지과학의 중요성을 더욱 높입니다. 작업 기억(Working Memory)에 관한 연구는 컨텍스트 관리(Context Management)에 활용될 수 있고, 주의 연구는 선택적 계산을 위한 아이디어를 제공할 수 있으며, 인간 학습은 지속 학습(Continual Learning)과 퓨샷 적응(Few-Shot Adaptation)에 영감을 줄 수 있습니다. 또한 인지 제어(Cognitive Control)는 에이전트 아키텍처에 영향을 미치며, 정신적 시뮬레이션(Mental Simulation) 연구는 계획과 예측형 월드 모델(Predictive World Models)에 기여할 수 있습니다.

이러한 관계는 체화 AI(Embodied AI)와 로보틱스(Robotics)에서 더욱 중요해집니다. 실제 물리 세계에서 작동하는 로봇은 불확실한 센서 정보를 해석하고, 관련 사건을 기억하며, 객체와 상황을 인식하고, 환경 동역학을 예측하며, 목표를 선택하고, 행동을 계획하고, 실패를 감지하며, 자신의 행동을 적응시켜야 합니다. 이러한 요구사항은 인지과학 전반에서 연구되는 통합적 인지 기능과 밀접하게 대응합니다.

월드 모델(World Models)은 인지과학과 현대 피지컬 AI(Physical AI)를 연결하는 특히 중요한 다리를 제공합니다. 내부 모델(Internal Model)은 개체(Entities), 관계(Relationships), 동역학(Dynamics), 불확실성(Uncertainty), 행동으로 인해 발생할 수 있는 미래 결과(Future Consequences)를 표현할 수 있습니다. 이러한 표현을 갖춘 에이전트는 현재 관찰에 단순히 반응하는 대신 여러 대안적 미래(Alternative Futures)를 내부적으로 평가하고, 실제 물리적 행동을 실행하기 전에 예측 결과에 따라 행동을 선택할 수 있습니다.

따라서 완전한 인지적 관점(Cognitive Perspective)은 단순한 지각 이후 의사결정과 행동이 이어지는 순차적 구조를 넘어섭니다. 지능적 행동은 지각, 주의, 기억, 표현, 학습, 예측, 추론, 계획, 의사결정, 행동 사이의 반복적 상호작용(Recurrent Interaction)에서 발생합니다. 각각의 과정은 다른 과정에 영향을 미치며, 과거 경험(Past Experience), 현재 관찰(Present Observation), 예상되는 미래(Anticipated Futures)를 연결하는 내부 상태(Internal State)를 지속적으로 갱신합니다.

AI 공학(AI Engineering)의 관점에서 인지과학이 중요한 이유는 인공 시스템이 인간 인지의 모든 세부사항을 모방해야 하기 때문이 아니라, 부족한 능력을 식별할 수 있는 구조화된 어휘(Structured Vocabulary)를 제공하기 때문입니다. AI 시스템이 실패할 때 그 원인은 단순히 모델 용량(Model Capacity)이 부족해서가 아니라 지각, 기억, 표현, 주의, 추론, 불확실성, 계획, 적응 또는 이러한 기능 사이의 협력 과정에서 발생할 수 있습니다.

보다 넓은 관점에서의 목표는 지능(Intelligence)을 통합된 적응 시스템(Integrated Adaptive System)으로 이해하는 것입니다. 인지과학은 인간에게서 이러한 통합이 어떻게 이루어지는지에 대한 이론과 실험적 증거를 제공하며, AI는 다양한 형태의 지능을 구축하고 검증할 수 있는 계산 메커니즘(Computational Mechanisms)을 제공합니다. 두 분야의 상호작용은 복잡한 환경에서 학습하고, 예측하고, 추론하고, 기억하고, 의사소통하며, 행동할 수 있는 더욱 발전된 지능형 에이전트(Intelligent Agents)를 구축하기 위한 기반을 제공합니다.

##  

## 01.01 Perception and Action [w/Code]

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

Perception and action are deeply interconnected components of cognition rather than independent stages arranged in a simple linear pipeline. Perception extracts meaningful structure from sensory information, while action changes the environment and determines what information becomes available next. Cognitive systems therefore operate through a continuous perception--action loop in which sensing, interpretation, decision, movement, and feedback repeatedly influence one another.

Perception begins with sensory signals generated by interactions between an organism and its environment. Vision, hearing, touch, proprioception, balance, and other modalities provide different forms of information about objects, events, spatial relationships, and the state of the body. These signals are incomplete and noisy, so cognition must transform them into structured representations that can guide behavior.

Human perception is constructive rather than purely receptive. The brain does not simply reproduce sensory input exactly as it arrives. Instead, perceptual processing combines incoming evidence with previous experience, expectations, context, attention, and task goals. This combination allows a person to recognize meaningful objects and situations even when sensory information is ambiguous, partially occluded, distorted, or rapidly changing.

Visual perception illustrates this principle clearly. Light patterns reaching the eyes must be transformed into representations of edges, surfaces, depth, motion, objects, and spatial relationships. The same retinal image may support several possible interpretations, so perceptual systems use contextual information and learned regularities to infer the most plausible structure of the environment rather than treating perception as direct measurement.

Auditory perception presents a similar challenge. Sound waves contain overlapping signals generated by speech, machines, music, environmental events, and background noise. Cognitive processing separates these sources, identifies relevant patterns, estimates their location, and links them with prior knowledge. Attention further determines which sounds become behaviorally important and which can be ignored during a particular task.

Touch and proprioception provide complementary information about physical interaction and body state. Tactile signals indicate contact, pressure, texture, temperature, and local forces, while proprioception provides information about joint configuration, movement, and body position. These modalities are particularly important for actions requiring precise manipulation because visual information alone may not reveal whether an object has been grasped securely.

Perception is therefore naturally multimodal. Different sensory channels provide partially overlapping but complementary evidence about the same environment. Humans combine vision, hearing, touch, proprioception, and vestibular signals to form more reliable estimates of objects, locations, events, and body state. When one modality becomes unreliable, other modalities can compensate, increasing robustness under uncertain conditions.

Multisensory integration requires information to be aligned across both time and space. A sound must be associated with the object that produced it, tactile feedback must be linked with the body part or tool generating contact, and visual movement must be related to proprioceptive estimates of self-motion. Accurate cognitive representation depends on solving these correspondence problems continuously.

Attention plays an important role in organizing perception for action. An environment may contain far more information than can be processed with equal precision, so cognitive systems selectively allocate processing resources. Task goals influence which objects, locations, sensory modalities, or features receive priority, allowing perception to become specialized for the action currently being prepared or executed.

This relationship means that perception depends partly on intention. A person searching for a door handle, avoiding an obstacle, reading text, or preparing to grasp a cup may observe the same scene differently because each task requires different information. Perception is consequently shaped not only by what exists in the environment but also by what the cognitive system is trying to accomplish.

Action begins with the selection of a behavior that can transform the current situation toward a desired state. Actions can include eye movements, reaching, grasping, walking, speaking, navigation, tool use, or complex sequences involving many coordinated movements. Cognitive control must translate abstract goals into executable commands while considering the body, environment, constraints, risks, and expected consequences.

Motor control operates hierarchically across multiple levels. High-level processes may specify goals such as reaching a location or obtaining an object, intermediate processes determine suitable movement strategies, and lower-level mechanisms regulate muscle activity, posture, force, timing, and trajectory. Feedback continuously corrects deviations between intended and actual movement during execution.

Actions are constrained by affordances, which describe opportunities for behavior that arise from relationships among the agent, objects, and environment. A surface may support walking, a handle may support pulling, a container may support placing objects inside, and a gap may or may not permit passage depending on body size. Perception for action therefore often involves detecting what can be done rather than merely identifying what something is.

Affordances demonstrate why object recognition alone is insufficient for intelligent behavior. Knowing that an object is a cup provides semantic information, but successful interaction requires knowledge about where it can be grasped, whether it is full, how heavy it may be, which orientations are stable, and what movements are safe. Cognitive systems connect semantic understanding with action possibilities and physical constraints.

The perception--action loop becomes especially clear during manipulation. When reaching toward an object, visual perception estimates its location and orientation, motor commands move the arm, proprioception reports limb position, and tactile feedback indicates contact. These observations continually update the movement, allowing the hand to correct its trajectory and adjust grip force until the intended interaction is completed.

Movement itself can also improve perception. Humans turn their heads to localize sounds, move their eyes to inspect visual details, touch surfaces to estimate texture, and reposition objects to reveal hidden structure. Such exploratory actions demonstrate active perception, in which an intelligent agent deliberately acts to obtain better information rather than passively waiting for sensory evidence.

Active perception transforms sensing into a goal-directed process. When uncertainty is high, a cognitive system can choose actions specifically because they reduce uncertainty. Moving closer to an object, changing viewpoint, asking a question, touching an unfamiliar surface, or examining another region of a scene can provide information required for later decisions. Perception thus becomes integrated with information-seeking behavior.

Predictions play an important role throughout this loop. Before executing an action, the cognitive system can estimate its likely sensory and environmental consequences. These predictions provide a reference against which actual observations can be compared. Differences between predicted and observed outcomes indicate that either the environmental model, action plan, or execution process may need to be updated.

Such prediction supports rapid feedback control. If the expected position of a moving object differs from its observed position, movement can be corrected. If an expected tactile signal does not occur during grasping, grip configuration can be adjusted. Perception and action therefore interact not only through complete task cycles but also through continuous prediction and correction at very short time scales.

Internal models make this predictive interaction possible. A cognitive system maintains representations of the environment, body, objects, goals, and causal relationships. These representations allow it to estimate how actions might change future states before physically executing them. Internal simulation therefore provides a bridge between perception, planning, and action and supports goal-directed behavior under uncertainty.

Forward models estimate the sensory or state consequences likely to result from a particular action. Given the current state and a candidate motor command, a forward model predicts what should happen next. Such models allow an agent to anticipate motion, detect unexpected disturbances, and compare intended outcomes with actual feedback during execution.

Inverse models address the complementary problem. Instead of predicting consequences from actions, they estimate which actions are required to achieve a desired state. For example, if an agent wishes to move its hand to a particular location, an inverse model helps determine the motor commands necessary to produce that movement. Effective behavior often requires interaction between forward and inverse computations.

The distinction between feedforward and feedback control is also important. Feedforward control relies on predictions made before an action is completed, enabling rapid responses without waiting for sensory correction. Feedback control uses observations during execution to reduce error. Skilled action generally combines both approaches, using prediction for speed and feedback for robustness.

Learning improves the perception--action relationship through experience. Repeated interaction teaches which sensory patterns correspond to relevant environmental structures, which actions are possible, and which consequences are likely to follow specific behaviors. As experience accumulates, frequently performed actions become more accurate, efficient, and automatic while perception becomes increasingly tuned to task-relevant information.

Sensorimotor learning is particularly important because it connects perception directly with movement consequences. An agent learns not only what objects look like but also how visual changes correspond to self-motion, how tactile patterns correspond to contact conditions, and how motor commands alter body configuration. These learned regularities support calibration, coordination, prediction, and adaptation.

Development provides strong evidence for the importance of sensorimotor interaction. Human perceptual and motor abilities develop together as infants explore their bodies and environments. Reaching, looking, crawling, manipulating objects, and interacting socially generate structured experience from which increasingly sophisticated internal representations emerge. Cognition develops partly through active engagement rather than passive observation alone.

Embodied cognition extends this insight by proposing that cognitive processes depend on the physical characteristics of the body and its interaction with the environment. Body geometry, sensory placement, movement range, strength, and physical constraints influence which actions are possible and which information can be acquired. Intelligence is therefore partly shaped by the embodiment through which perception and action occur.

The environment itself can become part of cognitive processing. Instead of representing every detail internally, humans frequently use external structure to reduce cognitive load. People reposition objects, write notes, arrange tools, look back at information, or use spatial layouts to support memory and reasoning. Action can therefore modify the environment in ways that make subsequent cognition easier.

Perception and action also operate across several temporal scales. Low-level sensorimotor corrections occur within fractions of a second, while activities such as navigation and manipulation unfold across seconds or minutes. Higher-level goals and plans may extend across hours or longer. Cognitive systems must coordinate these scales so that immediate actions remain aligned with broader objectives.

Hierarchical organization helps solve this coordination problem. High-level cognition represents goals and abstract actions, while lower levels manage detailed movement and sensory feedback. A single intention such as preparing a meal may be decomposed into navigation, object search, reaching, grasping, transport, placement, and manipulation, each containing further sensorimotor control processes.

Action selection must also consider uncertainty and risk. Perceptual estimates are rarely perfectly reliable, and actions can have irreversible or dangerous consequences. Cognitive systems therefore balance potential benefits against uncertainty, effort, physical limitations, and safety. When confidence is insufficient, an agent may seek additional information, choose a safer action, or delay commitment.

Failures provide valuable information within the perception--action loop. An unsuccessful grasp, unexpected obstacle, incorrect prediction, or unstable movement generates evidence that existing representations or policies are incomplete. Adaptive cognition uses these discrepancies to modify future perception, planning, and action, turning errors into opportunities for learning rather than treating them only as negative outcomes.

Social interaction creates another form of perception--action coupling. People perceive the expressions, gestures, speech, gaze, and movements of others while simultaneously producing actions that influence subsequent social responses. Communication is therefore inherently interactive, with perception and behavior repeatedly updating predictions about intentions, goals, emotional states, and shared tasks.

Language can also participate directly in action control. Verbal instructions establish goals, constrain behavior, describe objects, or specify action sequences. Spoken feedback can correct ongoing behavior, while internally represented language can support planning and self-regulation. This creates a connection among language, perception, reasoning, and physical action within integrated cognition.

For artificial intelligence, the perception--action relationship is fundamental to autonomous agents. An AI system operating only on static data can perform recognition or prediction without affecting its inputs, but an embodied agent changes the world through its decisions. Each action creates new observations, making the future input distribution partly dependent on the agent\'s own previous behavior.

This closed-loop property changes the engineering problem significantly. Errors in perception can produce incorrect actions, incorrect actions can move the system into unfamiliar states, and those states can produce additional perceptual errors. Robust autonomous systems therefore require continuous state estimation, uncertainty management, feedback, recovery behavior, and mechanisms for detecting when the perception--action loop is becoming unstable.

Robotics provides a direct computational realization of these ideas. Cameras, LiDAR, microphones, tactile sensors, force sensors, encoders, IMUs, and other devices provide multimodal observations. Perception algorithms transform these signals into representations of objects, geometry, motion, localization, affordances, and uncertainty, which planning and control systems then use to select and execute physical actions.

Modern Physical AI increasingly integrates these components with learned representations and foundation models. Perception foundation models can provide semantic and multimodal understanding, while action models or policies translate contextual representations into behavior. Memory, reasoning, planning, and world models can connect these layers, allowing the system to operate over longer horizons than conventional reactive control.

World models are especially relevant because they allow an agent to predict how the environment may evolve under different candidate actions. Instead of selecting behavior only from the current observation, the system can generate or estimate possible future states, compare predicted outcomes, and choose actions that best support its objectives. This resembles the role of internal simulation in cognitive accounts of planning.

However, intelligent perception--action systems must preserve a connection between abstract reasoning and physical feasibility. A high-level model may propose semantically reasonable actions that cannot be executed because of geometry, force limits, collision risk, timing, or hardware constraints. Effective embodied cognition therefore requires continual interaction between abstract knowledge and grounded sensorimotor information.

This grounding problem is one of the central challenges in both cognitive science and AI. Symbols and language must ultimately connect with objects, properties, relationships, actions, and consequences in the environment. Perception supplies this connection from the world to internal representations, while action provides the complementary path from internal goals and decisions back into the world.

The perception--action cycle can therefore be understood as a fundamental computational structure underlying adaptive intelligence. Observation updates internal state, internal state supports prediction and decision, decisions generate actions, actions change both the environment and the agent, and resulting sensory evidence begins the cycle again. Learning modifies every stage as repeated interaction produces increasingly useful representations and policies.

From a cognitive science perspective, this closed loop explains why perception cannot be fully understood without considering behavior, goals, memory, prediction, and embodiment. From an AI perspective, it suggests that increasingly capable autonomous systems should not treat perception, reasoning, and control as isolated modules. Their effectiveness depends on how accurately and efficiently information circulates through the entire loop.

Ultimately, intelligent behavior emerges from coordinated interaction between sensing and doing. Perception provides an actionable interpretation of the current world, while action tests predictions, achieves goals, and creates new evidence. Their continuous coupling enables adaptation, exploration, learning, planning, and purposeful interaction, making the perception--action loop one of the foundational mechanisms linking cognitive science, robotics, embodied AI, and general intelligent systems.

지각(Perception)과 행동(Action)은 단순한 선형 파이프라인(Linear Pipeline)에 배치된 독립적인 단계가 아니라 서로 깊게 연결된 인지(Cognition)의 구성요소입니다. 지각은 감각 정보(Sensory Information)에서 의미 있는 구조를 추출하고, 행동은 환경(Environment)을 변화시키면서 다음에 어떤 정보가 제공될지를 결정합니다. 따라서 인지 시스템(Cognitive Systems)은 감지(Sensing), 해석(Interpretation), 의사결정(Decision), 움직임(Movement), 피드백(Feedback)이 반복적으로 서로 영향을 주는 지속적인 지각-행동 루프(Perception--Action Loop)를 통해 작동합니다.

지각(Perception)은 유기체(Organism)와 환경(Environment)의 상호작용에서 생성되는 감각 신호(Sensory Signals)로부터 시작됩니다. 시각(Vision), 청각(Hearing), 촉각(Touch), 고유수용감각(Proprioception), 평형감각(Balance) 및 기타 감각 양식(Modalities)은 객체(Objects), 사건(Events), 공간적 관계(Spatial Relationships), 신체 상태(Body State)에 대한 서로 다른 형태의 정보를 제공합니다. 이러한 신호는 불완전하고 잡음이 포함될 수 있으므로 인지 시스템은 이를 행동을 유도할 수 있는 구조화된 표현(Structured Representations)으로 변환해야 합니다.

인간의 지각(Human Perception)은 순수하게 수용적인 과정이라기보다 구성적인 과정(Constructive Process)입니다. 뇌(Brain)는 감각 입력을 도착한 그대로 단순히 재현하지 않습니다. 대신 지각 처리는 입력되는 증거를 이전 경험(Previous Experience), 기대(Expectations), 문맥(Context), 주의(Attention), 작업 목표(Task Goals)와 결합합니다. 이러한 결합을 통해 감각 정보가 모호하거나 부분적으로 가려지고 왜곡되거나 빠르게 변화하는 상황에서도 의미 있는 객체와 상황을 인식할 수 있습니다.

시각적 지각(Visual Perception)은 이러한 원리를 명확하게 보여줍니다. 눈에 도달하는 빛의 패턴은 경계(Edges), 표면(Surfaces), 깊이(Depth), 움직임(Motion), 객체(Objects), 공간적 관계에 대한 표현으로 변환되어야 합니다. 동일한 망막 영상(Retinal Image)에서도 여러 해석이 가능하기 때문에 지각 시스템은 지각을 직접적인 측정으로 처리하기보다 문맥 정보와 학습된 규칙성(Learned Regularities)을 이용하여 환경의 가장 가능성 높은 구조를 추론합니다.

청각적 지각(Auditory Perception)도 이와 유사한 문제를 가집니다. 음파(Sound Waves)에는 음성(Speech), 기계(Machines), 음악(Music), 환경적 사건(Environmental Events), 배경 소음(Background Noise)에서 생성되는 신호가 서로 중첩되어 있습니다. 인지 처리는 이러한 음원을 분리하고, 관련 패턴을 식별하고, 위치를 추정하며, 기존 지식(Prior Knowledge)과 연결합니다. 또한 주의(Attention)는 특정 작업에서 어떤 소리가 행동적으로 중요한지와 어떤 소리를 무시할 수 있는지를 결정합니다.

촉각(Touch)과 고유수용감각(Proprioception)은 물리적 상호작용(Physical Interaction)과 신체 상태에 관한 상호보완적인 정보를 제공합니다. 촉각 신호는 접촉(Contact), 압력(Pressure), 질감(Texture), 온도(Temperature), 국부적인 힘(Local Forces)을 나타내며, 고유수용감각은 관절 구성(Joint Configuration), 움직임, 신체 위치에 대한 정보를 제공합니다. 이러한 감각 양식은 시각 정보만으로는 객체가 안정적으로 파지되었는지를 판단하기 어려운 정밀 조작(Precise Manipulation)에서 특히 중요합니다.

따라서 지각은 본질적으로 멀티모달(Multimodal)입니다. 서로 다른 감각 채널(Sensory Channels)은 동일한 환경에 대해 부분적으로 중첩되면서도 상호보완적인 증거를 제공합니다. 인간은 시각, 청각, 촉각, 고유수용감각, 전정감각(Vestibular Signals)을 결합하여 객체, 위치, 사건, 신체 상태를 보다 신뢰성 있게 추정합니다. 하나의 감각 양식이 신뢰하기 어려워지면 다른 감각 양식이 이를 보완하여 불확실한 조건에서도 강건성(Robustness)을 향상시킬 수 있습니다.

다중감각 통합(Multisensory Integration)을 위해서는 정보가 시간과 공간 모두에서 정렬되어야 합니다. 소리는 그것을 발생시킨 객체와 연결되어야 하고, 촉각 피드백(Tactile Feedback)은 접촉을 발생시킨 신체 부위 또는 도구와 연결되어야 하며, 시각적 움직임은 자기 움직임(Self-Motion)에 대한 고유수용감각 추정과 연관되어야 합니다. 정확한 인지 표현(Cognitive Representation)은 이러한 대응 문제(Correspondence Problems)를 지속적으로 해결하는 과정에 의존합니다.

주의(Attention)는 행동을 위한 지각(Perception for Action)을 구성하는 데 중요한 역할을 합니다. 환경에는 동일한 정밀도로 처리할 수 있는 수준을 훨씬 넘어서는 정보가 존재할 수 있으므로, 인지 시스템은 처리 자원(Processing Resources)을 선택적으로 할당합니다. 작업 목표는 어떤 객체, 위치, 감각 양식 또는 특징(Features)에 우선순위를 부여할지를 결정하며, 이를 통해 지각은 현재 준비되거나 실행되는 행동에 특화될 수 있습니다.

이러한 관계는 지각이 부분적으로 의도(Intention)에 의존한다는 것을 의미합니다. 문 손잡이를 찾거나, 장애물을 피하거나, 문자를 읽거나, 컵을 잡으려고 준비하는 사람은 동일한 장면(Scene)을 서로 다르게 관찰할 수 있습니다. 각각의 작업에는 서로 다른 정보가 필요하기 때문입니다. 따라서 지각은 환경에 무엇이 존재하는지뿐 아니라 인지 시스템이 무엇을 달성하려 하는지에 의해서도 형성됩니다.

행동(Action)은 현재 상황을 원하는 상태(Desired State)로 변화시킬 수 있는 행동 방식을 선택하는 과정에서 시작됩니다. 행동에는 안구 운동(Eye Movements), 손 뻗기(Reaching), 파지(Grasping), 보행(Walking), 말하기(Speaking), 내비게이션(Navigation), 도구 사용(Tool Use), 여러 움직임이 조정된 복잡한 시퀀스(Complex Sequences)가 포함될 수 있습니다. 인지 제어(Cognitive Control)는 신체, 환경, 제약조건, 위험, 예상 결과를 고려하면서 추상적인 목표를 실행 가능한 명령으로 변환해야 합니다.

운동 제어(Motor Control)는 여러 수준에 걸쳐 계층적으로 작동합니다. 상위 수준의 과정은 특정 위치에 도달하거나 객체를 획득하는 것과 같은 목표를 지정할 수 있고, 중간 수준의 과정은 적절한 움직임 전략(Movement Strategies)을 결정하며, 하위 수준의 메커니즘은 근육 활동(Muscle Activity), 자세(Posture), 힘(Force), 타이밍(Timing), 궤적(Trajectory)을 조절합니다. 실행 과정에서는 피드백을 통해 의도된 움직임과 실제 움직임 사이의 차이를 지속적으로 보정합니다.

행동은 어포던스(Affordances)에 의해 제약되기도 합니다. 어포던스는 에이전트(Agent), 객체, 환경 사이의 관계에서 발생하는 행동 가능성(Opportunities for Behavior)을 의미합니다. 표면은 보행을 가능하게 하고, 손잡이는 당기는 행동을 가능하게 하며, 용기는 객체를 내부에 넣을 수 있게 합니다. 또한 틈새를 통과할 수 있는지는 신체 크기에 따라 달라질 수 있습니다. 따라서 행동을 위한 지각은 단순히 어떤 것이 무엇인지를 식별하는 것이 아니라 무엇을 할 수 있는지를 탐지하는 과정과 관련됩니다.

어포던스(Affordances)는 객체 인식(Object Recognition)만으로 지능적 행동을 충분히 구현할 수 없는 이유를 보여줍니다. 어떤 객체가 컵이라는 것을 아는 것은 의미론적 정보(Semantic Information)를 제공하지만, 성공적으로 상호작용하려면 어디를 잡을 수 있는지, 내용물이 들어 있는지, 얼마나 무거울 가능성이 있는지, 어떤 방향이 안정적인지, 어떤 움직임이 안전한지를 알아야 합니다. 인지 시스템은 의미론적 이해(Semantic Understanding)를 행동 가능성과 물리적 제약조건(Physical Constraints)에 연결합니다.

지각-행동 루프(Perception--Action Loop)는 조작(Manipulation) 과정에서 특히 명확하게 나타납니다. 객체를 향해 손을 뻗을 때 시각적 지각은 객체의 위치와 방향(Orientation)을 추정하고, 운동 명령(Motor Commands)은 팔을 움직이며, 고유수용감각은 팔의 위치를 알려주고, 촉각 피드백은 접촉 여부를 제공합니다. 이러한 관찰은 움직임을 지속적으로 갱신하여 손의 궤적을 보정하고 의도한 상호작용이 완료될 때까지 파지력을 조절하도록 합니다.

움직임 자체도 지각을 향상시킬 수 있습니다. 인간은 소리의 위치를 파악하기 위해 머리를 돌리고, 시각적 세부사항을 확인하기 위해 눈을 움직이며, 질감을 추정하기 위해 표면을 만지고, 가려진 구조를 확인하기 위해 객체의 위치를 변경합니다. 이러한 탐색적 행동(Exploratory Actions)은 지능형 에이전트가 감각적 증거를 수동적으로 기다리는 대신 더 좋은 정보를 얻기 위해 의도적으로 행동하는 능동 지각(Active Perception)을 보여줍니다.

능동 지각(Active Perception)은 감지(Sensing)를 목표 지향적 과정(Goal-Directed Process)으로 변화시킵니다. 불확실성이 높을 경우 인지 시스템은 불확실성을 줄이기 위한 목적으로 행동을 선택할 수 있습니다. 객체에 가까이 이동하거나, 관점을 변경하거나, 질문하거나, 익숙하지 않은 표면을 만지거나, 장면의 다른 영역을 조사함으로써 이후 의사결정에 필요한 정보를 얻을 수 있습니다. 따라서 지각은 정보 탐색 행동(Information-Seeking Behavior)과 통합됩니다.

예측(Predictions)은 이러한 루프 전반에서 중요한 역할을 합니다. 행동을 실행하기 전에 인지 시스템은 예상되는 감각적 결과와 환경적 결과(Environmental Consequences)를 추정할 수 있습니다. 이러한 예측은 실제 관찰과 비교할 수 있는 기준을 제공합니다. 예측된 결과와 관찰된 결과의 차이는 환경 모델(Environmental Model), 행동 계획(Action Plan), 실행 과정 가운데 하나 이상을 갱신해야 할 가능성을 나타냅니다.

이러한 예측은 빠른 피드백 제어(Feedback Control)를 지원합니다. 움직이는 객체의 예상 위치와 관찰 위치가 다르면 움직임을 수정할 수 있습니다. 파지 과정에서 예상했던 촉각 신호가 발생하지 않으면 파지 구성(Grip Configuration)을 조정할 수 있습니다. 따라서 지각과 행동은 전체 작업 주기뿐 아니라 매우 짧은 시간 규모에서 이루어지는 지속적인 예측과 보정을 통해 상호작용합니다.

내부 모델(Internal Models)은 이러한 예측적 상호작용을 가능하게 합니다. 인지 시스템은 환경, 신체, 객체, 목표, 인과관계(Causal Relationships)에 대한 표현을 유지합니다. 이러한 표현을 이용하면 행동을 실제로 실행하기 전에 행동이 미래 상태(Future States)를 어떻게 변화시킬지를 추정할 수 있습니다. 따라서 내부 시뮬레이션(Internal Simulation)은 지각, 계획, 행동을 연결하며 불확실성 아래에서 목표 지향적 행동을 지원합니다.

순방향 모델(Forward Models)은 특정 행동으로 인해 발생할 가능성이 높은 감각적 또는 상태적 결과를 추정합니다. 현재 상태와 후보 운동 명령(Candidate Motor Command)이 주어지면 순방향 모델은 다음에 어떤 일이 발생할지를 예측합니다. 이러한 모델을 통해 에이전트는 움직임을 예상하고, 예상하지 못한 외란(Disturbances)을 감지하며, 실행 중 의도된 결과와 실제 피드백을 비교할 수 있습니다.

역방향 모델(Inverse Models)은 이와 상호보완적인 문제를 처리합니다. 행동으로부터 결과를 예측하는 대신 원하는 상태를 달성하기 위해 어떤 행동이 필요한지를 추정합니다. 예를 들어 에이전트가 손을 특정 위치로 이동하려는 경우 역방향 모델은 그 움직임을 생성하기 위해 필요한 운동 명령을 결정하는 데 도움을 줍니다. 효과적인 행동에는 순방향 계산과 역방향 계산 사이의 상호작용이 필요한 경우가 많습니다.

피드포워드 제어(Feedforward Control)와 피드백 제어(Feedback Control)의 구분 역시 중요합니다. 피드포워드 제어는 행동이 완료되기 전에 생성된 예측에 의존하여 감각적 보정을 기다리지 않고 빠르게 반응할 수 있도록 합니다. 반면 피드백 제어는 실행 중 관찰 정보를 사용하여 오류를 줄입니다. 숙련된 행동은 일반적으로 두 방식을 결합하여 예측을 통해 속도를 확보하고 피드백을 통해 강건성을 확보합니다.

학습(Learning)은 경험을 통해 지각-행동 관계를 향상시킵니다. 반복적인 상호작용을 통해 어떤 감각 패턴이 관련 환경 구조에 대응하는지, 어떤 행동이 가능한지, 특정 행동 이후 어떤 결과가 발생할 가능성이 높은지를 학습합니다. 경험이 축적되면서 자주 수행하는 행동은 더욱 정확하고 효율적이며 자동화되고, 지각은 작업과 관련된 정보에 점차 더 정교하게 조정됩니다.

감각운동 학습(Sensorimotor Learning)은 지각을 움직임의 결과와 직접 연결하기 때문에 특히 중요합니다. 에이전트는 객체가 어떻게 보이는지만 학습하는 것이 아니라 시각적 변화가 자기 움직임과 어떻게 연결되는지, 촉각 패턴이 접촉 조건과 어떻게 대응하는지, 운동 명령이 신체 구성을 어떻게 변화시키는지를 학습합니다. 이러한 학습된 규칙성은 보정(Calibration), 협응(Coordination), 예측, 적응을 지원합니다.

발달(Development)은 감각운동 상호작용의 중요성을 강하게 보여줍니다. 인간의 지각 능력과 운동 능력은 영아가 자신의 신체와 환경을 탐색하면서 함께 발달합니다. 손 뻗기, 바라보기, 기어가기, 객체 조작, 사회적 상호작용은 점차 정교한 내부 표현이 형성될 수 있는 구조화된 경험(Structured Experience)을 만들어냅니다. 따라서 인지는 수동적인 관찰만이 아니라 능동적인 참여(Active Engagement)를 통해 부분적으로 발달합니다.

체화 인지(Embodied Cognition)는 이러한 통찰을 확장하여 인지 과정이 신체의 물리적 특성과 환경과의 상호작용에 의존한다고 설명합니다. 신체 형상(Body Geometry), 센서 배치(Sensory Placement), 움직임 범위(Movement Range), 힘(Strength), 물리적 제약조건은 어떤 행동이 가능하고 어떤 정보를 획득할 수 있는지에 영향을 미칩니다. 따라서 지능은 지각과 행동이 발생하는 체화(Embodiment)의 특성에 의해 부분적으로 형성됩니다.

환경(Environment) 자체도 인지 처리(Cognitive Processing)의 일부가 될 수 있습니다. 인간은 모든 세부 정보를 내부적으로 표현하는 대신 외부 구조(External Structure)를 이용하여 인지 부하(Cognitive Load)를 줄이는 경우가 많습니다. 객체의 위치를 변경하거나, 메모를 작성하거나, 도구를 배열하거나, 정보를 다시 확인하거나, 공간적 배치를 기억과 추론에 활용합니다. 따라서 행동은 이후의 인지를 더 쉽게 만드는 방향으로 환경을 변경할 수 있습니다.

지각과 행동은 여러 시간 규모(Temporal Scales)에 걸쳐 작동합니다. 낮은 수준의 감각운동 보정은 1초보다 짧은 시간 안에 발생할 수 있는 반면, 내비게이션과 조작과 같은 활동은 수초 또는 수분에 걸쳐 진행됩니다. 상위 수준의 목표와 계획은 수시간 또는 그 이상 지속될 수 있습니다. 인지 시스템은 즉각적인 행동이 더 넓은 목표와 일치하도록 이러한 시간 규모를 조정해야 합니다.

계층적 구성(Hierarchical Organization)은 이러한 조정 문제를 해결하는 데 도움을 줍니다. 상위 수준의 인지는 목표와 추상적인 행동을 표현하고, 하위 수준은 세부적인 움직임과 감각 피드백을 관리합니다. 식사를 준비한다는 하나의 의도는 내비게이션, 객체 탐색(Object Search), 손 뻗기, 파지, 운반(Transport), 배치(Placement), 조작으로 분해될 수 있으며, 각각의 과정은 다시 세부적인 감각운동 제어 과정으로 구성됩니다.

행동 선택(Action Selection)은 불확실성(Uncertainty)과 위험(Risk)도 고려해야 합니다. 지각적 추정은 완벽하게 신뢰할 수 있는 경우가 드물며, 일부 행동은 되돌릴 수 없거나 위험한 결과를 가져올 수 있습니다. 따라서 인지 시스템은 잠재적인 이익을 불확실성, 노력(Effort), 물리적 한계, 안전(Safety)과 함께 고려합니다. 신뢰도가 충분하지 않으면 에이전트는 추가 정보를 탐색하거나, 보다 안전한 행동을 선택하거나, 결정을 지연할 수 있습니다.

실패(Failures)는 지각-행동 루프 안에서 중요한 정보를 제공합니다. 실패한 파지, 예상하지 못한 장애물, 잘못된 예측, 불안정한 움직임은 기존 표현이나 정책(Policies)이 불완전하다는 증거를 생성합니다. 적응형 인지(Adaptive Cognition)는 이러한 불일치를 이용하여 이후의 지각, 계획, 행동을 수정함으로써 오류를 단순한 부정적 결과가 아니라 학습의 기회로 전환합니다.

사회적 상호작용(Social Interaction)은 또 다른 형태의 지각-행동 결합을 형성합니다. 인간은 다른 사람의 표정, 몸짓, 언어, 시선(Gaze), 움직임을 지각하는 동시에 상대방의 다음 사회적 반응에 영향을 미치는 행동을 수행합니다. 따라서 의사소통은 본질적으로 상호작용적이며, 지각과 행동이 의도, 목표, 감정 상태, 공동 작업(Shared Tasks)에 대한 예측을 반복적으로 갱신합니다.

언어(Language)는 행동 제어(Action Control)에 직접 참여할 수도 있습니다. 언어적 지시(Verbal Instructions)는 목표를 설정하고, 행동을 제한하며, 객체를 설명하거나 행동 시퀀스를 지정할 수 있습니다. 음성 피드백(Spoken Feedback)은 진행 중인 행동을 수정할 수 있고, 내부적으로 표현된 언어는 계획과 자기조절(Self-Regulation)을 지원할 수 있습니다. 이를 통해 통합 인지(Integrated Cognition) 안에서 언어, 지각, 추론, 물리적 행동 사이의 연결이 형성됩니다.

인공지능(Artificial Intelligence)에서 지각-행동 관계는 자율 에이전트(Autonomous Agents)의 핵심적인 기반입니다. 정적 데이터(Static Data)만을 처리하는 AI 시스템은 자신의 입력에 영향을 주지 않으면서 인식이나 예측을 수행할 수 있지만, 체화된 에이전트(Embodied Agent)는 자신의 결정으로 실제 세계를 변화시킵니다. 각각의 행동은 새로운 관찰을 만들어내므로 미래의 입력 분포(Input Distribution)는 부분적으로 에이전트 자신의 이전 행동에 의존하게 됩니다.

이러한 폐루프 특성(Closed-Loop Property)은 공학적 문제를 크게 변화시킵니다. 지각 오류는 잘못된 행동으로 이어질 수 있고, 잘못된 행동은 시스템을 익숙하지 않은 상태로 이동시킬 수 있으며, 이러한 상태는 다시 추가적인 지각 오류를 발생시킬 수 있습니다. 따라서 강건한 자율 시스템(Robust Autonomous Systems)은 지속적인 상태 추정(State Estimation), 불확실성 관리(Uncertainty Management), 피드백, 복구 행동(Recovery Behavior), 지각-행동 루프가 불안정해지는 시점을 감지하는 메커니즘을 필요로 합니다.

로보틱스(Robotics)는 이러한 개념을 직접적으로 계산 시스템으로 구현합니다. 카메라(Camera), 라이다(LiDAR), 마이크(Microphones), 촉각 센서(Tactile Sensors), 힘 센서(Force Sensors), 엔코더(Encoders), 관성 측정 장치(IMUs) 등의 장치는 멀티모달 관찰(Multimodal Observations)을 제공합니다. 지각 알고리즘은 이러한 신호를 객체, 기하 구조(Geometry), 움직임, 위치 추정(Localization), 어포던스, 불확실성에 대한 표현으로 변환하며, 계획 및 제어 시스템은 이를 이용하여 물리적 행동을 선택하고 실행합니다.

현대 피지컬 AI(Physical AI)는 이러한 구성요소를 학습된 표현(Learned Representations) 및 파운데이션 모델(Foundation Models)과 점차 통합하고 있습니다. 지각 파운데이션 모델(Perception Foundation Models)은 의미론적·멀티모달 이해를 제공할 수 있으며, 행동 모델(Action Models) 또는 정책(Policies)은 문맥 표현(Contextual Representations)을 행동으로 변환할 수 있습니다. 기억, 추론, 계획, 월드 모델(World Models)은 이러한 계층을 연결하여 기존의 반응형 제어(Reactive Control)보다 긴 시간 범위에서 시스템이 동작하도록 지원할 수 있습니다.

월드 모델(World Models)은 에이전트가 서로 다른 후보 행동(Candidate Actions)에 따라 환경이 어떻게 변화할 수 있는지를 예측할 수 있게 한다는 점에서 특히 중요합니다. 시스템은 현재 관찰만을 기반으로 행동을 선택하는 대신 가능한 미래 상태를 생성하거나 추정하고, 예측된 결과를 비교한 후 자신의 목표를 가장 잘 지원하는 행동을 선택할 수 있습니다. 이는 인지과학에서 계획과 관련하여 설명되는 내부 시뮬레이션(Internal Simulation)의 역할과 유사합니다.

그러나 지능형 지각-행동 시스템(Intelligent Perception--Action Systems)은 추상적 추론(Abstract Reasoning)과 물리적 실행 가능성(Physical Feasibility) 사이의 연결을 유지해야 합니다. 상위 수준 모델이 의미론적으로 타당한 행동을 제안하더라도 기하학적 조건(Geometry), 힘의 한계(Force Limits), 충돌 위험(Collision Risk), 타이밍, 하드웨어 제약조건 때문에 실제 실행이 불가능할 수 있습니다. 따라서 효과적인 체화 인지는 추상적 지식과 현실에 기반한 감각운동 정보(Grounded Sensorimotor Information) 사이의 지속적인 상호작용을 필요로 합니다.

이러한 그라운딩 문제(Grounding Problem)는 인지과학과 AI 모두에서 핵심적인 과제 가운데 하나입니다. 기호(Symbols)와 언어는 궁극적으로 환경에 존재하는 객체, 속성, 관계, 행동, 결과와 연결되어야 합니다. 지각은 실제 세계에서 내부 표현으로 이어지는 연결을 제공하며, 행동은 내부 목표와 의사결정에서 다시 실제 세계로 이어지는 상호보완적인 경로를 제공합니다.

따라서 지각-행동 사이클(Perception--Action Cycle)은 적응 지능(Adaptive Intelligence)을 구성하는 근본적인 계산 구조(Computational Structure)로 이해할 수 있습니다. 관찰은 내부 상태(Internal State)를 갱신하고, 내부 상태는 예측과 의사결정을 지원하며, 의사결정은 행동을 생성하고, 행동은 환경과 에이전트 자체를 변화시키며, 그 결과 생성되는 감각적 증거가 다시 새로운 사이클을 시작합니다. 반복적인 상호작용을 통해 더욱 유용한 표현과 정책이 형성되면서 학습은 이러한 모든 단계를 변화시킵니다.

인지과학(Cognitive Science)의 관점에서 이러한 폐루프(Closed Loop)는 행동, 목표, 기억, 예측, 체화(Embodiment)를 고려하지 않고서는 지각을 완전히 이해할 수 없는 이유를 설명합니다. AI 관점에서는 더욱 발전된 자율 시스템이 지각, 추론, 제어를 서로 분리된 모듈(Isolated Modules)로만 취급해서는 안 된다는 점을 시사합니다. 전체 루프를 통해 정보가 얼마나 정확하고 효율적으로 순환하는지가 시스템의 성능을 결정합니다.

궁극적으로 지능적 행동(Intelligent Behavior)은 감지하는 것과 행동하는 것 사이의 조정된 상호작용에서 발생합니다. 지각은 현재 세계에 대해 행동 가능한 해석(Actionable Interpretation)을 제공하고, 행동은 예측을 검증하고, 목표를 달성하며, 새로운 증거를 만들어냅니다. 이들의 지속적인 결합은 적응(Adaptation), 탐색(Exploration), 학습, 계획, 목적 지향적 상호작용(Purposeful Interaction)을 가능하게 하며, 지각-행동 루프를 인지과학(Cognitive Science), 로보틱스(Robotics), 체화 AI(Embodied AI), 일반 지능 시스템(General Intelligent Systems)을 연결하는 핵심 메커니즘으로 만듭니다.

##  

## 01.02 Attention and Awareness [w/Code]

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

Attention is the cognitive process that selects and prioritizes information for deeper processing when sensory input, memory, and possible actions exceed available resources. At any moment, the environment contains far more information than a person can analyze equally. Attention therefore determines which signals, objects, thoughts, memories, or goals receive processing priority and which remain in the background.

Awareness refers to the information, experiences, or mental states that become available to a person in a form that can influence deliberate judgment, report, reflection, or flexible behavior. Attention and awareness are closely related, but they are not identical. Some information can influence behavior without entering explicit awareness, while some consciously experienced information may receive only weak or temporary attentional priority.

The distinction between attention and awareness is important because cognitive processing occurs at several levels. Sensory systems continuously process large amounts of information without requiring conscious access to every detail. Attention can amplify selected signals and increase their probability of entering awareness, but selection itself can occur before a person consciously recognizes what has been selected.

Selective attention allows the cognitive system to focus on relevant information while reducing interference from competing stimuli. A driver may concentrate on pedestrians and traffic signals while ignoring advertisements, building details, and background conversations. The ignored information still reaches sensory systems, but it receives less processing because current goals establish which information is behaviorally important.

Attention can be directed toward locations, objects, features, sensory modalities, memories, or internal thoughts. Spatial attention prioritizes particular regions of space, object-based attention selects specific entities, and feature-based attention emphasizes properties such as color, motion, orientation, or sound frequency. Cognitive attention can also be directed internally toward memories, plans, imagined events, or reasoning processes.

Bottom-up attention is driven primarily by the characteristics of incoming stimuli. Sudden motion, an unexpected sound, a flashing light, or a novel event can automatically capture processing resources even when it is unrelated to the current task. Such mechanisms are useful because potentially important changes in the environment sometimes require immediate processing before deliberate reasoning can occur.

Top-down attention is guided by goals, expectations, knowledge, and current task requirements. A person looking for a red vehicle will preferentially process visual information matching the expected characteristics of the target. Top-down control therefore shapes perception according to what the cognitive system is trying to achieve rather than relying only on the physical salience of incoming signals.

Effective cognition requires continuous interaction between bottom-up and top-down attention. A system that follows only internal goals could fail to notice unexpected dangers, while a system driven entirely by salient stimuli would be constantly distracted. Intelligent attention therefore balances goal-directed stability with sensitivity to novel or important environmental events.

Sustained attention describes the ability to maintain processing resources on a task over an extended period. Monitoring a display, driving for a long distance, reading technical material, or supervising an automated system requires sustained attention. Performance can gradually decline when tasks are repetitive or cognitively demanding, illustrating that attentional control is constrained by fatigue, motivation, workload, and time.

Divided attention becomes necessary when multiple tasks or information sources must be handled simultaneously. Humans can sometimes distribute resources among concurrent activities, but performance typically deteriorates when tasks compete for similar cognitive mechanisms. Apparent multitasking often consists of rapid switching between tasks rather than truly parallel processing of several complex activities.

Task switching introduces additional cognitive costs. When attention moves from one goal to another, the cognitive system must reconfigure priorities, retrieve different rules, activate relevant representations, and suppress the previous task set. Frequent switching can therefore reduce efficiency and increase errors even when each individual task is relatively simple.

Attention is strongly connected with working memory. Information receiving attentional priority is more likely to be maintained in a temporarily accessible form, while working memory contents can guide attention toward relevant information in the environment. These two mechanisms form a recurrent relationship in which attention determines what enters active processing and working memory helps determine what should be selected next.

Long-term memory also shapes attention through experience. Familiar patterns can be recognized rapidly because previous learning establishes expectations about what matters and where relevant information is likely to appear. Expertise often changes attentional behavior, allowing experienced individuals to notice meaningful structures that novices overlook even when both receive the same sensory information.

Attention can therefore be viewed as a resource-allocation mechanism operating across cognition. It influences perception, memory encoding, retrieval, reasoning, language processing, decision making, and motor preparation. Rather than functioning as an isolated module, attention continuously regulates which representations receive computational resources and which cognitive operations dominate at a particular moment.

The concept of limited attentional capacity explains many characteristic human errors. When processing demand becomes too high, relevant information can be missed even when it is physically visible. Inattentional blindness demonstrates that people may fail to notice an unexpected object when attention is strongly engaged elsewhere, showing that visual availability does not guarantee cognitive awareness.

Change blindness provides another example of attentional limitation. Significant modifications to a scene may go unnoticed when they occur during interruptions, eye movements, or other visual disturbances. These findings suggest that people do not maintain a complete, continuously detailed representation of the visual environment but instead construct task-relevant representations according to attentional demands.

The attentional blink reveals limitations in processing events that occur rapidly over time. When two meaningful targets appear within a short temporal interval, detecting the first can temporarily reduce the probability of consciously identifying the second. This phenomenon suggests that some stages of attentional processing and conscious access have limited temporal capacity.

Awareness adds another level to these questions because not all processed information becomes consciously accessible. Visual masking, subliminal presentation, priming, and other experimental paradigms demonstrate that stimuli can sometimes influence decisions or responses even when participants cannot explicitly report seeing them. Cognitive processing therefore extends beyond the boundaries of conscious experience.

Conscious awareness nevertheless provides important functional advantages. Information that becomes consciously available can often be integrated more flexibly with memory, goals, reasoning, language, and action planning. Awareness can support deliberate comparison among alternatives, explicit error detection, communication of internal states, and adaptation to situations that cannot be handled through familiar automatic responses.

Automatic processing contrasts with controlled processing in this respect. Well-practiced activities can often be performed with little conscious attention because repeated experience has created efficient routines. Reading common words, walking in familiar environments, or executing practiced motor actions may require less deliberate control than unfamiliar tasks requiring active monitoring and flexible reasoning.

Automaticity improves efficiency but can also create errors when environmental conditions change. A familiar response may continue even when it is no longer appropriate. Controlled attention allows the cognitive system to interrupt habitual behavior, reconsider assumptions, and apply a different strategy. Flexible intelligence therefore requires both efficient automatic processes and mechanisms capable of overriding them when necessary.

Awareness is also closely related to confidence and metacognition. A person may not only perceive or remember information but also estimate how reliable that representation is. Such judgments help determine whether additional evidence should be gathered, whether a decision should be delayed, or whether external assistance is required. Awareness can therefore include information about the quality of one\'s own cognitive states.

Several theories attempt to explain how selected information becomes consciously accessible. Global workspace approaches propose that many specialized processes operate partly independently, while selected information can become globally available to multiple cognitive systems. Once information enters this shared workspace, it can influence memory, reasoning, planning, language, and action in a coordinated manner.

According to this perspective, consciousness does not require every internal computation to become globally available. Most perceptual, motor, and memory operations can remain local and specialized. Global access is particularly useful when information must coordinate several systems, resolve conflict, support novel behavior, or remain available for explicit reasoning and communication.

Other approaches emphasize recurrent processing between higher and lower levels of perceptual systems. Initial feedforward processing may rapidly extract information from sensory input, while recurrent interactions refine interpretations through context and feedback. Some theories associate such recurrent integration with perceptual awareness, although the precise relationship between neural processing and subjective experience remains scientifically debated.

Predictive processing offers another useful perspective on attention and awareness. Cognitive systems continuously generate expectations about incoming information and compare those expectations with observed signals. Attention can influence which prediction errors receive greater weight, allowing unexpected or task-relevant discrepancies to update internal models more strongly than signals considered unreliable or irrelevant.

From this viewpoint, attention is not simply a spotlight directed toward an external object. It also regulates the precision assigned to competing sources of information. A highly reliable sensory signal may receive increased weight, while uncertain or noisy evidence receives less. Such mechanisms connect attention with Bayesian inference, uncertainty estimation, and adaptive information integration.

Emotion and motivation strongly influence attentional allocation. Threatening, rewarding, socially relevant, or personally significant stimuli can receive priority even when they are unrelated to an explicit task. This interaction demonstrates that attention reflects not only sensory characteristics and cognitive goals but also estimates of biological, emotional, or motivational importance.

Attention is also linked with action preparation. Objects relevant to an intended action often receive enhanced processing, and planning a movement can change which spatial regions or object features become important. A robot or human preparing to grasp an object, for example, requires information about position, orientation, shape, and affordance rather than equal analysis of every visible property.

This connection supports the idea that attention participates directly in the perception-action loop. Current goals guide attention, attention shapes perception, perception updates internal state, and selected information supports action planning. Actions then change both the environment and the available sensory input, requiring attention to be continuously redistributed as the task evolves.

Social attention introduces additional complexity. Humans are highly sensitive to faces, gaze direction, gestures, speech, emotional expressions, and the actions of other people. Following another person\'s gaze can redirect attention toward relevant objects, while joint attention allows multiple individuals to focus on the same entity and establish a shared reference for communication and collaboration.

Joint attention plays an important role in language learning, teaching, cooperation, and social understanding. Recognizing what another person is attending to provides evidence about goals and intentions. For intelligent AI systems interacting with people, corresponding mechanisms could help determine which object a user refers to, what event requires immediate response, or when human intervention should receive priority.

Attention has become an important concept in artificial intelligence, although computational attention mechanisms should not be assumed to reproduce human attention directly. In neural networks, attention commonly refers to mechanisms that assign different weights to representations, allowing a model to emphasize information judged relevant to the current computation.

Transformer architectures provide a prominent example through self-attention. Each token representation can evaluate relationships with other tokens and construct a new representation weighted by those relationships. This mechanism allows models to capture long-range dependencies and dynamically determine which parts of an input are most relevant, but it remains a mathematical operation rather than a complete model of biological attention.

Cross-attention extends the same principle across different information sources. A language representation may attend to visual features, a robot instruction may attend to detected objects, or a planning representation may attend to relevant memory. Such mechanisms are especially important in multimodal AI because they provide a flexible method for relating information across language, vision, audio, action, and other modalities.

AI attention can also operate through explicit computational selection. An autonomous system may allocate high-resolution perception to a particular region, activate expensive models only when uncertainty increases, or process selected sensors at higher frequency. Attention then becomes an architectural mechanism for managing limited compute, energy, bandwidth, latency, and memory resources.

This resource-management perspective is particularly relevant for edge AI and robotics. A physical robot cannot always run every model at maximum resolution and frequency simultaneously. It may need to prioritize obstacle detection during navigation, manipulation features during grasping, human monitoring during collaboration, or localization signals when position uncertainty increases.

Active perception further links attention with information gathering. An intelligent agent can move a camera, reposition its body, select another sensor, change viewpoint, or approach an uncertain object to obtain better evidence. Attention can therefore determine not only which existing information should be processed but also which future observations should be deliberately acquired.

For AI agents using external tools, attention can be interpreted more broadly as deciding which information source should receive computational focus. An agent may choose whether to inspect a document, retrieve a memory, query a database, call a perception model, perform a calculation, or request human input. This extends attentional control from internal representation weighting to system-level resource orchestration.

Memory systems create another challenge because modern AI agents may have access to enormous quantities of stored information. Efficient cognition requires selecting a small subset that is relevant to the current situation. Retrieval mechanisms, relevance scoring, context management, and working-memory selection can therefore be understood as computational analogues of attentional prioritization.

Awareness is more difficult to translate into AI terminology. Current AI systems can maintain internal representations, report confidence, monitor some of their outputs, and expose selected state information, but these capabilities should not automatically be equated with human conscious experience. Functional monitoring and self-report can be studied computationally without assuming subjective awareness.

A useful engineering interpretation is operational awareness. An autonomous system may maintain explicit representations of its current task, environment, uncertainty, resource state, failures, safety constraints, and interactions with humans. Making this information globally available across planning, control, memory, and communication modules can improve coordinated behavior without making claims about machine consciousness.

Situation awareness provides a practical example. A robot operating around people should maintain an integrated representation of nearby objects, human positions, motion, task status, hazards, available actions, and expected future events. Attention determines which parts of this representation require immediate processing, while system-level awareness supports coordinated decisions across multiple functional components.

Self-awareness can similarly be interpreted carefully in engineering systems as access to representations of one\'s own state. An AI agent may monitor battery level, computational load, sensor health, localization confidence, task progress, model uncertainty, or available capabilities. Such self-monitoring supports more reliable decisions because the agent can modify behavior when its own operating conditions deteriorate.

Attention is therefore closely related to safety. A system that focuses excessively on task completion while neglecting unexpected hazards can behave dangerously. Safety-critical architectures may require protected attentional priorities in which collision risk, human proximity, system faults, or emergency signals can interrupt lower-priority activities regardless of the agent\'s current goal.

Human-AI interaction also requires managing human attention. Interfaces that generate excessive alerts can produce alarm fatigue, causing important information to be ignored. Conversely, an AI system that fails to communicate critical uncertainty may leave a human operator unaware of developing risk. Effective systems must therefore consider both machine attention and the limited attentional capacity of human collaborators.

Adaptive interfaces can support this goal by presenting information according to urgency, context, workload, and user state. Routine information may remain in the background while anomalies are emphasized. However, excessive automation of attentional control can also hide important context, so interface design must balance filtering with transparency and preserve opportunities for human oversight.

Attention and awareness are particularly important for long-horizon autonomous agents. As tasks extend over minutes, hours, or days, the agent must maintain persistent goals while responding appropriately to interruptions and changing circumstances. It must know which information remains relevant, which subtask is currently active, what changed while attention was elsewhere, and when priorities should be reorganized.

Hierarchical attention can help manage such complexity. High-level processes may allocate resources among goals or tasks, intermediate processes select objects or information sources, and low-level mechanisms prioritize features or sensory signals. Hierarchical organization allows an intelligent system to combine long-term goal stability with rapid local responses to unexpected events.

Learning can improve attention by discovering which signals are useful for predicting outcomes. Repeated experience teaches an agent where relevant information tends to occur, which cues indicate danger, and which observations reduce uncertainty. Attention consequently becomes increasingly specialized as the system learns relationships among context, goals, observations, actions, and outcomes.

Poorly learned attention can create systematic failure. If a model repeatedly relies on superficial correlations, it may focus on irrelevant features while ignoring causal information. In robotics, attending to visual appearance without considering geometry could produce unsafe actions. In language systems, emphasizing misleading contextual patterns can result in confident but incorrect reasoning.

Evaluating attention therefore requires more than visualizing attention weights. A model may assign high computational weight to a representation without that representation being causally responsible for the final output. Reliable evaluation should test how behavior changes when information is removed, altered, delayed, or made uncertain, revealing whether the system actually depends on the features it appears to prioritize.

The relationship between attention and awareness ultimately illustrates a broader principle of cognitive science: intelligent systems must selectively organize information rather than process everything equally. Selection provides efficiency, while broader availability allows selected information to coordinate perception, memory, reasoning, planning, and action. Together these mechanisms help transform limited resources into flexible behavior.

For future AI and embodied intelligence, the important lesson is not simply to imitate human attention but to design systems capable of adaptive prioritization. Such systems should allocate computation according to goals, uncertainty, novelty, risk, expected information value, and environmental change while preserving mechanisms that allow critical information to override normal processing.

Attention provides focus, while awareness provides broader access to information needed for coordinated cognition. Their interaction enables an intelligent system to concentrate resources without losing the capacity to reconsider priorities, detect unexpected events, integrate information across functional modules, and adapt behavior. These capabilities form an essential bridge between human cognition, cognitive architectures, autonomous agents, and more general forms of artificial intelligence.

주의(Attention)는 감각 입력(Sensory Input), 기억(Memory), 가능한 행동(Possible Actions)이 이용 가능한 자원을 초과할 때 더 깊은 처리를 위해 정보를 선택하고 우선순위를 부여하는 인지 과정(Cognitive Process)입니다. 어느 순간이든 환경에는 사람이 동일한 수준으로 분석할 수 있는 양보다 훨씬 많은 정보가 존재합니다. 따라서 주의는 어떤 신호, 객체, 생각, 기억 또는 목표가 처리 우선순위를 받고 어떤 것이 배경에 남을지를 결정합니다.

자각(Awareness)은 의도적인 판단(Deliberate Judgment), 보고(Report), 성찰(Reflection), 유연한 행동(Flexible Behavior)에 영향을 줄 수 있는 형태로 사람에게 접근 가능해지는 정보, 경험 또는 정신 상태(Mental States)를 의미합니다. 주의와 자각은 밀접하게 관련되어 있지만 동일하지는 않습니다. 일부 정보는 명시적인 자각 없이 행동에 영향을 줄 수 있으며, 의식적으로 경험되는 일부 정보는 약하거나 일시적인 주의 우선순위만 받을 수도 있습니다.

주의와 자각의 구분이 중요한 이유는 인지 처리(Cognitive Processing)가 여러 수준에서 발생하기 때문입니다. 감각 시스템(Sensory Systems)은 모든 세부 정보에 대한 의식적 접근(Conscious Access)을 요구하지 않으면서도 지속적으로 많은 양의 정보를 처리합니다. 주의는 선택된 신호를 증폭하고 그것이 자각에 진입할 가능성을 높일 수 있지만, 선택 자체는 사람이 무엇이 선택되었는지를 의식적으로 인식하기 전에 발생할 수 있습니다.

선택적 주의(Selective Attention)는 인지 시스템이 관련 정보에 집중하면서 경쟁하는 자극(Competing Stimuli)의 간섭을 감소시킬 수 있도록 합니다. 운전자는 광고, 건물의 세부사항, 배경 대화를 무시하면서 보행자와 교통 신호에 집중할 수 있습니다. 무시된 정보도 감각 시스템에는 도달하지만 현재의 목표가 어떤 정보가 행동적으로 중요한지를 결정하기 때문에 더 적은 처리를 받습니다.

주의는 위치(Locations), 객체(Objects), 특징(Features), 감각 양식(Sensory Modalities), 기억 또는 내부 생각(Internal Thoughts)을 향할 수 있습니다. 공간적 주의(Spatial Attention)는 특정 공간 영역에 우선순위를 부여하고, 객체 기반 주의(Object-Based Attention)는 특정 개체를 선택하며, 특징 기반 주의(Feature-Based Attention)는 색상, 움직임, 방향 또는 소리 주파수와 같은 속성을 강조합니다. 인지적 주의(Cognitive Attention)는 기억, 계획, 상상된 사건 또는 추론 과정과 같은 내부 정보에도 향할 수 있습니다.

상향식 주의(Bottom-Up Attention)는 주로 입력되는 자극의 특성에 의해 유도됩니다. 갑작스러운 움직임, 예상하지 못한 소리, 깜박이는 빛 또는 새로운 사건은 현재 작업과 관련이 없더라도 자동으로 처리 자원을 확보할 수 있습니다. 이러한 메커니즘은 환경에서 잠재적으로 중요한 변화가 의도적인 추론이 이루어지기 전에 즉각적으로 처리되어야 하는 경우가 있기 때문에 유용합니다.

하향식 주의(Top-Down Attention)는 목표(Goals), 기대(Expectations), 지식(Knowledge), 현재 작업 요구사항(Current Task Requirements)에 의해 유도됩니다. 빨간색 차량을 찾고 있는 사람은 예상되는 목표의 특성과 일치하는 시각 정보를 우선적으로 처리합니다. 따라서 하향식 제어(Top-Down Control)는 입력 신호의 물리적 현저성(Physical Salience)에만 의존하는 대신 인지 시스템이 달성하려는 목표에 따라 지각을 형성합니다.

효과적인 인지(Effective Cognition)를 위해서는 상향식 주의와 하향식 주의 사이의 지속적인 상호작용이 필요합니다. 내부 목표만을 따르는 시스템은 예상하지 못한 위험을 발견하지 못할 수 있으며, 현저한 자극만을 따라가는 시스템은 지속적으로 주의가 분산될 수 있습니다. 따라서 지능적 주의(Intelligent Attention)는 목표 지향적 안정성(Goal-Directed Stability)과 새롭거나 중요한 환경 사건에 대한 민감성 사이에서 균형을 유지합니다.

지속적 주의(Sustained Attention)는 장시간에 걸쳐 하나의 작업에 처리 자원을 유지하는 능력을 의미합니다. 디스플레이 감시, 장거리 운전, 기술 자료 읽기 또는 자동화 시스템 감독에는 지속적 주의가 필요합니다. 작업이 반복적이거나 인지적으로 많은 부담을 요구하면 성능이 점차 저하될 수 있으며, 이는 주의 제어(Attentional Control)가 피로(Fatigue), 동기(Motivation), 작업 부하(Workload), 시간의 제약을 받는다는 것을 보여줍니다.

분할 주의(Divided Attention)는 여러 작업이나 정보원을 동시에 처리해야 할 때 필요합니다. 인간은 때때로 동시에 수행되는 활동들 사이에 자원을 분배할 수 있지만, 작업들이 유사한 인지 메커니즘을 두고 경쟁하면 일반적으로 성능이 저하됩니다. 겉으로 보이는 멀티태스킹(Multitasking)은 여러 복잡한 활동을 실제로 병렬 처리하는 것이 아니라 작업 사이를 빠르게 전환하는 과정인 경우가 많습니다.

작업 전환(Task Switching)은 추가적인 인지 비용(Cognitive Costs)을 발생시킵니다. 주의가 하나의 목표에서 다른 목표로 이동할 때 인지 시스템은 우선순위를 다시 구성하고, 다른 규칙을 검색하며, 관련 표현을 활성화하고, 이전 작업 집합(Task Set)을 억제해야 합니다. 따라서 각각의 개별 작업이 비교적 단순하더라도 빈번한 전환은 효율성을 감소시키고 오류를 증가시킬 수 있습니다.

주의(Attention)는 작업 기억(Working Memory)과 강하게 연결되어 있습니다. 주의 우선순위를 받은 정보는 일시적으로 접근 가능한 형태로 유지될 가능성이 높으며, 작업 기억의 내용은 환경에서 관련 정보로 주의를 유도할 수 있습니다. 이 두 메커니즘은 주의가 활성 처리(Active Processing)에 무엇이 들어갈지를 결정하고 작업 기억이 다음에 무엇을 선택해야 할지를 결정하는 데 도움을 주는 반복적 관계(Recurrent Relationship)를 형성합니다.

장기 기억(Long-Term Memory) 역시 경험을 통해 주의를 형성합니다. 이전 학습이 무엇이 중요하고 관련 정보가 어디에 나타날 가능성이 높은지에 대한 기대를 형성하기 때문에 익숙한 패턴은 빠르게 인식될 수 있습니다. 전문성(Expertise)은 주의 행동을 변화시키는 경우가 많으며, 동일한 감각 정보를 받더라도 숙련자는 초보자가 놓치는 의미 있는 구조를 발견할 수 있습니다.

따라서 주의는 인지 전반에서 작동하는 자원 할당 메커니즘(Resource-Allocation Mechanism)으로 볼 수 있습니다. 주의는 지각(Perception), 기억 부호화(Memory Encoding), 검색(Retrieval), 추론(Reasoning), 언어 처리(Language Processing), 의사결정(Decision Making), 운동 준비(Motor Preparation)에 영향을 미칩니다. 독립적인 모듈로 작동하기보다 어떤 표현이 계산 자원을 받을지와 특정 순간에 어떤 인지 연산이 지배적일지를 지속적으로 조절합니다.

제한된 주의 용량(Limited Attentional Capacity)의 개념은 인간에게 나타나는 여러 특징적인 오류를 설명합니다. 처리 요구량이 지나치게 높아지면 관련 정보가 물리적으로 눈에 보이더라도 놓칠 수 있습니다. 부주의 맹시(Inattentional Blindness)는 주의가 다른 곳에 강하게 집중될 때 예상하지 못한 객체를 발견하지 못할 수 있음을 보여주며, 시각적으로 이용 가능하다는 사실이 인지적 자각을 보장하지 않는다는 것을 보여줍니다.

변화 맹시(Change Blindness)는 주의 제한의 또 다른 사례를 제공합니다. 장면(Scene)의 상당한 변화도 중단, 안구 운동(Eye Movements) 또는 기타 시각적 방해가 발생하는 동안에는 인식되지 않을 수 있습니다. 이러한 연구 결과는 인간이 시각 환경에 대한 완전하고 지속적으로 상세한 표현을 유지하는 것이 아니라 주의 요구에 따라 작업 관련 표현(Task-Relevant Representations)을 구성한다는 것을 시사합니다.

주의 깜박임(Attentional Blink)은 시간적으로 빠르게 발생하는 사건을 처리하는 능력의 한계를 보여줍니다. 두 개의 의미 있는 목표 자극이 짧은 시간 간격으로 나타날 때 첫 번째 목표를 탐지하면 두 번째 목표를 의식적으로 식별할 가능성이 일시적으로 감소할 수 있습니다. 이러한 현상은 주의 처리와 의식적 접근의 일부 단계가 제한된 시간적 처리 용량(Temporal Capacity)을 가진다는 것을 시사합니다.

모든 처리된 정보가 의식적으로 접근 가능한 상태가 되는 것은 아니기 때문에 자각(Awareness)은 이러한 문제에 또 다른 수준을 추가합니다. 시각적 마스킹(Visual Masking), 잠재의식적 제시(Subliminal Presentation), 점화(Priming) 등의 실험 패러다임은 참가자가 자극을 보았다고 명시적으로 보고할 수 없는 경우에도 그 자극이 의사결정이나 반응에 영향을 미칠 수 있음을 보여줍니다. 따라서 인지 처리는 의식적 경험(Conscious Experience)의 경계를 넘어 발생합니다.

그럼에도 불구하고 의식적 자각(Conscious Awareness)은 중요한 기능적 이점을 제공합니다. 의식적으로 접근 가능한 정보는 기억, 목표, 추론, 언어, 행동 계획(Action Planning)과 더욱 유연하게 통합될 수 있습니다. 자각은 대안들 사이의 의도적인 비교, 명시적 오류 탐지(Explicit Error Detection), 내부 상태의 의사소통, 익숙한 자동 반응으로 처리할 수 없는 상황에 대한 적응을 지원할 수 있습니다.

자동 처리(Automatic Processing)는 이러한 측면에서 통제 처리(Controlled Processing)와 대비됩니다. 반복적인 경험을 통해 효율적인 루틴(Routines)이 형성되면 충분히 숙련된 활동은 의식적 주의를 거의 사용하지 않고도 수행될 수 있습니다. 익숙한 단어를 읽거나, 익숙한 환경을 걷거나, 숙련된 운동 행동을 실행하는 것은 적극적인 감시와 유연한 추론을 요구하는 익숙하지 않은 작업보다 의도적인 제어를 적게 필요로 할 수 있습니다.

자동성(Automaticity)은 효율성을 높이지만 환경 조건이 변화하면 오류를 발생시킬 수도 있습니다. 익숙한 반응이 더 이상 적절하지 않은 상황에서도 계속될 수 있기 때문입니다. 통제된 주의(Controlled Attention)는 인지 시스템이 습관적 행동을 중단하고, 기존 가정을 재검토하며, 다른 전략을 적용할 수 있도록 합니다. 따라서 유연한 지능(Flexible Intelligence)은 효율적인 자동 과정과 필요할 때 이를 무시하거나 대체할 수 있는 메커니즘을 모두 필요로 합니다.

자각은 신뢰도(Confidence)와 메타인지(Metacognition)와도 밀접하게 관련됩니다. 사람은 정보를 지각하거나 기억하는 것뿐 아니라 해당 표현이 얼마나 신뢰할 수 있는지를 추정할 수 있습니다. 이러한 판단은 추가 증거를 수집해야 하는지, 의사결정을 지연해야 하는지, 외부 지원(External Assistance)이 필요한지를 결정하는 데 도움을 줍니다. 따라서 자각에는 자신의 인지 상태 품질에 대한 정보도 포함될 수 있습니다.

여러 이론은 선택된 정보가 어떻게 의식적으로 접근 가능한 상태가 되는지를 설명하려고 합니다. 전역 작업공간 접근법(Global Workspace Approaches)은 많은 전문화된 과정이 부분적으로 독립적으로 작동하지만 선택된 정보는 여러 인지 시스템에서 전역적으로 이용 가능해질 수 있다고 제안합니다. 정보가 이러한 공유 작업공간(Shared Workspace)에 진입하면 기억, 추론, 계획, 언어, 행동에 조정된 방식으로 영향을 줄 수 있습니다.

이러한 관점에 따르면 의식(Consciousness)을 위해 모든 내부 계산이 전역적으로 이용 가능해질 필요는 없습니다. 대부분의 지각, 운동, 기억 연산은 국소적이고 전문화된 상태로 유지될 수 있습니다. 전역적 접근(Global Access)은 정보가 여러 시스템을 조정하고, 충돌을 해결하며, 새로운 행동을 지원하거나, 명시적 추론과 의사소통을 위해 유지되어야 할 때 특히 유용합니다.

다른 접근법은 지각 시스템의 상위 수준과 하위 수준 사이에서 이루어지는 반복 처리(Recurrent Processing)를 강조합니다. 초기 피드포워드 처리(Feedforward Processing)는 감각 입력에서 정보를 빠르게 추출할 수 있으며, 이후 반복적 상호작용은 문맥과 피드백을 이용하여 해석을 정교화합니다. 일부 이론은 이러한 반복적 통합을 지각적 자각(Perceptual Awareness)과 연관시키지만, 신경 처리와 주관적 경험(Subjective Experience) 사이의 정확한 관계는 여전히 과학적으로 논쟁 중입니다.

예측 처리(Predictive Processing)는 주의와 자각을 이해하는 또 다른 유용한 관점을 제공합니다. 인지 시스템은 입력될 정보에 대한 기대를 지속적으로 생성하고 이러한 기대를 관찰된 신호와 비교합니다. 주의는 어떤 예측 오류(Prediction Errors)에 더 높은 가중치를 부여할지를 결정할 수 있으며, 이를 통해 예상하지 못했거나 작업과 관련된 불일치가 신뢰할 수 없거나 관련성이 낮은 신호보다 내부 모델(Internal Models)을 더 강하게 갱신하도록 할 수 있습니다.

이러한 관점에서 주의는 단순히 외부 객체를 향하는 스포트라이트(Spotlight)가 아닙니다. 주의는 경쟁하는 정보원에 부여되는 정밀도(Precision)를 조절하기도 합니다. 신뢰도가 높은 감각 신호에는 더 큰 가중치가 부여될 수 있고, 불확실하거나 잡음이 많은 증거에는 더 낮은 가중치가 부여될 수 있습니다. 이러한 메커니즘은 주의를 베이지안 추론(Bayesian Inference), 불확실성 추정(Uncertainty Estimation), 적응형 정보 통합(Adaptive Information Integration)과 연결합니다.

감정(Emotion)과 동기(Motivation)는 주의 자원 할당에 강하게 영향을 미칩니다. 위협적이거나 보상과 관련되거나 사회적으로 중요하거나 개인적으로 의미 있는 자극은 명시적인 작업과 관련이 없더라도 우선순위를 받을 수 있습니다. 이러한 상호작용은 주의가 감각적 특성과 인지적 목표뿐 아니라 생물학적, 감정적 또는 동기적 중요성에 대한 평가도 반영한다는 것을 보여줍니다.

주의는 행동 준비(Action Preparation)와도 연결되어 있습니다. 의도된 행동과 관련된 객체는 강화된 처리를 받는 경우가 많으며, 움직임을 계획하는 것은 어떤 공간 영역이나 객체 특징이 중요해지는지를 변화시킬 수 있습니다. 예를 들어 객체를 잡으려고 준비하는 로봇이나 인간에게는 모든 시각적 속성을 동일하게 분석하는 것보다 위치, 방향(Orientation), 형상(Shape), 어포던스(Affordance)에 관한 정보가 중요합니다.

이러한 연결은 주의가 지각-행동 루프(Perception-Action Loop)에 직접 참여한다는 개념을 뒷받침합니다. 현재 목표가 주의를 유도하고, 주의는 지각을 형성하며, 지각은 내부 상태(Internal State)를 갱신하고, 선택된 정보는 행동 계획을 지원합니다. 이후 행동은 환경과 이용 가능한 감각 입력을 변화시키므로 작업이 진행됨에 따라 주의 역시 지속적으로 재분배되어야 합니다.

사회적 주의(Social Attention)는 추가적인 복잡성을 만들어냅니다. 인간은 얼굴, 시선 방향(Gaze Direction), 몸짓(Gestures), 음성, 감정 표현(Emotional Expressions), 다른 사람의 행동에 매우 민감합니다. 다른 사람의 시선을 따라가는 것은 관련 객체로 주의를 이동시킬 수 있으며, 공동 주의(Joint Attention)는 여러 사람이 동일한 개체에 집중하고 의사소통과 협력을 위한 공유 참조(Shared Reference)를 형성하도록 합니다.

공동 주의(Joint Attention)는 언어 학습(Language Learning), 교육(Teaching), 협력(Cooperation), 사회적 이해(Social Understanding)에서 중요한 역할을 합니다. 다른 사람이 무엇에 주의를 기울이고 있는지를 인식하는 것은 그 사람의 목표와 의도에 대한 증거를 제공합니다. 인간과 상호작용하는 지능형 AI 시스템에서는 이러한 메커니즘이 사용자가 어떤 객체를 지칭하는지, 어떤 사건에 즉시 대응해야 하는지, 언제 인간의 개입에 우선순위를 부여해야 하는지를 판단하는 데 도움을 줄 수 있습니다.

주의는 인공지능(Artificial Intelligence)에서도 중요한 개념이 되었지만, 계산적 주의 메커니즘(Computational Attention Mechanisms)이 인간의 주의를 직접적으로 재현한다고 가정해서는 안 됩니다. 신경망(Neural Networks)에서 주의는 일반적으로 표현에 서로 다른 가중치를 부여하여 모델이 현재 계산과 관련성이 높은 것으로 판단되는 정보를 강조할 수 있도록 하는 메커니즘을 의미합니다.

트랜스포머 아키텍처(Transformer Architectures)는 자기 주의(Self-Attention)를 통해 대표적인 사례를 제공합니다. 각 토큰 표현(Token Representation)은 다른 토큰과의 관계를 평가하고 그 관계에 따라 가중된 새로운 표현을 구성할 수 있습니다. 이 메커니즘을 통해 모델은 장거리 의존성(Long-Range Dependencies)을 포착하고 입력의 어느 부분이 가장 관련성이 높은지를 동적으로 결정할 수 있지만, 이는 완전한 생물학적 주의 모델이 아니라 수학적 연산(Mathematical Operation)입니다.

교차 주의(Cross-Attention)는 동일한 원리를 서로 다른 정보원 사이로 확장합니다. 언어 표현(Language Representation)은 시각적 특징에 주의를 기울일 수 있고, 로봇 명령은 탐지된 객체에 주의를 기울일 수 있으며, 계획 표현은 관련 기억에 주의를 기울일 수 있습니다. 이러한 메커니즘은 언어, 비전(Vision), 오디오(Audio), 행동 및 기타 양식의 정보를 유연하게 연결할 수 있기 때문에 멀티모달 AI(Multimodal AI)에서 특히 중요합니다.

AI의 주의는 명시적인 계산 선택(Computational Selection)을 통해서도 작동할 수 있습니다. 자율 시스템(Autonomous System)은 특정 영역에 고해상도 지각(High-Resolution Perception)을 할당하거나, 불확실성이 증가할 때만 계산 비용이 높은 모델을 활성화하거나, 선택된 센서를 더 높은 주파수로 처리할 수 있습니다. 이 경우 주의는 제한된 연산(Compute), 에너지(Energy), 대역폭(Bandwidth), 지연시간(Latency), 메모리 자원을 관리하는 아키텍처 메커니즘이 됩니다.

이러한 자원 관리(Resource Management)의 관점은 엣지 AI(Edge AI)와 로보틱스(Robotics)에서 특히 중요합니다. 물리적 로봇은 모든 모델을 최대 해상도와 최대 주파수로 항상 동시에 실행할 수 없습니다. 내비게이션(Navigation) 중에는 장애물 탐지(Obstacle Detection)를 우선하고, 파지 중에는 조작 관련 특징을 우선하며, 인간과 협업할 때는 인간 모니터링을 우선하고, 위치 불확실성이 증가하면 위치 추정(Localization) 신호를 우선적으로 처리해야 할 수 있습니다.

능동 지각(Active Perception)은 주의를 정보 획득(Information Gathering)과 더욱 긴밀하게 연결합니다. 지능형 에이전트(Intelligent Agent)는 더 좋은 증거를 얻기 위해 카메라를 움직이거나, 신체 위치를 변경하거나, 다른 센서를 선택하거나, 관점을 바꾸거나, 불확실한 객체에 접근할 수 있습니다. 따라서 주의는 이미 존재하는 정보 중 무엇을 처리할지를 결정할 뿐 아니라 미래에 어떤 관찰을 의도적으로 획득할지도 결정할 수 있습니다.

외부 도구(External Tools)를 사용하는 AI 에이전트의 경우 주의는 어떤 정보원에 계산적 초점을 맞출 것인지를 결정하는 보다 넓은 개념으로 해석할 수 있습니다. 에이전트는 문서를 조사할지, 기억을 검색할지, 데이터베이스(Database)를 조회할지, 지각 모델을 호출할지, 계산을 수행할지, 인간에게 입력을 요청할지를 선택할 수 있습니다. 이는 주의 제어를 내부 표현의 가중치 조절에서 시스템 수준의 자원 오케스트레이션(System-Level Resource Orchestration)으로 확장합니다.

현대 AI 에이전트는 매우 많은 양의 저장 정보에 접근할 수 있기 때문에 기억 시스템(Memory Systems)은 또 다른 문제를 발생시킵니다. 효율적인 인지를 위해서는 현재 상황과 관련된 작은 정보 집합만을 선택해야 합니다. 따라서 검색 메커니즘(Retrieval Mechanisms), 관련성 점수화(Relevance Scoring), 컨텍스트 관리(Context Management), 작업 기억 선택(Working-Memory Selection)은 주의 우선순위화(Attentional Prioritization)의 계산적 대응물로 이해할 수 있습니다.

자각(Awareness)은 AI 용어로 변환하기가 더욱 어렵습니다. 현재의 AI 시스템은 내부 표현을 유지하고, 신뢰도를 보고하며, 일부 출력을 모니터링하고, 선택된 상태 정보를 외부에 제공할 수 있지만 이러한 능력을 인간의 의식적 경험과 자동으로 동일시해서는 안 됩니다. 기능적 모니터링(Functional Monitoring)과 자기 보고(Self-Report)는 주관적인 자각을 가정하지 않고도 계산적으로 연구할 수 있습니다.

공학적으로 유용한 해석 가운데 하나는 운영 자각(Operational Awareness)입니다. 자율 시스템은 현재 작업, 환경, 불확실성, 자원 상태(Resource State), 실패(Failures), 안전 제약조건(Safety Constraints), 인간과의 상호작용에 대한 명시적인 표현을 유지할 수 있습니다. 이러한 정보를 계획, 제어, 기억, 의사소통 모듈 전체에서 전역적으로 이용 가능하게 만들면 기계 의식(Machine Consciousness)에 대한 주장을 하지 않으면서도 조정된 행동을 향상시킬 수 있습니다.

상황 자각(Situation Awareness)은 실용적인 사례를 제공합니다. 사람 주변에서 작동하는 로봇은 주변 객체, 인간의 위치, 움직임, 작업 상태(Task Status), 위험 요소(Hazards), 이용 가능한 행동, 예상되는 미래 사건에 대한 통합 표현(Integrated Representation)을 유지해야 합니다. 주의는 이러한 표현 가운데 어느 부분을 즉시 처리해야 하는지를 결정하며, 시스템 수준의 자각은 여러 기능적 구성요소에 걸친 조정된 의사결정을 지원합니다.

자기 자각(Self-Awareness) 역시 공학 시스템에서는 자신의 상태 표현에 접근하는 능력으로 신중하게 해석할 수 있습니다. AI 에이전트는 배터리 수준(Battery Level), 계산 부하(Computational Load), 센서 상태(Sensor Health), 위치 추정 신뢰도(Localization Confidence), 작업 진행 상태(Task Progress), 모델 불확실성(Model Uncertainty), 이용 가능한 능력(Capabilities)을 모니터링할 수 있습니다. 이러한 자기 모니터링(Self-Monitoring)은 자체 운영 조건이 악화될 때 행동을 변경할 수 있게 하므로 더욱 신뢰성 높은 의사결정을 지원합니다.

따라서 주의는 안전(Safety)과 밀접하게 관련됩니다. 예상하지 못한 위험을 무시하면서 작업 완료에 지나치게 집중하는 시스템은 위험하게 행동할 수 있습니다. 안전 중요 아키텍처(Safety-Critical Architectures)는 충돌 위험(Collision Risk), 인간 근접성(Human Proximity), 시스템 고장(System Faults), 비상 신호(Emergency Signals)가 에이전트의 현재 목표와 관계없이 낮은 우선순위의 활동을 중단할 수 있도록 보호된 주의 우선순위(Protected Attentional Priorities)를 요구할 수 있습니다.

인간-AI 상호작용(Human-AI Interaction)에서는 인간의 주의를 관리하는 것도 필요합니다. 지나치게 많은 경고를 생성하는 인터페이스는 경보 피로(Alarm Fatigue)를 발생시켜 중요한 정보가 무시되게 할 수 있습니다. 반대로 중요한 불확실성을 전달하지 못하는 AI 시스템은 인간 운영자가 증가하는 위험을 인식하지 못하게 만들 수 있습니다. 따라서 효과적인 시스템은 기계의 주의와 인간 협력자의 제한된 주의 용량을 모두 고려해야 합니다.

적응형 인터페이스(Adaptive Interfaces)는 긴급성(Urgency), 문맥(Context), 작업 부하, 사용자 상태(User State)에 따라 정보를 제공함으로써 이러한 목표를 지원할 수 있습니다. 일상적인 정보는 배경에 유지하고 이상 상황(Anomalies)은 강조할 수 있습니다. 그러나 주의 제어를 지나치게 자동화하면 중요한 문맥을 숨길 수도 있으므로 인터페이스 설계는 필터링(Filtering)과 투명성(Transparency) 사이의 균형을 유지하고 인간 감독(Human Oversight)의 기회를 보존해야 합니다.

주의와 자각은 장기 시간 범위 자율 에이전트(Long-Horizon Autonomous Agents)에서 특히 중요합니다. 작업이 수분, 수시간 또는 수일에 걸쳐 지속되면 에이전트는 중단과 변화하는 상황에 적절히 대응하면서 지속적인 목표(Persistent Goals)를 유지해야 합니다. 어떤 정보가 여전히 관련성이 있는지, 현재 어떤 하위 작업(Subtask)이 활성화되어 있는지, 주의가 다른 곳에 있는 동안 무엇이 변화했는지, 언제 우선순위를 다시 구성해야 하는지를 파악해야 합니다.

계층적 주의(Hierarchical Attention)는 이러한 복잡성을 관리하는 데 도움을 줄 수 있습니다. 상위 수준 과정은 목표나 작업 사이에 자원을 할당하고, 중간 수준 과정은 객체 또는 정보원을 선택하며, 하위 수준 메커니즘은 특징이나 감각 신호에 우선순위를 부여할 수 있습니다. 이러한 계층적 구성(Hierarchical Organization)은 지능 시스템이 장기적인 목표 안정성과 예상하지 못한 사건에 대한 빠른 국소적 반응을 결합할 수 있도록 합니다.

학습(Learning)은 결과를 예측하는 데 어떤 신호가 유용한지를 발견함으로써 주의를 향상시킬 수 있습니다. 반복적인 경험을 통해 에이전트는 관련 정보가 어디에서 나타나는 경향이 있는지, 어떤 단서가 위험을 나타내는지, 어떤 관찰이 불확실성을 감소시키는지를 학습합니다. 따라서 시스템이 문맥, 목표, 관찰, 행동, 결과 사이의 관계를 학습하면서 주의는 점차 더 전문화됩니다.

잘못 학습된 주의(Poorly Learned Attention)는 체계적인 실패(Systematic Failure)를 발생시킬 수 있습니다. 모델이 표면적인 상관관계(Superficial Correlations)에 반복적으로 의존하면 인과적 정보(Causal Information)를 무시하면서 관련 없는 특징에 집중할 수 있습니다. 로보틱스에서는 기하 구조를 고려하지 않고 시각적 외형에만 주의를 기울이면 위험한 행동이 발생할 수 있으며, 언어 시스템에서는 오해를 유발하는 문맥 패턴을 강조하면 확신에 찬 잘못된 추론이 발생할 수 있습니다.

따라서 주의를 평가하려면 단순히 어텐션 가중치(Attention Weights)를 시각화하는 것 이상이 필요합니다. 모델은 특정 표현에 높은 계산적 가중치를 부여하더라도 해당 표현이 최종 출력에 인과적으로 기여하지 않을 수 있습니다. 신뢰할 수 있는 평가는 정보를 제거하거나 변경하거나 지연시키거나 불확실하게 만들었을 때 행동이 어떻게 변화하는지를 검증하여 시스템이 실제로 자신이 우선시하는 것으로 보이는 특징에 의존하는지를 확인해야 합니다.

주의와 자각의 관계는 궁극적으로 인지과학(Cognitive Science)의 더 넓은 원리를 보여줍니다. 지능 시스템은 모든 정보를 동일하게 처리하는 대신 정보를 선택적으로 조직해야 합니다. 선택(Selection)은 효율성을 제공하며, 더 넓은 접근 가능성(Broader Availability)은 선택된 정보가 지각, 기억, 추론, 계획, 행동을 조정할 수 있도록 합니다. 이러한 메커니즘들은 제한된 자원을 유연한 행동으로 전환하는 데 도움을 줍니다.

미래의 AI와 체화 지능(Embodied Intelligence)에서 중요한 교훈은 단순히 인간의 주의를 모방하는 것이 아니라 적응형 우선순위화(Adaptive Prioritization)가 가능한 시스템을 설계하는 것입니다. 이러한 시스템은 목표, 불확실성, 새로움(Novelty), 위험, 기대 정보 가치(Expected Information Value), 환경 변화에 따라 계산 자원을 할당하면서 중요한 정보가 필요할 때 정상적인 처리 과정을 우선적으로 중단하거나 대체할 수 있는 메커니즘을 유지해야 합니다.

주의(Attention)는 집중(Focus)을 제공하고, 자각(Awareness)은 조정된 인지(Coordinated Cognition)에 필요한 정보에 대한 보다 광범위한 접근을 제공합니다. 두 기능의 상호작용을 통해 지능 시스템은 우선순위를 재검토하고, 예상하지 못한 사건을 탐지하며, 기능 모듈 사이에서 정보를 통합하고, 행동을 적응시키는 능력을 유지하면서도 제한된 자원을 집중적으로 사용할 수 있습니다. 이러한 능력은 인간 인지(Human Cognition), 인지 아키텍처(Cognitive Architectures), 자율 에이전트(Autonomous Agents), 더욱 일반적인 형태의 인공지능(Artificial Intelligence)을 연결하는 핵심적인 기반을 형성합니다.

##  

## 01.03 Learning and Adaptation [w/Code]

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

Learning is the process through which a cognitive system changes its internal representations, expectations, skills, or behavior as a consequence of experience. Adaptation refers more specifically to adjusting those learned mechanisms when tasks, environments, goals, or operating conditions change. Together, learning and adaptation allow intelligence to improve over time rather than relying only on fixed responses.

A cognitive system encounters regularities in sensory input, actions, outcomes, and social interaction. Learning extracts useful structure from these experiences and incorporates it into memory, predictive models, concepts, policies, or procedures. The resulting knowledge can influence future perception, attention, reasoning, decision making, and action, creating a continuous relationship between experience and behavior.

Learning can occur through several mechanisms. Association connects events that repeatedly occur together, reinforcement strengthens actions associated with useful outcomes, observation allows knowledge to be acquired from others, and instruction provides explicit information about rules or goals. Cognitive learning also includes abstraction, analogy, concept formation, causal inference, and the reorganization of existing knowledge.

Classical conditioning demonstrates associative learning by showing how a previously neutral stimulus can acquire predictive meaning after repeated pairing with another event. The important principle is not simply behavioral response formation but the ability to learn relationships among events. Such learned predictions allow an organism to anticipate future conditions and prepare appropriate actions before important events occur.

Operant learning emphasizes the consequences of behavior. Actions followed by desirable outcomes tend to become more likely under similar circumstances, while actions associated with undesirable outcomes may become less likely. This mechanism connects behavior with environmental feedback and provides a conceptual foundation for reinforcement learning, where an agent improves a policy according to reward signals generated through interaction.

Reinforcement learning involves more than immediate reward. Intelligent agents often need to estimate how current actions influence outcomes that occur much later. Learning therefore requires assigning credit across time, balancing short-term and long-term consequences, and estimating the expected value of states or actions. These problems are central both to cognitive theories of decision making and computational reinforcement learning.

Exploration is necessary because an agent cannot learn the value of unfamiliar actions without occasionally trying them. Exploitation, in contrast, uses actions already believed to produce good outcomes. Effective adaptation requires balancing exploration and exploitation so that an agent continues gathering useful information without sacrificing excessive performance or safety in situations where reliable knowledge already exists.

Observational learning allows knowledge to be acquired without directly experiencing every possible action and consequence. Humans can learn by watching other people perform tasks, observing successful and unsuccessful strategies, and interpreting the intentions behind demonstrated behavior. This greatly increases learning efficiency because information accumulated by one individual can be transferred socially to others.

Imitation learning provides a computational analogue of this process. Instead of discovering an entire behavior policy through trial and error, an artificial agent can learn from demonstrations provided by humans, experts, or other agents. Demonstrations can supply useful trajectories through complex state spaces, although successful imitation still requires handling situations that were not represented sufficiently in the observed examples.

Instruction further accelerates learning by transmitting structured knowledge directly. Humans can use language to communicate procedures, constraints, concepts, goals, warnings, and explanations that might otherwise require extensive experimentation. The combination of instruction and experience allows cognitive systems to exploit both symbolic knowledge and sensorimotor evidence when adapting to unfamiliar situations.

Learning is closely connected with memory because changes produced by experience must persist long enough to influence future behavior. Working memory temporarily maintains information required during an ongoing learning episode, while long-term memory preserves knowledge across extended periods. Episodic memory records particular experiences, semantic memory captures generalized knowledge, and procedural memory stores learned skills and behavioral routines.

Memory consolidation describes processes through which initially fragile information becomes more stable over time. New experiences may first depend heavily on recently formed representations before becoming integrated with existing knowledge. Consolidation is important because learning should not merely record isolated events; it must organize them into structures that remain useful across future situations.

Generalization allows learning acquired from particular examples to influence behavior in related but previously unseen situations. Without generalization, an intelligent system would need to relearn every variation of every task independently. Effective cognition identifies relevant similarities while ignoring irrelevant differences, allowing knowledge to transfer across objects, environments, viewpoints, people, and task configurations.

Discrimination complements generalization by recognizing when apparently similar situations require different responses. An overly general learner may treat distinct conditions as equivalent, while an overly specific learner may fail to transfer useful knowledge. Intelligent adaptation therefore requires finding representations that preserve distinctions important for behavior while remaining invariant to variations that do not matter.

Concept formation supports this balance by organizing individual experiences into categories and relational structures. A learner can recognize that several visually different objects belong to the same functional class or that different tasks share a common underlying structure. Concepts reduce complexity because rules and predictions can be associated with categories rather than separately memorized for every individual observation.

Abstraction extends learning beyond surface similarity. Instead of memorizing specific sensory patterns, a cognitive system can extract higher-level relationships such as containment, support, causation, sequence, ownership, or goal dependency. Abstract knowledge can transfer across domains because the same relational pattern may occur in environments that look very different at the sensory level.

Transfer learning describes the reuse of previously acquired knowledge when solving a new problem. Knowledge of one language may facilitate learning another, experience with one tool may help in understanding a similar tool, and a robot trained in one environment may reuse navigation representations in another. Transfer improves efficiency when previous knowledge captures structure that remains relevant under new conditions.

Negative transfer occurs when previously learned knowledge is applied where it is no longer appropriate. Familiar strategies can become misleading when environmental dynamics, rules, object properties, or goals change. Adaptation therefore requires mechanisms for detecting mismatches between expectations and observations and reducing reliance on outdated knowledge when necessary.

Prediction error provides one important learning signal. A cognitive system can compare what it expected to happen with what actually occurred. Small errors confirm that existing models remain useful, while systematic errors indicate that some representation or prediction must change. Learning can therefore be understood partly as the continual reduction or interpretation of discrepancies between prediction and experience.

Not all prediction errors should produce equal changes. Sensory observations can be noisy, unusual events may be accidental, and some outcomes may be poorly measured. Adaptive learning must estimate uncertainty and reliability so that strong updates occur when evidence is informative while unstable fluctuations are ignored. This protects learned knowledge from being continually disrupted by random variation.

Bayesian perspectives describe learning as updating beliefs when new evidence arrives. Existing beliefs provide prior expectations, observations contribute likelihood information, and the resulting posterior beliefs combine previous knowledge with current evidence. Although human cognition does not necessarily perform exact Bayesian computation, this framework provides a useful model of adaptive inference under uncertainty.

Learning rate determines how quickly new evidence changes existing knowledge. A high learning rate enables rapid adaptation but can make representations unstable, while a low learning rate preserves previous knowledge but may respond too slowly to real changes. Intelligent systems therefore benefit from adjusting learning rates according to uncertainty, environmental volatility, confidence, and the consequences of error.

Adaptation becomes particularly important in nonstationary environments. If relationships among observations, actions, and outcomes remain constant, knowledge learned previously can remain useful for a long time. In real environments, however, objects move, users change behavior, sensors degrade, goals change, and new situations appear. Cognition must detect these changes and revise its models without rebuilding everything from the beginning.

Continual learning addresses the challenge of acquiring new knowledge throughout the lifetime of a system. Traditional machine learning often separates training from deployment, but biological intelligence continues learning during operation. Continual learning seeks similar capability by allowing models to incorporate new tasks, environments, classes, or experiences while preserving useful knowledge acquired previously.

A major problem in continual learning is catastrophic forgetting. When a neural system is optimized strongly for new data, parameter changes may overwrite representations supporting earlier capabilities. The system can improve on the new task while unexpectedly degrading on old ones. Stable adaptation therefore requires mechanisms that balance plasticity for new learning with stability for previously acquired knowledge.

Replay is one approach for reducing forgetting. Previously encountered examples or representative experiences are stored and revisited during later learning so that new optimization remains constrained by older knowledge. Biological theories of memory consolidation also motivate replay-like mechanisms, particularly the idea that past experiences can be reactivated to strengthen and reorganize long-term representations.

Regularization provides another strategy by restricting changes to parameters considered important for previously learned tasks. Instead of treating every model parameter as equally replaceable, the learner preserves components strongly associated with existing capabilities while allowing other components to adapt more freely. This creates a computational balance between stability and plasticity.

Modular architectures can support continual adaptation by separating reusable capabilities into components. New tasks may activate, combine, or extend existing modules instead of modifying one monolithic representation. Modularity can reduce interference and improve transfer because skills learned in one context may later become building blocks for more complex behavior.

Meta-learning approaches the problem from a different direction by learning how to learn. Instead of optimizing only for performance on individual tasks, a meta-learning system develops representations, initialization parameters, update rules, or strategies that make later adaptation faster. Experience across many tasks can therefore improve the system\'s ability to learn future tasks with relatively little new data.

Few-shot adaptation is particularly important for general intelligence because real systems cannot always collect thousands of labeled examples whenever conditions change. A cognitive learner should ideally use strong prior knowledge and adapt from a small number of demonstrations, observations, corrections, or interactions. This resembles human learning, where existing concepts greatly accelerate acquisition of related skills.

Zero-shot generalization pushes this idea further by applying existing knowledge to situations for which no direct training examples were provided. Language, conceptual representations, compositional reasoning, and foundation models can support such behavior by connecting unfamiliar tasks with known structures. Zero-shot ability is useful, although practical systems must still recognize when their extrapolation is unreliable.

Self-supervised learning provides another route toward efficient adaptation. Instead of depending entirely on manually labeled examples, the system creates learning signals from relationships already present in its observations. Predicting missing information, future states, transformations, correspondences, or relationships can produce useful representations from large amounts of naturally occurring experience.

For embodied agents, temporal prediction provides especially valuable self-supervision. A robot can observe how scenes change after movement, how objects respond to contact, and how sensor measurements evolve through time. Predicting these changes teaches representations of dynamics and causality that can later support navigation, manipulation, planning, anomaly detection, and world modeling.

World models extend learning from direct stimulus-response mappings toward internal models of how environments evolve. An agent learns relationships among states, objects, actions, and future outcomes. By simulating possible consequences internally, the system can evaluate actions before execution, learn from imagined trajectories, and adapt behavior without physically testing every possibility.

Model-based learning can therefore improve data efficiency, but incorrect internal models introduce another risk. Planning performed with an inaccurate world model may generate actions that appear effective in simulation but fail in reality. Adaptation must consequently include mechanisms for continuously comparing predicted and observed outcomes and correcting model errors as real experience accumulates.

Active learning allows an intelligent system to influence which examples it learns from. Instead of accepting observations passively, the learner can seek situations expected to reduce uncertainty most effectively. It may request a label, inspect another viewpoint, conduct an experiment, ask a human for clarification, or select an informative task. Learning thus becomes an information-seeking activity.

Curiosity-driven learning follows a related principle. Novel, uncertain, or surprising situations can generate intrinsic motivation even when no external reward is immediately available. Exploring such situations expands an agent\'s understanding of the environment and may create knowledge useful for later tasks. Curiosity therefore provides a mechanism for autonomous knowledge acquisition before specific needs arise.

Causal learning is particularly valuable for robust adaptation. Statistical correlations may predict outcomes reliably within a familiar environment yet fail when conditions change. Causal knowledge attempts to represent how interventions produce consequences, making it more suitable for reasoning about unfamiliar situations, counterfactual alternatives, and deliberate actions that modify the environment.

Learning also depends on representation quality. If important variables are hidden inside poor representations, adaptation can require large amounts of data. Representations that separate objects, relations, actions, goals, and causal factors allow new knowledge to be incorporated more efficiently. Representation learning and adaptation are therefore tightly connected rather than independent problems.

Human cognition benefits greatly from compositional learning. Existing concepts and skills can be combined to construct new behaviors without learning every combination independently. Someone who understands objects, containers, movement, and spatial relations can understand many new instructions by composing these known elements. Compositionality provides a powerful mechanism for scalable generalization.

Skill learning gradually transforms deliberate behavior into efficient procedures. Early stages of learning may require substantial working memory, attention, and explicit reasoning. With practice, repeated components become faster and more automatic, reducing cognitive load. This frees high-level resources for monitoring goals, adapting to unusual events, and coordinating more complex activities.

However, automaticity introduces a stability-adaptation tradeoff. Highly optimized skills are efficient under familiar conditions but may become difficult to modify when circumstances change. Cognitive flexibility requires detecting when automatic behavior is failing and restoring deliberate control. Adaptation therefore depends not only on learning new routines but also on knowing when established routines should be suspended.

Metacognition contributes to adaptive learning by monitoring the learning process itself. A learner may estimate confidence, recognize uncertainty, detect repeated failure, compare strategies, or decide that more practice is required. Such self-monitoring enables learning resources to be directed toward weaknesses rather than distributed uniformly across information already understood well.

Feedback quality strongly influences adaptation. Clear feedback can identify which components of behavior were successful or incorrect, while delayed, sparse, or ambiguous feedback makes learning more difficult. Humans frequently supplement environmental feedback with instruction and explanation, whereas AI systems may combine rewards, demonstrations, labels, corrective feedback, uncertainty signals, and safety constraints.

Social learning expands the available information even further. Knowledge can be transferred through imitation, language, teaching, correction, collaboration, and cultural artifacts. Humans therefore do not learn only from individual interaction with the physical environment. They inherit accumulated knowledge from other people, dramatically accelerating adaptation across generations and communities.

For AI, human-in-the-loop learning provides a practical form of this interaction. People can supply demonstrations, preferences, corrections, labels, approval, explanations, or interventions when system confidence is low. Selectively requesting human assistance can improve learning efficiency and safety while reducing the burden that would result from continuous supervision.

Learning systems must also consider safety during adaptation. Trial-and-error exploration that is acceptable in simulation may be dangerous when performed by a physical robot, vehicle, or industrial system. Safe learning therefore constrains exploration, monitors uncertainty, limits actions to approved regions, and provides recovery mechanisms when unexpected behavior occurs.

Simulation can reduce this risk by allowing large amounts of experience to be generated without damaging hardware or environments. Agents can explore failures, unusual conditions, rare events, and alternative strategies within virtual environments before deployment. However, differences between simulation and reality require domain adaptation, validation, and continued real-world learning.

Embodiment changes the nature of adaptation because a physical agent learns through its own sensors, actuators, morphology, and interaction possibilities. A manipulation policy cannot be separated entirely from arm geometry, joint limits, force characteristics, gripper design, sensor placement, and latency. Learning must therefore be grounded in the actual capabilities and constraints of the agent.

Sensorimotor adaptation illustrates this principle directly. When a tool changes effective reach, a sensor becomes miscalibrated, or a motor response differs from expectation, an agent can gradually adjust its internal mapping between commands and consequences. Such adaptation allows stable performance despite changes in the body, hardware, environment, or external tools.

Robotics makes continual adaptation an operational requirement. Lighting conditions change, floors become slippery, payloads vary, objects are rearranged, people behave unpredictably, and mechanical characteristics evolve through wear. A robot that cannot update its assumptions may perform well during initial testing yet gradually become unreliable as deployment conditions diverge from training conditions.

Physical AI extends this requirement to systems that combine perception, language, reasoning, world models, planning, and control. Learning can modify representations at several levels, ranging from low-level sensor calibration and motor policies to semantic knowledge and high-level strategies. Successful adaptation therefore requires coordination across multiple learning timescales rather than one uniform update mechanism.

Fast adaptation may occur within seconds or minutes through context, working memory, or temporary parameter changes. Slower learning can update models across hours or days, while long-term consolidation may reorganize knowledge over much longer periods. Separating these timescales helps a system respond quickly without allowing temporary events to destabilize long-established capabilities.

Foundation models provide strong prior representations that can improve adaptation efficiency. A model pretrained across diverse data may already understand many objects, relationships, linguistic concepts, or action patterns before encountering a specific deployment environment. Fine-tuning, prompting, retrieval, adapters, or policy learning can then specialize this general knowledge using relatively limited additional experience.

Yet adaptation of large models must be carefully controlled. Excessive specialization can reduce general capabilities, while insufficient adaptation may leave the system insensitive to local requirements. Parameter-efficient methods, modular updates, external memory, retrieval, and context-based adaptation offer different ways to incorporate new information while reducing destructive modification of foundational knowledge.

Memory-based adaptation can sometimes avoid changing model parameters entirely. New facts, experiences, procedures, or environmental observations can be stored externally and retrieved when relevant. This allows rapid updates and preserves the underlying model, although retrieval quality becomes critical because irrelevant or outdated memories can mislead later reasoning.

Evaluation of learning should measure more than immediate task performance. An adaptive system should be examined for learning speed, data efficiency, generalization, retention of prior skills, robustness to distribution shift, recovery from failure, calibration under uncertainty, and safety during adaptation. Long-term evaluation is essential because some failures appear only after repeated updates.

Adaptation speed must also be considered together with stability. A system that changes rapidly may respond well to genuine environmental shifts but also overreact to noise or malicious input. A highly stable system resists disruption but can remain stuck with obsolete assumptions. Reliable intelligence therefore requires mechanisms that distinguish meaningful change from temporary variation.

The ultimate purpose of learning is not simply to minimize an error measure but to improve future interaction. New representations should make perception more informative, predictions more accurate, decisions more appropriate, and actions more effective. Because each action produces new experience, learning is embedded inside the same perception-action loop that generates the data from which adaptation occurs.

Learning and adaptation therefore form a continual cycle. Experience changes internal models, changed models alter attention and decisions, new decisions produce different actions, and those actions expose the learner to new observations and consequences. Intelligence emerges partly from repeatedly closing this loop while preserving useful knowledge and remaining flexible enough to incorporate unexpected information.

For cognitive science, this cycle explains how relatively stable knowledge can coexist with lifelong behavioral flexibility. For artificial intelligence, it motivates systems that continue improving after deployment rather than remaining fixed at the end of training. Such systems must combine memory, prediction, feedback, uncertainty, transfer, continual learning, and safe exploration within a coherent adaptive architecture.

Future intelligent agents will increasingly need to adapt across tasks, environments, hardware platforms, users, and long operational lifetimes. Their success will depend not only on how much knowledge they initially possess but on how efficiently they can acquire new knowledge without losing old capabilities. Learning and adaptation are therefore fundamental mechanisms connecting cognition, autonomous agents, robotics, Physical AI, and increasingly general forms of intelligence.

학습(Learning)은 인지 시스템(Cognitive System)이 경험(Experience)의 결과로 내부 표현(Internal Representations), 기대(Expectations), 기술(Skills), 행동(Behavior)을 변화시키는 과정입니다. 적응(Adaptation)은 보다 구체적으로 작업(Tasks), 환경(Environments), 목표(Goals), 운영 조건(Operating Conditions)이 변화할 때 이러한 학습된 메커니즘을 조정하는 것을 의미합니다. 학습과 적응은 지능(Intelligence)이 고정된 반응에만 의존하지 않고 시간에 따라 향상될 수 있도록 합니다.

인지 시스템은 감각 입력(Sensory Input), 행동(Actions), 결과(Outcomes), 사회적 상호작용(Social Interaction)에서 반복적으로 나타나는 규칙성을 경험합니다. 학습은 이러한 경험에서 유용한 구조를 추출하고 이를 기억(Memory), 예측 모델(Predictive Models), 개념(Concepts), 정책(Policies), 절차(Procedures)에 통합합니다. 이렇게 형성된 지식은 이후의 지각, 주의, 추론, 의사결정, 행동에 영향을 주어 경험과 행동 사이의 지속적인 관계를 형성합니다.

학습은 여러 메커니즘을 통해 이루어질 수 있습니다. 연합(Association)은 반복적으로 함께 발생하는 사건들을 연결하고, 강화(Reinforcement)는 유용한 결과와 관련된 행동을 강화하며, 관찰(Observation)은 다른 사람을 통해 지식을 습득하게 하고, 지시(Instruction)는 규칙이나 목표에 대한 명시적인 정보를 제공합니다. 인지 학습(Cognitive Learning)에는 추상화(Abstraction), 유추(Analogy), 개념 형성(Concept Formation), 인과 추론(Causal Inference), 기존 지식의 재구성(Reorganization)도 포함됩니다.

고전적 조건형성(Classical Conditioning)은 이전에는 중립적이었던 자극이 다른 사건과 반복적으로 결합된 후 예측적 의미를 획득할 수 있음을 보여주는 연합 학습(Associative Learning)의 사례입니다. 중요한 원리는 단순히 행동 반응을 형성하는 것이 아니라 사건들 사이의 관계를 학습하는 능력입니다. 이러한 학습된 예측은 유기체가 미래 조건을 예상하고 중요한 사건이 발생하기 전에 적절한 행동을 준비할 수 있도록 합니다.

조작적 학습(Operant Learning)은 행동의 결과를 강조합니다. 바람직한 결과가 뒤따르는 행동은 유사한 상황에서 다시 발생할 가능성이 높아지고, 바람직하지 않은 결과와 연관된 행동은 발생 가능성이 낮아질 수 있습니다. 이러한 메커니즘은 행동을 환경 피드백(Environmental Feedback)과 연결하며, 에이전트가 상호작용을 통해 생성되는 보상 신호(Reward Signals)에 따라 정책을 개선하는 강화학습(Reinforcement Learning)의 개념적 기반을 제공합니다.

강화학습(Reinforcement Learning)은 단순한 즉각적 보상만을 다루는 것이 아닙니다. 지능형 에이전트(Intelligent Agents)는 현재 행동이 훨씬 나중에 발생하는 결과에 어떤 영향을 주는지를 추정해야 하는 경우가 많습니다. 따라서 학습에는 시간에 걸친 신용 할당(Credit Assignment), 단기 결과와 장기 결과 사이의 균형, 상태(State) 또는 행동(Action)의 기대 가치(Expected Value) 추정이 필요합니다. 이러한 문제는 인지적 의사결정 이론과 계산 강화학습 모두에서 핵심적입니다.

탐색(Exploration)은 에이전트가 익숙하지 않은 행동의 가치를 가끔 직접 시도하지 않고는 학습할 수 없기 때문에 필요합니다. 반대로 활용(Exploitation)은 이미 좋은 결과를 생성한다고 판단되는 행동을 사용합니다. 효과적인 적응은 탐색과 활용 사이의 균형을 요구하며, 신뢰할 수 있는 지식이 이미 존재하는 상황에서 지나치게 성능이나 안전을 희생하지 않으면서도 새로운 정보를 계속 획득할 수 있어야 합니다.

관찰 학습(Observational Learning)은 가능한 모든 행동과 결과를 직접 경험하지 않고도 지식을 습득할 수 있도록 합니다. 인간은 다른 사람이 작업을 수행하는 모습을 보고, 성공하거나 실패하는 전략을 관찰하며, 시연된 행동의 의도를 해석함으로써 학습할 수 있습니다. 이는 한 개인이 축적한 정보를 사회적으로 다른 사람에게 전달할 수 있기 때문에 학습 효율을 크게 향상시킵니다.

모방 학습(Imitation Learning)은 이러한 과정을 계산적으로 구현한 형태입니다. 인공 에이전트는 시행착오만으로 전체 행동 정책을 발견하는 대신 인간, 전문가 또는 다른 에이전트가 제공한 시연(Demonstrations)으로부터 학습할 수 있습니다. 시연은 복잡한 상태 공간(State Spaces)을 통과하는 유용한 경로를 제공할 수 있지만, 성공적인 모방을 위해서는 관찰 사례에 충분히 포함되지 않았던 상황도 처리할 수 있어야 합니다.

지시(Instruction)는 구조화된 지식을 직접 전달함으로써 학습을 더욱 빠르게 할 수 있습니다. 인간은 언어(Language)를 이용하여 절차(Procedures), 제약조건(Constraints), 개념(Concepts), 목표(Goals), 경고(Warnings), 설명(Explanations)을 전달할 수 있으며, 그렇지 않다면 이러한 지식은 많은 실험을 통해 획득해야 할 수 있습니다. 지시와 경험의 결합은 인지 시스템이 낯선 상황에 적응할 때 기호적 지식(Symbolic Knowledge)과 감각운동 증거(Sensorimotor Evidence)를 모두 활용할 수 있도록 합니다.

학습은 경험으로 인해 발생한 변화가 미래 행동에 영향을 줄 만큼 충분히 오래 유지되어야 하기 때문에 기억(Memory)과 밀접하게 연결됩니다. 작업 기억(Working Memory)은 진행 중인 학습 과정에서 필요한 정보를 일시적으로 유지하고, 장기 기억(Long-Term Memory)은 지식을 장기간 보존합니다. 일화 기억(Episodic Memory)은 특정 경험을 저장하고, 의미 기억(Semantic Memory)은 일반화된 지식을 저장하며, 절차 기억(Procedural Memory)은 학습된 기술과 행동 루틴을 저장합니다.

기억 공고화(Memory Consolidation)는 처음에는 불안정했던 정보가 시간이 지나면서 보다 안정적으로 되는 과정을 설명합니다. 새로운 경험은 처음에는 최근에 형성된 표현에 크게 의존하다가 이후 기존 지식과 통합될 수 있습니다. 공고화는 학습이 고립된 사건을 단순히 기록하는 데 그치지 않고 미래 상황에서도 유용하게 사용할 수 있는 구조로 조직되어야 한다는 점에서 중요합니다.

일반화(Generalization)는 특정 사례에서 학습한 내용이 관련되지만 이전에 보지 못한 상황에서도 행동에 영향을 미치도록 합니다. 일반화가 없다면 지능 시스템은 모든 작업의 모든 변형을 각각 다시 학습해야 합니다. 효과적인 인지는 중요하지 않은 차이를 무시하면서 관련된 유사성을 식별하여 객체, 환경, 시점(Viewpoints), 사람, 작업 구성(Task Configurations) 사이에서 지식을 전이할 수 있도록 합니다.

변별(Discrimination)은 일반화를 보완하여 겉으로 유사한 상황이라도 서로 다른 반응이 필요한 경우를 구분합니다. 지나치게 일반화하는 학습자는 실제로 다른 조건을 동일하게 취급할 수 있고, 지나치게 구체적인 학습자는 유용한 지식을 전이하지 못할 수 있습니다. 따라서 지능적 적응은 행동에 중요한 차이는 보존하면서 중요하지 않은 변형에는 불변적인 표현(Representations)을 찾는 능력을 필요로 합니다.

개념 형성(Concept Formation)은 개별 경험을 범주(Categories)와 관계 구조(Relational Structures)로 조직함으로써 이러한 균형을 지원합니다. 학습자는 시각적으로 서로 다른 여러 객체가 동일한 기능적 범주(Functional Class)에 속하거나, 서로 다른 작업이 공통된 기본 구조를 가진다는 것을 인식할 수 있습니다. 개념은 각각의 관찰을 별도로 기억하는 대신 범주와 규칙 및 예측을 연결할 수 있게 하므로 복잡성을 줄입니다.

추상화(Abstraction)는 표면적인 유사성을 넘어 학습을 확장합니다. 인지 시스템은 특정 감각 패턴을 암기하는 대신 포함 관계(Containment), 지지(Support), 인과관계(Causation), 순서(Sequence), 소유(Ownership), 목표 의존성(Goal Dependency)과 같은 상위 수준 관계를 추출할 수 있습니다. 동일한 관계 패턴은 감각적으로 매우 다른 환경에도 나타날 수 있기 때문에 추상 지식(Abstract Knowledge)은 여러 도메인 사이에서 전이될 수 있습니다.

전이 학습(Transfer Learning)은 새로운 문제를 해결할 때 이전에 획득한 지식을 재사용하는 것을 의미합니다. 하나의 언어에 대한 지식이 다른 언어 학습에 도움을 줄 수 있고, 한 도구에 대한 경험이 유사한 도구를 이해하는 데 활용될 수 있으며, 한 환경에서 학습한 로봇이 다른 환경에서도 내비게이션 표현(Navigation Representations)을 재사용할 수 있습니다. 이전 지식이 새로운 조건에서도 유효한 구조를 포착하고 있을 경우 전이는 학습 효율을 크게 향상시킵니다.

부정적 전이(Negative Transfer)는 이전에 학습한 지식이 더 이상 적절하지 않은 상황에 적용될 때 발생합니다. 환경 동역학(Environmental Dynamics), 규칙(Rules), 객체 특성(Object Properties), 목표가 변경되면 익숙한 전략이 오히려 잘못된 방향으로 유도할 수 있습니다. 따라서 적응에는 기대와 관찰 사이의 불일치를 감지하고 필요할 때 오래된 지식에 대한 의존도를 낮추는 메커니즘이 필요합니다.

예측 오류(Prediction Error)는 중요한 학습 신호 가운데 하나를 제공합니다. 인지 시스템은 예상했던 결과와 실제로 발생한 결과를 비교할 수 있습니다. 작은 오류는 기존 모델이 여전히 유용하다는 것을 확인하는 반면, 체계적인 오류(Systematic Errors)는 표현이나 예측 중 일부를 변경해야 함을 나타냅니다. 따라서 학습은 예측과 경험 사이의 불일치를 지속적으로 줄이거나 해석하는 과정으로도 이해할 수 있습니다.

모든 예측 오류가 동일한 정도의 변화를 유발해야 하는 것은 아닙니다. 감각 관찰에는 잡음이 있을 수 있고, 특이한 사건이 우연히 발생할 수 있으며, 일부 결과는 부정확하게 측정될 수 있습니다. 적응형 학습(Adaptive Learning)은 불확실성과 신뢰도를 추정하여 정보 가치가 높은 증거에 대해서는 강하게 갱신하고 무작위 변동(Random Variation)은 무시할 수 있어야 합니다. 이를 통해 학습된 지식이 불필요하게 계속 흔들리는 것을 방지할 수 있습니다.

베이지안 관점(Bayesian Perspectives)은 학습을 새로운 증거가 들어올 때 믿음(Beliefs)을 갱신하는 과정으로 설명합니다. 기존 믿음은 사전 기대(Prior Expectations)를 제공하고, 관찰은 가능도 정보(Likelihood Information)를 제공하며, 그 결과 형성되는 사후 믿음(Posterior Beliefs)은 이전 지식과 현재 증거를 결합합니다. 인간 인지가 정확한 베이지안 계산을 수행한다고 단정할 수는 없지만, 이 프레임워크는 불확실성 아래에서 적응형 추론(Adaptive Inference)을 이해하는 유용한 모델을 제공합니다.

학습률(Learning Rate)은 새로운 증거가 기존 지식을 얼마나 빠르게 변화시키는지를 결정합니다. 높은 학습률은 빠른 적응을 가능하게 하지만 표현을 불안정하게 만들 수 있고, 낮은 학습률은 기존 지식을 보호하지만 실제 변화에 너무 느리게 반응할 수 있습니다. 따라서 지능 시스템은 불확실성, 환경 변동성(Environmental Volatility), 신뢰도, 오류의 결과에 따라 학습률을 조절할 수 있을 때 더 효과적으로 작동합니다.

비정상 환경(Nonstationary Environments)에서는 적응의 중요성이 더욱 커집니다. 관찰, 행동, 결과 사이의 관계가 일정하다면 이전에 학습한 지식은 오랫동안 유용할 수 있습니다. 그러나 실제 환경에서는 객체가 움직이고, 사용자의 행동이 변하며, 센서가 열화되고, 목표가 변경되며, 새로운 상황이 발생합니다. 인지는 이러한 변화를 감지하고 모든 것을 처음부터 다시 구축하지 않으면서 모델을 수정해야 합니다.

지속 학습(Continual Learning)은 시스템의 전체 수명 동안 새로운 지식을 습득하는 문제를 다룹니다. 전통적인 머신러닝(Machine Learning)은 종종 학습(Training)과 배포(Deployment)를 구분하지만, 생물학적 지능은 운영 중에도 계속 학습합니다. 지속 학습은 모델이 이전에 획득한 유용한 지식을 유지하면서 새로운 작업, 환경, 클래스(Classes), 경험을 통합할 수 있도록 하는 유사한 능력을 목표로 합니다.

지속 학습의 주요 문제 가운데 하나는 치명적 망각(Catastrophic Forgetting)입니다. 신경 시스템이 새로운 데이터에 강하게 최적화되면 파라미터 변화(Parameter Changes)가 이전 능력을 지원하던 표현을 덮어쓸 수 있습니다. 시스템은 새로운 작업에서는 향상되면서도 기존 작업에서는 예상하지 못한 성능 저하가 발생할 수 있습니다. 안정적인 적응을 위해서는 새로운 학습을 위한 가소성(Plasticity)과 기존 지식을 보존하는 안정성(Stability) 사이의 균형이 필요합니다.

리플레이(Replay)는 망각을 줄이기 위한 한 가지 접근법입니다. 이전에 경험한 사례나 대표적인 경험을 저장해 두었다가 이후의 학습 과정에서 다시 사용함으로써 새로운 최적화가 기존 지식에 의해 제약되도록 합니다. 생물학적 기억 공고화 이론도 리플레이와 유사한 메커니즘에 영감을 주며, 특히 과거 경험이 다시 활성화되어 장기 표현을 강화하고 재구성할 수 있다는 개념이 중요합니다.

정규화(Regularization)는 이전에 학습한 작업에서 중요하다고 판단되는 파라미터의 변화를 제한하는 또 다른 전략입니다. 모든 모델 파라미터를 동일하게 교체 가능한 것으로 취급하는 대신 기존 능력과 강하게 연관된 구성요소는 보존하고 다른 구성요소는 더 자유롭게 적응하도록 합니다. 이를 통해 안정성(Stability)과 가소성(Plasticity) 사이의 계산적 균형을 형성할 수 있습니다.

모듈형 아키텍처(Modular Architectures)는 재사용 가능한 능력을 구성요소로 분리하여 지속적인 적응을 지원할 수 있습니다. 새로운 작업은 하나의 거대한 표현 전체를 수정하는 대신 기존 모듈을 활성화하거나 결합하거나 확장할 수 있습니다. 모듈성(Modularity)은 하나의 문맥에서 학습한 기술이 이후 더 복잡한 행동을 구성하는 빌딩 블록(Building Blocks)으로 활용될 수 있기 때문에 간섭을 줄이고 전이를 향상시킬 수 있습니다.

메타 학습(Meta-Learning)은 학습하는 방법 자체를 학습하는 방식으로 문제에 접근합니다. 개별 작업의 성능만 최적화하는 대신 메타 학습 시스템은 이후 적응을 빠르게 만드는 표현, 초기 파라미터(Initialization Parameters), 업데이트 규칙(Update Rules), 전략을 개발합니다. 다양한 작업에 걸친 경험은 따라서 상대적으로 적은 새로운 데이터만으로 미래 작업을 학습할 수 있는 능력을 향상시킬 수 있습니다.

퓨샷 적응(Few-Shot Adaptation)은 실제 시스템이 조건이 바뀔 때마다 수천 개의 라벨 데이터(Labeled Examples)를 항상 확보할 수는 없기 때문에 일반 지능(General Intelligence)에 특히 중요합니다. 인지 학습자는 강한 사전 지식(Prior Knowledge)을 활용하여 소수의 시연, 관찰, 교정(Corrections), 상호작용만으로도 적응할 수 있어야 합니다. 이는 인간이 기존 개념을 이용하여 관련 기술을 빠르게 습득하는 방식과 유사합니다.

제로샷 일반화(Zero-Shot Generalization)는 직접적인 학습 사례가 제공되지 않은 상황에 기존 지식을 적용함으로써 이 개념을 더욱 확장합니다. 언어, 개념 표현(Conceptual Representations), 조합적 추론(Compositional Reasoning), 파운데이션 모델(Foundation Models)은 익숙하지 않은 작업을 이미 알고 있는 구조와 연결함으로써 이러한 행동을 지원할 수 있습니다. 다만 실제 시스템에서는 이러한 외삽(Extrapolation)이 신뢰하기 어려운 상황을 스스로 인식할 수 있어야 합니다.

자기지도학습(Self-Supervised Learning)은 효율적인 적응을 위한 또 다른 경로를 제공합니다. 사람이 수동으로 라벨을 부여한 사례에 전적으로 의존하는 대신 시스템은 관찰 내부에 이미 존재하는 관계에서 학습 신호를 생성합니다. 누락된 정보, 미래 상태, 변환(Transformations), 대응 관계(Correspondences), 구조적 관계를 예측함으로써 자연적으로 발생하는 대규모 경험에서 유용한 표현을 학습할 수 있습니다.

체화 에이전트(Embodied Agents)에서는 시간적 예측(Temporal Prediction)이 특히 가치 있는 자기지도 신호를 제공합니다. 로봇은 이동 후 장면이 어떻게 변화하는지, 객체가 접촉에 어떻게 반응하는지, 센서 측정값이 시간에 따라 어떻게 변화하는지를 관찰할 수 있습니다. 이러한 변화를 예측하는 과정은 이후 내비게이션, 조작, 계획, 이상 탐지(Anomaly Detection), 월드 모델링(World Modeling)을 지원할 수 있는 동역학과 인과관계의 표현을 학습하게 합니다.

월드 모델(World Models)은 직접적인 자극-반응 매핑(Stimulus-Response Mappings)을 넘어 환경이 어떻게 변화하는지에 대한 내부 모델로 학습을 확장합니다. 에이전트는 상태(States), 객체, 행동, 미래 결과 사이의 관계를 학습합니다. 가능한 결과를 내부적으로 시뮬레이션함으로써 시스템은 실행 전에 행동을 평가하고, 상상된 궤적(Imagined Trajectories)에서 학습하며, 모든 가능성을 실제로 물리적으로 시험하지 않고도 행동을 적응시킬 수 있습니다.

따라서 모델 기반 학습(Model-Based Learning)은 데이터 효율성을 향상시킬 수 있지만 부정확한 내부 모델은 또 다른 위험을 발생시킵니다. 부정확한 월드 모델을 기반으로 수행된 계획은 시뮬레이션에서는 효과적으로 보이지만 실제 환경에서는 실패할 수 있습니다. 따라서 적응에는 예측 결과와 실제 관찰 결과를 지속적으로 비교하고 실제 경험이 축적됨에 따라 모델 오류(Model Errors)를 수정하는 메커니즘이 포함되어야 합니다.

능동 학습(Active Learning)은 지능 시스템이 어떤 사례로부터 학습할지를 스스로 결정할 수 있도록 합니다. 학습자는 관찰을 수동적으로 받아들이는 대신 불확실성을 가장 효과적으로 줄일 것으로 예상되는 상황을 탐색할 수 있습니다. 라벨을 요청하거나, 다른 관점을 조사하거나, 실험을 수행하거나, 인간에게 명확한 설명을 요청하거나, 정보 가치가 높은 작업을 선택할 수 있습니다. 따라서 학습은 정보 탐색 활동(Information-Seeking Activity)이 됩니다.

호기심 기반 학습(Curiosity-Driven Learning)은 이와 관련된 원리를 따릅니다. 새로운 상황, 불확실한 상황, 놀라운 상황은 즉각적인 외부 보상(External Reward)이 없어도 내재적 동기(Intrinsic Motivation)를 생성할 수 있습니다. 이러한 상황을 탐색하면 에이전트의 환경 이해가 확장되고 이후의 작업에 유용한 지식을 형성할 수 있습니다. 따라서 호기심은 특정 요구가 발생하기 전에 자율적으로 지식을 획득하는 메커니즘을 제공합니다.

인과 학습(Causal Learning)은 강건한 적응(Robust Adaptation)에 특히 중요합니다. 통계적 상관관계(Statistical Correlations)는 익숙한 환경에서는 결과를 정확하게 예측하더라도 조건이 달라지면 실패할 수 있습니다. 인과 지식(Causal Knowledge)은 개입(Interventions)이 어떤 결과를 발생시키는지를 표현하려 하므로 낯선 상황, 반사실적 대안(Counterfactual Alternatives), 환경을 의도적으로 변화시키는 행동을 추론하는 데 더 적합합니다.

학습은 표현 품질(Representation Quality)에 크게 의존합니다. 중요한 변수가 부적절한 표현 안에 숨겨져 있으면 적응에 많은 데이터가 필요할 수 있습니다. 객체, 관계, 행동, 목표, 인과 요인을 분리하는 표현은 새로운 지식을 보다 효율적으로 통합할 수 있도록 합니다. 따라서 표현 학습(Representation Learning)과 적응은 서로 독립된 문제가 아니라 밀접하게 연결되어 있습니다.

인간 인지는 조합적 학습(Compositional Learning)으로부터 큰 이점을 얻습니다. 기존 개념과 기술을 결합하여 모든 조합을 각각 학습하지 않고도 새로운 행동을 구성할 수 있습니다. 객체, 용기(Container), 이동, 공간 관계를 이해하는 사람은 이러한 알려진 요소를 조합하여 많은 새로운 지시를 이해할 수 있습니다. 조합성(Compositionality)은 확장 가능한 일반화를 위한 강력한 메커니즘을 제공합니다.

기술 학습(Skill Learning)은 의도적인 행동을 점차 효율적인 절차로 변화시킵니다. 학습 초기에는 많은 작업 기억, 주의, 명시적 추론이 필요할 수 있습니다. 연습이 반복되면서 반복되는 구성요소는 더 빠르고 자동적으로 수행되며 인지 부하(Cognitive Load)가 감소합니다. 이를 통해 상위 수준 자원은 목표를 모니터링하고, 비정상적인 사건에 적응하며, 더 복잡한 활동을 조정하는 데 사용될 수 있습니다.

그러나 자동성(Automaticity)은 안정성과 적응 사이의 트레이드오프(Tradeoff)를 발생시킵니다. 고도로 최적화된 기술은 익숙한 조건에서는 효율적이지만 상황이 변화하면 수정하기 어려워질 수 있습니다. 인지적 유연성(Cognitive Flexibility)을 위해서는 자동화된 행동이 실패하고 있음을 감지하고 다시 의도적 제어(Deliberate Control)를 활성화할 수 있어야 합니다. 따라서 적응은 새로운 루틴을 학습하는 것뿐 아니라 기존 루틴을 언제 중단해야 하는지를 아는 것에도 의존합니다.

메타인지(Metacognition)는 학습 과정 자체를 모니터링함으로써 적응형 학습에 기여합니다. 학습자는 신뢰도를 추정하고, 불확실성을 인식하고, 반복적인 실패를 감지하고, 전략을 비교하거나, 추가 연습이 필요하다고 판단할 수 있습니다. 이러한 자기 모니터링(Self-Monitoring)은 이미 충분히 이해한 정보에 학습 자원을 균등하게 배분하는 대신 취약한 부분에 자원을 집중할 수 있도록 합니다.

피드백 품질(Feedback Quality)은 적응에 큰 영향을 미칩니다. 명확한 피드백은 행동의 어느 구성요소가 성공적이었거나 잘못되었는지를 식별할 수 있지만, 지연되고 희소하거나 모호한 피드백은 학습을 어렵게 만듭니다. 인간은 환경 피드백을 지시와 설명으로 보완하는 경우가 많으며, AI 시스템은 보상, 시연, 라벨, 교정 피드백(Corrective Feedback), 불확실성 신호, 안전 제약조건을 함께 사용할 수 있습니다.

사회적 학습(Social Learning)은 이용 가능한 정보를 더욱 확장합니다. 지식은 모방, 언어, 교육, 교정, 협업(Collaboration), 문화적 산출물(Cultural Artifacts)을 통해 전달될 수 있습니다. 따라서 인간은 물리적 환경과의 개인적 상호작용만으로 학습하는 것이 아니라 다른 사람들로부터 축적된 지식을 물려받으며, 이를 통해 세대와 공동체에 걸친 적응 속도가 크게 향상됩니다.

AI에서 인간 참여형 학습(Human-in-the-Loop Learning)은 이러한 상호작용의 실용적인 형태를 제공합니다. 사람은 시연, 선호(Preferences), 교정, 라벨, 승인(Approval), 설명, 또는 시스템 신뢰도가 낮을 때의 개입을 제공할 수 있습니다. 필요한 경우에만 선택적으로 인간 지원을 요청하면 지속적인 감독으로 인한 부담을 줄이면서도 학습 효율과 안전을 향상시킬 수 있습니다.

학습 시스템은 적응 과정에서 안전(Safety)도 고려해야 합니다. 시뮬레이션에서는 허용될 수 있는 시행착오 탐색이 실제 물리 로봇, 차량, 산업 시스템에서는 위험할 수 있습니다. 따라서 안전 학습(Safe Learning)은 탐색을 제약하고, 불확실성을 모니터링하며, 승인된 영역으로 행동을 제한하고, 예상하지 못한 행동이 발생할 경우 복구 메커니즘(Recovery Mechanisms)을 제공해야 합니다.

시뮬레이션(Simulation)은 하드웨어나 환경을 손상시키지 않고 대규모 경험을 생성할 수 있으므로 이러한 위험을 줄일 수 있습니다. 에이전트는 배포 전에 가상 환경에서 실패, 비정상 조건, 희귀 사건(Rare Events), 대안적 전략을 탐색할 수 있습니다. 그러나 시뮬레이션과 현실 사이에는 차이가 존재하므로 도메인 적응(Domain Adaptation), 검증(Validation), 지속적인 실제 환경 학습이 필요합니다.

체화(Embodiment)는 물리적 에이전트가 자신의 센서, 액추에이터(Actuators), 형태학(Morphology), 상호작용 가능성을 통해 학습하기 때문에 적응의 본질을 변화시킵니다. 조작 정책(Manipulation Policy)은 로봇 팔의 형상, 관절 한계(Joint Limits), 힘 특성, 그리퍼 설계(Gripper Design), 센서 위치, 지연시간과 완전히 분리해서 이해할 수 없습니다. 따라서 학습은 에이전트의 실제 능력과 제약조건에 기반해야 합니다.

감각운동 적응(Sensorimotor Adaptation)은 이러한 원리를 직접 보여줍니다. 도구를 사용하여 실제 도달 거리가 변하거나, 센서가 보정에서 벗어나거나, 모터 응답이 예상과 달라지면 에이전트는 명령과 결과 사이의 내부 매핑(Internal Mapping)을 점차 조정할 수 있습니다. 이러한 적응은 신체, 하드웨어, 환경, 외부 도구가 변화해도 안정적인 성능을 유지할 수 있도록 합니다.

로보틱스(Robotics)에서는 지속적인 적응이 운영 요구사항(Operational Requirement)이 됩니다. 조명 조건이 변화하고, 바닥이 미끄러워지며, 페이로드(Payload)가 달라지고, 객체가 재배치되며, 사람은 예측하기 어렵게 행동하고, 기계적 특성은 마모에 따라 변화합니다. 자신의 가정을 갱신할 수 없는 로봇은 초기 시험에서는 잘 작동하더라도 실제 배포 조건이 학습 조건과 달라지면서 점차 신뢰성이 낮아질 수 있습니다.

피지컬 AI(Physical AI)는 지각, 언어, 추론, 월드 모델, 계획, 제어를 결합하는 시스템으로 이러한 요구사항을 확장합니다. 학습은 저수준 센서 보정과 운동 정책부터 의미 지식(Semantic Knowledge)과 상위 수준 전략까지 여러 수준의 표현을 변화시킬 수 있습니다. 따라서 성공적인 적응에는 하나의 균일한 업데이트 메커니즘이 아니라 여러 학습 시간 규모(Learning Timescales)에 걸친 조정이 필요합니다.

빠른 적응(Fast Adaptation)은 컨텍스트(Context), 작업 기억 또는 일시적인 파라미터 변화를 통해 수초나 수분 안에 이루어질 수 있습니다. 더 느린 학습은 수시간 또는 수일 동안 모델을 갱신할 수 있으며, 장기 공고화(Long-Term Consolidation)는 훨씬 더 긴 기간에 걸쳐 지식을 재구성할 수 있습니다. 이러한 시간 규모를 분리하면 시스템이 일시적인 사건으로 장기간 축적된 능력을 불안정하게 만들지 않으면서 빠르게 대응할 수 있습니다.

파운데이션 모델(Foundation Models)은 강력한 사전 표현(Prior Representations)을 제공하여 적응 효율성을 향상시킬 수 있습니다. 다양한 데이터에 대해 사전학습(Pretraining)된 모델은 특정 배포 환경을 경험하기 전에도 많은 객체, 관계, 언어적 개념, 행동 패턴을 이미 이해할 수 있습니다. 이후 미세조정(Fine-Tuning), 프롬프팅(Prompting), 검색(Retrieval), 어댑터(Adapters), 정책 학습(Policy Learning)을 통해 상대적으로 적은 추가 경험으로 일반 지식을 특정 환경에 특화할 수 있습니다.

그러나 대규모 모델의 적응은 신중하게 제어되어야 합니다. 지나친 특화(Specialization)는 일반적인 능력을 감소시킬 수 있고, 적응이 부족하면 지역적 요구사항(Local Requirements)에 충분히 반응하지 못할 수 있습니다. 파라미터 효율적 방법(Parameter-Efficient Methods), 모듈형 업데이트(Modular Updates), 외부 기억(External Memory), 검색, 컨텍스트 기반 적응(Context-Based Adaptation)은 기반 지식을 파괴적으로 변경할 위험을 줄이면서 새로운 정보를 통합할 수 있는 서로 다른 방법을 제공합니다.

기억 기반 적응(Memory-Based Adaptation)은 경우에 따라 모델 파라미터를 전혀 변경하지 않아도 가능합니다. 새로운 사실, 경험, 절차, 환경 관찰을 외부에 저장하고 필요할 때 검색할 수 있습니다. 이는 기본 모델을 보존하면서 빠른 업데이트를 가능하게 하지만, 관련성이 낮거나 오래된 기억이 이후 추론을 잘못된 방향으로 유도할 수 있으므로 검색 품질(Retrieval Quality)이 매우 중요합니다.

학습 평가(Evaluation of Learning)는 즉각적인 작업 성능만 측정해서는 안 됩니다. 적응형 시스템은 학습 속도(Learning Speed), 데이터 효율성(Data Efficiency), 일반화, 기존 기술의 유지(Retention), 분포 변화(Distribution Shift)에 대한 강건성, 실패 이후의 복구, 불확실성 하의 보정(Calibration), 적응 중 안전성 측면에서 평가되어야 합니다. 일부 실패는 반복적인 업데이트 이후에만 나타나므로 장기 평가(Long-Term Evaluation)가 필수적입니다.

적응 속도(Adaptation Speed)는 안정성과 함께 고려해야 합니다. 매우 빠르게 변화하는 시스템은 실제 환경 변화에는 잘 대응할 수 있지만 잡음이나 악의적인 입력(Malicious Input)에 지나치게 반응할 수 있습니다. 매우 안정적인 시스템은 교란에 강하지만 오래된 가정에 갇힐 수 있습니다. 따라서 신뢰할 수 있는 지능은 의미 있는 변화와 일시적인 변동을 구분하는 메커니즘을 필요로 합니다.

학습의 궁극적인 목적은 단순히 오류 측정값(Error Measure)을 최소화하는 것이 아니라 미래의 상호작용을 개선하는 것입니다. 새로운 표현은 지각을 더 유용하게 만들고, 예측을 더 정확하게 하며, 의사결정을 더 적절하게 하고, 행동을 더 효과적으로 만들어야 합니다. 각각의 행동이 새로운 경험을 생성하기 때문에 학습은 적응이 이루어지는 데이터를 만들어내는 동일한 지각-행동 루프(Perception-Action Loop) 안에 포함되어 있습니다.

따라서 학습과 적응은 지속적인 순환 구조(Continual Cycle)를 형성합니다. 경험은 내부 모델을 변화시키고, 변화된 모델은 주의와 의사결정을 변화시키며, 새로운 의사결정은 다른 행동을 생성하고, 그 행동은 학습자를 새로운 관찰과 결과에 노출시킵니다. 지능은 유용한 지식을 보존하면서 예상하지 못한 정보를 받아들일 만큼 충분한 유연성을 유지하며 이러한 루프를 반복적으로 닫는 과정에서 부분적으로 형성됩니다.

인지과학(Cognitive Science)의 관점에서 이러한 순환은 비교적 안정적인 지식과 평생에 걸친 행동적 유연성(Lifelong Behavioral Flexibility)이 어떻게 공존할 수 있는지를 설명합니다. 인공지능(Artificial Intelligence)의 관점에서는 학습이 끝난 이후 고정된 상태로 남는 시스템이 아니라 배포 이후에도 지속적으로 개선되는 시스템의 필요성을 제시합니다. 이러한 시스템은 기억, 예측, 피드백, 불확실성, 전이, 지속 학습, 안전한 탐색을 하나의 일관된 적응형 아키텍처(Adaptive Architecture) 안에서 결합해야 합니다.

미래의 지능형 에이전트(Intelligent Agents)는 다양한 작업, 환경, 하드웨어 플랫폼(Hardware Platforms), 사용자, 긴 운영 수명(Operational Lifetimes)에 걸쳐 점점 더 많은 적응 능력을 요구받게 될 것입니다. 성공 여부는 초기 단계에서 얼마나 많은 지식을 보유하고 있는지뿐 아니라 기존 능력을 잃지 않으면서 새로운 지식을 얼마나 효율적으로 획득할 수 있는지에 의해 결정될 것입니다. 따라서 학습(Learning)과 적응(Adaptation)은 인지(Cognition), 자율 에이전트(Autonomous Agents), 로보틱스(Robotics), 피지컬 AI(Physical AI), 더욱 일반적인 형태의 지능을 연결하는 근본적인 메커니즘입니다.

##  

## 01.04 Mental Models

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

Mental models are internal representations that people use to understand how objects, systems, situations, and other agents behave. They provide simplified structures for interpreting observations, predicting future events, explaining causes, evaluating alternatives, and selecting actions. Rather than storing every detail of reality, cognition constructs useful approximations that capture relationships considered relevant to current goals and experience.

A mental model can represent physical structure, causal relationships, social expectations, task procedures, spatial layouts, or abstract systems. For example, a person may maintain a model of how a door opens, how traffic flows through an intersection, how a software system responds to input, or how another person may react to a decision. The form of the representation depends on the problem being solved.

Mental models differ from isolated facts because they describe relationships among elements. Knowing that a battery stores energy is factual knowledge, while understanding how battery charge, load, temperature, and operating time interact forms a richer model. Such relational structure allows a cognitive system to generate predictions about conditions that have not been observed directly.

Prediction is one of the most important functions of mental models. Once a person has an internal representation of how a system behaves, possible future states can be estimated before acting. A driver predicts how nearby vehicles may move, an engineer predicts how a component may respond to load, and a robot can predict how an object might move when pushed or grasped.

Mental models also support explanation. When an unexpected event occurs, cognition can compare the observation with what the current model predicted and search for a cause of the mismatch. This process allows people to diagnose failures, identify hidden variables, revise assumptions, and construct better explanations. Explanation and prediction therefore reinforce each other within model-based cognition.

These models are necessarily incomplete. The real world contains far more detail than can be represented or processed at once, so cognition compresses reality into manageable structures. A useful mental model preserves information relevant to prediction or action while ignoring less important details. The quality of a model depends not on perfect completeness but on whether its simplifications remain appropriate for the task.

Different tasks can require different models of the same object. A mechanic may represent a vehicle through components, forces, and failure modes, while a driver represents the same vehicle through controls, motion, and road behavior. A passenger may need an even simpler model. Cognition therefore constructs representations according to goals rather than maintaining one universal description of every system.

Mental models can be symbolic, spatial, visual, procedural, probabilistic, or distributed across several representational forms. A route through a building may be represented spatially, a troubleshooting procedure may be represented as conditional steps, and uncertainty about another person\'s intention may be represented probabilistically. Human cognition often combines several forms within the same problem.

Spatial mental models are especially important because many tasks depend on relationships among locations, directions, distances, and objects. People can navigate familiar environments, imagine rotations, reason about containment, and predict movement even when the relevant scene is not currently visible. Such capabilities suggest that cognition maintains internal spatial structures beyond immediate sensory input.

Temporal structure is equally important. Mental models often represent not only what exists but how states change over time. A sequence of actions, a causal process, a conversation, or a machine cycle contains temporal relationships that determine what can happen next. Models that capture transition dynamics support planning because they connect present conditions with possible future states.

Causal mental models represent how interventions or events produce consequences. They differ from simple correlations because they support questions about what would happen if a particular variable were deliberately changed. Causal models therefore enable diagnosis, planning, counterfactual reasoning, scientific explanation, and adaptation when familiar statistical patterns no longer hold.

Counterfactual reasoning depends strongly on mental simulation. A person can consider what might have happened if a different action had been chosen or imagine how a future outcome could change under another condition. These imagined alternatives are useful for learning from mistakes, evaluating plans, assigning responsibility, and comparing strategies without physically executing every possibility.

Mental simulation can be understood as running a mental model forward under hypothetical conditions. The model begins from an assumed state, applies expected relationships or dynamics, and produces one or more possible outcomes. Humans use such simulation when planning a route, assembling an object, anticipating a conversation, solving a mechanical problem, or predicting the consequence of a risky action.

Mental models are closely connected with working memory. During active reasoning, relevant parts of a model must remain accessible while information is manipulated and alternatives are compared. Because working memory is limited, complex systems are often simplified into chunks, hierarchies, or intermediate representations. Good mental models reduce cognitive load by organizing many details into meaningful structures.

Long-term memory provides the knowledge from which mental models are constructed. Previous experiences, concepts, rules, procedures, and episodes supply components that can be retrieved and combined for a current problem. Mental models are therefore often assembled dynamically rather than stored as complete fixed structures. Familiar problems can reuse well-established models, while novel situations require greater construction effort.

Schemas are closely related to mental models. A schema organizes generalized knowledge about a familiar category of situations, such as restaurants, classrooms, meetings, or driving. Mental models can use these schemas as starting structures and then incorporate information specific to the current situation. This allows cognition to form useful expectations rapidly from limited observations.

Scripts represent another related concept, emphasizing typical sequences of events. A person may know that entering a restaurant usually involves being seated, ordering, eating, and paying. Scripts reduce uncertainty by providing expectations about what normally happens next. However, rigid reliance on scripts can create mistakes when actual situations depart from familiar sequences.

Conceptual knowledge also contributes to model construction. Categories and semantic relationships allow cognition to infer properties not explicitly observed. Recognizing an object as a container, tool, vehicle, or living agent activates expectations about possible behaviors and interactions. Mental models therefore connect perception with stored conceptual structure and transform recognition into prediction.

Attention influences which elements enter a mental model. Because only part of available information can be processed deeply, task goals determine which objects, variables, and relationships receive priority. If attention focuses on irrelevant features, the resulting model may omit important causal factors. Model quality consequently depends partly on effective information selection.

Perception provides continuous evidence for updating mental models. Sensory observations are compared with existing expectations, and discrepancies may indicate that the environment changed or that the current representation is inaccurate. This creates a recurring relationship in which models guide perception while perception corrects models. Cognition is therefore both model-driven and evidence-driven.

Prediction error is especially important during model revision. When observed outcomes repeatedly differ from predictions, a cognitive system must decide whether the discrepancy results from noise, an unusual event, or a systematic weakness in the model. Persistent errors can motivate new variables, revised causal assumptions, or different representations capable of explaining previously unexpected behavior.

Learning therefore improves mental models through experience. Repeated interactions reveal regularities among states, actions, and outcomes. The learner gradually discovers which variables matter, which relationships remain stable, and which predictions fail under particular conditions. A good learning system does not merely memorize observations but reorganizes them into models that support future inference and action.

Model revision creates a balance between stability and flexibility. Changing a model after every unexpected observation would make knowledge unstable, while refusing to change established assumptions would prevent adaptation. Intelligent cognition evaluates the reliability, frequency, and importance of conflicting evidence before deciding whether an existing representation should be preserved or modified.

Expertise often depends on acquiring better mental models rather than simply accumulating more facts. Experts recognize deeper structures, anticipate likely failures, identify relevant variables rapidly, and ignore distracting details. Their models allow them to compress complex situations into meaningful patterns, making reasoning faster and more accurate within domains where extensive experience has been acquired.

Novices frequently rely on surface features because they have not yet developed representations of deeper relationships. Two problems that look different may be structurally identical to an expert, while visually similar problems may require different solutions. Learning therefore involves moving from superficial descriptions toward models that capture functional, relational, and causal structure.

Mental models can nevertheless be systematically wrong. People may construct explanations from incomplete evidence, assume incorrect causal relationships, underestimate uncertainty, or preserve intuitive models that conflict with reality. Such misconceptions can remain stable because new observations are sometimes interpreted in ways that protect existing beliefs rather than challenge them.

Confirmation bias can reinforce inaccurate models when attention and memory preferentially select evidence consistent with current expectations. If contradictory information is ignored or explained away, the model becomes increasingly resistant to revision. Reliable reasoning therefore requires actively testing assumptions, searching for disconfirming evidence, and distinguishing predictions generated by competing models.

Uncertainty should consequently be represented as part of a mental model rather than treated as an afterthought. Some relationships may be reliable while others remain speculative. A cognitive system that represents confidence can compare alternatives more effectively and determine when additional information is needed. Explicit uncertainty also reduces the risk of treating incomplete models as certain descriptions of reality.

Multiple models can sometimes coexist for the same situation. When evidence is ambiguous, cognition may maintain several hypotheses rather than selecting one immediately. Additional observations can then increase or decrease support for each possibility. This approach is particularly important in diagnosis, scientific reasoning, perception under uncertainty, and complex social interpretation.

Hierarchical mental models allow complex systems to be represented at several levels of abstraction. A vehicle can be represented as a transportation system, a collection of functional subsystems, or a detailed set of mechanical and electronic components. Higher levels simplify reasoning about goals, while lower levels provide detail when precise diagnosis or control becomes necessary.

Hierarchies also support planning. A high-level goal can be decomposed into subgoals, tasks, and executable actions. Rather than reasoning over every motor command simultaneously, cognition can plan first at an abstract level and refine details only when required. This decomposition greatly reduces the complexity of decision making in long-horizon activities.

Mental models also support analogical reasoning. If two situations share relational structure, a model developed for one can guide understanding of the other even when their surface appearances differ. Analogies are powerful because they transfer organized relationships rather than isolated facts. Scientific discovery, engineering design, education, and everyday reasoning frequently depend on this capability.

Language provides an important mechanism for constructing and communicating mental models. Descriptions can specify objects, relationships, events, causes, constraints, and hypothetical situations that are not directly observable. People can therefore share approximate models through explanation and instruction, allowing knowledge to spread without every individual independently experiencing the underlying situation.

However, language does not fully determine mental representation. A verbal explanation may produce different internal models in different people depending on prior knowledge and experience. Effective communication often requires diagrams, demonstrations, examples, or interaction because these additional forms help align the speaker\'s intended structure with the listener\'s constructed representation.

Shared mental models are especially important in collaborative activity. Members of a team need compatible expectations about goals, roles, system state, procedures, and likely actions of others. Perfectly identical internal representations are unnecessary, but sufficient alignment improves coordination because each participant can predict how others are likely to interpret events and respond.

Failures of shared models can produce coordination errors even when individual participants are competent. If two people interpret responsibilities differently or maintain conflicting assumptions about system status, their individually reasonable actions may interfere with each other. Team communication therefore often serves to synchronize models rather than simply exchange isolated information.

Social cognition itself depends heavily on models of other agents. Humans infer beliefs, intentions, goals, knowledge, emotions, and likely behavior from limited observations. These representations support cooperation, negotiation, teaching, competition, and communication. A person can predict another individual\'s behavior partly by simulating what that individual may know or want.

Theory of mind describes this ability to represent mental states that may differ from one\'s own. Recognizing that another person has incomplete or incorrect information is essential for effective communication and social reasoning. For AI systems, related capabilities may support human-aware planning, instruction following, collaboration, and interpretation of ambiguous requests.

Mental models are closely related to cognitive architectures because an integrated intelligent system needs representations connecting perception, memory, reasoning, decision making, and action. The model serves as an intermediate structure through which observations acquire meaning and possible actions acquire predicted consequences. Without such structure, behavior would rely primarily on direct stimulus-response mappings.

Classical artificial intelligence represented models explicitly through symbols, rules, logical statements, state spaces, and structured knowledge bases. These representations made relationships relatively interpretable and allowed deliberate reasoning over states and actions. Their limitation was that constructing complete symbolic models manually could be difficult in complex, uncertain, or continuously changing environments.

Modern machine learning often represents knowledge implicitly within neural network parameters and distributed embeddings. Such models can capture complex statistical relationships without explicit symbolic specification. However, their internal structure may be difficult to inspect, and implicit representations do not automatically provide reliable causal reasoning, persistent state, or controllable simulation.

Hybrid AI systems attempt to combine learned representations with more explicit structures. Neural networks may perform perception and feature extraction, while graphs, symbolic relations, databases, planners, simulators, or external memories maintain information that requires structured manipulation. Such combinations resemble the idea that cognition can use several representational forms rather than relying on a single mechanism.

Large language models demonstrate sophisticated behavior that sometimes appears compatible with mental-model reasoning. They can describe causal relationships, simulate scenarios, infer intentions, and reason about hypothetical conditions through learned linguistic representations. However, coherent language generation does not guarantee that a persistent, grounded, or causally correct internal model exists behind every response.

For this reason, AI systems increasingly use explicit state representations alongside foundation models. An agent may maintain a structured record of goals, observations, objects, relationships, tool results, uncertainties, and previous actions. This externalized state helps preserve continuity across interactions and reduces reliance on reconstructing the entire situation from language context alone.

World models provide a direct computational counterpart to many functions associated with mental models. A world model represents how relevant aspects of an environment evolve, often conditioned on actions. It can predict future states, generate imagined trajectories, estimate consequences, and support planning. In embodied AI, such models connect perception with decision making over time.

A useful world model does not need to reconstruct every pixel or physical detail. Depending on the task, it may represent objects, semantic relationships, geometry, dynamics, affordances, uncertainty, or latent features. This parallels human mental models, which preserve task-relevant structure while discarding details that contribute little to prediction or action.

Object-centric representations can make these models more compositional. Instead of representing an entire scene as an undifferentiated state, the system represents objects and their properties separately along with relationships among them. Such structure can improve generalization because familiar interaction rules may be reused when known object types appear in new configurations.

Relational models further capture connections such as proximity, support, containment, ownership, communication, or causal influence. Graph representations are useful because nodes can represent entities and edges can represent relationships. Dynamic graphs can then describe how both entities and relationships change as actions and events occur.

For robotics, mental-model-like representations must be grounded in physical constraints. A robot may understand semantically that an object should be moved but must also model its position, size, mass, reachability, collision constraints, and interaction dynamics. Abstract reasoning must therefore connect continuously with geometric and sensorimotor representations.

Affordances provide an important bridge between models and action. Instead of representing only what an object is, an agent represents what actions the object permits under current conditions. A chair may support sitting, a handle may support pulling, and a surface may support placement. These action possibilities depend on relationships between object properties and agent capabilities.

Planning uses models to evaluate candidate actions before execution. If an agent can estimate transitions from current states to future states, it can compare possible sequences according to expected reward, cost, risk, or goal achievement. Planning thus converts a descriptive model of how the world works into a prescriptive mechanism for deciding what should be done.

Model-based reinforcement learning formalizes this relationship computationally. The agent learns or receives a model of state transitions and outcomes, then uses that model to evaluate actions. This can improve data efficiency because hypothetical experiences generated through simulation supplement direct interaction, although planning quality depends strongly on model accuracy.

Model errors can accumulate during long simulations. Small prediction inaccuracies at one step may produce states unlike those encountered during training, causing later predictions to become increasingly unreliable. Practical systems therefore need uncertainty estimates, short-horizon replanning, real-world feedback, and mechanisms for recognizing when simulated trajectories should no longer be trusted.

Active perception can be interpreted as deliberate model improvement. If an agent\'s internal representation is uncertain, it can choose actions whose primary purpose is to obtain better information. Moving a camera, inspecting an occluded region, touching an object, or asking a human question can reduce uncertainty and improve the model before a critical decision is made.

Mental models also help explain situation awareness. An operator or autonomous system needs more than a collection of sensor readings; it needs an integrated representation of what is happening, why it matters, and what is likely to occur next. Situation awareness therefore depends on transforming raw observations into a model containing entities, relationships, goals, hazards, and predicted developments.

Operational awareness in autonomous systems can extend this model to the agent itself. Battery level, sensor reliability, localization confidence, computational capacity, task progress, and hardware condition can be represented alongside external state. An agent that models its own capabilities can choose plans that remain feasible under current operating constraints.

Long-horizon agents require persistent models because tasks may extend beyond the immediate context window or sensory scene. Goals, commitments, intermediate results, unresolved uncertainties, environmental changes, and past decisions must remain available across time. External memory and structured state management can therefore become essential components of artificial mental-model architectures.

Model synchronization becomes necessary when several robots or agents cooperate. Each agent observes only part of the environment, so shared maps, task states, object information, or beliefs may need to be exchanged. Differences between local models must be detected and reconciled carefully because inconsistent representations can produce conflicting actions.

Human-AI collaboration introduces the additional challenge of aligning machine and human mental models. A system may possess information the human operator lacks, while the human may understand contextual constraints unavailable to the AI. Effective interaction requires communicating goals, assumptions, confidence, intentions, and system limitations so that both sides can predict each other\'s behavior.

Explainable AI can partly be understood as supporting this alignment. Explanations help a user construct an appropriate model of why the system produced a recommendation or action. Useful explanations should communicate the factors that materially influenced behavior rather than merely produce plausible narratives, because inaccurate explanations can create misleading mental models of the AI itself.

Interface design is strongly influenced by mental-model theory. Users interact more successfully with systems when interface behavior matches understandable expectations. Inconsistent controls, hidden state changes, or unpredictable automation create incorrect user models and increase error. Good design makes system state, available actions, consequences, and important constraints sufficiently visible.

Digital twins provide an engineering example of explicit external models. A digital twin maintains a computational representation of a physical asset, process, or environment using sensor data, simulation, and system knowledge. Although more formal than ordinary human mental models, it serves a similar purpose by supporting monitoring, prediction, diagnosis, planning, and evaluation of hypothetical interventions.

Simulation environments likewise provide models in which intelligent agents can experiment safely. By varying conditions and actions, agents can explore consequences that would be costly or dangerous to test physically. The usefulness of simulation depends on whether the modeled relationships transfer sufficiently to reality, making model validation and sim-to-real adaptation essential.

Mental models also play an important role in scientific reasoning. Scientists construct models that simplify phenomena while preserving mechanisms relevant to explanation and prediction. Models are evaluated through their predictions and revised when evidence conflicts with them. Scientific reasoning therefore provides a disciplined example of model construction, testing, comparison, and revision.

This perspective suggests an important principle for AI: internal models should be treated as hypotheses rather than unquestionable truth. Representations can be incomplete, outdated, or wrong. Systems that explicitly monitor uncertainty, compare predictions with observations, and revise assumptions are more likely to remain reliable when operating conditions differ from prior experience.

Evaluation of model-based intelligence should therefore examine predictive accuracy, causal validity, calibration, transfer, planning performance, and robustness under distribution change. A model that performs well only on familiar observations may not support reliable intervention. Testing should include novel combinations, counterfactual conditions, unexpected events, and changes in environmental dynamics.

For Physical AI, mental-model concepts become especially important because the system must connect semantic understanding with real physical consequences. A robot may need to understand that a container can hold an object, predict whether the object fits, determine whether the container is reachable, plan a collision-free manipulation, and update its model if the interaction produces an unexpected result.

World models, foundation models, structured memory, causal reasoning, and sensorimotor learning can therefore be viewed as complementary mechanisms for constructing increasingly capable artificial mental models. Foundation models supply broad prior knowledge, world models predict dynamics, memory preserves experience, and perception continually grounds these structures in the current environment.

The goal is not to reproduce human mental models exactly. Human representations are shaped by biological constraints, development, culture, and cognitive biases, whereas engineered systems can use explicit databases, simulators, optimization algorithms, and high-dimensional learned representations unavailable to biological cognition. The useful objective is to preserve the functional principles of structured prediction and adaptive model revision.

A capable intelligent agent should maintain models that are simple enough for efficient inference but rich enough to support reliable prediction and action. It should know which aspects of those models are uncertain, detect when reality diverges from expectation, gather information when necessary, and update representations without discarding useful prior knowledge.

Mental models ultimately connect perception with purposeful behavior. They transform observations into structured interpretations, provide expectations about how states may evolve, support imagined alternatives, and allow actions to be evaluated before execution. Through continuous interaction with memory, attention, learning, reasoning, and feedback, they give cognition a mechanism for operating beyond immediate sensory input.

For cognitive science, mental models help explain how humans reason about systems that are not directly present and how they plan actions before performing them. For artificial intelligence, the same general principle motivates agents with persistent state, world models, simulation, causal structure, and adaptive memory. Such capabilities form a central bridge from reactive computation toward predictive, deliberative, and increasingly general intelligence.

멘탈 모델(Mental Models)은 사람들이 객체, 시스템, 상황, 다른 에이전트(Agents)가 어떻게 행동하는지를 이해하기 위해 사용하는 내부 표현(Internal Representations)입니다. 멘탈 모델은 관찰을 해석하고, 미래 사건을 예측하며, 원인을 설명하고, 대안을 평가하고, 행동을 선택하기 위한 단순화된 구조를 제공합니다. 인지는 현실의 모든 세부사항을 저장하는 대신 현재 목표와 경험에 관련된 관계를 포착하는 유용한 근사 표현을 구성합니다.

멘탈 모델은 물리적 구조(Physical Structure), 인과관계(Causal Relationships), 사회적 기대(Social Expectations), 작업 절차(Task Procedures), 공간 배치(Spatial Layouts), 추상 시스템(Abstract Systems)을 표현할 수 있습니다. 예를 들어 사람은 문이 어떻게 열리는지, 교차로에서 교통이 어떻게 흐르는지, 소프트웨어 시스템이 입력에 어떻게 반응하는지, 다른 사람이 특정 결정에 어떻게 반응할지를 나타내는 모델을 유지할 수 있습니다. 표현의 형태는 해결하려는 문제에 따라 달라집니다.

멘탈 모델은 요소들 사이의 관계를 설명한다는 점에서 개별적인 사실(Isolated Facts)과 다릅니다. 배터리가 에너지를 저장한다는 것을 아는 것은 사실적 지식(Factual Knowledge)이지만, 배터리 충전량, 부하(Load), 온도, 작동 시간이 어떻게 상호작용하는지를 이해하는 것은 더욱 풍부한 모델을 형성합니다. 이러한 관계적 구조(Relational Structure)를 통해 인지 시스템은 직접 관찰하지 않은 조건에 대해서도 예측을 생성할 수 있습니다.

예측(Prediction)은 멘탈 모델의 가장 중요한 기능 가운데 하나입니다. 사람이 시스템이 어떻게 작동하는지에 대한 내부 표현을 갖게 되면 행동하기 전에 가능한 미래 상태(Future States)를 추정할 수 있습니다. 운전자는 주변 차량이 어떻게 움직일지를 예측하고, 엔지니어는 부품이 하중에 어떻게 반응할지를 예측하며, 로봇은 객체를 밀거나 잡았을 때 어떻게 움직일지를 예측할 수 있습니다.

멘탈 모델은 설명(Explanation)도 지원합니다. 예상하지 못한 사건이 발생하면 인지는 관찰 결과를 현재 모델이 예측한 결과와 비교하고 불일치의 원인을 탐색할 수 있습니다. 이러한 과정을 통해 사람은 고장을 진단하고, 숨겨진 변수(Hidden Variables)를 식별하며, 가정을 수정하고, 더 나은 설명을 구성할 수 있습니다. 따라서 설명과 예측은 모델 기반 인지(Model-Based Cognition) 안에서 서로를 강화합니다.

이러한 모델은 필연적으로 불완전합니다. 실제 세계에는 한 번에 표현하거나 처리할 수 있는 것보다 훨씬 많은 세부사항이 존재하므로 인지는 현실을 관리 가능한 구조로 압축합니다. 유용한 멘탈 모델은 예측이나 행동에 관련된 정보를 보존하면서 덜 중요한 세부사항은 무시합니다. 모델의 품질은 완전성 자체가 아니라 단순화가 해당 작업에 얼마나 적절하게 유지되는지에 의해 결정됩니다.

동일한 객체에 대해서도 서로 다른 작업은 서로 다른 모델을 요구할 수 있습니다. 정비사는 차량을 부품, 힘(Forces), 고장 모드(Failure Modes)를 중심으로 표현할 수 있지만, 운전자는 동일한 차량을 제어 장치, 움직임, 도로에서의 행동을 중심으로 표현합니다. 승객은 더욱 단순한 모델만 필요할 수도 있습니다. 따라서 인지는 모든 시스템에 대해 하나의 보편적인 설명을 유지하는 대신 목표에 따라 표현을 구성합니다.

멘탈 모델은 기호적(Symbolic), 공간적(Spatial), 시각적(Visual), 절차적(Procedural), 확률적(Probabilistic) 형태를 가질 수 있으며 여러 표현 형태에 분산될 수도 있습니다. 건물 내부의 경로는 공간적으로 표현될 수 있고, 문제 해결 절차(Troubleshooting Procedure)는 조건부 단계로 표현될 수 있으며, 다른 사람의 의도에 대한 불확실성은 확률적으로 표현될 수 있습니다. 인간 인지는 하나의 문제 안에서도 여러 표현 형태를 결합하는 경우가 많습니다.

공간적 멘탈 모델(Spatial Mental Models)은 많은 작업이 위치, 방향, 거리, 객체 사이의 관계에 의존하기 때문에 특히 중요합니다. 사람은 관련 장면이 현재 눈에 보이지 않더라도 익숙한 환경을 탐색하고, 회전을 상상하며, 포함 관계를 추론하고, 움직임을 예측할 수 있습니다. 이러한 능력은 인지가 즉각적인 감각 입력을 넘어서는 내부 공간 구조를 유지한다는 것을 시사합니다.

시간적 구조(Temporal Structure)도 마찬가지로 중요합니다. 멘탈 모델은 무엇이 존재하는지만이 아니라 상태가 시간에 따라 어떻게 변화하는지도 표현합니다. 행동 시퀀스(Action Sequence), 인과 과정(Causal Process), 대화, 기계 작동 주기에는 다음에 어떤 일이 발생할 수 있는지를 결정하는 시간적 관계가 포함됩니다. 상태 전이 동역학(Transition Dynamics)을 포착하는 모델은 현재 조건과 가능한 미래 상태를 연결하여 계획을 지원합니다.

인과 멘탈 모델(Causal Mental Models)은 개입(Interventions)이나 사건이 어떻게 결과를 발생시키는지를 표현합니다. 이러한 모델은 특정 변수를 의도적으로 변경했을 때 어떤 일이 발생할지를 추론할 수 있다는 점에서 단순한 상관관계와 다릅니다. 따라서 인과 모델은 진단(Diagnosis), 계획(Planning), 반사실적 추론(Counterfactual Reasoning), 과학적 설명(Scientific Explanation), 익숙한 통계 패턴이 더 이상 유지되지 않을 때의 적응을 가능하게 합니다.

반사실적 추론(Counterfactual Reasoning)은 정신적 시뮬레이션(Mental Simulation)에 크게 의존합니다. 사람은 다른 행동을 선택했다면 어떤 일이 발생했을지를 생각하거나 다른 조건에서 미래 결과가 어떻게 달라질지를 상상할 수 있습니다. 이러한 가상의 대안은 모든 가능성을 실제로 실행하지 않고도 실수에서 학습하고, 계획을 평가하며, 책임을 판단하고, 전략을 비교하는 데 유용합니다.

정신적 시뮬레이션은 가상의 조건에서 멘탈 모델을 앞으로 실행하는 과정으로 이해할 수 있습니다. 모델은 가정된 상태에서 시작하여 예상되는 관계나 동역학을 적용하고 하나 이상의 가능한 결과를 생성합니다. 인간은 경로를 계획하거나, 객체를 조립하거나, 대화를 예상하거나, 기계적 문제를 해결하거나, 위험한 행동의 결과를 예측할 때 이러한 시뮬레이션을 사용합니다.

멘탈 모델은 작업 기억(Working Memory)과 밀접하게 연결되어 있습니다. 능동적인 추론 과정에서는 모델의 관련 부분을 접근 가능한 상태로 유지하면서 정보를 조작하고 대안을 비교해야 합니다. 작업 기억은 제한되어 있기 때문에 복잡한 시스템은 청크(Chunks), 계층(Hierarchies), 중간 표현(Intermediate Representations)으로 단순화되는 경우가 많습니다. 좋은 멘탈 모델은 많은 세부사항을 의미 있는 구조로 조직하여 인지 부하(Cognitive Load)를 줄입니다.

장기 기억(Long-Term Memory)은 멘탈 모델을 구성하는 데 필요한 지식을 제공합니다. 이전 경험, 개념, 규칙, 절차, 일화(Episodes)는 현재 문제에 맞게 검색되고 결합될 수 있는 구성요소를 제공합니다. 따라서 멘탈 모델은 완전하고 고정된 구조로 저장되기보다 동적으로 조립되는 경우가 많습니다. 익숙한 문제는 잘 확립된 모델을 재사용할 수 있지만 새로운 상황에서는 더 많은 구성 노력이 필요합니다.

스키마(Schemas)는 멘탈 모델과 밀접하게 관련되어 있습니다. 스키마는 식당, 교실, 회의, 운전과 같은 익숙한 상황의 범주에 대한 일반화된 지식을 조직합니다. 멘탈 모델은 이러한 스키마를 초기 구조로 사용한 다음 현재 상황에 특화된 정보를 통합할 수 있습니다. 이를 통해 인지는 제한된 관찰만으로도 유용한 기대를 빠르게 형성할 수 있습니다.

스크립트(Scripts)는 일반적으로 발생하는 사건의 순서를 강조하는 또 다른 관련 개념입니다. 사람은 식당에 들어가면 일반적으로 자리에 앉고, 주문하고, 식사하고, 비용을 지불한다는 것을 알고 있을 수 있습니다. 스크립트는 다음에 일반적으로 어떤 일이 발생하는지에 대한 기대를 제공하여 불확실성을 줄입니다. 그러나 실제 상황이 익숙한 순서에서 벗어나면 스크립트에 지나치게 의존하는 것이 오류를 발생시킬 수 있습니다.

개념적 지식(Conceptual Knowledge)도 모델 구성에 기여합니다. 범주와 의미적 관계(Semantic Relationships)를 통해 인지는 명시적으로 관찰하지 않은 속성을 추론할 수 있습니다. 객체를 용기(Container), 도구(Tool), 차량(Vehicle), 생명체(Living Agent)로 인식하면 가능한 행동과 상호작용에 대한 기대가 활성화됩니다. 따라서 멘탈 모델은 지각을 저장된 개념 구조와 연결하고 인식을 예측으로 변환합니다.

주의(Attention)는 어떤 요소가 멘탈 모델에 포함되는지에 영향을 미칩니다. 이용 가능한 정보 중 일부만 깊게 처리할 수 있기 때문에 작업 목표는 어떤 객체, 변수, 관계가 우선순위를 받을지를 결정합니다. 주의가 관련성이 낮은 특징에 집중되면 결과적으로 형성된 모델에서 중요한 인과 요인이 누락될 수 있습니다. 따라서 모델의 품질은 부분적으로 효과적인 정보 선택에 의존합니다.

지각(Perception)은 멘탈 모델을 갱신하기 위한 지속적인 증거를 제공합니다. 감각 관찰은 기존 기대와 비교되며, 불일치는 환경이 변화했거나 현재 표현이 부정확하다는 것을 나타낼 수 있습니다. 이 과정은 모델이 지각을 유도하는 동시에 지각이 모델을 수정하는 반복적인 관계를 형성합니다. 따라서 인지는 모델 주도(Model-Driven) 방식과 증거 주도(Evidence-Driven) 방식 모두로 작동합니다.

예측 오류(Prediction Error)는 모델 수정(Model Revision) 과정에서 특히 중요합니다. 관찰된 결과가 예측과 반복적으로 다를 경우 인지 시스템은 이러한 차이가 잡음(Noise), 특이한 사건(Unusual Event), 모델의 체계적인 약점(Systematic Weakness) 가운데 무엇에서 발생했는지를 판단해야 합니다. 지속적인 오류는 새로운 변수, 수정된 인과 가정 또는 이전에는 예상하지 못했던 행동을 설명할 수 있는 새로운 표현을 도입하도록 유도할 수 있습니다.

따라서 학습(Learning)은 경험을 통해 멘탈 모델을 개선합니다. 반복적인 상호작용은 상태, 행동, 결과 사이의 규칙성을 드러냅니다. 학습자는 어떤 변수가 중요한지, 어떤 관계가 안정적으로 유지되는지, 어떤 조건에서 예측이 실패하는지를 점차 발견합니다. 좋은 학습 시스템은 관찰을 단순히 기억하는 것이 아니라 미래의 추론과 행동을 지원할 수 있는 모델로 재구성합니다.

모델 수정은 안정성(Stability)과 유연성(Flexibility) 사이의 균형을 형성합니다. 예상하지 못한 관찰이 발생할 때마다 모델을 변경하면 지식이 불안정해지고, 반대로 확립된 가정을 전혀 변경하지 않으면 적응이 불가능해집니다. 지능적 인지는 기존 표현을 유지할지 수정할지를 결정하기 전에 상충되는 증거의 신뢰성, 빈도, 중요성을 평가합니다.

전문성(Expertise)은 단순히 더 많은 사실을 축적하는 것이 아니라 더 나은 멘탈 모델을 획득하는 데 의존하는 경우가 많습니다. 전문가는 더 깊은 구조를 인식하고, 발생 가능성이 높은 실패를 예측하며, 관련 변수를 빠르게 식별하고, 주의를 분산시키는 세부사항을 무시합니다. 이러한 모델은 복잡한 상황을 의미 있는 패턴으로 압축하여 풍부한 경험이 축적된 영역에서 더 빠르고 정확한 추론을 가능하게 합니다.

초보자(Novices)는 더 깊은 관계에 대한 표현을 아직 개발하지 못했기 때문에 표면적 특징(Surface Features)에 의존하는 경우가 많습니다. 외형적으로 서로 다른 두 문제가 전문가에게는 구조적으로 동일하게 보일 수 있고, 반대로 시각적으로 유사한 문제들이 서로 다른 해결책을 요구할 수도 있습니다. 따라서 학습은 표면적 설명에서 기능적, 관계적, 인과적 구조를 포착하는 모델로 이동하는 과정을 포함합니다.

그러나 멘탈 모델은 체계적으로 잘못될 수도 있습니다. 사람은 불완전한 증거로 설명을 구성하고, 잘못된 인과관계를 가정하며, 불확실성을 과소평가하거나, 현실과 충돌하는 직관적인 모델을 계속 유지할 수 있습니다. 새로운 관찰이 기존 믿음에 도전하기보다 그것을 보호하는 방식으로 해석되는 경우 이러한 오개념(Misconceptions)은 오랫동안 안정적으로 유지될 수 있습니다.

확증 편향(Confirmation Bias)은 주의와 기억이 현재 기대와 일치하는 증거를 우선적으로 선택할 때 부정확한 모델을 강화할 수 있습니다. 모순되는 정보를 무시하거나 다른 방식으로 설명해 버리면 모델은 수정에 점점 더 저항하게 됩니다. 따라서 신뢰할 수 있는 추론을 위해서는 가정을 적극적으로 검증하고, 반증 증거(Disconfirming Evidence)를 탐색하며, 경쟁하는 모델이 생성하는 예측을 구별해야 합니다.

따라서 불확실성(Uncertainty)은 사후적으로 추가되는 요소가 아니라 멘탈 모델의 일부로 표현되어야 합니다. 일부 관계는 신뢰할 수 있지만 다른 관계는 여전히 추측적일 수 있습니다. 신뢰도(Confidence)를 표현할 수 있는 인지 시스템은 대안을 더욱 효과적으로 비교하고 추가 정보가 필요한 시점을 판단할 수 있습니다. 명시적인 불확실성은 불완전한 모델을 현실에 대한 확정적인 설명으로 취급할 위험도 감소시킵니다.

동일한 상황에 대해 여러 모델(Multiple Models)이 동시에 존재할 수도 있습니다. 증거가 모호할 경우 인지는 하나를 즉시 선택하기보다 여러 가설(Hypotheses)을 유지할 수 있습니다. 이후 추가적인 관찰에 따라 각각의 가능성에 대한 지지가 증가하거나 감소할 수 있습니다. 이러한 접근법은 진단, 과학적 추론, 불확실한 상황에서의 지각, 복잡한 사회적 해석에서 특히 중요합니다.

계층적 멘탈 모델(Hierarchical Mental Models)은 복잡한 시스템을 여러 추상화 수준(Levels of Abstraction)에서 표현할 수 있도록 합니다. 차량은 운송 시스템(Transportation System), 기능적 서브시스템(Functional Subsystems)의 집합, 또는 상세한 기계 및 전자 부품의 집합으로 표현될 수 있습니다. 상위 수준은 목표에 관한 추론을 단순화하고, 하위 수준은 정밀한 진단이나 제어가 필요한 경우 세부 정보를 제공합니다.

계층 구조(Hierarchies)는 계획(Planning)도 지원합니다. 상위 수준 목표는 하위 목표(Subgoals), 작업(Tasks), 실행 가능한 행동(Executable Actions)으로 분해될 수 있습니다. 모든 운동 명령을 동시에 추론하는 대신 인지는 먼저 추상적인 수준에서 계획한 후 필요한 경우에만 세부사항을 구체화할 수 있습니다. 이러한 분해(Decomposition)는 장기 시간 범위(Long-Horizon)의 활동에서 의사결정 복잡성을 크게 감소시킵니다.

멘탈 모델은 유추 추론(Analogical Reasoning)도 지원합니다. 두 상황이 관계적 구조를 공유하면 표면적인 외형이 서로 다르더라도 하나를 위해 개발된 모델을 다른 상황을 이해하는 데 사용할 수 있습니다. 유추는 개별적인 사실이 아니라 조직된 관계를 전이하기 때문에 강력합니다. 과학적 발견, 공학 설계, 교육, 일상적인 추론은 이러한 능력에 자주 의존합니다.

언어(Language)는 멘탈 모델을 구성하고 전달하는 중요한 메커니즘을 제공합니다. 설명은 직접 관찰할 수 없는 객체, 관계, 사건, 원인, 제약조건, 가상 상황을 지정할 수 있습니다. 따라서 사람은 설명과 지시를 통해 근사적인 모델을 공유할 수 있으며, 모든 사람이 기본 상황을 독립적으로 직접 경험하지 않아도 지식을 전달할 수 있습니다.

그러나 언어가 멘탈 표현(Mental Representation)을 완전히 결정하는 것은 아닙니다. 동일한 언어적 설명이라도 사람마다 기존 지식과 경험에 따라 서로 다른 내부 모델을 형성할 수 있습니다. 효과적인 의사소통에서는 다이어그램(Diagrams), 시연(Demonstrations), 사례(Examples), 상호작용을 함께 사용하는 경우가 많으며, 이러한 추가적인 형태는 화자가 의도한 구조와 청자가 구성한 표현을 정렬하는 데 도움을 줍니다.

공유 멘탈 모델(Shared Mental Models)은 협업 활동(Collaborative Activity)에서 특히 중요합니다. 팀 구성원은 목표, 역할, 시스템 상태(System State), 절차, 다른 구성원의 예상 행동에 대해 서로 호환 가능한 기대를 가져야 합니다. 완전히 동일한 내부 표현을 가질 필요는 없지만 충분한 정렬(Alignment)이 이루어지면 각 참여자가 다른 사람이 사건을 어떻게 해석하고 반응할지를 예측할 수 있기 때문에 협업 효율이 향상됩니다.

공유 모델의 실패는 개별 참여자가 유능하더라도 협업 오류(Coordination Errors)를 발생시킬 수 있습니다. 두 사람이 책임을 서로 다르게 해석하거나 시스템 상태에 대해 상충하는 가정을 가지고 있다면 각각의 관점에서는 합리적인 행동도 서로 충돌할 수 있습니다. 따라서 팀 의사소통은 단순히 개별 정보를 교환하는 것이 아니라 모델을 동기화(Synchronize)하는 역할을 수행하는 경우가 많습니다.

사회적 인지(Social Cognition) 자체도 다른 에이전트에 대한 모델에 크게 의존합니다. 인간은 제한된 관찰로부터 다른 사람의 믿음(Beliefs), 의도(Intentions), 목표, 지식, 감정, 예상 행동을 추론합니다. 이러한 표현은 협력(Cooperation), 협상(Negotiation), 교육(Teaching), 경쟁(Competition), 의사소통을 지원합니다. 사람은 상대방이 무엇을 알고 무엇을 원하는지를 부분적으로 시뮬레이션함으로써 그 사람의 행동을 예측할 수 있습니다.

마음 이론(Theory of Mind)은 자신의 정신 상태와 다를 수 있는 다른 사람의 정신 상태를 표현하는 이러한 능력을 설명합니다. 다른 사람이 불완전하거나 잘못된 정보를 가지고 있다는 것을 인식하는 것은 효과적인 의사소통과 사회적 추론에 필수적입니다. AI 시스템에서도 이와 관련된 능력은 인간 인식 계획(Human-Aware Planning), 지시 수행(Instruction Following), 협업, 모호한 요청의 해석을 지원할 수 있습니다.

멘탈 모델은 통합된 지능 시스템이 지각, 기억, 추론, 의사결정, 행동을 연결하는 표현을 필요로 한다는 점에서 인지 아키텍처(Cognitive Architectures)와 밀접하게 관련됩니다. 모델은 관찰에 의미를 부여하고 가능한 행동에 예상되는 결과를 연결하는 중간 구조(Intermediate Structure)로 작동합니다. 이러한 구조가 없다면 행동은 주로 직접적인 자극-반응 매핑(Stimulus-Response Mappings)에 의존하게 됩니다.

고전적 인공지능(Classical Artificial Intelligence)은 기호(Symbols), 규칙(Rules), 논리적 명제(Logical Statements), 상태 공간(State Spaces), 구조화된 지식베이스(Structured Knowledge Bases)를 통해 모델을 명시적으로 표현했습니다. 이러한 표현은 관계를 비교적 해석 가능하게 만들었으며 상태와 행동에 대한 의도적인 추론을 가능하게 했습니다. 그러나 복잡하고 불확실하며 지속적으로 변화하는 환경에서는 완전한 기호 모델을 수동으로 구성하기 어렵다는 한계가 있었습니다.

현대 머신러닝(Modern Machine Learning)은 신경망 파라미터(Neural Network Parameters)와 분산 임베딩(Distributed Embeddings) 내부에 지식을 암묵적으로 표현하는 경우가 많습니다. 이러한 모델은 명시적인 기호 지정 없이 복잡한 통계적 관계를 포착할 수 있습니다. 그러나 내부 구조를 조사하기 어려울 수 있으며, 암묵적 표현만으로 신뢰할 수 있는 인과 추론, 지속적인 상태(Persistent State), 제어 가능한 시뮬레이션(Controllable Simulation)이 자동으로 제공되는 것은 아닙니다.

하이브리드 AI 시스템(Hybrid AI Systems)은 학습된 표현과 보다 명시적인 구조를 결합하려고 합니다. 신경망은 지각과 특징 추출(Feature Extraction)을 수행하고, 그래프(Graphs), 기호적 관계(Symbolic Relations), 데이터베이스(Databases), 플래너(Planners), 시뮬레이터(Simulators), 외부 기억(External Memories)은 구조적 조작이 필요한 정보를 유지할 수 있습니다. 이러한 결합은 인지가 하나의 메커니즘에만 의존하지 않고 여러 표현 형태를 사용할 수 있다는 개념과 유사합니다.

대규모 언어 모델(Large Language Models)은 때때로 멘탈 모델 기반 추론과 유사하게 보이는 정교한 행동을 보여줍니다. 인과관계를 설명하고, 시나리오를 시뮬레이션하며, 의도를 추론하고, 학습된 언어 표현을 통해 가상의 조건에 대해 추론할 수 있습니다. 그러나 일관된 언어 생성(Coherent Language Generation)이 모든 응답 뒤에 지속적이고 현실에 기반하며 인과적으로 정확한 내부 모델이 존재한다는 것을 보장하지는 않습니다.

이러한 이유로 AI 시스템은 파운데이션 모델(Foundation Models)과 함께 명시적인 상태 표현(Explicit State Representations)을 점점 더 많이 사용하고 있습니다. 에이전트는 목표, 관찰, 객체, 관계, 도구 실행 결과(Tool Results), 불확실성, 이전 행동을 구조적으로 기록할 수 있습니다. 이러한 외부화된 상태(Externalized State)는 상호작용 전반에서 연속성을 유지하고 언어적 문맥만으로 전체 상황을 다시 구성해야 하는 의존성을 줄이는 데 도움을 줍니다.

월드 모델(World Models)은 멘탈 모델과 관련된 많은 기능에 직접적으로 대응하는 계산적 구조를 제공합니다. 월드 모델은 환경의 관련 요소가 어떻게 변화하는지를 표현하며 일반적으로 행동을 조건으로 포함합니다. 미래 상태를 예측하고, 가상의 궤적(Imagined Trajectories)을 생성하며, 결과를 추정하고, 계획을 지원할 수 있습니다. 체화 AI(Embodied AI)에서는 이러한 모델이 시간에 걸쳐 지각과 의사결정을 연결합니다.

유용한 월드 모델은 모든 픽셀이나 물리적 세부사항을 완벽하게 재구성할 필요가 없습니다. 작업에 따라 객체, 의미적 관계, 기하 구조(Geometry), 동역학(Dynamics), 어포던스(Affordances), 불확실성, 잠재 특징(Latent Features)을 표현할 수 있습니다. 이는 인간의 멘탈 모델이 작업 관련 구조는 유지하면서 예측이나 행동에 거의 기여하지 않는 세부사항은 제거하는 방식과 유사합니다.

객체 중심 표현(Object-Centric Representations)은 이러한 모델을 더욱 조합적으로 만들 수 있습니다. 전체 장면을 구분되지 않은 하나의 상태로 표현하는 대신 시스템은 객체와 객체의 속성을 개별적으로 표현하고 객체 사이의 관계를 함께 표현합니다. 이러한 구조는 익숙한 상호작용 규칙을 이미 알려진 객체 유형이 새로운 구성으로 나타날 때 재사용할 수 있기 때문에 일반화 성능을 향상시킬 수 있습니다.

관계 모델(Relational Models)은 근접성(Proximity), 지지(Support), 포함(Containment), 소유(Ownership), 의사소통, 인과적 영향(Causal Influence)과 같은 연결 관계를 추가로 포착합니다. 그래프 표현(Graph Representations)은 노드(Node)가 개체를 나타내고 엣지(Edge)가 관계를 나타낼 수 있기 때문에 유용합니다. 동적 그래프(Dynamic Graphs)는 행동과 사건이 발생함에 따라 개체와 관계가 모두 어떻게 변화하는지를 표현할 수 있습니다.

로보틱스(Robotics)에서 멘탈 모델과 유사한 표현은 물리적 제약조건(Physical Constraints)에 기반해야 합니다. 로봇은 의미적으로 객체를 이동해야 한다는 것을 이해하면서 동시에 객체의 위치, 크기, 질량, 도달 가능성(Reachability), 충돌 제약조건(Collision Constraints), 상호작용 동역학(Interaction Dynamics)을 모델링해야 합니다. 따라서 추상적 추론은 기하학적 표현 및 감각운동 표현과 지속적으로 연결되어야 합니다.

어포던스(Affordances)는 모델과 행동 사이의 중요한 연결을 제공합니다. 에이전트는 객체가 무엇인지만 표현하는 것이 아니라 현재 조건에서 해당 객체가 어떤 행동을 허용하는지도 표현합니다. 의자는 앉는 행동을 가능하게 하고, 손잡이는 당기는 행동을 가능하게 하며, 표면은 객체를 놓는 행동을 가능하게 할 수 있습니다. 이러한 행동 가능성은 객체 특성과 에이전트 능력 사이의 관계에 따라 달라집니다.

계획(Planning)은 모델을 이용하여 실행 전에 후보 행동(Candidate Actions)을 평가합니다. 에이전트가 현재 상태에서 미래 상태로의 전이를 추정할 수 있다면 기대 보상(Expected Reward), 비용(Cost), 위험(Risk), 목표 달성(Goal Achievement)을 기준으로 가능한 시퀀스를 비교할 수 있습니다. 따라서 계획은 세계가 어떻게 작동하는지에 대한 기술적 모델(Descriptive Model)을 무엇을 해야 하는지를 결정하는 규범적 메커니즘(Prescriptive Mechanism)으로 변환합니다.

모델 기반 강화학습(Model-Based Reinforcement Learning)은 이러한 관계를 계산적으로 형식화합니다. 에이전트는 상태 전이(State Transitions)와 결과에 대한 모델을 학습하거나 제공받은 후 이를 이용하여 행동을 평가합니다. 시뮬레이션을 통해 생성된 가상의 경험이 직접적인 상호작용을 보완하기 때문에 데이터 효율성을 향상시킬 수 있지만, 계획 품질은 모델 정확도(Model Accuracy)에 크게 의존합니다.

장시간의 시뮬레이션에서는 모델 오류(Model Errors)가 누적될 수 있습니다. 한 단계에서 발생한 작은 예측 오차가 학습 과정에서 경험하지 못한 상태를 생성할 수 있으며, 이로 인해 이후의 예측은 점점 더 신뢰하기 어려워질 수 있습니다. 따라서 실제 시스템은 불확실성 추정, 단기 시간 범위 재계획(Short-Horizon Replanning), 실제 환경 피드백(Real-World Feedback), 시뮬레이션된 궤적을 더 이상 신뢰해서는 안 되는 시점을 판단하는 메커니즘을 필요로 합니다.

능동 지각(Active Perception)은 의도적인 모델 개선(Deliberate Model Improvement)으로 해석할 수 있습니다. 에이전트의 내부 표현이 불확실할 경우 더 나은 정보를 얻는 것을 주요 목적으로 하는 행동을 선택할 수 있습니다. 카메라를 움직이거나, 가려진 영역을 조사하거나, 객체를 만지거나, 사람에게 질문함으로써 중요한 결정을 내리기 전에 불확실성을 줄이고 모델을 개선할 수 있습니다.

멘탈 모델은 상황 자각(Situation Awareness)을 설명하는 데에도 도움을 줍니다. 운영자나 자율 시스템은 단순한 센서 측정값의 집합 이상을 필요로 하며, 현재 무엇이 발생하고 있는지, 그것이 왜 중요한지, 다음에 어떤 일이 발생할 가능성이 있는지에 대한 통합 표현이 필요합니다. 따라서 상황 자각은 원시 관찰(Raw Observations)을 개체, 관계, 목표, 위험 요소(Hazards), 예상되는 전개를 포함하는 모델로 변환하는 과정에 의존합니다.

자율 시스템의 운영 자각(Operational Awareness)은 이러한 모델을 에이전트 자신에게까지 확장할 수 있습니다. 배터리 수준(Battery Level), 센서 신뢰성(Sensor Reliability), 위치 추정 신뢰도(Localization Confidence), 계산 능력(Computational Capacity), 작업 진행 상태(Task Progress), 하드웨어 상태(Hardware Condition)를 외부 상태와 함께 표현할 수 있습니다. 자신의 능력을 모델링하는 에이전트는 현재 운영 제약조건에서 실제 실행 가능한 계획을 선택할 수 있습니다.

장기 시간 범위 에이전트(Long-Horizon Agents)는 작업이 즉각적인 컨텍스트 윈도(Context Window)나 감각 장면을 넘어 지속될 수 있기 때문에 지속적인 모델(Persistent Models)을 필요로 합니다. 목표, 약속(Commitments), 중간 결과, 해결되지 않은 불확실성, 환경 변화, 이전 의사결정을 시간에 걸쳐 유지해야 합니다. 따라서 외부 기억과 구조화된 상태 관리(Structured State Management)는 인공 멘탈 모델 아키텍처의 핵심 구성요소가 될 수 있습니다.

여러 로봇이나 에이전트가 협력할 때는 모델 동기화(Model Synchronization)가 필요합니다. 각 에이전트는 환경의 일부만 관찰하기 때문에 공유 지도(Shared Maps), 작업 상태, 객체 정보, 믿음(Beliefs)을 교환해야 할 수 있습니다. 일관되지 않은 표현은 상충하는 행동을 발생시킬 수 있으므로 로컬 모델(Local Models) 사이의 차이를 탐지하고 신중하게 조정해야 합니다.

인간-AI 협업(Human-AI Collaboration)에서는 기계와 인간의 멘탈 모델을 정렬하는 추가적인 문제가 발생합니다. 시스템은 인간 운영자가 알지 못하는 정보를 보유할 수 있고, 반대로 인간은 AI가 이용할 수 없는 문맥적 제약조건을 이해할 수 있습니다. 효과적인 상호작용을 위해서는 목표, 가정, 신뢰도, 의도, 시스템 한계를 전달하여 양측이 서로의 행동을 예측할 수 있도록 해야 합니다.

설명 가능한 AI(Explainable AI)는 이러한 정렬을 지원하는 방법으로 이해할 수 있습니다. 설명은 사용자가 시스템이 왜 특정 추천이나 행동을 생성했는지에 대한 적절한 모델을 구성하도록 도와줍니다. 유용한 설명은 단순히 그럴듯한 이야기를 생성하는 것이 아니라 실제 행동에 실질적으로 영향을 미친 요인을 전달해야 합니다. 부정확한 설명은 AI 자체에 대한 잘못된 멘탈 모델을 형성할 수 있기 때문입니다.

인터페이스 설계(Interface Design)는 멘탈 모델 이론의 영향을 크게 받습니다. 사용자는 인터페이스의 동작이 이해 가능한 기대와 일치할 때 시스템과 더욱 성공적으로 상호작용합니다. 일관되지 않은 제어, 숨겨진 상태 변화, 예측하기 어려운 자동화는 잘못된 사용자 모델(User Models)을 형성하고 오류를 증가시킵니다. 좋은 설계는 시스템 상태, 가능한 행동, 결과, 중요한 제약조건을 충분히 가시화합니다.

디지털 트윈(Digital Twins)은 명시적인 외부 모델(Explicit External Models)의 공학적 사례입니다. 디지털 트윈은 센서 데이터, 시뮬레이션, 시스템 지식을 이용하여 물리적 자산(Physical Asset), 프로세스 또는 환경에 대한 계산적 표현을 유지합니다. 일반적인 인간의 멘탈 모델보다 형식적이지만 모니터링, 예측, 진단, 계획, 가상 개입 평가를 지원한다는 점에서 유사한 목적을 수행합니다.

시뮬레이션 환경(Simulation Environments) 역시 지능형 에이전트가 안전하게 실험할 수 있는 모델을 제공합니다. 조건과 행동을 변화시키면서 실제 환경에서 시험하기에는 비용이 높거나 위험한 결과를 탐색할 수 있습니다. 시뮬레이션의 유용성은 모델링된 관계가 실제 세계로 충분히 전이되는지에 달려 있으므로 모델 검증(Model Validation)과 시뮬레이션-현실 적응(Sim-to-Real Adaptation)이 필수적입니다.

멘탈 모델은 과학적 추론(Scientific Reasoning)에서도 중요한 역할을 합니다. 과학자는 현상을 단순화하면서 설명과 예측에 중요한 메커니즘을 보존하는 모델을 구성합니다. 모델은 예측을 통해 평가되고 증거와 충돌하면 수정됩니다. 따라서 과학적 추론은 모델 구성(Model Construction), 검증(Testing), 비교(Comparison), 수정(Revision)을 체계적으로 수행하는 대표적인 사례를 제공합니다.

이러한 관점은 AI에 중요한 원칙을 제시합니다. 내부 모델(Internal Models)은 의심할 수 없는 진실이 아니라 가설(Hypotheses)로 취급되어야 합니다. 표현은 불완전하거나 오래되었거나 잘못될 수 있습니다. 불확실성을 명시적으로 모니터링하고, 예측을 관찰과 비교하며, 가정을 수정할 수 있는 시스템은 운영 조건이 이전 경험과 달라질 때에도 높은 신뢰성을 유지할 가능성이 큽니다.

따라서 모델 기반 지능(Model-Based Intelligence)의 평가는 예측 정확도(Predictive Accuracy), 인과적 타당성(Causal Validity), 보정(Calibration), 전이(Transfer), 계획 성능(Planning Performance), 분포 변화(Distribution Change)에 대한 강건성을 검토해야 합니다. 익숙한 관찰에서만 잘 작동하는 모델은 신뢰할 수 있는 개입을 지원하지 못할 수 있습니다. 새로운 조합, 반사실적 조건, 예상하지 못한 사건, 환경 동역학 변화도 평가에 포함되어야 합니다.

피지컬 AI(Physical AI)에서는 시스템이 의미적 이해(Semantic Understanding)를 실제 물리적 결과와 연결해야 하기 때문에 멘탈 모델 개념이 특히 중요합니다. 로봇은 용기가 객체를 담을 수 있다는 것을 이해하고, 객체가 실제로 들어가는지를 예측하며, 용기에 도달 가능한지를 판단하고, 충돌 없는 조작(Collision-Free Manipulation)을 계획하며, 상호작용에서 예상하지 못한 결과가 발생하면 자신의 모델을 갱신해야 할 수 있습니다.

따라서 월드 모델(World Models), 파운데이션 모델(Foundation Models), 구조화된 기억(Structured Memory), 인과 추론(Causal Reasoning), 감각운동 학습(Sensorimotor Learning)은 점점 더 강력한 인공 멘탈 모델(Artificial Mental Models)을 구성하기 위한 상호보완적 메커니즘으로 볼 수 있습니다. 파운데이션 모델은 폭넓은 사전 지식을 제공하고, 월드 모델은 동역학을 예측하며, 기억은 경험을 보존하고, 지각은 이러한 구조를 현재 환경에 지속적으로 그라운딩(Grounding)합니다.

목표는 인간의 멘탈 모델을 정확하게 복제하는 것이 아닙니다. 인간의 표현은 생물학적 제약조건(Biological Constraints), 발달(Development), 문화(Culture), 인지 편향(Cognitive Biases)의 영향을 받는 반면, 공학 시스템은 생물학적 인지가 사용할 수 없는 명시적 데이터베이스, 시뮬레이터, 최적화 알고리즘(Optimization Algorithms), 고차원 학습 표현(High-Dimensional Learned Representations)을 사용할 수 있습니다. 중요한 목표는 구조화된 예측과 적응형 모델 수정이라는 기능적 원리를 유지하는 것입니다.

유능한 지능형 에이전트(Intelligent Agent)는 효율적인 추론이 가능할 만큼 단순하면서도 신뢰할 수 있는 예측과 행동을 지원할 만큼 풍부한 모델을 유지해야 합니다. 또한 모델의 어느 부분이 불확실한지를 파악하고, 현실이 기대와 달라지는 시점을 탐지하며, 필요한 경우 추가 정보를 수집하고, 유용한 기존 지식을 버리지 않으면서 표현을 갱신할 수 있어야 합니다.

멘탈 모델은 궁극적으로 지각(Perception)을 목적 지향적 행동(Purposeful Behavior)과 연결합니다. 관찰을 구조화된 해석으로 변환하고, 상태가 어떻게 변화할지에 대한 기대를 제공하며, 가상의 대안을 검토할 수 있게 하고, 행동을 실제로 실행하기 전에 평가할 수 있도록 합니다. 기억, 주의, 학습, 추론, 피드백과의 지속적인 상호작용을 통해 멘탈 모델은 인지가 즉각적인 감각 입력을 넘어 작동할 수 있는 메커니즘을 제공합니다.

인지과학(Cognitive Science)의 관점에서 멘탈 모델은 인간이 직접 눈앞에 존재하지 않는 시스템에 대해 어떻게 추론하고 실제 행동을 수행하기 전에 어떻게 계획할 수 있는지를 설명하는 데 도움을 줍니다. 인공지능(Artificial Intelligence)의 관점에서 동일한 일반 원리는 지속적 상태(Persistent State), 월드 모델, 시뮬레이션, 인과 구조(Causal Structure), 적응형 기억(Adaptive Memory)을 갖춘 에이전트의 개발을 촉진합니다. 이러한 능력은 반응형 계산(Reactive Computation)에서 예측적(Predictive), 숙고적(Deliberative), 그리고 점점 더 일반적인 지능(General Intelligence)으로 발전하는 핵심적인 연결 고리를 형성합니다.

##  

## 01.05 Cognitive Load

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

Cognitive load refers to the amount of mental effort required to process information, maintain relevant representations, reason about alternatives, and perform a task. Because attention and working memory are limited, cognitive systems cannot process unlimited information simultaneously. Performance therefore depends not only on task difficulty but also on how efficiently information is represented, organized, and presented.

Working memory is central to cognitive load because it temporarily holds information that is actively used during reasoning and action. When too many elements must be remembered, compared, or manipulated at the same time, working-memory capacity can be exceeded. Errors then become more likely, processing slows, and important information may be lost before it can contribute to a decision or action.

Cognitive load is not determined solely by the amount of information available. The structure of the information also matters. Ten unrelated facts may require more effort than a larger set organized into meaningful patterns. Cognitive systems reduce load by grouping related elements into chunks, using familiar concepts, and connecting new information with knowledge already stored in long-term memory.

Chunking allows several individual elements to be represented as a single meaningful unit. A novice may need to process each component of a technical system independently, while an expert can recognize the same components as one functional subsystem. Expertise therefore effectively expands usable cognitive capacity by compressing many details into structured representations that can be manipulated more efficiently.

Cognitive load theory often distinguishes intrinsic load, extraneous load, and learning-related processing. Intrinsic load arises from the inherent complexity and interdependence of the material itself. Extraneous load results from unnecessary complexity in presentation or task design, while productive processing supports the construction and refinement of useful schemas, concepts, and mental models.

Intrinsic cognitive load depends partly on element interactivity. A task becomes demanding when many pieces of information must be considered together because understanding one element depends on several others. Solving an unfamiliar control problem, for example, may require simultaneous reasoning about system state, constraints, dynamics, goals, and possible actions rather than considering each variable independently.

Expertise can change intrinsic load because information that is highly interactive for a novice may become a single familiar structure for an expert. A complex formula, machine configuration, or software architecture can initially require substantial working-memory resources, but repeated experience allows relationships to become encoded in long-term memory and retrieved as integrated patterns.

Extraneous cognitive load is generated when information is harder to process than necessary. Poorly organized interfaces, inconsistent terminology, irrelevant details, redundant instructions, unnecessary navigation, or scattered information can consume attention without contributing to the actual goal. Good design therefore attempts to remove processing demands that do not improve understanding or performance.

Split attention is a common source of unnecessary load. When related information is separated across several locations, users must repeatedly shift attention and mentally integrate the pieces. A diagram explained on another page, a warning disconnected from the relevant control, or a robot status distributed across several displays can increase effort even when each individual information source is understandable.

Redundancy can also increase cognitive load when multiple representations provide the same information without adding useful clarification. Repeating identical content in text, speech, and graphics may force a user to coordinate unnecessary inputs. However, carefully designed multimodal presentation can reduce load when different modalities provide complementary information rather than competing versions of the same content.

Multimodal processing is useful because visual and auditory information can sometimes distribute demands across partially distinct processing resources. Spoken guidance may accompany visual navigation, for example, without requiring the user to repeatedly look away from the environment. The benefit depends on coordination, timing, relevance, and whether the modalities truly complement each other.

Attention determines which information receives cognitive resources, so attentional demand is closely related to cognitive load. When many signals compete for priority, more effort is required to maintain focus and suppress distraction. Environments containing frequent interruptions, alarms, messages, moving objects, or competing goals can therefore increase load even when the primary task itself remains unchanged.

Task switching creates additional load because the cognitive system must repeatedly change goals, retrieve new rules, activate different representations, and suppress the previous task context. Switching from navigation to communication, then to diagnosis, and back to navigation may consume more resources than completing the same activities sequentially. Frequent interruptions can therefore reduce efficiency and increase recovery time.

Sustained high cognitive load can also degrade situation awareness. When most resources are consumed by immediate task demands, there may be insufficient capacity to monitor the broader environment, anticipate future events, or detect weak warning signals. A person may successfully solve a local problem while becoming unaware of changes occurring elsewhere in the system.

Overload occurs when processing demand exceeds the resources available for effective performance. Typical consequences include slower responses, forgotten information, reduced accuracy, narrow attention, poor prioritization, and simplified decision strategies. Under severe overload, individuals may focus only on the most obvious or urgent cues while neglecting information that would support better long-term decisions.

Underload can also create problems. Tasks that require very little active processing for long periods may reduce vigilance, engagement, and readiness to respond. An operator supervising highly reliable automation may have little to do until an unusual event occurs, yet the sudden transition from low demand to emergency intervention can require rapid reconstruction of situation awareness.

Effective system design therefore seeks an appropriate level of cognitive demand rather than simply minimizing all mental effort. Some processing is necessary for learning, understanding, monitoring, and decision making. The objective is to reduce avoidable burden while preserving the effort required to construct accurate mental models and maintain meaningful engagement with the task.

Learning itself changes cognitive load over time. Early practice often requires conscious attention to individual steps, rules, and relationships. With repeated experience, procedures become more automatic and schemas become more developed. Working-memory demand decreases, allowing attention to shift toward higher-level goals, unusual conditions, and strategic decisions rather than routine operations.

Automation can reduce cognitive load by performing repetitive perception, calculation, monitoring, or control tasks. Navigation assistance, automatic stabilization, anomaly detection, and decision support can free cognitive resources for more complex reasoning. However, poorly designed automation may simply move the burden from continuous control to difficult supervision and occasional high-stakes intervention.

Automation can also produce hidden cognitive costs when users must understand complex system modes, predict automated behavior, or determine when to intervene. If system state is unclear, operators may spend substantial effort reconstructing what the automation is doing and why. Mode confusion demonstrates that reducing physical workload does not necessarily reduce cognitive workload.

Trust influences cognitive load in human-machine interaction. When automation is reliable and understandable, users can delegate appropriate tasks without continuously checking every output. When trust is too low, excessive monitoring wastes attention, while excessive trust can reduce meaningful oversight. Appropriate trust therefore helps allocate limited cognitive resources between automation and human supervision.

Mental models strongly affect cognitive load because a coherent model reduces the effort required to interpret new information. If a system behaves according to understandable principles, users can predict its state and actions without memorizing every detail. Inconsistent behavior forces repeated reconstruction, increasing cognitive demand and making errors more likely.

Interface consistency similarly reduces processing effort. Controls, symbols, terminology, and feedback that follow stable conventions allow users to reuse learned expectations. When identical actions produce different outcomes or similar displays represent unrelated states, additional reasoning is required. Predictability therefore acts as a form of cognitive compression in human-system interaction.

External representations can reduce internal cognitive load by moving information from memory into the environment. Notes, diagrams, dashboards, maps, checklists, labels, and visual indicators allow people to inspect information instead of remembering it. External memory becomes especially valuable when tasks involve many variables, long procedures, or interruptions that make internal maintenance unreliable.

Checklists illustrate this principle by converting a memory-intensive task into a recognition-based process. Rather than recalling every required step, the user can verify visible items sequentially. The advantage is not that the checklist replaces expertise but that it protects working memory from routine demands, leaving more capacity for judgment when unusual conditions arise.

Visualization can also reduce load when spatial relationships, trends, or system structure would otherwise require complex mental reconstruction. A well-designed diagram can make dependencies visible directly, while an appropriate dashboard can reveal status differences without repeated calculation. Poor visualization, however, can increase load if it introduces unnecessary decoration, ambiguous encoding, or excessive density.

Cognitive load is highly dependent on context. The same information may be easy to process in a quiet environment but difficult under time pressure, physical movement, noise, fatigue, or competing tasks. Real-world cognition therefore reflects the interaction between task complexity, environmental conditions, individual expertise, emotional state, and available support mechanisms.

Time pressure increases load because fewer processing cycles are available for information gathering, comparison, and verification. Under severe time constraints, people rely more heavily on heuristics and familiar patterns. Such strategies can be efficient when experience is relevant, but they can also produce errors when the situation differs from previously learned conditions.

Uncertainty adds another form of cognitive demand. When information is incomplete or conflicting, several possible interpretations may need to be maintained simultaneously. The cognitive system must evaluate evidence, update confidence, and determine whether additional information is required. Representing uncertainty clearly can therefore reduce load by preventing users from having to infer reliability indirectly.

Decision complexity increases as the number of alternatives, constraints, and possible consequences grows. Evaluating many options requires maintaining comparisons in working memory and predicting outcomes under uncertainty. Hierarchical decision making reduces this burden by first eliminating broad classes of unsuitable options and then examining a smaller set of promising alternatives in greater detail.

Planning over long horizons creates similar demands because intermediate goals, dependencies, resources, and predicted future states must remain coordinated. Hierarchical planning reduces load by decomposing large goals into manageable subgoals. Instead of considering every possible low-level action at once, cognition can reason at an abstract level and expand details only when necessary.

Cognitive load also affects error detection. When working memory and attention are heavily occupied, fewer resources remain for monitoring one\'s own performance. Errors may therefore continue longer before being noticed. Metacognitive mechanisms that monitor uncertainty, workload, and confidence can help determine when a task should be slowed, simplified, delegated, or supported by additional information.

Stress interacts with cognitive load in complex ways. Moderate arousal can improve focus in some situations, but excessive stress may narrow attention, impair working memory, and promote rigid response patterns. Safety-critical systems should therefore avoid designs that require users to perform unfamiliar, cognitively complex procedures precisely when emergencies already increase stress and uncertainty.

Fatigue similarly reduces available cognitive resources. Long operating periods, sleep loss, repetitive monitoring, and sustained concentration can degrade attention and working memory. A task that is manageable under normal conditions may become effectively overloaded when the operator is fatigued. Cognitive workload assessment should therefore consider how performance changes across time rather than only under ideal conditions.

Individual differences also influence effective capacity. Experience, domain knowledge, age, training, strategy, and familiarity with the interface can change how demanding a task feels. A design optimized only for experts may overwhelm new users, while a system that explains every elementary step may unnecessarily burden experts. Adaptive presentation can help accommodate different levels of knowledge.

Instructional design uses cognitive-load principles to improve learning. Complex material can be segmented into manageable units, unnecessary information can be removed, important relationships can be highlighted, and prerequisites can be introduced before advanced concepts. The goal is to preserve intellectual complexity while reducing presentation demands that interfere with schema construction.

Worked examples can lower load during early learning by showing how a problem is solved rather than requiring novices to search blindly through many possibilities. As expertise develops, assistance can gradually be removed so that learners actively perform more of the reasoning themselves. This transition helps shift knowledge from externally supported procedures toward internalized problem-solving skills.

The expertise-reversal effect demonstrates that support beneficial to novices can become unnecessary or distracting for experts. Detailed explanations may reduce load for beginners but increase redundancy for experienced users. Effective learning systems therefore adapt guidance according to competence rather than assuming that one information format is optimal for everyone.

Cognitive load has direct relevance to cognitive architectures because intelligent systems must also operate under limited computational resources. Although machine limitations differ from biological working-memory limits, artificial agents face constraints involving compute, memory, bandwidth, latency, energy, and context length. Resource allocation therefore becomes an engineering analogue of cognitive-load management.

An AI system that processes every available observation with maximum computational depth may become too slow or energy intensive for real-time operation. Selective attention, hierarchical processing, sparse computation, event-driven sensing, and model routing can reduce unnecessary computation. These mechanisms prioritize information according to relevance, uncertainty, expected value, or safety.

Context management in language-based agents provides another analogy. An agent may possess more stored information than can fit efficiently into the active context used for reasoning. Retrieval systems must therefore select relevant memories, documents, goals, and previous actions. Poor selection can overload the context with irrelevant information and reduce reasoning quality even when more data is technically available.

Long prompts and large memory stores do not automatically improve intelligence. Excessive context can introduce distraction, conflicting information, and retrieval difficulty. Effective AI systems require mechanisms for compression, summarization, hierarchical memory, relevance filtering, and state abstraction so that the active reasoning workspace contains information appropriate to the current task.

Foundation models illustrate another computational tradeoff. Larger models can represent broader knowledge and perform more complex reasoning, but they also require greater memory, energy, and inference time. Practical systems therefore balance model capability with latency and resource constraints, often combining large high-level models with smaller specialized models for frequent or time-critical operations.

For robotics, cognitive-load-like resource management becomes particularly important because sensing, perception, localization, planning, communication, and control must often run simultaneously. An autonomous robot has finite compute and power, so processing all sensors at maximum fidelity may be impossible. Resources must be allocated dynamically according to task phase and environmental conditions.

During normal navigation, a robot may prioritize localization, obstacle detection, and path tracking. During manipulation, computational emphasis can shift toward object pose, depth, tactile feedback, and motion planning. If a safety hazard appears, collision avoidance may override other tasks. Such dynamic prioritization resembles attentional management under limited cognitive capacity.

Edge AI intensifies these constraints because onboard systems operate within strict power, thermal, memory, and latency limits. Efficient architectures may use low-cost models continuously and activate expensive perception or reasoning modules only when uncertainty, novelty, or risk increases. Cognitive-load concepts therefore provide a useful analogy for adaptive computational resource allocation.

World models can reduce computational demand by replacing repeated raw sensory reasoning with compact internal state representations. Instead of reconsidering every pixel or LiDAR point for every decision, the agent may reason over objects, relationships, dynamics, and uncertainties. Such abstraction reduces the effective dimensionality of planning while preserving information relevant to future actions.

However, compression creates risk if important details are discarded. A highly abstract representation may be efficient but fail to capture small obstacles, rare hazards, or physical constraints critical to execution. Intelligent systems therefore require mechanisms for moving between abstraction levels, using coarse representations for broad reasoning and detailed processing when precision becomes necessary.

Hierarchical architectures provide a natural solution. Slow, computationally expensive reasoning can operate at a high level, while fast specialized controllers handle immediate responses. Intermediate layers translate goals into tasks and monitor execution. This separation prevents every decision from requiring full high-level reasoning while preserving the ability to intervene when unexpected conditions arise.

Cognitive load is also important in human-robot interaction. A robot that repeatedly asks unnecessary questions, provides verbose status reports, or generates excessive warnings can consume human attention and reduce overall team performance. Communication should therefore deliver the right information at the right level of detail according to urgency, uncertainty, task phase, and user expertise.

An effective robot should recognize when human cognitive resources are likely to be limited. During emergencies or complex manual operations, additional noncritical requests should be delayed. During low-workload periods, the system can provide explanations, summaries, or planning information. Adaptive interaction treats human attention as a limited shared resource rather than an unlimited communication channel.

Alarm management provides an important practical example. If every minor deviation generates the same alert priority, users may become overwhelmed and begin ignoring notifications. Effective systems classify severity, aggregate related events, suppress redundant alarms, and escalate only when intervention is needed. The objective is to preserve sensitivity to critical events without creating continuous overload.

Shared autonomy can reduce cognitive burden by dividing responsibilities between humans and machines. The autonomous system handles routine sensing and control, while humans provide strategic goals, judgment, or intervention in ambiguous situations. Successful shared autonomy requires clear responsibility boundaries because uncertainty about who controls which function can itself create substantial cognitive load.

Situation-aware assistance can further reduce burden by anticipating what information is likely to be needed next. Instead of presenting every available option, the system can emphasize task-relevant controls, likely hazards, or predicted consequences. Such assistance should remain transparent so that users understand what has been filtered and can access additional detail when required.

Evaluating cognitive load is challenging because it is not directly observable. Researchers use behavioral performance, response time, error rates, secondary-task performance, subjective workload ratings, eye movements, physiological measurements, and other indicators. No single measure captures every aspect, so workload assessment usually benefits from combining multiple forms of evidence.

Subjective workload measures are valuable because individuals can report perceived mental demand, effort, frustration, and time pressure. However, perceived load does not always correspond directly to objective performance. An expert may perform accurately while reporting high effort, or a novice may underestimate task complexity. Evaluation should therefore distinguish experienced difficulty from observable performance degradation.

Behavioral measures provide complementary information. Increased response time, forgotten steps, repeated corrections, narrow search patterns, and higher error frequency may indicate growing load. Secondary-task methods estimate spare capacity by measuring how well a person can respond to an additional simple task while performing the primary activity.

Physiological indicators can provide further evidence but require careful interpretation. Pupil diameter, heart-rate variability, brain activity, or other measurements may correlate with workload under some conditions, yet they are also influenced by emotion, lighting, physical effort, and fatigue. Reliable assessment therefore requires context rather than treating physiological signals as direct measurements of cognitive load.

For AI systems, analogous monitoring can examine GPU utilization, memory pressure, latency, queue lengths, token usage, uncertainty, sensor processing demand, and planning complexity. Such measurements can allow the architecture to reduce resolution, switch models, summarize memory, postpone low-priority tasks, or allocate additional resources before real-time performance degrades.

Adaptive load management can therefore operate as a feedback loop. The system estimates current demand, compares it with available capacity, detects overload risk, changes processing strategy, and monitors whether performance recovers. Human-centered systems can similarly adjust information density, automation level, warning frequency, or task allocation according to estimated operator workload.

The concept of cognitive load ultimately illustrates that intelligence depends not only on possessing information but on controlling how much information is actively processed at a particular moment. Unlimited data without prioritization can reduce rather than improve performance. Efficient cognition requires selection, abstraction, memory organization, automation, and flexible allocation of limited resources.

For cognitive science, cognitive load explains many limitations and strategies observed in attention, working memory, reasoning, learning, and multitasking. For artificial intelligence, the same functional principle motivates selective computation, memory management, hierarchical reasoning, adaptive model activation, and resource-aware planning rather than processing every possible signal equally.

For Physical AI, this principle becomes especially important because robots must coordinate perception, prediction, planning, control, communication, and safety within finite onboard resources while interacting with humans who also have limited attention. Effective systems must therefore manage both computational load and human cognitive load as interconnected parts of the overall intelligence architecture.

The broader objective is not to eliminate cognitive or computational effort but to use limited capacity where it creates the greatest value. Information should be organized so that routine details require minimal resources while uncertainty, novelty, risk, and complex decisions receive deeper processing. Managing cognitive load in this way supports more reliable learning, reasoning, collaboration, adaptation, and intelligent action.

인지 부하(Cognitive Load)는 정보를 처리하고, 관련 표현을 유지하며, 대안을 추론하고, 작업을 수행하는 데 필요한 정신적 노력(Mental Effort)의 양을 의미합니다. 주의(Attention)와 작업 기억(Working Memory)은 제한적이기 때문에 인지 시스템은 무한한 정보를 동시에 처리할 수 없습니다. 따라서 성능은 작업 난이도뿐 아니라 정보가 얼마나 효율적으로 표현되고, 조직되고, 제시되는지에도 크게 영향을 받습니다.

작업 기억(Working Memory)은 현재 추론과 행동에 사용되는 정보를 일시적으로 유지하기 때문에 인지 부하의 핵심 요소입니다. 너무 많은 요소를 동시에 기억하고, 비교하고, 조작해야 하면 작업 기억 용량을 초과할 수 있습니다. 그 결과 오류 가능성이 높아지고, 처리 속도가 느려지며, 중요한 정보가 의사결정이나 행동에 활용되기 전에 사라질 수 있습니다.

인지 부하는 단순히 이용 가능한 정보의 양만으로 결정되지 않습니다. 정보의 구조(Structure) 역시 중요합니다. 서로 관련이 없는 열 개의 사실은 의미 있는 패턴으로 조직된 더 많은 양의 정보보다 처리하기 어려울 수 있습니다. 인지 시스템은 관련 요소를 청크(Chunks)로 묶고, 익숙한 개념을 사용하며, 새로운 정보를 장기 기억(Long-Term Memory)에 이미 저장된 지식과 연결함으로써 부하를 줄입니다.

청킹(Chunking)은 여러 개별 요소를 하나의 의미 있는 단위로 표현할 수 있도록 합니다. 초보자(Novice)는 기술 시스템의 각 구성요소를 개별적으로 처리해야 할 수 있지만, 전문가는 동일한 구성요소를 하나의 기능적 서브시스템(Functional Subsystem)으로 인식할 수 있습니다. 따라서 전문성(Expertise)은 많은 세부사항을 효율적으로 조작할 수 있는 구조화된 표현으로 압축하여 실질적으로 사용할 수 있는 인지 용량을 확장합니다.

인지 부하 이론(Cognitive Load Theory)은 일반적으로 내재적 부하(Intrinsic Load), 외재적 부하(Extraneous Load), 학습 관련 처리(Learning-Related Processing)를 구분합니다. 내재적 부하는 학습 내용 자체의 복잡성과 상호의존성에서 발생합니다. 외재적 부하는 불필요하게 복잡한 표현이나 작업 설계에서 발생하며, 생산적인 처리(Productive Processing)는 유용한 스키마(Schemas), 개념, 멘탈 모델(Mental Models)을 구성하고 개선하는 데 기여합니다.

내재적 인지 부하(Intrinsic Cognitive Load)는 부분적으로 요소 상호작용성(Element Interactivity)에 따라 달라집니다. 여러 정보 요소를 함께 고려해야 하고 하나의 요소를 이해하려면 다른 여러 요소를 동시에 이해해야 하는 경우 작업은 더 어려워집니다. 예를 들어 익숙하지 않은 제어 문제를 해결하려면 시스템 상태, 제약조건, 동역학(Dynamics), 목표, 가능한 행동을 각각 독립적으로 보기보다 동시에 고려해야 할 수 있습니다.

전문성(Expertise)은 내재적 부하도 변화시킬 수 있습니다. 초보자에게 높은 상호작용성을 가지는 정보가 전문가에게는 하나의 익숙한 구조로 인식될 수 있기 때문입니다. 복잡한 공식, 기계 구성 또는 소프트웨어 아키텍처(Software Architecture)는 처음에는 상당한 작업 기억 자원을 요구하지만, 반복 경험을 통해 관계가 장기 기억에 저장되면 하나의 통합된 패턴으로 빠르게 검색할 수 있습니다.

외재적 인지 부하(Extraneous Cognitive Load)는 정보를 필요 이상으로 어렵게 처리해야 할 때 발생합니다. 잘못 구성된 인터페이스(Interfaces), 일관되지 않은 용어, 관련 없는 세부사항, 중복된 지시, 불필요한 내비게이션(Navigation), 흩어진 정보는 실제 목표에 기여하지 않으면서 주의를 소비할 수 있습니다. 따라서 좋은 설계는 이해나 성능 향상에 기여하지 않는 처리 요구를 줄이는 것을 목표로 합니다.

분할 주의(Split Attention)는 불필요한 부하를 발생시키는 대표적인 원인입니다. 서로 관련된 정보가 여러 위치에 분리되어 있으면 사용자는 주의를 반복적으로 이동시키고 각각의 정보를 정신적으로 통합해야 합니다. 다른 페이지에 설명이 있는 다이어그램(Diagram), 관련 제어 장치와 떨어져 있는 경고, 여러 화면에 분산된 로봇 상태 정보는 각각 이해하기 쉬워도 전체 처리 부담을 증가시킬 수 있습니다.

중복성(Redundancy) 역시 여러 표현이 유용한 추가 설명 없이 동일한 정보를 반복할 경우 인지 부하를 증가시킬 수 있습니다. 동일한 내용을 텍스트, 음성, 그래픽으로 반복 제공하면 사용자가 불필요한 입력을 조정해야 할 수 있습니다. 그러나 서로 다른 양식(Modality)이 동일 내용을 경쟁적으로 반복하는 것이 아니라 상호보완적인 정보를 제공한다면 잘 설계된 멀티모달 표현(Multimodal Presentation)은 오히려 부하를 줄일 수 있습니다.

멀티모달 처리(Multimodal Processing)는 시각 정보와 청각 정보가 부분적으로 서로 다른 처리 자원에 요구를 분산할 수 있기 때문에 유용할 수 있습니다. 예를 들어 음성 안내는 사용자가 환경에서 시선을 반복적으로 이동하지 않으면서 시각적 내비게이션을 지원할 수 있습니다. 이러한 효과는 양식들이 실제로 서로를 보완하는지, 그리고 조정, 타이밍, 관련성이 적절한지에 따라 달라집니다.

주의(Attention)는 어떤 정보가 인지 자원을 받을지를 결정하므로 주의 요구(Attentional Demand)는 인지 부하와 밀접하게 관련됩니다. 많은 신호가 동시에 우선순위를 두고 경쟁하면 집중을 유지하고 방해 요소를 억제하는 데 더 많은 노력이 필요합니다. 잦은 중단, 경보, 메시지, 움직이는 객체, 경쟁하는 목표가 존재하는 환경에서는 주요 작업 자체가 변하지 않더라도 부하가 증가할 수 있습니다.

작업 전환(Task Switching)은 인지 시스템이 목표를 반복적으로 변경하고, 새로운 규칙을 검색하고, 다른 표현을 활성화하고, 이전 작업 문맥을 억제해야 하기 때문에 추가적인 부하를 발생시킵니다. 내비게이션에서 의사소통으로, 다시 진단으로, 이후 다시 내비게이션으로 전환하는 것은 동일한 작업들을 순차적으로 완료하는 것보다 더 많은 자원을 사용할 수 있습니다. 따라서 잦은 중단은 효율성을 감소시키고 회복 시간(Recovery Time)을 증가시킬 수 있습니다.

지속적으로 높은 인지 부하는 상황 자각(Situation Awareness)도 저하시킬 수 있습니다. 대부분의 자원이 즉각적인 작업 요구에 소비되면 더 넓은 환경을 모니터링하고, 미래 사건을 예상하거나, 약한 경고 신호를 탐지할 수 있는 여유가 부족해집니다. 그 결과 사람은 국소적인 문제는 성공적으로 해결하면서도 시스템의 다른 영역에서 발생하는 변화를 인식하지 못할 수 있습니다.

과부하(Overload)는 처리 요구가 효과적인 성능을 위해 이용 가능한 자원을 초과할 때 발생합니다. 일반적인 결과로는 느려진 반응, 정보 망각, 정확도 감소, 좁아진 주의, 낮은 우선순위 판단 능력, 단순화된 의사결정 전략이 나타납니다. 심각한 과부하에서는 장기적으로 더 좋은 결정을 지원하는 정보를 무시하고 가장 눈에 띄거나 긴급한 단서에만 집중할 수 있습니다.

과소부하(Underload) 역시 문제를 발생시킬 수 있습니다. 오랜 시간 동안 능동적인 처리를 거의 요구하지 않는 작업은 경계심(Vigilance), 몰입(Engagement), 대응 준비도를 감소시킬 수 있습니다. 매우 신뢰성 높은 자동화를 감독하는 운영자는 대부분의 시간 동안 할 일이 거의 없을 수 있지만, 이상 사건이 발생하면 낮은 요구 상태에서 갑자기 긴급 개입 상태로 전환되면서 상황 자각을 빠르게 재구성해야 할 수 있습니다.

따라서 효과적인 시스템 설계는 모든 정신적 노력을 단순히 최소화하는 것이 아니라 적절한 수준의 인지 요구를 유지하는 것을 목표로 합니다. 학습, 이해, 모니터링, 의사결정을 위해 일정 수준의 처리는 필요합니다. 핵심 목표는 정확한 멘탈 모델을 구성하고 작업에 의미 있게 참여하는 데 필요한 노력을 유지하면서 피할 수 있는 부담을 줄이는 것입니다.

학습(Learning)은 시간에 따라 인지 부하 자체를 변화시킵니다. 초기 연습 단계에서는 개별 단계, 규칙, 관계에 의식적으로 주의를 기울여야 하는 경우가 많습니다. 반복 경험이 축적되면 절차가 점차 자동화되고 스키마가 발달합니다. 작업 기억 요구가 감소하면서 주의 자원을 일상적인 작업보다 상위 수준 목표, 비정상 조건, 전략적 의사결정에 더 많이 사용할 수 있습니다.

자동화(Automation)는 반복적인 지각, 계산, 모니터링, 제어 작업을 대신 수행함으로써 인지 부하를 줄일 수 있습니다. 내비게이션 지원, 자동 안정화(Automatic Stabilization), 이상 탐지(Anomaly Detection), 의사결정 지원(Decision Support)은 더 복잡한 추론을 위한 인지 자원을 확보할 수 있습니다. 그러나 잘못 설계된 자동화는 지속적인 제어 부담을 어려운 감독과 드물지만 고위험의 개입 부담으로 단순히 이동시킬 수도 있습니다.

자동화된 시스템이 복잡한 동작 모드(System Modes)를 이해하고, 자동화의 행동을 예측하거나, 언제 개입해야 하는지를 판단하도록 요구하면 숨겨진 인지 비용(Hidden Cognitive Costs)이 발생할 수 있습니다. 시스템 상태가 명확하지 않으면 운영자는 자동화가 무엇을 하고 있으며 왜 그렇게 행동하는지를 다시 구성하는 데 상당한 노력을 사용해야 합니다. 모드 혼란(Mode Confusion)은 물리적 작업량 감소가 반드시 인지적 작업량 감소를 의미하지 않는다는 것을 보여줍니다.

신뢰(Trust)는 인간-기계 상호작용(Human-Machine Interaction)에서 인지 부하에 영향을 줍니다. 자동화가 신뢰할 수 있고 이해 가능하면 사용자는 모든 출력을 지속적으로 확인하지 않고 적절한 작업을 위임할 수 있습니다. 신뢰가 지나치게 낮으면 과도한 모니터링으로 주의를 낭비하고, 반대로 지나치게 높은 신뢰는 의미 있는 감독을 감소시킬 수 있습니다. 따라서 적절한 신뢰는 자동화와 인간 감독 사이에 제한된 인지 자원을 효과적으로 배분하도록 합니다.

멘탈 모델(Mental Models)은 일관된 모델이 새로운 정보를 해석하는 데 필요한 노력을 감소시키기 때문에 인지 부하에 큰 영향을 줍니다. 시스템이 이해 가능한 원칙에 따라 행동하면 사용자는 모든 세부사항을 기억하지 않고도 상태와 행동을 예측할 수 있습니다. 반대로 일관되지 않은 행동은 반복적인 재구성을 요구하여 인지 요구를 증가시키고 오류 가능성을 높입니다.

인터페이스 일관성(Interface Consistency) 역시 처리 노력을 감소시킵니다. 안정적인 규칙을 따르는 제어 장치, 기호, 용어, 피드백은 사용자가 이미 학습한 기대를 재사용할 수 있게 합니다. 동일한 행동이 서로 다른 결과를 발생시키거나 유사한 화면 표시가 서로 관련 없는 상태를 의미하면 추가적인 추론이 필요합니다. 따라서 예측 가능성(Predictability)은 인간-시스템 상호작용에서 일종의 인지적 압축(Cognitive Compression)으로 작동합니다.

외부 표현(External Representations)은 정보를 내부 기억에서 환경으로 이동시킴으로써 내부 인지 부하를 줄일 수 있습니다. 메모, 다이어그램, 대시보드(Dashboards), 지도, 체크리스트(Checklists), 라벨, 시각적 표시기는 사람이 정보를 기억하는 대신 직접 확인할 수 있게 합니다. 외부 기억(External Memory)은 특히 많은 변수, 긴 절차, 중단이 포함되어 내부 정보 유지가 불안정한 작업에서 중요합니다.

체크리스트는 기억에 크게 의존하는 작업을 인식 기반 과정(Recognition-Based Process)으로 전환한다는 점에서 이러한 원리를 잘 보여줍니다. 모든 필수 단계를 직접 회상하는 대신 사용자는 눈에 보이는 항목을 순차적으로 확인할 수 있습니다. 체크리스트의 장점은 전문성을 대체하는 것이 아니라 일상적인 기억 요구로부터 작업 기억을 보호하여 예외 상황에서 판단에 더 많은 용량을 사용할 수 있게 하는 것입니다.

시각화(Visualization)는 공간적 관계, 추세(Trends), 시스템 구조를 머릿속에서 복잡하게 재구성해야 하는 경우 인지 부하를 줄일 수 있습니다. 잘 설계된 다이어그램은 의존 관계를 직접 가시화할 수 있고, 적절한 대시보드는 반복 계산 없이 상태 차이를 보여줄 수 있습니다. 그러나 불필요한 장식, 모호한 인코딩(Ambiguous Encoding), 지나친 정보 밀도를 포함하는 나쁜 시각화는 오히려 부하를 증가시킬 수 있습니다.

인지 부하는 문맥(Context)에 크게 의존합니다. 동일한 정보라도 조용한 환경에서는 쉽게 처리할 수 있지만 시간 압박(Time Pressure), 신체 움직임, 소음, 피로, 경쟁 작업이 존재하면 어려워질 수 있습니다. 따라서 실제 세계의 인지는 작업 복잡성, 환경 조건, 개인의 전문성, 감정 상태(Emotional State), 이용 가능한 지원 메커니즘 사이의 상호작용을 반영합니다.

시간 압박은 정보 수집, 비교, 검증에 사용할 수 있는 처리 주기(Processing Cycles)를 줄이기 때문에 인지 부하를 증가시킵니다. 심한 시간 제약에서는 사람들이 휴리스틱(Heuristics)과 익숙한 패턴에 더 많이 의존합니다. 이러한 전략은 경험이 현재 상황에 적합하면 효율적일 수 있지만, 상황이 이전에 학습한 조건과 다르면 오류를 발생시킬 수 있습니다.

불확실성(Uncertainty)은 또 다른 형태의 인지 요구를 추가합니다. 정보가 불완전하거나 서로 충돌하면 여러 가능한 해석을 동시에 유지해야 할 수 있습니다. 인지 시스템은 증거를 평가하고, 신뢰도를 갱신하며, 추가 정보가 필요한지를 결정해야 합니다. 따라서 불확실성을 명확하게 표현하면 사용자가 신뢰성을 간접적으로 추론해야 하는 부담을 줄일 수 있습니다.

의사결정 복잡성(Decision Complexity)은 대안, 제약조건, 가능한 결과의 수가 증가할수록 커집니다. 많은 선택지를 평가하려면 작업 기억 안에서 비교 내용을 유지하고 불확실한 상태에서 결과를 예측해야 합니다. 계층적 의사결정(Hierarchical Decision Making)은 먼저 부적합한 대안의 큰 범주를 제거한 후 더 작은 유망한 후보 집합을 상세히 검토함으로써 이러한 부담을 줄입니다.

장기 시간 범위(Long Horizon)의 계획 역시 중간 목표, 의존성, 자원, 예상 미래 상태를 조정해야 하기 때문에 유사한 요구를 발생시킵니다. 계층적 계획(Hierarchical Planning)은 큰 목표를 관리 가능한 하위 목표로 분해하여 부하를 줄입니다. 모든 가능한 저수준 행동을 한 번에 고려하는 대신 인지는 추상적인 수준에서 먼저 추론하고 필요한 경우에만 세부사항을 확장할 수 있습니다.

인지 부하는 오류 탐지(Error Detection)에도 영향을 줍니다. 작업 기억과 주의가 크게 점유되어 있으면 자신의 성능을 모니터링할 자원이 줄어듭니다. 따라서 오류가 발생해도 발견되기까지 더 오랜 시간이 걸릴 수 있습니다. 불확실성, 작업 부하, 신뢰도를 모니터링하는 메타인지(Metacognitive) 메커니즘은 작업 속도를 줄이거나, 단순화하거나, 위임하거나, 추가 정보로 지원해야 할 시점을 판단하는 데 도움을 줄 수 있습니다.

스트레스(Stress)는 인지 부하와 복잡하게 상호작용합니다. 적당한 각성(Arousal)은 일부 상황에서 집중력을 높일 수 있지만 지나친 스트레스는 주의를 좁히고, 작업 기억을 저하시키며, 경직된 반응 패턴을 촉진할 수 있습니다. 따라서 안전 중요 시스템(Safety-Critical Systems)은 비상 상황 자체가 이미 스트레스와 불확실성을 높이는 시점에 익숙하지 않고 복잡한 절차를 정확하게 수행하도록 요구하는 설계를 피해야 합니다.

피로(Fatigue) 역시 이용 가능한 인지 자원을 감소시킵니다. 장시간 운용, 수면 부족, 반복적인 모니터링, 지속적인 집중은 주의와 작업 기억을 저하시킬 수 있습니다. 정상 조건에서는 관리 가능한 작업도 운영자가 피로하면 실질적으로 과부하 상태가 될 수 있습니다. 따라서 인지 작업량 평가는 이상적인 조건만이 아니라 시간에 따라 성능이 어떻게 변화하는지도 고려해야 합니다.

개인차(Individual Differences)도 실질적인 처리 용량에 영향을 줍니다. 경험, 도메인 지식(Domain Knowledge), 연령, 훈련, 전략, 인터페이스 친숙도에 따라 동일한 작업의 난이도가 다르게 느껴질 수 있습니다. 전문가만을 위해 최적화된 설계는 새로운 사용자를 압도할 수 있고, 모든 기초 단계를 설명하는 시스템은 전문가에게 불필요한 부담을 줄 수 있습니다. 적응형 정보 제시(Adaptive Presentation)는 서로 다른 지식 수준을 지원하는 데 도움을 줍니다.

교육 설계(Instructional Design)는 학습 효과를 높이기 위해 인지 부하 원리를 활용합니다. 복잡한 내용을 관리 가능한 단위로 분할하고, 불필요한 정보를 제거하며, 중요한 관계를 강조하고, 고급 개념보다 선행 지식을 먼저 제공할 수 있습니다. 목표는 지적 복잡성 자체를 제거하는 것이 아니라 스키마 형성을 방해하는 표현상의 요구를 줄이는 것입니다.

완성 예제(Worked Examples)는 초보자가 많은 가능성을 무작정 탐색하도록 요구하는 대신 문제 해결 방법을 직접 보여줌으로써 초기 학습의 부하를 줄일 수 있습니다. 전문성이 향상되면 이러한 지원을 점차 줄여 학습자가 더 많은 추론을 스스로 수행하게 할 수 있습니다. 이러한 전환은 외부에서 지원되는 절차를 내부화된 문제 해결 능력으로 변화시키는 데 도움을 줍니다.

전문성 역전 효과(Expertise-Reversal Effect)는 초보자에게 유익한 지원이 전문가에게는 불필요하거나 방해가 될 수 있음을 보여줍니다. 상세한 설명은 초보자의 부하를 줄이지만 숙련된 사용자에게는 중복성을 증가시킬 수 있습니다. 따라서 효과적인 학습 시스템은 하나의 정보 형식이 모든 사람에게 최적이라고 가정하기보다 능력 수준에 따라 안내를 조정해야 합니다.

인지 부하는 지능 시스템도 제한된 계산 자원(Computational Resources) 아래에서 작동해야 한다는 점에서 인지 아키텍처(Cognitive Architectures)와 직접적인 관련이 있습니다. 기계의 한계는 생물학적 작업 기억의 한계와 다르지만, 인공 에이전트도 연산량(Compute), 메모리, 대역폭(Bandwidth), 지연시간(Latency), 에너지, 컨텍스트 길이(Context Length)의 제약을 받습니다. 따라서 자원 할당(Resource Allocation)은 인지 부하 관리의 공학적 대응 개념이 됩니다.

AI 시스템이 이용 가능한 모든 관찰을 항상 최대 계산 깊이(Maximum Computational Depth)로 처리한다면 실시간 동작에 필요한 속도를 충족하지 못하거나 지나치게 많은 에너지를 사용할 수 있습니다. 선택적 주의(Selective Attention), 계층적 처리(Hierarchical Processing), 희소 계산(Sparse Computation), 이벤트 기반 감지(Event-Driven Sensing), 모델 라우팅(Model Routing)은 불필요한 계산을 줄일 수 있습니다. 이러한 메커니즘은 관련성, 불확실성, 기대 가치(Expected Value), 안전에 따라 정보의 우선순위를 결정합니다.

언어 기반 에이전트(Language-Based Agents)의 컨텍스트 관리(Context Management)는 또 다른 유사한 사례를 제공합니다. 에이전트는 능동적인 추론 컨텍스트에 효율적으로 포함할 수 있는 양보다 훨씬 많은 저장 정보를 가지고 있을 수 있습니다. 따라서 검색 시스템(Retrieval Systems)은 관련 기억, 문서, 목표, 이전 행동을 선택해야 합니다. 관련성이 낮은 정보를 잘못 선택하면 기술적으로 더 많은 데이터를 제공하더라도 컨텍스트가 과부하되어 추론 품질이 감소할 수 있습니다.

긴 프롬프트(Long Prompts)와 대규모 기억 저장소가 자동으로 지능을 향상시키는 것은 아닙니다. 지나친 컨텍스트는 방해 요소, 상충하는 정보, 검색 어려움을 증가시킬 수 있습니다. 효과적인 AI 시스템은 활성 추론 작업공간(Active Reasoning Workspace)에 현재 작업과 관련된 정보만 유지하기 위해 압축(Compression), 요약(Summarization), 계층적 기억(Hierarchical Memory), 관련성 필터링(Relevance Filtering), 상태 추상화(State Abstraction) 메커니즘을 필요로 합니다.

파운데이션 모델(Foundation Models)은 또 다른 계산적 트레이드오프(Computational Tradeoff)를 보여줍니다. 큰 모델은 더 광범위한 지식을 표현하고 복잡한 추론을 수행할 수 있지만 더 많은 메모리, 에너지, 추론 시간(Inference Time)을 요구합니다. 따라서 실제 시스템은 모델 능력과 지연시간 및 자원 제약 사이에서 균형을 유지하며, 자주 사용하거나 시간에 민감한 작업에는 작은 특화 모델을, 상위 수준의 복잡한 추론에는 큰 모델을 결합하는 경우가 많습니다.

로보틱스(Robotics)에서는 감지, 지각, 위치 추정(Localization), 계획, 통신, 제어가 동시에 실행되어야 하는 경우가 많기 때문에 인지 부하와 유사한 자원 관리가 특히 중요합니다. 자율 로봇은 제한된 계산 능력과 전력을 가지므로 모든 센서를 항상 최대 정밀도로 처리하는 것은 불가능할 수 있습니다. 따라서 작업 단계와 환경 조건에 따라 자원을 동적으로 할당해야 합니다.

일반적인 내비게이션 상황에서는 로봇이 위치 추정, 장애물 탐지(Obstacle Detection), 경로 추종(Path Tracking)을 우선할 수 있습니다. 조작(Manipulation) 과정에서는 객체 자세(Object Pose), 깊이(Depth), 촉각 피드백(Tactile Feedback), 모션 플래닝(Motion Planning)에 더 많은 계산을 할당할 수 있습니다. 안전 위험이 발생하면 충돌 회피(Collision Avoidance)가 다른 작업보다 우선할 수 있습니다. 이러한 동적 우선순위는 제한된 인지 용량 아래에서의 주의 관리와 유사합니다.

엣지 AI(Edge AI)는 온보드 시스템이 엄격한 전력, 열(Thermal), 메모리, 지연시간 제약 아래에서 작동하기 때문에 이러한 제한을 더욱 강화합니다. 효율적인 아키텍처는 계산 비용이 낮은 모델을 지속적으로 실행하고, 불확실성, 새로움(Novelty), 위험이 증가할 때만 비용이 높은 지각 또는 추론 모듈을 활성화할 수 있습니다. 따라서 인지 부하 개념은 적응형 계산 자원 할당(Adaptive Computational Resource Allocation)을 이해하는 유용한 비유를 제공합니다.

월드 모델(World Models)은 원시 감각 데이터를 반복적으로 직접 추론하는 대신 압축된 내부 상태 표현(Compact Internal State Representations)을 제공하여 계산 요구를 줄일 수 있습니다. 에이전트는 모든 의사결정마다 모든 픽셀이나 라이다(LiDAR) 포인트를 다시 처리하는 대신 객체, 관계, 동역학, 불확실성을 중심으로 추론할 수 있습니다. 이러한 추상화(Abstraction)는 미래 행동에 관련된 정보를 유지하면서 계획의 실질적인 차원(Dimensionality)을 낮춥니다.

그러나 압축은 중요한 세부정보가 제거될 경우 위험을 발생시킵니다. 매우 추상적인 표현은 효율적일 수 있지만 작은 장애물, 희귀 위험(Rare Hazards), 실제 실행에 중요한 물리적 제약조건을 포착하지 못할 수 있습니다. 따라서 지능 시스템은 넓은 수준의 추론에는 거친 표현(Coarse Representations)을 사용하고 정밀도가 필요할 때 상세 처리를 활성화하는 등 서로 다른 추상화 수준을 오갈 수 있어야 합니다.

계층적 아키텍처(Hierarchical Architectures)는 이에 대한 자연스러운 해결책을 제공합니다. 느리고 계산 비용이 높은 추론은 상위 수준에서 수행하고, 빠른 특화 제어기는 즉각적인 반응을 담당할 수 있습니다. 중간 계층은 목표를 작업으로 변환하고 실행 상태를 모니터링합니다. 이러한 분리는 모든 의사결정이 전체 상위 수준 추론을 필요로 하지 않게 하면서도 예상하지 못한 상황에서 상위 계층이 개입할 수 있도록 합니다.

인지 부하는 인간-로봇 상호작용(Human-Robot Interaction)에서도 중요합니다. 로봇이 불필요한 질문을 반복하거나, 지나치게 긴 상태 보고를 제공하거나, 과도한 경고를 생성하면 인간의 주의를 소비하고 전체 팀 성능을 떨어뜨릴 수 있습니다. 따라서 의사소통은 긴급성, 불확실성, 작업 단계, 사용자 전문성에 따라 적절한 정보와 적절한 세부 수준을 제공해야 합니다.

효과적인 로봇은 인간의 인지 자원이 제한될 가능성이 높은 시점을 인식해야 합니다. 비상 상황이나 복잡한 수동 작업 중에는 중요하지 않은 추가 요청을 지연할 수 있어야 합니다. 반대로 낮은 작업 부하 상태에서는 설명, 요약, 계획 정보를 제공할 수 있습니다. 적응형 상호작용(Adaptive Interaction)은 인간의 주의를 무한한 통신 채널이 아니라 제한된 공유 자원(Shared Resource)으로 취급합니다.

경보 관리(Alarm Management)는 중요한 실제 사례입니다. 모든 작은 이상이 동일한 우선순위의 경고를 발생시키면 사용자는 과부하 상태가 되어 알림을 무시하기 시작할 수 있습니다. 효과적인 시스템은 심각도(Severity)를 분류하고, 관련 사건을 통합하며, 중복 경보를 억제하고, 실제 개입이 필요한 경우에만 단계적으로 경보를 강화합니다. 목표는 지속적인 과부하 없이 중요 사건에 대한 민감성을 유지하는 것입니다.

공유 자율성(Shared Autonomy)은 인간과 기계 사이에 책임을 분배함으로써 인지 부담을 감소시킬 수 있습니다. 자율 시스템은 일상적인 감지와 제어를 담당하고, 인간은 전략적 목표, 판단, 모호한 상황에서의 개입을 제공합니다. 성공적인 공유 자율성을 위해서는 어떤 기능을 누가 제어하는지에 대한 경계가 명확해야 합니다. 제어 책임의 불확실성 자체가 상당한 인지 부하를 만들 수 있기 때문입니다.

상황 인식형 지원(Situation-Aware Assistance)은 다음에 필요한 정보가 무엇일지 예상함으로써 부담을 더욱 줄일 수 있습니다. 모든 가능한 옵션을 동시에 표시하는 대신 시스템은 작업 관련 제어, 예상 위험, 예측 결과를 강조할 수 있습니다. 이러한 지원은 무엇이 필터링되었는지를 사용자가 이해하고 필요한 경우 추가적인 세부 정보에 접근할 수 있도록 충분한 투명성을 유지해야 합니다.

인지 부하는 직접 관찰할 수 없기 때문에 평가가 어렵습니다. 연구자들은 행동 성능(Behavioral Performance), 반응 시간(Response Time), 오류율(Error Rates), 보조 작업 성능(Secondary-Task Performance), 주관적 작업량 평가(Subjective Workload Ratings), 안구 움직임(Eye Movements), 생리학적 측정(Physiological Measurements) 등을 사용합니다. 어느 하나의 측정도 모든 측면을 완전히 포착하지 못하므로 여러 형태의 증거를 결합하는 것이 일반적입니다.

주관적 작업량 측정(Subjective Workload Measures)은 개인이 인지한 정신적 요구, 노력, 좌절(Frustration), 시간 압박을 직접 보고할 수 있기 때문에 유용합니다. 그러나 인지된 부하가 항상 객관적 성능과 직접적으로 일치하는 것은 아닙니다. 전문가는 높은 노력을 보고하면서도 정확한 성능을 유지할 수 있고, 초보자는 작업의 복잡성을 과소평가할 수도 있습니다. 따라서 경험한 난이도와 실제 성능 저하를 구분해서 평가해야 합니다.

행동 측정(Behavioral Measures)은 보완적인 정보를 제공합니다. 반응 시간 증가, 단계 망각, 반복적인 수정, 좁아진 탐색 패턴, 오류 빈도 증가는 부하가 증가하고 있음을 나타낼 수 있습니다. 보조 작업 방법(Secondary-Task Methods)은 주요 작업을 수행하는 동안 추가적인 단순 작업에 얼마나 잘 반응하는지를 측정하여 남아 있는 여유 용량(Spare Capacity)을 추정합니다.

생리학적 지표(Physiological Indicators)는 추가적인 증거를 제공할 수 있지만 신중한 해석이 필요합니다. 동공 크기(Pupil Diameter), 심박 변이도(Heart-Rate Variability), 뇌 활동(Brain Activity) 등의 측정값은 일부 조건에서 작업 부하와 상관될 수 있지만 감정, 조명, 신체적 노력, 피로의 영향도 받습니다. 따라서 생리 신호를 인지 부하의 직접적인 측정값으로 취급하기보다 문맥과 함께 해석해야 합니다.

AI 시스템에서도 이와 유사하게 GPU 사용률(GPU Utilization), 메모리 압력(Memory Pressure), 지연시간, 큐 길이(Queue Lengths), 토큰 사용량(Token Usage), 불확실성, 센서 처리 요구, 계획 복잡성을 모니터링할 수 있습니다. 이러한 측정을 기반으로 실시간 성능이 저하되기 전에 해상도를 낮추거나, 모델을 전환하거나, 기억을 요약하거나, 낮은 우선순위 작업을 연기하거나, 추가 자원을 할당할 수 있습니다.

따라서 적응형 부하 관리(Adaptive Load Management)는 피드백 루프(Feedback Loop)로 동작할 수 있습니다. 시스템은 현재 요구를 추정하고, 이용 가능한 용량과 비교하고, 과부하 위험을 탐지하고, 처리 전략을 변경한 후 성능이 회복되는지를 모니터링합니다. 인간 중심 시스템에서도 예상 운영자 작업량에 따라 정보 밀도, 자동화 수준, 경고 빈도, 작업 분배(Task Allocation)를 조절할 수 있습니다.

인지 부하 개념은 궁극적으로 지능이 단순히 많은 정보를 보유하는 것이 아니라 특정 순간에 얼마나 많은 정보를 능동적으로 처리할지를 제어하는 능력에도 의존한다는 것을 보여줍니다. 우선순위가 없는 무제한 데이터는 성능을 향상시키기보다 오히려 감소시킬 수 있습니다. 효율적인 인지를 위해서는 선택(Selection), 추상화, 기억 조직(Memory Organization), 자동화, 제한된 자원의 유연한 할당이 필요합니다.

인지과학(Cognitive Science)의 관점에서 인지 부하는 주의, 작업 기억, 추론, 학습, 멀티태스킹(Multitasking)에서 관찰되는 여러 한계와 전략을 설명합니다. 인공지능(Artificial Intelligence)의 관점에서는 모든 가능한 신호를 동일하게 처리하는 대신 선택적 계산(Selective Computation), 기억 관리(Memory Management), 계층적 추론(Hierarchical Reasoning), 적응형 모델 활성화(Adaptive Model Activation), 자원 인식 계획(Resource-Aware Planning)을 활용하도록 합니다.

피지컬 AI(Physical AI)에서는 로봇이 제한된 온보드 자원 안에서 지각, 예측, 계획, 제어, 의사소통, 안전을 동시에 조정해야 하고 함께 상호작용하는 인간 역시 제한된 주의를 가지기 때문에 이러한 원리가 특히 중요합니다. 따라서 효과적인 시스템은 계산 부하(Computational Load)와 인간 인지 부하(Human Cognitive Load)를 전체 지능 아키텍처의 상호연결된 요소로 함께 관리해야 합니다.

더 넓은 목표는 인지적 또는 계산적 노력을 제거하는 것이 아니라 제한된 용량을 가장 큰 가치를 생성하는 곳에 사용하는 것입니다. 일상적인 세부사항은 최소한의 자원으로 처리하고, 불확실성, 새로움(Novelty), 위험(Risk), 복잡한 의사결정에는 더 깊은 처리를 할당하도록 정보를 구성해야 합니다. 이러한 방식의 인지 부하 관리는 더 신뢰할 수 있는 학습, 추론, 협업(Collaboration), 적응, 지능적 행동(Intelligent Action)을 지원합니다.

##  

## 01.06 Human Error and Reliability [w/Code]

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

Human error refers to actions, judgments, interpretations, or omissions that lead to outcomes different from what was intended or required. Reliability describes the probability that a person, team, or human-machine system will perform a required function correctly under specified conditions. Cognitive science studies error not simply as individual failure, but as the result of interactions among people, tasks, environments, procedures, tools, and organizational systems.

Human performance is inherently variable because attention, memory, perception, judgment, and motor control operate under limited resources. Even skilled people can make mistakes when information is incomplete, tasks are unfamiliar, workload is high, or environmental conditions change rapidly. Reliability engineering therefore assumes that errors are possible and designs systems so that individual mistakes do not automatically produce serious consequences.

Errors can arise during perception when relevant information is not detected, is misinterpreted, or is confused with similar signals. Poor visibility, ambiguous displays, weak alarms, sensory overload, or divided attention can prevent a person from recognizing important events. Because perception is selective rather than complete, system reliability depends partly on ensuring that critical information is salient, understandable, and available at the correct time.

Attention failures are another major source of error. A person may focus intensely on one problem while failing to notice a different hazard, or may become distracted by interruptions and lose track of the current task. Inattentional blindness, task switching, and competing priorities demonstrate that simply presenting information does not guarantee that it will receive sufficient cognitive processing.

Memory limitations can produce omissions, sequence errors, or incorrect recall. Working memory can maintain only a limited amount of active information, making long procedures and interrupted tasks particularly vulnerable. Prospective memory is also important because people must remember actions that need to be performed later, such as completing a final inspection or restoring a system after maintenance.

External aids reduce memory-related errors by transferring information from internal memory into the environment. Checklists, procedures, labels, status indicators, logs, and automated reminders allow users to recognize required actions rather than recall everything unaided. These tools are especially valuable when tasks are infrequent, complex, interrupted, or performed under time pressure.

Reasoning and decision errors occur when information is interpreted incorrectly or unsuitable alternatives are selected. People may rely on incomplete mental models, underestimate uncertainty, overvalue recent evidence, or choose familiar actions that do not match the current situation. Reliability therefore depends on supporting accurate situation understanding rather than assuming that access to information alone guarantees good decisions.

A useful distinction separates slips and lapses from mistakes. Slips occur when the intended goal is appropriate but execution is incorrect, such as pressing the wrong control. Lapses involve failures of memory, such as forgetting a required step. Mistakes occur when the plan or decision itself is wrong because the situation has been misunderstood or an inappropriate rule has been selected.

Skill-based behavior relies on highly practiced routines that usually require little conscious attention. Such behavior is efficient but vulnerable to slips when similar actions or controls are confused. A person may perform a familiar sequence automatically even though the current situation requires a deviation. Good interface design reduces opportunities for habitual actions to produce unintended effects.

Rule-based behavior occurs when familiar procedures or learned rules are applied to recognized situations. Errors can occur if the wrong rule is selected, if conditions are misclassified, or if a normally useful procedure is applied outside its valid range. Clear criteria, consistent terminology, and feedback about system state help users determine whether a rule remains appropriate.

Knowledge-based behavior becomes necessary when no familiar procedure adequately describes the situation. People must construct a mental model, generate hypotheses, reason about causes, and evaluate possible actions. This mode is flexible but cognitively demanding, making performance more sensitive to workload, uncertainty, expertise, time pressure, and the quality of available information.

Violations differ from unintentional errors because a person deliberately departs from a rule, procedure, or expected practice. Violations may arise from time pressure, poorly designed procedures, conflicting goals, organizational norms, or the belief that a shortcut is necessary to complete the task. Reliability analysis therefore examines why deviations become attractive rather than treating every violation as simple misconduct.

Human reliability is strongly influenced by workload. Excessive cognitive load can narrow attention, slow reasoning, increase memory failures, and encourage simplified strategies. Very low workload can also reduce vigilance and readiness. Reliable system design seeks a manageable operating region where people remain sufficiently engaged without being overwhelmed by unnecessary information or simultaneous demands.

Fatigue can significantly reduce reliability by degrading attention, reaction time, working memory, and judgment. Long shifts, repetitive monitoring, insufficient rest, and sustained mental effort can gradually increase error probability. Because the effects may emerge slowly, operators may not recognize their own performance decline accurately, making organizational scheduling and workload management important safety mechanisms.

Stress and time pressure can modify decision strategies. Moderate urgency may increase focus, while extreme pressure can narrow attention and encourage rapid reliance on familiar responses. In emergencies, people may overlook secondary information, repeat unsuccessful actions, or become fixated on an incorrect diagnosis. Procedures and interfaces should therefore remain usable when cognitive resources are already reduced.

Situation awareness is critical for reliable performance. A person must perceive important elements, understand their significance, and anticipate how the situation may develop. Failures at any of these stages can produce incorrect actions even when technical skills are strong. Reliable systems help users maintain an integrated understanding of system state, hazards, goals, constraints, and expected future changes.

Mental models strongly influence situation awareness because users interpret information through assumptions about how a system works. If a model is incomplete or outdated, normal observations may be misunderstood and abnormal behavior may be explained incorrectly. Transparent system behavior, training, simulation, and meaningful feedback help users construct models that support more accurate prediction.

Interface design can either prevent or create errors. Controls that look similar, hidden system states, inconsistent commands, unclear terminology, or weak feedback increase the probability of incorrect action. Error-resistant interfaces make important distinctions visible, constrain impossible actions where practical, confirm high-risk commands, and provide immediate feedback showing whether intended actions were actually executed.

Forcing functions are design mechanisms that prevent an unsafe action or require specific conditions before an action can proceed. Interlocks, keyed connectors, confirmation sequences, and physical constraints can eliminate certain error paths entirely. Such mechanisms are valuable when the consequence of a mistake is severe and relying solely on memory or attention would be insufficient.

Error tolerance addresses situations where prevention cannot be guaranteed. A resilient system assumes that mistakes will sometimes occur and provides ways to detect, contain, and recover from them. Undo functions, safe defaults, redundancy, graceful degradation, fault isolation, and recovery procedures reduce the probability that a small human error will escalate into a system-level failure.

Feedback is essential for error detection. People need timely information about whether an action was accepted, what state changed, and whether the outcome matches expectations. Delayed or ambiguous feedback allows incorrect assumptions to persist. Effective feedback closes the perception-action loop by making consequences visible enough for users to correct deviations before they become dangerous.

Alarms are intended to attract attention to abnormal conditions, but poorly designed alarm systems can reduce reliability. Excessive alarms create overload and alarm fatigue, while frequent false alarms reduce trust. Effective alarm management prioritizes severity, suppresses redundant notifications, groups related events, and communicates the action or interpretation required rather than simply announcing that something changed.

Automation can improve reliability by performing repetitive calculations, monitoring, stabilization, and control with greater consistency than humans. However, automation also creates new failure modes involving mode confusion, overreliance, poor transparency, and loss of manual skill. Human reliability therefore depends not only on whether automation works, but on whether people understand its state, limits, and expected behavior.

Automation bias occurs when people accept automated recommendations without sufficient independent evaluation. If a system is usually correct, users may stop searching for contradictory evidence. The opposite problem occurs when unreliable automation creates excessive distrust and unnecessary manual verification. Appropriate reliance requires calibrated trust based on understandable system capability and uncertainty.

Out-of-the-loop performance problems can appear when automation handles a task for long periods and suddenly requires human intervention. Operators may have lost detailed situation awareness or may need time to understand what happened before taking control. Reliable automation should therefore maintain meaningful human engagement and provide concise state reconstruction when responsibility must be transferred.

Human-machine teaming can improve reliability when responsibilities are allocated according to complementary strengths. Machines are effective at repetitive monitoring, precise calculation, and high-speed data processing, while humans remain valuable for contextual reasoning, unusual situations, ethical judgment, and flexible goal interpretation. Effective allocation should change dynamically as task conditions and confidence change.

Redundancy can improve reliability when independent people, sensors, models, or procedures verify critical outcomes. However, redundant elements are useful only when failures are not strongly correlated. Two operators using the same incorrect assumption may produce the same error. Diversity of information sources, methods, and perspectives can therefore be more valuable than simple duplication.

Cross-checking is an important team reliability mechanism. A second person can confirm calculations, procedures, or system states before high-risk actions are executed. Effective cross-checking requires clear responsibility and psychological permission to challenge assumptions. If organizational hierarchy discourages questioning, nominal redundancy may exist without providing meaningful protection.

Communication failures frequently contribute to human error. Ambiguous language, incomplete handovers, inconsistent terminology, and unspoken assumptions can cause different people to maintain incompatible mental models. Structured communication techniques improve reliability by explicitly identifying critical information, responsibilities, uncertainties, and confirmation of shared understanding.

Team reliability therefore depends on shared situation awareness and shared mental models. Members do not need identical knowledge, but they should understand overall goals, role boundaries, system state, and expected actions of others. When these representations become misaligned, individually reasonable decisions can combine into unsafe system behavior.

Organizational conditions strongly influence individual reliability. Staffing levels, training quality, maintenance policy, scheduling, incentive structures, supervision, and management priorities shape the environment in which decisions are made. A system that repeatedly places people under conflicting goals or unrealistic deadlines can create predictable conditions for error even when individual workers are highly capable.

The concept of latent conditions captures weaknesses that exist before an accident occurs. Poor procedures, confusing interfaces, inadequate training, deferred maintenance, or organizational communication gaps may remain unnoticed until combined with an active error. Reliability analysis therefore examines the entire chain of contributing conditions instead of searching only for the final person who made a mistake.

A just culture supports reliability by distinguishing intentional reckless behavior from reasonable mistakes and system-induced errors. If every error is punished, people may hide near misses and reduce organizational learning. If all behavior is excused, accountability disappears. Effective safety cultures encourage reporting while maintaining clear standards for deliberate and unacceptable risk-taking.

Near misses are especially valuable because they reveal weaknesses without producing the full consequences of an accident. Analyzing near misses can identify recurring error patterns, poor interfaces, inadequate procedures, and unexpected interactions. Organizations that collect and learn from such events can improve reliability before equivalent failures cause serious harm.

Root-cause analysis should therefore move beyond identifying immediate operator actions. Asking why the action appeared reasonable at the time often reveals missing information, misleading feedback, workload, training limitations, poor procedures, or organizational pressure. Understanding the context of behavior produces more effective corrective actions than simply instructing people to be more careful.

Human reliability analysis attempts to estimate the probability and consequences of human actions within larger technical systems. Methods may examine task complexity, environmental conditions, dependencies, recovery opportunities, and performance-shaping factors. Exact numerical prediction is difficult because human behavior is context dependent, but structured analysis still helps identify high-risk tasks and weak defenses.

Performance-shaping factors include workload, experience, training, interface quality, time pressure, fatigue, environmental conditions, procedure design, teamwork, and organizational support. These factors modify the probability that a task will be performed correctly. Reliability improvement therefore focuses on changing conditions around behavior rather than expecting identical performance under every circumstance.

Training improves reliability when it develops not only procedural memory but also accurate mental models and recovery strategies. Memorizing normal procedures may be insufficient for rare abnormal events. Simulation and scenario-based training allow people to experience unusual conditions, practice diagnosis, recognize failure signatures, and learn how systems behave when standard assumptions no longer apply.

Adaptive expertise is particularly valuable in complex systems. Routine expertise enables efficient execution under familiar conditions, while adaptive expertise allows people to recognize when familiar procedures are inadequate and construct new solutions. Reliable organizations need both capabilities because excessive dependence on fixed procedures can become dangerous when situations fall outside anticipated scenarios.

Checklists and procedures should support cognition rather than replace judgment. Overly detailed procedures can become difficult to use under pressure, while vague procedures provide insufficient guidance. Effective procedures organize critical steps, decision points, warnings, and verification actions while leaving appropriate flexibility for conditions that cannot be predicted completely.

Error recovery is an essential component of reliability because many mistakes are reversible if detected early. Systems should make errors visible, preserve safe states, and provide straightforward recovery paths. Training should also include recovery rather than focusing only on perfect execution, because operators who understand how to recognize and correct deviations can prevent escalation.

Resilience extends reliability beyond preventing expected failures. A resilient system can monitor changing conditions, respond to unexpected events, recover from disruption, and adapt its behavior while preserving essential functions. Human flexibility is often central to resilience because people can reinterpret goals and improvise when predefined procedures or automated responses become inadequate.

For artificial intelligence, human error research offers important lessons about designing reliable autonomous systems. AI models also operate with incomplete information, limited computational resources, uncertain predictions, and imperfect internal representations. Reliability therefore requires confidence estimation, failure detection, redundancy, feedback, recovery mechanisms, and monitoring rather than assuming that high benchmark accuracy guarantees safe operation.

AI systems can produce errors analogous to human perceptual or reasoning failures. A perception model may miss an object, a language model may infer an incorrect relationship, or a planner may choose an unsafe action because its world model is inaccurate. Reliable architecture should detect when uncertainty increases and prevent uncertain outputs from directly becoming high-risk actions.

Human-AI systems introduce coupled failure modes in which machine errors influence human decisions and human behavior influences machine performance. An incorrect AI recommendation may become more dangerous if an operator trusts it excessively, while poor human input may cause a model to operate outside its intended conditions. Reliability must therefore be evaluated at the combined system level.

Explainability can support reliability when it helps users understand important evidence, uncertainty, assumptions, and system limitations. Explanations should improve the user\'s mental model rather than merely justify an output after the fact. When explanations are plausible but disconnected from actual system behavior, they can increase rather than reduce the risk of inappropriate trust.

For robotics and Physical AI, reliability is inseparable from the perception-action loop. A small sensing error can affect localization, planning, control, and physical interaction, producing new observations that further amplify the initial mistake. Closed-loop monitoring, safety constraints, collision checking, uncertainty-aware planning, and rapid recovery are therefore essential for preventing error propagation.

Physical interaction also makes consequences more immediate. A conversational error may be corrected with another message, while an incorrect robot motion can damage equipment or injure a person. Physical AI therefore requires layered safeguards in which learned models operate within geometric, dynamic, operational, and safety constraints that remain effective even when high-level reasoning is incorrect.

World models can improve reliability by allowing an agent to predict consequences before execution, but incorrect models can also create confident planning errors. Reliable agents should compare predicted and observed outcomes continuously, track model uncertainty, shorten planning horizons when confidence decreases, and return to safer behavior when the environment falls outside learned assumptions.

Human oversight remains important for many high-consequence autonomous systems, but oversight must itself be designed realistically. A human cannot reliably monitor hundreds of low-value events while remaining ready for an extremely rare emergency. Effective supervision requires prioritization, meaningful alerts, transparent state information, and sufficient time for the operator to understand and respond.

Reliability should therefore be considered as an architectural property rather than an attribute of a single component. Sensors, software, AI models, interfaces, procedures, operators, organizations, and recovery mechanisms collectively determine whether a system continues functioning safely. Improving only one element may have little effect if other parts continue creating predictable failure paths.

Evaluation should include nominal performance, abnormal conditions, rare events, degraded sensors, conflicting information, interruptions, workload changes, and recovery after error. Systems that perform perfectly in routine conditions may remain fragile when assumptions are violated. Reliability testing must therefore intentionally explore situations where humans and machines are likely to become confused or uncertain.

The central principle is that error cannot be eliminated completely from complex intelligent systems. The practical objective is to reduce error probability, detect deviations early, prevent propagation, support recovery, and learn from failures. Reliable systems accept human and machine limitations as design constraints rather than assuming that perfect attention, memory, reasoning, or prediction can always be achieved.

For cognitive science, human error reveals how perception, attention, memory, mental models, workload, and decision making interact under realistic constraints. For AI engineering, the same lessons motivate architectures built around uncertainty, monitoring, redundancy, graceful degradation, and recovery. Reliability emerges when cognition, technology, procedures, and organizational design work together to manage inevitable variability.

For future autonomous and Physical AI systems, the strongest approach is therefore not to replace supposedly unreliable humans with supposedly perfect machines. Both humans and artificial systems have characteristic strengths and failure modes. High reliability is achieved by understanding these limitations, allocating responsibility appropriately, and designing layered systems in which errors are detected, contained, corrected, and converted into opportunities for learning.

인적 오류(Human Error)는 의도하거나 요구된 결과와 다른 결과를 초래하는 행동, 판단, 해석 또는 누락을 의미합니다. 신뢰성(Reliability)은 사람, 팀 또는 인간-기계 시스템(Human-Machine System)이 지정된 조건에서 요구되는 기능을 올바르게 수행할 확률을 나타냅니다. 인지과학(Cognitive Science)은 오류를 단순한 개인의 실패가 아니라 사람, 작업, 환경, 절차, 도구, 조직 시스템 사이의 상호작용 결과로 연구합니다.

인간의 수행(Human Performance)은 주의(Attention), 기억(Memory), 지각(Perception), 판단(Judgment), 운동 제어(Motor Control)가 제한된 자원 아래에서 작동하기 때문에 본질적으로 가변적입니다. 숙련된 사람도 정보가 불완전하거나, 작업이 익숙하지 않거나, 작업 부하가 높거나, 환경 조건이 빠르게 변화하면 실수할 수 있습니다. 따라서 신뢰성 공학(Reliability Engineering)은 오류 가능성을 전제로 하며 개별 실수가 곧바로 심각한 결과로 이어지지 않도록 시스템을 설계합니다.

관련 정보를 탐지하지 못하거나, 잘못 해석하거나, 유사한 신호와 혼동할 경우 지각 단계에서 오류가 발생할 수 있습니다. 낮은 가시성, 모호한 디스플레이, 약한 경보, 감각 과부하(Sensory Overload), 분산된 주의(Divided Attention)는 중요한 사건을 인식하지 못하게 할 수 있습니다. 지각은 완전한 것이 아니라 선택적이므로 시스템 신뢰성은 중요 정보가 적절한 시점에 명확하고 이해 가능한 형태로 제공되는지에 부분적으로 의존합니다.

주의 실패(Attention Failures)는 또 다른 주요 오류 원인입니다. 사람은 하나의 문제에 강하게 집중하면서 다른 위험을 인식하지 못할 수 있으며, 방해나 중단으로 인해 현재 수행 중인 작업의 흐름을 놓칠 수도 있습니다. 부주의 맹시(Inattentional Blindness), 작업 전환(Task Switching), 경쟁하는 우선순위는 단순히 정보를 제공하는 것만으로는 충분한 인지 처리가 이루어진다고 보장할 수 없음을 보여줍니다.

기억의 한계(Memory Limitations)는 누락, 순서 오류, 잘못된 회상 등을 발생시킬 수 있습니다. 작업 기억(Working Memory)은 제한된 양의 활성 정보만 유지할 수 있기 때문에 긴 절차와 중단된 작업은 특히 취약합니다. 미래 기억(Prospective Memory)도 중요하며, 사람은 최종 검사 완료나 유지보수 후 시스템 복원과 같이 나중에 수행해야 할 행동을 기억해야 합니다.

외부 보조 수단(External Aids)은 정보를 내부 기억에서 환경으로 이전하여 기억 관련 오류를 줄입니다. 체크리스트(Checklists), 절차서, 라벨, 상태 표시기(Status Indicators), 로그(Logs), 자동 알림은 사용자가 모든 내용을 스스로 기억하는 대신 필요한 행동을 확인할 수 있게 합니다. 이러한 도구는 작업 빈도가 낮거나, 복잡하거나, 중단이 발생하거나, 시간 압박이 있는 경우 특히 유용합니다.

추론 및 의사결정 오류(Reasoning and Decision Errors)는 정보를 잘못 해석하거나 적절하지 않은 대안을 선택할 때 발생합니다. 사람은 불완전한 멘탈 모델(Mental Models)에 의존하거나, 불확실성을 과소평가하거나, 최근 증거를 지나치게 중요하게 평가하거나, 현재 상황에 적합하지 않은 익숙한 행동을 선택할 수 있습니다. 따라서 신뢰성은 단순한 정보 접근만으로 좋은 의사결정을 보장한다고 가정하기보다 정확한 상황 이해를 지원하는 데 달려 있습니다.

유용한 구분 방법으로 실수(Slips)와 망각(Lapses)을 판단 오류(Mistakes)와 구분할 수 있습니다. 실수는 의도한 목표는 적절하지만 실행이 잘못된 경우로, 예를 들어 잘못된 제어 장치를 누르는 경우입니다. 망각은 필요한 단계를 잊는 것과 같은 기억 실패를 의미합니다. 판단 오류는 상황을 잘못 이해하거나 부적절한 규칙을 선택하여 계획이나 결정 자체가 잘못된 경우입니다.

숙련 기반 행동(Skill-Based Behavior)은 일반적으로 의식적인 주의를 거의 필요로 하지 않는 고도로 연습된 루틴에 의존합니다. 이러한 행동은 효율적이지만 유사한 행동이나 제어 장치를 혼동할 경우 실수에 취약합니다. 현재 상황에서는 다른 행동이 필요함에도 사람이 익숙한 순서를 자동으로 수행할 수 있습니다. 좋은 인터페이스 설계(Interface Design)는 습관적인 행동이 의도하지 않은 결과를 만들어낼 가능성을 줄입니다.

규칙 기반 행동(Rule-Based Behavior)은 익숙한 절차나 학습된 규칙을 인식된 상황에 적용할 때 발생합니다. 잘못된 규칙을 선택하거나, 조건을 잘못 분류하거나, 일반적으로 유용한 절차를 유효 범위를 벗어난 상황에 적용하면 오류가 발생할 수 있습니다. 명확한 기준, 일관된 용어, 시스템 상태에 대한 피드백은 사용자가 해당 규칙이 여전히 적절한지 판단하도록 지원합니다.

지식 기반 행동(Knowledge-Based Behavior)은 익숙한 절차로 현재 상황을 충분히 설명할 수 없을 때 필요합니다. 사람은 멘탈 모델을 구성하고, 가설(Hypotheses)을 생성하며, 원인을 추론하고, 가능한 행동을 평가해야 합니다. 이러한 방식은 유연하지만 인지적으로 많은 자원을 요구하므로 작업 부하, 불확실성, 전문성, 시간 압박, 이용 가능한 정보의 품질에 더욱 민감합니다.

위반(Violations)은 사람이 규칙, 절차 또는 기대되는 관행에서 의도적으로 벗어난다는 점에서 비의도적 오류와 다릅니다. 위반은 시간 압박, 잘못 설계된 절차, 상충하는 목표, 조직적 규범(Organizational Norms), 또는 작업을 완료하려면 지름길이 필요하다는 판단에서 발생할 수 있습니다. 따라서 신뢰성 분석은 모든 위반을 단순한 잘못된 행동으로 간주하기보다 왜 그러한 일탈이 매력적인 선택이 되었는지를 분석합니다.

인간 신뢰성(Human Reliability)은 작업 부하(Workload)의 영향을 크게 받습니다. 과도한 인지 부하(Cognitive Load)는 주의를 좁히고, 추론을 느리게 하며, 기억 실패를 증가시키고, 단순화된 전략을 사용하도록 만들 수 있습니다. 매우 낮은 작업 부하도 경계심과 준비 상태를 저하시킬 수 있습니다. 신뢰할 수 있는 시스템 설계는 불필요한 정보나 동시 작업에 압도되지 않으면서 충분한 참여 상태를 유지할 수 있는 관리 가능한 운영 영역을 추구합니다.

피로(Fatigue)는 주의, 반응 시간, 작업 기억, 판단 능력을 저하시켜 신뢰성을 크게 감소시킬 수 있습니다. 장시간 근무, 반복적인 모니터링, 부족한 휴식, 지속적인 정신적 노력은 점진적으로 오류 확률을 증가시킵니다. 이러한 영향은 천천히 나타날 수 있기 때문에 운영자가 자신의 성능 저하를 정확히 인식하지 못할 수 있으며, 조직 차원의 일정 관리와 작업 부하 관리가 중요한 안전 메커니즘이 됩니다.

스트레스(Stress)와 시간 압박(Time Pressure)은 의사결정 전략을 변화시킬 수 있습니다. 적절한 긴급성은 집중력을 높일 수 있지만 극단적인 압박은 주의를 좁히고 익숙한 반응에 빠르게 의존하도록 만들 수 있습니다. 비상 상황에서 사람은 부수적인 정보를 놓치거나, 실패한 행동을 반복하거나, 잘못된 진단에 고착될 수 있습니다. 따라서 절차와 인터페이스는 인지 자원이 이미 감소한 상황에서도 사용할 수 있도록 설계되어야 합니다.

상황 자각(Situation Awareness)은 신뢰할 수 있는 수행을 위해 매우 중요합니다. 사람은 중요한 요소를 지각하고, 그 의미를 이해하며, 상황이 앞으로 어떻게 변화할지를 예상해야 합니다. 이 과정 중 어느 단계에서든 실패하면 기술적 능력이 뛰어나더라도 잘못된 행동이 발생할 수 있습니다. 신뢰성 높은 시스템은 사용자가 시스템 상태, 위험, 목표, 제약조건, 예상되는 미래 변화를 통합적으로 이해할 수 있도록 지원합니다.

멘탈 모델(Mental Models)은 사용자가 시스템의 작동 방식에 대한 가정을 통해 정보를 해석하기 때문에 상황 자각에 큰 영향을 줍니다. 모델이 불완전하거나 오래된 경우 정상적인 관찰을 잘못 이해하거나 비정상적인 행동을 잘못 설명할 수 있습니다. 투명한 시스템 동작, 훈련, 시뮬레이션(Simulation), 의미 있는 피드백은 사용자가 더 정확한 예측을 지원하는 모델을 구성하도록 도와줍니다.

인터페이스 설계(Interface Design)는 오류를 방지할 수도 있고 오히려 오류를 발생시킬 수도 있습니다. 서로 비슷하게 보이는 제어 장치, 숨겨진 시스템 상태, 일관되지 않은 명령, 불명확한 용어, 약한 피드백은 잘못된 행동의 가능성을 높입니다. 오류 저항형 인터페이스(Error-Resistant Interface)는 중요한 차이를 명확히 표시하고, 가능한 경우 불가능한 행동을 제한하며, 고위험 명령을 확인하고, 의도한 행동이 실제로 실행되었는지를 즉시 보여줍니다.

강제 기능(Forcing Functions)은 안전하지 않은 행동을 방지하거나 특정 조건이 충족되어야 행동을 진행할 수 있도록 하는 설계 메커니즘입니다. 인터록(Interlocks), 키 방식 커넥터(Keyed Connectors), 확인 절차(Confirmation Sequences), 물리적 제약조건은 특정 오류 경로를 완전히 제거할 수 있습니다. 실수의 결과가 심각하고 기억이나 주의에만 의존하는 것이 충분하지 않을 때 이러한 메커니즘은 특히 중요합니다.

오류 허용성(Error Tolerance)은 오류 예방을 완벽하게 보장할 수 없는 상황을 다룹니다. 회복탄력적인 시스템(Resilient System)은 실수가 때때로 발생한다는 것을 가정하고 이를 탐지하고, 제한하고, 복구할 방법을 제공합니다. 실행 취소(Undo), 안전 기본값(Safe Defaults), 중복성(Redundancy), 점진적 성능 저하(Graceful Degradation), 고장 격리(Fault Isolation), 복구 절차는 작은 인적 오류가 시스템 수준의 고장으로 확대될 가능성을 줄입니다.

피드백(Feedback)은 오류 탐지에 필수적입니다. 사람은 행동이 수용되었는지, 어떤 상태가 변화했는지, 결과가 기대와 일치하는지에 대한 적절한 정보를 필요로 합니다. 지연되거나 모호한 피드백은 잘못된 가정이 계속 유지되도록 합니다. 효과적인 피드백은 사용자가 편차가 위험한 수준으로 발전하기 전에 수정할 수 있도록 결과를 명확히 보여주어 지각-행동 루프(Perception-Action Loop)를 완성합니다.

경보(Alarms)는 비정상적인 상태에 주의를 집중시키기 위한 것이지만 잘못 설계된 경보 시스템은 오히려 신뢰성을 떨어뜨릴 수 있습니다. 지나치게 많은 경보는 과부하와 경보 피로(Alarm Fatigue)를 발생시키며, 빈번한 오경보(False Alarms)는 신뢰를 감소시킵니다. 효과적인 경보 관리는 심각도에 따라 우선순위를 정하고, 중복 알림을 억제하며, 관련 사건을 그룹화하고, 단순히 변화 사실만 알리는 대신 필요한 행동이나 해석을 전달합니다.

자동화(Automation)는 반복적인 계산, 모니터링, 안정화, 제어 작업을 인간보다 일관되게 수행하여 신뢰성을 향상시킬 수 있습니다. 그러나 자동화는 모드 혼란(Mode Confusion), 과도한 의존(Overreliance), 낮은 투명성, 수동 기술 저하와 같은 새로운 고장 모드를 만들기도 합니다. 따라서 인간 신뢰성은 자동화 자체가 정상적으로 작동하는지만이 아니라 사람이 자동화의 상태, 한계, 예상 행동을 이해할 수 있는지에도 달려 있습니다.

자동화 편향(Automation Bias)은 사람이 자동화된 권고를 충분한 독립적 평가 없이 받아들일 때 발생합니다. 시스템이 대부분 정확하면 사용자는 모순되는 증거를 적극적으로 탐색하지 않게 될 수 있습니다. 반대의 경우에는 신뢰성이 낮은 자동화가 과도한 불신과 불필요한 수동 검증을 유발합니다. 적절한 의존을 위해서는 이해 가능한 시스템 능력과 불확실성을 바탕으로 보정된 신뢰(Calibrated Trust)가 필요합니다.

루프 이탈 성능 문제(Out-of-the-Loop Performance Problems)는 자동화가 장시간 작업을 처리하다가 갑자기 인간의 개입을 요구할 때 발생할 수 있습니다. 운영자는 세부적인 상황 자각을 잃었을 수 있으며 제어권을 인수하기 전에 무슨 일이 발생했는지를 이해하는 시간이 필요할 수 있습니다. 따라서 신뢰할 수 있는 자동화는 의미 있는 인간 참여를 유지하고 책임이 전환될 때 간결한 상태 재구성(State Reconstruction)을 제공해야 합니다.

인간-기계 팀 구성(Human-Machine Teaming)은 상호보완적인 강점에 따라 책임을 할당하면 신뢰성을 향상시킬 수 있습니다. 기계는 반복적인 모니터링, 정밀 계산, 고속 데이터 처리에 효과적이며, 인간은 문맥적 추론, 비정상적인 상황, 윤리적 판단, 유연한 목표 해석에서 중요한 역할을 수행합니다. 효과적인 역할 할당은 작업 조건과 신뢰도가 변화함에 따라 동적으로 조정되어야 합니다.

중복성(Redundancy)은 독립적인 사람, 센서, 모델 또는 절차가 중요한 결과를 검증할 때 신뢰성을 향상시킬 수 있습니다. 그러나 중복 요소들의 실패가 강하게 상관되지 않을 때에만 효과적입니다. 두 운영자가 동일하게 잘못된 가정을 사용하면 같은 오류를 발생시킬 수 있습니다. 따라서 단순한 복제보다 정보 출처, 방법, 관점의 다양성(Diversity)이 더 가치 있을 수 있습니다.

교차 확인(Cross-Checking)은 중요한 팀 신뢰성 메커니즘입니다. 두 번째 사람이 고위험 행동을 실행하기 전에 계산, 절차, 시스템 상태를 확인할 수 있습니다. 효과적인 교차 확인에는 명확한 책임과 기존 가정에 이의를 제기할 수 있는 심리적 허용이 필요합니다. 조직의 위계가 질문을 억제한다면 형식적인 중복성은 존재하더라도 실질적인 보호 기능을 제공하지 못할 수 있습니다.

의사소통 실패(Communication Failures)는 인적 오류에 빈번하게 기여합니다. 모호한 언어, 불완전한 인수인계(Handovers), 일관되지 않은 용어, 말하지 않은 가정은 서로 다른 사람들이 호환되지 않는 멘탈 모델을 유지하도록 만들 수 있습니다. 구조화된 의사소통 기법은 중요한 정보, 책임, 불확실성, 공유된 이해에 대한 확인을 명시적으로 전달함으로써 신뢰성을 향상시킵니다.

따라서 팀 신뢰성(Team Reliability)은 공유 상황 자각(Shared Situation Awareness)과 공유 멘탈 모델(Shared Mental Models)에 의존합니다. 구성원들이 완전히 동일한 지식을 가질 필요는 없지만 전체 목표, 역할 경계, 시스템 상태, 다른 구성원의 예상 행동을 이해해야 합니다. 이러한 표현이 서로 어긋나면 개별적으로 합리적인 의사결정들이 결합되어 안전하지 않은 시스템 행동을 만들어낼 수 있습니다.

조직적 조건(Organizational Conditions)은 개인의 신뢰성에 강한 영향을 줍니다. 인력 수준, 훈련 품질, 유지보수 정책, 일정 계획, 인센티브 구조(Incentive Structures), 감독, 경영 우선순위는 의사결정이 이루어지는 환경을 형성합니다. 사람에게 지속적으로 상충하는 목표나 비현실적인 마감시간을 부여하는 시스템은 개별 작업자가 매우 유능하더라도 예측 가능한 오류 조건을 만들어낼 수 있습니다.

잠재 조건(Latent Conditions)은 사고가 발생하기 이전부터 존재하는 취약점을 의미합니다. 잘못된 절차, 혼란스러운 인터페이스, 불충분한 훈련, 지연된 유지보수, 조직적 의사소통의 단절은 활성 오류(Active Error)와 결합될 때까지 발견되지 않을 수 있습니다. 따라서 신뢰성 분석은 마지막으로 실수한 사람만 찾는 대신 사고에 기여한 전체 조건의 연쇄를 분석합니다.

공정 문화(Just Culture)는 의도적인 무모한 행동과 합리적인 실수 및 시스템에 의해 유발된 오류를 구분함으로써 신뢰성을 지원합니다. 모든 오류를 처벌하면 사람들이 아차 사고(Near Misses)를 숨기게 되어 조직 학습이 감소할 수 있습니다. 반대로 모든 행동을 용인하면 책임성이 사라집니다. 효과적인 안전 문화(Safety Culture)는 보고를 장려하면서도 의도적이고 허용할 수 없는 위험 행동에 대해서는 명확한 기준을 유지합니다.

아차 사고(Near Misses)는 사고의 전체 결과가 발생하지 않은 상태에서 시스템의 약점을 드러내기 때문에 특히 가치가 있습니다. 아차 사고 분석을 통해 반복되는 오류 패턴, 잘못된 인터페이스, 부적절한 절차, 예상하지 못한 상호작용을 식별할 수 있습니다. 이러한 사건을 수집하고 학습하는 조직은 동일한 유형의 실패가 심각한 피해를 발생시키기 전에 신뢰성을 개선할 수 있습니다.

근본 원인 분석(Root-Cause Analysis)은 즉각적인 운영자의 행동만을 식별하는 수준을 넘어야 합니다. 당시 그 행동이 왜 합리적으로 보였는지를 질문하면 정보 부족, 오해를 유발하는 피드백, 작업 부하, 훈련 한계, 잘못된 절차, 조직적 압박 등을 발견할 수 있습니다. 행동이 발생한 문맥을 이해하는 것은 단순히 사람들에게 더 주의하라고 지시하는 것보다 효과적인 개선 조치를 가능하게 합니다.

인간 신뢰성 분석(Human Reliability Analysis)은 더 큰 기술 시스템 안에서 인간 행동의 확률과 결과를 추정하려고 합니다. 분석 방법은 작업 복잡성, 환경 조건, 의존성, 복구 기회, 수행 영향 요인(Performance-Shaping Factors)을 검토할 수 있습니다. 인간 행동은 문맥에 의존하므로 정확한 수치 예측은 어렵지만 구조화된 분석을 통해 고위험 작업과 취약한 방어 체계를 식별할 수 있습니다.

수행 영향 요인(Performance-Shaping Factors)에는 작업 부하, 경험, 훈련, 인터페이스 품질, 시간 압박, 피로, 환경 조건, 절차 설계, 팀워크, 조직적 지원 등이 포함됩니다. 이러한 요인들은 작업이 올바르게 수행될 확률을 변화시킵니다. 따라서 신뢰성 개선은 모든 상황에서 동일한 성능을 기대하기보다 행동을 둘러싼 조건을 개선하는 데 초점을 맞춥니다.

훈련(Training)은 절차적 기억뿐 아니라 정확한 멘탈 모델과 복구 전략(Recovery Strategies)을 개발할 때 신뢰성을 향상시킵니다. 정상 절차만 암기하는 것으로는 드물게 발생하는 비정상 사건에 충분히 대응하지 못할 수 있습니다. 시뮬레이션과 시나리오 기반 훈련(Scenario-Based Training)은 비정상 조건을 경험하고, 진단을 연습하고, 고장 특징을 인식하고, 표준 가정이 더 이상 적용되지 않을 때 시스템이 어떻게 행동하는지를 학습할 수 있게 합니다.

적응형 전문성(Adaptive Expertise)은 복잡한 시스템에서 특히 중요합니다. 일상적 전문성(Routine Expertise)은 익숙한 조건에서 효율적인 실행을 가능하게 하고, 적응형 전문성은 익숙한 절차가 충분하지 않은 시점을 인식하고 새로운 해결책을 구성할 수 있게 합니다. 고정된 절차에 지나치게 의존하면 예상된 시나리오를 벗어난 상황에서 위험해질 수 있기 때문에 신뢰성 높은 조직에는 두 능력이 모두 필요합니다.

체크리스트와 절차는 판단을 대체하기보다 인지를 지원해야 합니다. 지나치게 상세한 절차는 압박 상황에서 사용하기 어려울 수 있고, 지나치게 모호한 절차는 충분한 지침을 제공하지 못합니다. 효과적인 절차는 중요한 단계, 의사결정 지점(Decision Points), 경고, 검증 행동을 조직하면서 완전히 예측할 수 없는 상황에 대응할 적절한 유연성을 남겨둡니다.

오류 복구(Error Recovery)는 많은 실수가 조기에 탐지되면 되돌릴 수 있기 때문에 신뢰성의 핵심 구성요소입니다. 시스템은 오류를 가시화하고, 안전한 상태를 유지하며, 명확한 복구 경로를 제공해야 합니다. 훈련 역시 완벽한 실행에만 집중하지 않고 복구를 포함해야 합니다. 편차를 인식하고 수정하는 방법을 이해하는 운영자는 오류가 더 큰 문제로 확대되는 것을 방지할 수 있습니다.

회복탄력성(Resilience)은 예상되는 고장을 예방하는 것 이상으로 신뢰성의 범위를 확장합니다. 회복탄력적인 시스템은 변화하는 조건을 모니터링하고, 예상하지 못한 사건에 대응하고, 중단으로부터 복구하며, 핵심 기능을 유지하면서 행동을 적응시킬 수 있습니다. 인간은 사전에 정의된 절차나 자동화된 대응이 충분하지 않을 때 목표를 재해석하고 새로운 방법을 만들어낼 수 있기 때문에 회복탄력성에서 중요한 역할을 합니다.

인공지능(Artificial Intelligence)의 관점에서 인적 오류 연구는 신뢰할 수 있는 자율 시스템(Autonomous Systems)을 설계하는 데 중요한 교훈을 제공합니다. AI 모델 역시 불완전한 정보, 제한된 계산 자원, 불확실한 예측, 불완전한 내부 표현 아래에서 작동합니다. 따라서 높은 벤치마크 정확도가 안전한 운용을 보장한다고 가정하기보다 신뢰도 추정(Confidence Estimation), 고장 탐지(Failure Detection), 중복성, 피드백, 복구 메커니즘, 모니터링이 필요합니다.

AI 시스템에서도 인간의 지각 또는 추론 실패와 유사한 오류가 발생할 수 있습니다. 지각 모델(Perception Model)은 객체를 놓칠 수 있고, 언어 모델(Language Model)은 잘못된 관계를 추론할 수 있으며, 플래너(Planner)는 월드 모델(World Model)이 부정확하여 위험한 행동을 선택할 수 있습니다. 신뢰성 높은 아키텍처는 불확실성이 증가하는 시점을 탐지하고 불확실한 출력이 곧바로 고위험 행동으로 연결되지 않도록 해야 합니다.

인간-AI 시스템(Human-AI Systems)에서는 기계 오류가 인간의 의사결정에 영향을 주고 인간의 행동이 기계 성능에 영향을 주는 결합 고장 모드(Coupled Failure Modes)가 발생합니다. 잘못된 AI 권고는 운영자가 지나치게 신뢰하면 더욱 위험해질 수 있으며, 부적절한 인간 입력은 모델이 의도된 조건을 벗어나 작동하도록 만들 수 있습니다. 따라서 신뢰성은 인간과 AI를 결합한 전체 시스템 수준에서 평가되어야 합니다.

설명 가능성(Explainability)은 사용자가 중요한 증거, 불확실성, 가정, 시스템 한계를 이해하도록 도울 때 신뢰성을 지원할 수 있습니다. 설명은 단순히 결과를 사후적으로 정당화하는 것이 아니라 사용자의 멘탈 모델을 개선해야 합니다. 실제 시스템 행동과 연결되지 않은 그럴듯한 설명은 부적절한 신뢰를 감소시키기보다 오히려 증가시킬 수 있습니다.

로보틱스(Robotics)와 피지컬 AI(Physical AI)에서 신뢰성은 지각-행동 루프(Perception-Action Loop)와 분리할 수 없습니다. 작은 센싱 오류(Sensing Error)가 위치 추정(Localization), 계획, 제어, 물리적 상호작용에 영향을 주고, 그 결과 다시 새로운 관찰이 생성되면서 초기 오류가 더욱 증폭될 수 있습니다. 따라서 폐루프 모니터링(Closed-Loop Monitoring), 안전 제약조건, 충돌 검사(Collision Checking), 불확실성 인식 계획(Uncertainty-Aware Planning), 신속한 복구가 오류 전파를 방지하는 데 필수적입니다.

물리적 상호작용(Physical Interaction)은 오류의 결과를 더욱 즉각적으로 만듭니다. 대화에서 발생한 오류는 다음 메시지로 수정할 수 있지만 잘못된 로봇 동작은 장비를 손상시키거나 사람을 다치게 할 수 있습니다. 따라서 피지컬 AI는 학습된 모델이 기하학적(Geometric), 동역학적(Dynamic), 운영적(Operational), 안전 제약조건(Safety Constraints) 안에서 작동하도록 하는 계층적 안전장치(Layered Safeguards)를 필요로 합니다. 이러한 안전장치는 상위 수준 추론이 잘못되더라도 효과적으로 작동해야 합니다.

월드 모델(World Models)은 실행 전에 결과를 예측할 수 있게 하여 신뢰성을 향상시킬 수 있지만, 잘못된 모델은 높은 확신을 가진 계획 오류를 발생시킬 수도 있습니다. 신뢰할 수 있는 에이전트는 예측 결과와 실제 관찰을 지속적으로 비교하고, 모델 불확실성을 추적하며, 신뢰도가 감소하면 계획 시간 범위(Planning Horizon)를 줄이고, 환경이 학습된 가정의 범위를 벗어나면 더 안전한 행동으로 전환해야 합니다.

인간 감독(Human Oversight)은 많은 고위험 자율 시스템에서 여전히 중요하지만 감독 자체도 현실적으로 설계되어야 합니다. 인간은 수백 개의 중요하지 않은 사건을 지속적으로 감시하면서 극히 드문 비상 상황에 완벽하게 대비할 수 없습니다. 효과적인 감독에는 우선순위 설정, 의미 있는 경보, 투명한 상태 정보, 운영자가 상황을 이해하고 대응할 수 있는 충분한 시간이 필요합니다.

따라서 신뢰성은 하나의 구성요소가 가진 특성이 아니라 아키텍처적 속성(Architectural Property)으로 고려되어야 합니다. 센서, 소프트웨어, AI 모델, 인터페이스, 절차, 운영자, 조직, 복구 메커니즘이 함께 시스템의 안전한 기능 지속 여부를 결정합니다. 다른 부분에서 예측 가능한 고장 경로가 계속 존재한다면 하나의 요소만 개선해도 전체 신뢰성에는 제한적인 효과만 나타날 수 있습니다.

평가(Evaluation)는 정상 성능뿐 아니라 비정상 조건, 희귀 사건(Rare Events), 성능이 저하된 센서, 상충하는 정보, 중단, 작업 부하 변화, 오류 이후의 복구까지 포함해야 합니다. 일상적인 조건에서 완벽하게 작동하는 시스템도 기본 가정이 위반되면 취약할 수 있습니다. 따라서 신뢰성 시험(Reliability Testing)은 인간과 기계가 혼란을 느끼거나 불확실해질 가능성이 높은 상황을 의도적으로 탐색해야 합니다.

핵심 원칙은 복잡한 지능 시스템에서 오류를 완전히 제거할 수 없다는 것입니다. 실질적인 목표는 오류 확률을 줄이고, 편차를 조기에 탐지하며, 오류 전파를 방지하고, 복구를 지원하며, 실패로부터 학습하는 것입니다. 신뢰할 수 있는 시스템은 완벽한 주의, 기억, 추론, 예측이 항상 가능하다고 가정하지 않고 인간과 기계의 한계를 설계 제약조건(Design Constraints)으로 받아들입니다.

인지과학(Cognitive Science)의 관점에서 인적 오류는 지각, 주의, 기억, 멘탈 모델, 작업 부하, 의사결정이 실제 제약조건 아래에서 어떻게 상호작용하는지를 보여줍니다. AI 공학(AI Engineering)의 관점에서는 동일한 교훈이 불확실성, 모니터링, 중복성, 점진적 성능 저하(Graceful Degradation), 복구를 중심으로 하는 아키텍처를 요구합니다. 신뢰성은 인지, 기술, 절차, 조직 설계가 함께 작동하여 피할 수 없는 변동성을 관리할 때 형성됩니다.

미래의 자율 시스템(Autonomous Systems)과 피지컬 AI(Physical AI)에서 가장 강력한 접근법은 신뢰할 수 없다고 가정한 인간을 완벽하다고 가정한 기계로 단순히 대체하는 것이 아닙니다. 인간과 인공지능 시스템은 각각 고유한 강점과 고장 모드(Failure Modes)를 가지고 있습니다. 높은 신뢰성은 이러한 한계를 이해하고, 책임을 적절하게 배분하며, 오류를 탐지하고 제한하고 수정하며 학습의 기회로 전환할 수 있는 다계층 시스템(Layered Systems)을 설계함으로써 달성됩니다.

##  

## 01.07 Cognition vs Intelligence

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

Cognition refers to the collection of processes through which an agent acquires information, represents the world, remembers experience, directs attention, learns patterns, reasons about situations, makes decisions, and controls action. Intelligence is a broader functional capacity describing how effectively these cognitive processes are coordinated to achieve goals, solve problems, adapt to change, and operate successfully under uncertainty.

The distinction is important because possessing cognitive mechanisms does not automatically imply high intelligence. A system may perceive objects, store memories, or follow learned rules while remaining unable to integrate these abilities effectively when circumstances change. Intelligence emerges from the organization, coordination, flexibility, and adaptive use of cognitive capabilities rather than from the mere presence of individual cognitive functions.

Cognition can therefore be viewed as the machinery of information processing, while intelligence describes the quality and effectiveness of its integrated operation. Perception, attention, memory, learning, reasoning, planning, and action provide functional components. Intelligence depends on whether these components cooperate to produce behavior that remains useful across different tasks, environments, constraints, and levels of uncertainty.

Perception is a cognitive process that transforms sensory signals into representations useful for understanding the environment. Intelligence determines how effectively those representations are connected with goals, memory, prediction, and action. Recognizing an obstacle is cognitive processing, but understanding whether it should be avoided, moved, ignored, investigated, or used as part of a task requires broader intelligent integration.

Attention provides another example of the distinction. Cognitive systems can selectively allocate processing resources toward particular signals, objects, or tasks. Intelligent behavior requires deciding what deserves attention according to goals, uncertainty, risk, novelty, and expected value. Effective intelligence therefore involves not merely attending, but allocating limited cognitive resources strategically as circumstances change.

Memory allows past information and experience to influence current processing. However, intelligence requires more than storing large quantities of information. An intelligent system must retrieve relevant knowledge at the appropriate moment, distinguish useful memories from irrelevant ones, combine previous experience with current observations, and revise stored knowledge when new evidence contradicts earlier assumptions.

Learning is a fundamental cognitive capability through which behavior or internal representations change with experience. Intelligence depends on the efficiency, generality, and stability of this adaptation. A system that learns one narrow task through enormous amounts of data may possess learning capability, but a more intelligent system should transfer knowledge, adapt from limited evidence, and preserve useful previous abilities.

Reasoning transforms representations into conclusions, explanations, predictions, or decisions. Cognitive mechanisms may perform logical, probabilistic, causal, spatial, analogical, or heuristic reasoning. Intelligence is reflected in the ability to select appropriate reasoning strategies, recognize when assumptions are uncertain, combine multiple forms of evidence, and revise conclusions when the environment produces unexpected results.

Problem solving demonstrates how cognition becomes integrated intelligence. Solving a novel problem may require perceiving relevant features, retrieving prior knowledge, constructing a mental model, generating alternatives, predicting consequences, selecting actions, observing results, and correcting errors. Intelligence is expressed through the coordinated execution of this complete cycle rather than through any single stage alone.

Planning extends cognition across future time. A cognitive system can represent goals and possible actions, while intelligent planning requires evaluating dependencies, constraints, uncertainty, resources, risks, and future consequences. More capable intelligence can reason over longer horizons while preserving flexibility, revising plans when assumptions change instead of rigidly following previously selected sequences.

Decision making connects cognition directly with action. A system may understand several alternatives but still perform poorly if it cannot select actions appropriately. Intelligence therefore includes the ability to balance objectives, costs, rewards, safety, uncertainty, and available resources. The quality of decisions becomes one observable expression of how effectively underlying cognitive processes are integrated.

Adaptation is one of the strongest characteristics distinguishing intelligence from fixed information processing. A calculator performs sophisticated computation but does not normally reorganize its behavior when environmental conditions change. An intelligent agent should detect when existing strategies become ineffective, identify the source of failure, modify its internal representations or policies, and improve future behavior.

Generalization is similarly important. Cognition can support recognition or behavior within familiar conditions, while intelligence requires extending learned structure beyond exact previous examples. An agent demonstrates stronger intelligence when it identifies deeper relationships that remain useful across new objects, environments, tasks, or combinations rather than memorizing superficial patterns.

Transfer learning illustrates this principle computationally. Knowledge developed for one problem can accelerate learning or improve performance in another related problem. Effective transfer indicates that internal representations capture reusable structure. Intelligence therefore depends partly on whether knowledge is organized in forms that support recombination and adaptation rather than remaining isolated within individual tasks.

Abstraction enables cognitive systems to ignore unnecessary details and reason about general structure. A robot can represent a specific chair through pixels and geometry, but higher-level cognition may represent it as furniture, an obstacle, a support surface, or an object with particular affordances. Intelligence requires selecting the abstraction level appropriate to the current goal.

Hierarchical representation allows intelligence to operate across multiple levels of abstraction. High-level cognition can reason about missions, goals, and strategies, while lower levels manage tasks, trajectories, motor commands, and sensor feedback. Intelligence depends on coordinating these levels so that abstract intentions can become executable actions and physical outcomes can update higher-level reasoning.

Cognitive flexibility describes the ability to change representations, strategies, or goals when circumstances require it. A system may be highly optimized for one procedure but perform poorly when the situation falls outside expected conditions. Intelligence requires recognizing such mismatch and shifting from routine processing toward exploration, diagnosis, learning, or alternative strategies.

Metacognition extends cognition by allowing an agent to reason about its own cognitive processes. Humans can sometimes estimate whether they understand a problem, whether a memory is uncertain, or whether additional information is required. Artificial systems can implement analogous functions through confidence estimation, uncertainty monitoring, self-evaluation, verification, and resource management.

Metacognitive capability contributes strongly to reliable intelligence because intelligent behavior requires knowing when not to trust an internal conclusion. A system that produces accurate answers most of the time but cannot recognize unfamiliar conditions may fail dangerously. Monitoring uncertainty allows an agent to gather additional evidence, request assistance, choose safer actions, or postpone decisions.

Intelligence therefore includes effective management of uncertainty. Real environments rarely provide complete information, and observations may be noisy, delayed, contradictory, or ambiguous. Cognitive processes generate interpretations from available evidence, while intelligent systems maintain alternative hypotheses, estimate confidence, seek information actively, and adjust behavior according to the consequences of being wrong.

Creativity can also be understood as an advanced integration of cognitive mechanisms. Memory supplies previous concepts, abstraction identifies transferable structure, imagination generates combinations, reasoning evaluates possibilities, and learning preserves useful discoveries. Intelligence appears when these processes generate solutions that are both novel and appropriate rather than merely producing random variation.

Social cognition introduces another dimension. Humans represent the intentions, beliefs, knowledge, emotions, and expected behavior of other people. Intelligence in social environments requires using these representations to communicate, cooperate, negotiate, teach, coordinate, or compete. The ability to model other agents extends cognition beyond understanding physical objects toward understanding interactive minds.

Language provides a powerful cognitive medium for representing and communicating abstract relationships. It supports reasoning about events that are distant, hypothetical, invisible, or impossible to experience directly. Linguistic capability contributes to intelligence when language becomes connected with memory, perception, reasoning, planning, social understanding, and action rather than operating only as isolated symbol manipulation.

Embodied cognition emphasizes that cognition is not necessarily separated from the body and environment. Perception and action continuously influence each other, and physical interaction can simplify reasoning. Humans often solve problems by moving objects, changing viewpoints, writing notes, or manipulating external structures rather than performing every computation internally.

From this perspective, intelligence can emerge partly from effective interaction between brain, body, and environment. A robot does not need a perfect internal representation of every physical detail if sensing and feedback allow continuous correction. Intelligent behavior can therefore combine internal models with active perception, environmental structure, physical compliance, and closed-loop control.

Cognitive efficiency is another important dimension of intelligence. Two systems may solve the same problem, but one may require dramatically more computation, memory, data, energy, or time. Intelligence is often associated with achieving useful performance under limited resources. Efficient representation, selective attention, abstraction, reuse of knowledge, and hierarchical processing contribute to this efficiency.

Human intelligence operates under severe biological limitations. Working memory is limited, sensory processing is selective, reasoning can be biased, and learning requires time. Yet humans achieve flexible behavior through mechanisms such as chunking, external memory, abstraction, language, social learning, tool use, and cultural knowledge. Intelligence therefore cannot be understood simply as unlimited computational capacity.

Expertise demonstrates how cognitive organization can improve apparent intelligence within a domain. Experts recognize meaningful patterns, retrieve appropriate knowledge rapidly, predict likely outcomes, and ignore irrelevant details. Their advantage often comes from better structured representations and more efficient cognitive processing rather than from fundamentally larger working-memory capacity.

Intelligence is nevertheless broader than expertise. An expert can perform exceptionally within a familiar domain while struggling in unrelated situations. General intelligence requires the ability to acquire new competencies, transfer concepts, reason across domains, adapt strategies, and operate when established knowledge is incomplete. Breadth and adaptability therefore complement depth of expertise.

Cognition and intelligence also differ in how they are evaluated. Individual cognitive functions can be measured through perception accuracy, memory capacity, reaction time, learning rate, or reasoning performance. Intelligence requires broader evaluation across problem solving, generalization, adaptation, planning, transfer, efficiency, robustness, autonomy, and the ability to combine capabilities across changing conditions.

Traditional intelligence tests attempt to measure common factors underlying performance across multiple cognitive tasks. However, intelligence in real environments includes dimensions difficult to capture through isolated tests, such as practical adaptation, social interaction, long-term planning, physical competence, creativity, uncertainty management, and the ability to recover from unexpected failure.

Artificial intelligence makes the cognition-intelligence distinction particularly important. A machine can possess highly capable modules for vision, language, planning, or control without functioning as a generally intelligent agent. Intelligence requires these components to share relevant representations, coordinate goals, maintain persistent state, learn from outcomes, and adapt their operation across time.

Classical AI often represented cognition through explicit symbols, rules, search procedures, and knowledge structures. Such systems could demonstrate strong reasoning within carefully defined domains but frequently lacked robust perception and adaptation. Their limitations showed that sophisticated reasoning alone is insufficient when intelligence must operate in complex, uncertain, continuously changing environments.

Machine learning shifted emphasis toward cognition acquired from data. Neural networks learned representations for perception, prediction, language, and control without requiring every rule to be programmed manually. This greatly expanded artificial cognitive capability, but specialized learned models can still remain narrow if they cannot transfer knowledge, reason about unfamiliar conditions, or coordinate with broader goals.

Deep learning demonstrates that powerful cognitive functions can emerge from distributed representations. Vision systems classify objects, speech systems recognize language, and control policies map observations to actions. Yet high performance on a benchmark does not necessarily indicate broad intelligence. A system may succeed statistically while lacking causal understanding, persistent memory, planning, or robust adaptation.

Foundation models broaden artificial cognition by learning reusable representations from large and diverse datasets. A single model may support language understanding, visual interpretation, reasoning, generation, or multimodal interaction across many tasks. This represents a major movement from task-specific cognition toward more general capabilities, although broad competence still differs from fully integrated intelligence.

Large language models provide a clear example. They can summarize, translate, reason, generate plans, explain concepts, and interact through language. These abilities reflect extensive learned cognitive structure. However, reliable autonomous intelligence additionally requires persistent goals, grounded perception, long-term memory, environmental feedback, uncertainty handling, action execution, and mechanisms for learning from consequences.

Multimodal foundation models extend cognition by connecting language with images, audio, video, sensor data, and other modalities. This improves the ability to construct richer representations of situations. Intelligence increases further when multimodal perception is connected to prediction and action, allowing an agent not only to describe what it observes but also to decide what should happen next.

Agentic AI adds goal-directed operation to foundation-model capabilities. An agent can maintain objectives, select tools, execute actions, inspect results, and continue across multiple steps. This begins to transform passive cognitive capability into active intelligence because the system becomes responsible for managing a perception-reasoning-action loop rather than generating isolated responses.

Memory is essential for this transition. Without persistent memory, an agent may repeatedly reconstruct context and fail to accumulate useful experience across long tasks. Structured memory allows goals, decisions, observations, failures, preferences, environmental states, and learned procedures to persist. Intelligence requires retrieving and updating this information selectively rather than storing everything without organization.

World models provide another important bridge from cognition toward intelligence. They represent how relevant aspects of an environment change over time, often conditioned on actions. By predicting possible future states, an agent can mentally or computationally simulate consequences before acting. This enables planning, counterfactual reasoning, risk assessment, and more efficient learning.

A world model alone is not intelligence. It provides predictive cognitive structure, but an intelligent system must determine which futures matter, evaluate them according to goals, select actions, observe real outcomes, and revise the model when predictions fail. Intelligence therefore emerges from the closed-loop integration of world modeling with perception, planning, action, learning, and feedback.

Reinforcement learning contributes another component by connecting actions with consequences and objectives. An agent learns policies that improve expected outcomes through interaction. When combined with world models, reinforcement learning can evaluate imagined trajectories as well as direct experience. This creates a computational framework for adaptive decision making but still requires reliable representations and safety constraints.

Physical AI makes the difference between cognition and intelligence especially visible. A robot may recognize objects and understand instructions yet remain unable to complete a physical task reliably. Intelligent physical behavior requires localization, geometry, dynamics, affordances, motion planning, control, uncertainty handling, safety, and continuous feedback to operate together.

Embodied intelligence therefore depends on grounding abstract cognition in physical reality. The concept "cup" is insufficient for manipulation unless the system can estimate where the cup is, whether it can be reached, how it can be grasped, how much force is appropriate, what obstacles exist, and whether the observed motion matches the predicted result.

Perception foundation models can provide rich semantic understanding, while action foundation models can supply reusable behavior patterns. Neither alone constitutes complete robotic intelligence. A broader architecture must connect perception, world state, memory, world models, task reasoning, action generation, low-level control, and safety monitoring within a continuous closed-loop system.

Intelligence in robotics also requires temporal integration. Decisions cannot be based only on isolated sensor frames because actions unfold over time and modify future observations. The robot must maintain state, track moving entities, estimate dynamics, remember previous interactions, predict future conditions, and revise plans continuously as the physical world changes.

Real-time constraints distinguish embodied intelligence from many offline cognitive tasks. A theoretically excellent plan is useless if it is generated after the robot must already have acted. Intelligence therefore includes matching computational complexity to available time. Fast reactive mechanisms, medium-horizon prediction, and slower strategic reasoning may need to operate simultaneously at different levels.

Edge computing makes this resource problem explicit. Robots have finite GPU performance, memory, battery capacity, communication bandwidth, and thermal limits. Intelligent architectures should allocate computation according to current needs rather than running every model at maximum complexity continuously. Resource-aware intelligence becomes essential when cognition must operate inside a physical machine.

On-premise or cloud computing can extend cognitive capability by providing larger models, fleet-level learning, long-term analysis, or computationally expensive optimization. However, network latency and availability prevent remote computation from replacing all onboard intelligence. Practical Physical AI therefore benefits from hierarchical intelligence distributed across real-time edge systems and more powerful external infrastructure.

Multi-agent systems extend intelligence from individual cognition toward collective coordination. Each robot may maintain local perception and goals while sharing maps, tasks, observations, or learned information with others. Collective intelligence emerges when agents coordinate efficiently, avoid duplicated effort, resolve conflicting plans, and use distributed information to improve group performance.

Human-AI collaboration introduces another form of distributed intelligence. Humans contribute contextual understanding, values, flexible judgment, and broad experience, while machines provide computation, memory, monitoring, and large-scale pattern processing. Effective collaboration requires both sides to maintain sufficiently aligned models of goals, responsibilities, uncertainty, and system state.

Reliability is essential when evaluating intelligence because capability without dependable behavior may have limited practical value. An intelligent system should recognize uncertainty, detect failures, preserve safe operation, recover from errors, and request assistance when necessary. Knowing the limits of a cognitive capability is often as important as maximizing its nominal performance.

Robustness describes the ability to maintain useful performance when conditions vary. Cognitive systems trained under narrow distributions may fail when lighting, terrain, language, objects, or user behavior changes. More capable intelligence should identify distribution shifts, adapt representations, use alternative strategies, and avoid confidently applying assumptions that no longer match reality.

Autonomy is related to intelligence but should not be treated as identical to it. A simple thermostat can operate autonomously with minimal intelligence, while a powerful reasoning system may remain under human control. Higher autonomy increases the range of decisions delegated to the system, whereas intelligence determines how competently those decisions can be made.

Agency adds persistent goal-directed behavior. An agent selects actions that influence the environment and evaluates progress toward objectives. Intelligent agency requires maintaining goals over time, resolving conflicts, adapting plans, managing resources, learning from outcomes, and distinguishing between actions that are possible, desirable, safe, and necessary.

Consciousness should also be distinguished from cognition and intelligence. Cognitive processing and intelligent behavior do not automatically establish subjective awareness. Humans combine cognition, intelligence, and conscious experience, but engineering systems can perform sophisticated perception, reasoning, learning, and planning without demonstrating that they possess human-like subjective experience.

This distinction prevents unnecessary confusion in discussions of advanced AI. Increasing model size, reasoning performance, autonomy, or multimodal capability can improve functional intelligence without answering philosophical questions about consciousness. Engineering evaluation should therefore focus on observable capabilities, limitations, reliability, adaptation, and consequences unless subjective experience is specifically under investigation.

A useful architectural perspective is to view cognition as a collection of interacting functional layers. Perception constructs representations, attention allocates resources, memory preserves information, learning modifies models, reasoning transforms knowledge, prediction estimates futures, planning organizes actions, and control executes behavior. Intelligence describes how effectively the entire architecture achieves goals across changing conditions.

Under this perspective, intelligence is not located in one neural network, algorithm, or module. It is a system-level property emerging from coordination among components. A highly capable perception model cannot compensate completely for poor planning, and sophisticated reasoning cannot produce reliable physical behavior if sensing, control, memory, or safety mechanisms are inadequate.

The same principle explains why increasing model scale alone may not produce proportional increases in practical intelligence. Larger models can improve representation and reasoning, but complete agents still require memory architectures, tool use, world models, feedback loops, planning mechanisms, safety constraints, and interfaces with physical or digital environments.

Future AI systems are therefore likely to become increasingly modular and hierarchical even when foundation models provide broad shared representations. Specialized perception, prediction, planning, control, verification, and memory mechanisms can operate around general models. Intelligence will depend on orchestration among these components as much as on the capability of the largest model.

Cognitive science provides useful guidance because biological intelligence demonstrates how multiple imperfect mechanisms can cooperate effectively. Human perception is incomplete, memory is fallible, reasoning is biased, and attention is limited, yet humans compensate through learning, external tools, communication, social cooperation, abstraction, prediction, and adaptive control.

Artificial intelligence does not need to reproduce human cognition exactly. Machines can use high-dimensional memory, precise computation, large databases, simulation, distributed processing, and sensor modalities unavailable to humans. However, principles such as selective attention, hierarchical organization, prediction, feedback, uncertainty management, and adaptation remain valuable for constructing effective intelligence.

The distinction between cognition and intelligence ultimately shifts attention from individual capabilities toward integration. Cognition provides mechanisms for knowing, representing, learning, reasoning, and acting. Intelligence describes the ability to organize those mechanisms into coherent, adaptive, efficient, and goal-directed behavior across situations that cannot all be anticipated in advance.

For Physical AI, this distinction becomes a practical architecture principle. Perception models, language models, world models, memory systems, planners, controllers, and safety modules provide cognitive capabilities. Intelligence emerges when these components share state, predict consequences, coordinate decisions, learn from physical feedback, manage limited resources, and maintain reliable behavior in changing environments.

The long-term objective is therefore not simply to build machines with more cognitive functions, but to construct systems capable of integrating those functions across perception, prediction, reasoning, learning, planning, and action. As integration improves, artificial systems can progress from specialized cognitive tools toward adaptive agents capable of increasingly general, reliable, and physically grounded intelligence.

인지(Cognition)는 에이전트가 정보를 획득하고, 세계를 표현하며, 경험을 기억하고, 주의(Attention)를 조절하고, 패턴을 학습하며, 상황을 추론하고, 의사결정을 내리고, 행동을 제어하는 과정들의 집합을 의미합니다. 지능(Intelligence)은 이러한 인지 과정들이 목표 달성, 문제 해결, 변화에 대한 적응, 불확실한 환경에서의 성공적인 행동을 위해 얼마나 효과적으로 통합되고 조정되는지를 나타내는 보다 광범위한 기능적 능력입니다.

이러한 구분이 중요한 이유는 인지 메커니즘(Cognitive Mechanisms)을 가지고 있다는 사실만으로 높은 지능을 의미하지 않기 때문입니다. 시스템이 객체를 지각하고, 기억을 저장하고, 학습된 규칙을 따를 수 있더라도 상황이 변화했을 때 이러한 능력을 효과적으로 통합하지 못할 수 있습니다. 지능은 개별 인지 기능의 단순한 존재가 아니라 인지 능력의 조직화, 조정, 유연성, 적응적 활용을 통해 나타납니다.

따라서 인지는 정보 처리(Information Processing)를 수행하는 기계적 기반으로 볼 수 있으며, 지능은 이러한 기능들이 통합적으로 작동하는 품질과 효과성을 의미합니다. 지각(Perception), 주의, 기억(Memory), 학습(Learning), 추론(Reasoning), 계획(Planning), 행동(Action)은 기능적 구성요소를 제공합니다. 지능은 이러한 구성요소가 서로 협력하여 다양한 작업, 환경, 제약조건, 불확실성 수준에서도 유용한 행동을 만들어낼 수 있는지에 달려 있습니다.

지각은 감각 신호(Sensory Signals)를 환경을 이해하는 데 유용한 표현으로 변환하는 인지 과정입니다. 지능은 이러한 표현을 목표, 기억, 예측, 행동과 얼마나 효과적으로 연결하는지를 결정합니다. 장애물을 인식하는 것은 인지 처리이지만, 그 장애물을 피해야 하는지, 이동시켜야 하는지, 무시해야 하는지, 조사해야 하는지 또는 작업의 일부로 활용해야 하는지를 이해하려면 더 광범위한 지능적 통합(Intelligent Integration)이 필요합니다.

주의는 인지와 지능의 차이를 보여주는 또 다른 사례입니다. 인지 시스템은 특정 신호, 객체 또는 작업에 처리 자원을 선택적으로 할당할 수 있습니다. 지능적 행동(Intelligent Behavior)은 목표, 불확실성, 위험, 새로움(Novelty), 기대 가치(Expected Value)에 따라 무엇에 주의를 기울여야 하는지를 결정해야 합니다. 따라서 효과적인 지능은 단순히 주의를 기울이는 것이 아니라 상황 변화에 따라 제한된 인지 자원을 전략적으로 할당하는 능력을 포함합니다.

기억은 과거의 정보와 경험이 현재의 처리 과정에 영향을 줄 수 있도록 합니다. 그러나 지능은 단순히 많은 양의 정보를 저장하는 것 이상을 요구합니다. 지능적인 시스템은 적절한 순간에 관련 지식을 검색하고, 유용한 기억과 관련 없는 기억을 구분하며, 이전 경험을 현재 관찰과 결합하고, 새로운 증거가 기존 가정과 충돌할 경우 저장된 지식을 수정할 수 있어야 합니다.

학습은 경험에 따라 행동이나 내부 표현(Internal Representations)이 변화하는 기본적인 인지 능력입니다. 지능은 이러한 적응의 효율성, 일반성, 안정성에 달려 있습니다. 방대한 데이터를 이용하여 하나의 좁은 작업을 학습하는 시스템도 학습 능력을 가질 수 있지만, 더 지능적인 시스템은 지식을 전이하고, 제한된 증거로부터 적응하며, 이전에 획득한 유용한 능력을 유지할 수 있어야 합니다.

추론은 표현을 결론, 설명, 예측 또는 의사결정으로 변환합니다. 인지 메커니즘은 논리적(Logical), 확률적(Probabilistic), 인과적(Causal), 공간적(Spatial), 유추적(Analogical), 휴리스틱(Heuristic) 추론을 수행할 수 있습니다. 지능은 적절한 추론 전략을 선택하고, 가정이 불확실한 시점을 인식하며, 여러 형태의 증거를 결합하고, 환경에서 예상하지 못한 결과가 나타났을 때 결론을 수정하는 능력으로 나타납니다.

문제 해결(Problem Solving)은 인지가 어떻게 통합된 지능으로 발전하는지를 보여줍니다. 새로운 문제를 해결하려면 관련 특징을 지각하고, 이전 지식을 검색하고, 멘탈 모델(Mental Model)을 구성하고, 대안을 생성하고, 결과를 예측하고, 행동을 선택하고, 결과를 관찰하며, 오류를 수정해야 할 수 있습니다. 지능은 이러한 전체 주기를 조정하여 실행하는 과정에서 나타나며 어느 하나의 단계만으로 결정되지 않습니다.

계획은 인지를 미래 시간으로 확장합니다. 인지 시스템은 목표와 가능한 행동을 표현할 수 있지만, 지능적 계획(Intelligent Planning)은 의존성, 제약조건, 불확실성, 자원, 위험, 미래 결과를 평가해야 합니다. 더 높은 수준의 지능은 긴 시간 범위(Long Horizon)를 추론하면서도 유연성을 유지하고, 기존에 선택한 순서를 경직되게 따르는 대신 가정이 변화하면 계획을 수정할 수 있습니다.

의사결정(Decision Making)은 인지를 행동과 직접 연결합니다. 시스템이 여러 대안을 이해하더라도 적절한 행동을 선택하지 못하면 성능이 낮을 수 있습니다. 따라서 지능에는 목표, 비용, 보상(Rewards), 안전, 불확실성, 이용 가능한 자원의 균형을 조정하는 능력이 포함됩니다. 의사결정의 품질은 기반 인지 과정들이 얼마나 효과적으로 통합되는지를 보여주는 관찰 가능한 표현 중 하나입니다.

적응(Adaptation)은 지능과 고정된 정보 처리를 구분하는 가장 강력한 특성 중 하나입니다. 계산기(Calculator)는 복잡한 계산을 수행하지만 일반적으로 환경 조건이 변한다고 해서 자신의 행동 방식을 재구성하지 않습니다. 지능적 에이전트(Intelligent Agent)는 기존 전략이 효과적이지 않은 시점을 탐지하고, 실패의 원인을 파악하며, 내부 표현이나 정책(Policy)을 수정하고, 미래 행동을 개선할 수 있어야 합니다.

일반화(Generalization) 역시 중요합니다. 인지는 익숙한 조건에서 인식이나 행동을 지원할 수 있지만, 지능은 학습된 구조를 과거의 정확한 사례를 넘어 확장할 수 있어야 합니다. 에이전트가 표면적인 패턴을 암기하는 대신 새로운 객체, 환경, 작업 또는 새로운 조합에서도 유용한 더 깊은 관계를 식별할 때 더 높은 수준의 지능을 보여줍니다.

전이 학습(Transfer Learning)은 이러한 원리를 계산적으로 보여줍니다. 하나의 문제에서 개발된 지식은 관련된 다른 문제의 학습을 가속하거나 성능을 향상시킬 수 있습니다. 효과적인 전이는 내부 표현이 재사용 가능한 구조를 포착하고 있음을 의미합니다. 따라서 지능은 지식이 개별 작업 안에 고립되어 있기보다 재조합과 적응을 지원하는 형태로 조직되어 있는지에 부분적으로 의존합니다.

추상화(Abstraction)는 인지 시스템이 불필요한 세부사항을 무시하고 일반적인 구조를 중심으로 추론할 수 있도록 합니다. 로봇은 특정 의자를 픽셀과 기하학(Geometry)으로 표현할 수 있지만, 상위 수준의 인지는 이를 가구, 장애물, 지지 표면(Support Surface) 또는 특정 행동 유도성(Affordances)을 가진 객체로 표현할 수 있습니다. 지능은 현재 목표에 적합한 추상화 수준을 선택하는 능력을 필요로 합니다.

계층적 표현(Hierarchical Representation)은 지능이 여러 추상화 수준에서 작동하도록 합니다. 상위 수준 인지는 임무(Missions), 목표, 전략을 추론하고, 하위 수준에서는 작업, 궤적(Trajectories), 모터 명령, 센서 피드백을 관리할 수 있습니다. 지능은 추상적인 의도를 실행 가능한 행동으로 변환하고 물리적 결과가 다시 상위 수준의 추론을 갱신하도록 이러한 계층들을 조정하는 능력에 달려 있습니다.

인지적 유연성(Cognitive Flexibility)은 상황에 따라 표현, 전략 또는 목표를 변경할 수 있는 능력을 의미합니다. 하나의 절차에 매우 최적화된 시스템도 상황이 예상 조건을 벗어나면 성능이 급격히 저하될 수 있습니다. 지능은 이러한 불일치를 인식하고 일상적인 처리에서 탐색(Exploration), 진단(Diagnosis), 학습 또는 대안 전략으로 전환할 수 있어야 합니다.

메타인지(Metacognition)는 에이전트가 자신의 인지 과정 자체에 대해 추론할 수 있도록 인지의 범위를 확장합니다. 인간은 자신이 문제를 이해하고 있는지, 기억이 불확실한지, 추가 정보가 필요한지를 어느 정도 판단할 수 있습니다. 인공 시스템에서는 신뢰도 추정(Confidence Estimation), 불확실성 모니터링(Uncertainty Monitoring), 자기 평가(Self-Evaluation), 검증(Verification), 자원 관리(Resource Management)를 통해 유사한 기능을 구현할 수 있습니다.

메타인지 능력은 신뢰할 수 있는 지능(Reliable Intelligence)에 크게 기여합니다. 지능적 행동에는 내부 결론을 신뢰하지 말아야 할 시점을 아는 능력이 필요하기 때문입니다. 대부분의 경우 정확한 답을 생성하지만 익숙하지 않은 조건을 인식하지 못하는 시스템은 위험하게 실패할 수 있습니다. 불확실성을 모니터링하면 에이전트가 추가 증거를 수집하고, 도움을 요청하고, 더 안전한 행동을 선택하거나, 의사결정을 연기할 수 있습니다.

따라서 지능에는 불확실성을 효과적으로 관리하는 능력이 포함됩니다. 실제 환경은 완전한 정보를 제공하는 경우가 드물며 관찰은 잡음이 있거나, 지연되거나, 서로 충돌하거나, 모호할 수 있습니다. 인지 과정은 이용 가능한 증거로부터 해석을 생성하고, 지능 시스템은 여러 대안 가설을 유지하며, 신뢰도를 추정하고, 능동적으로 정보를 탐색하며, 잘못된 판단의 결과를 고려하여 행동을 조정합니다.

창의성(Creativity) 역시 인지 메커니즘의 고급 통합으로 이해할 수 있습니다. 기억은 이전 개념을 제공하고, 추상화는 전이 가능한 구조를 식별하며, 상상(Imagination)은 새로운 조합을 생성하고, 추론은 가능성을 평가하며, 학습은 유용한 발견을 보존합니다. 지능은 이러한 과정이 단순한 무작위 변형이 아니라 새롭고 적절한 해결책을 생성할 때 나타납니다.

사회적 인지(Social Cognition)는 또 다른 차원을 추가합니다. 인간은 다른 사람의 의도, 신념, 지식, 감정, 예상 행동을 표현합니다. 사회적 환경에서의 지능은 이러한 표현을 이용하여 의사소통하고, 협력하고, 협상하고, 가르치고, 조정하거나 경쟁할 수 있어야 합니다. 다른 에이전트를 모델링하는 능력은 인지를 물리적 객체의 이해에서 상호작용하는 지능 주체의 이해로 확장합니다.

언어(Language)는 추상적인 관계를 표현하고 전달할 수 있는 강력한 인지 매체입니다. 언어는 멀리 떨어져 있거나, 가상적이거나, 직접 볼 수 없거나, 직접 경험하기 어려운 사건에 대해서도 추론할 수 있도록 합니다. 언어 능력은 고립된 기호 조작(Symbol Manipulation)에 머무르지 않고 기억, 지각, 추론, 계획, 사회적 이해, 행동과 연결될 때 지능에 기여합니다.

체화된 인지(Embodied Cognition)는 인지가 반드시 신체와 환경으로부터 분리되어 있는 것은 아니라는 점을 강조합니다. 지각과 행동은 지속적으로 서로 영향을 주며 물리적 상호작용은 추론을 단순화할 수 있습니다. 인간은 모든 계산을 내부적으로 수행하기보다 객체를 움직이고, 관점을 변경하고, 메모를 작성하거나, 외부 구조를 조작하여 문제를 해결하는 경우가 많습니다.

이러한 관점에서 지능은 두뇌, 신체, 환경 사이의 효과적인 상호작용을 통해 부분적으로 나타날 수 있습니다. 로봇은 센싱과 피드백을 통해 지속적으로 오류를 수정할 수 있다면 모든 물리적 세부사항에 대한 완벽한 내부 표현을 가질 필요가 없습니다. 따라서 지능적 행동은 내부 모델과 능동적 지각(Active Perception), 환경 구조, 물리적 순응성(Physical Compliance), 폐루프 제어(Closed-Loop Control)를 결합할 수 있습니다.

인지 효율성(Cognitive Efficiency)은 지능의 또 다른 중요한 차원입니다. 두 시스템이 동일한 문제를 해결하더라도 하나의 시스템이 훨씬 더 많은 계산, 메모리, 데이터, 에너지 또는 시간을 필요로 할 수 있습니다. 지능은 제한된 자원 아래에서 유용한 성능을 달성하는 능력과도 관련됩니다. 효율적인 표현, 선택적 주의, 추상화, 지식 재사용, 계층적 처리는 이러한 효율성에 기여합니다.

인간 지능(Human Intelligence)은 심각한 생물학적 한계 아래에서 작동합니다. 작업 기억(Working Memory)은 제한적이고, 감각 처리는 선택적이며, 추론에는 편향(Bias)이 존재하고, 학습에는 시간이 필요합니다. 그러나 인간은 청킹(Chunking), 외부 기억(External Memory), 추상화, 언어, 사회적 학습(Social Learning), 도구 사용, 문화적 지식(Cultural Knowledge)을 통해 유연한 행동을 달성합니다. 따라서 지능을 단순히 무제한적인 계산 능력으로 이해할 수는 없습니다.

전문성(Expertise)은 인지적 조직화가 특정 영역에서 겉으로 드러나는 지능을 어떻게 향상시키는지를 보여줍니다. 전문가는 의미 있는 패턴을 인식하고, 적절한 지식을 빠르게 검색하고, 가능한 결과를 예측하며, 관련 없는 세부사항을 무시합니다. 이러한 장점은 근본적으로 더 큰 작업 기억 용량을 가지기보다 더 잘 구조화된 표현과 효율적인 인지 처리에서 비롯되는 경우가 많습니다.

그러나 지능은 전문성보다 더 광범위합니다. 전문가는 익숙한 영역에서 탁월한 성능을 발휘하면서도 관련 없는 상황에서는 어려움을 겪을 수 있습니다. 일반 지능(General Intelligence)은 새로운 능력을 습득하고, 개념을 전이하고, 여러 영역을 넘나들며 추론하고, 전략을 적응시키고, 기존 지식이 불완전한 상황에서도 작동할 수 있는 능력을 요구합니다. 따라서 전문성의 깊이뿐 아니라 범위와 적응성도 중요합니다.

인지와 지능은 평가 방법에서도 차이가 있습니다. 개별 인지 기능은 지각 정확도, 기억 용량, 반응 시간, 학습 속도, 추론 성능 등을 통해 측정할 수 있습니다. 반면 지능은 문제 해결, 일반화, 적응, 계획, 전이, 효율성, 강건성(Robustness), 자율성(Autonomy), 변화하는 조건에서 여러 능력을 결합하는 능력 등을 포함하여 보다 폭넓게 평가해야 합니다.

전통적인 지능 검사(Intelligence Tests)는 여러 인지 작업의 수행에 공통적으로 영향을 미치는 요인을 측정하려고 합니다. 그러나 실제 환경에서의 지능에는 고립된 시험으로 측정하기 어려운 실용적 적응(Practical Adaptation), 사회적 상호작용, 장기 계획, 물리적 능력, 창의성, 불확실성 관리, 예상하지 못한 실패에서 회복하는 능력 등이 포함됩니다.

인공지능(Artificial Intelligence)에서는 인지와 지능의 구분이 특히 중요합니다. 기계가 비전(Vision), 언어(Language), 계획, 제어를 위한 매우 뛰어난 개별 모듈을 가지고 있더라도 일반적으로 지능적인 에이전트로 작동하지 못할 수 있습니다. 지능을 위해서는 이러한 구성요소들이 관련 표현을 공유하고, 목표를 조정하고, 지속적인 상태(Persistent State)를 유지하며, 결과로부터 학습하고, 시간에 따라 동작 방식을 적응시켜야 합니다.

고전적 인공지능(Classical AI)은 명시적인 기호(Symbols), 규칙(Rules), 탐색 절차(Search Procedures), 지식 구조(Knowledge Structures)를 통해 인지를 표현하는 경우가 많았습니다. 이러한 시스템은 명확하게 정의된 영역에서 강력한 추론을 보여줄 수 있었지만 강건한 지각과 적응 능력이 부족한 경우가 많았습니다. 이러한 한계는 복잡하고 불확실하며 지속적으로 변화하는 환경에서 지능이 작동하려면 정교한 추론만으로 충분하지 않음을 보여주었습니다.

머신러닝(Machine Learning)은 데이터로부터 획득되는 인지에 초점을 이동시켰습니다. 신경망(Neural Networks)은 모든 규칙을 수동으로 프로그래밍하지 않고도 지각, 예측, 언어, 제어를 위한 표현을 학습했습니다. 이는 인공 인지 능력을 크게 확장했지만, 학습된 특화 모델도 지식을 전이하거나, 익숙하지 않은 조건을 추론하거나, 더 광범위한 목표와 조정할 수 없다면 여전히 좁은 범위에 머무를 수 있습니다.

딥러닝(Deep Learning)은 분산 표현(Distributed Representations)으로부터 강력한 인지 기능이 나타날 수 있음을 보여줍니다. 비전 시스템은 객체를 분류하고, 음성 시스템은 언어를 인식하며, 제어 정책(Control Policies)은 관찰을 행동으로 변환합니다. 그러나 벤치마크에서 높은 성능을 보인다는 사실만으로 광범위한 지능을 의미하지는 않습니다. 시스템은 통계적으로 성공하면서도 인과적 이해, 지속적 기억, 계획, 강건한 적응 능력이 부족할 수 있습니다.

파운데이션 모델(Foundation Models)은 대규모의 다양한 데이터셋에서 재사용 가능한 표현을 학습함으로써 인공 인지의 범위를 확장합니다. 하나의 모델이 여러 작업에 걸쳐 언어 이해, 시각적 해석, 추론, 생성, 멀티모달 상호작용(Multimodal Interaction)을 지원할 수 있습니다. 이는 작업별 인지에서 보다 일반적인 능력으로 이동하는 중요한 변화이지만 광범위한 능력과 완전히 통합된 지능은 여전히 구분되어야 합니다.

대규모 언어 모델(Large Language Models)은 이를 명확하게 보여주는 사례입니다. 이러한 모델은 요약, 번역, 추론, 계획 생성, 개념 설명, 언어적 상호작용을 수행할 수 있습니다. 이러한 능력은 광범위하게 학습된 인지 구조를 반영합니다. 그러나 신뢰할 수 있는 자율 지능(Reliable Autonomous Intelligence)을 위해서는 지속적인 목표, 현실에 기반한 지각(Grounded Perception), 장기 기억(Long-Term Memory), 환경 피드백, 불확실성 처리, 행동 실행, 결과로부터 학습하는 메커니즘이 추가적으로 필요합니다.

멀티모달 파운데이션 모델(Multimodal Foundation Models)은 언어를 이미지, 오디오, 비디오, 센서 데이터 및 다른 양식과 연결함으로써 인지를 확장합니다. 이를 통해 상황에 대한 더욱 풍부한 표현을 구성할 수 있습니다. 멀티모달 지각이 예측과 행동에 연결되면 지능은 더욱 발전하며, 에이전트는 관찰한 내용을 설명하는 것을 넘어 다음에 무엇이 일어나야 하는지를 결정할 수 있습니다.

에이전틱 AI(Agentic AI)는 파운데이션 모델의 능력에 목표 지향적 작동(Goal-Directed Operation)을 추가합니다. 에이전트는 목표를 유지하고, 도구를 선택하고, 행동을 실행하고, 결과를 검사하며, 여러 단계에 걸쳐 작업을 지속할 수 있습니다. 이는 시스템이 고립된 응답을 생성하는 대신 지각-추론-행동 루프(Perception-Reasoning-Action Loop)를 관리하기 시작한다는 점에서 수동적인 인지 능력을 능동적인 지능으로 전환하기 시작합니다.

기억은 이러한 전환에 필수적입니다. 지속적 기억(Persistent Memory)이 없다면 에이전트는 문맥을 반복적으로 재구성해야 하며 장기 작업에서 유용한 경험을 축적하지 못할 수 있습니다. 구조화된 기억(Structured Memory)은 목표, 의사결정, 관찰, 실패, 선호, 환경 상태, 학습된 절차를 지속적으로 유지할 수 있게 합니다. 지능은 모든 것을 조직 없이 저장하는 것이 아니라 이러한 정보를 선택적으로 검색하고 갱신하는 능력을 요구합니다.

월드 모델(World Models)은 인지에서 지능으로 연결되는 또 다른 중요한 다리를 제공합니다. 월드 모델은 환경의 관련 요소가 시간에 따라 어떻게 변화하는지를 표현하며, 일반적으로 행동에 따른 변화를 포함합니다. 가능한 미래 상태를 예측함으로써 에이전트는 실제로 행동하기 전에 결과를 정신적 또는 계산적으로 시뮬레이션할 수 있습니다. 이를 통해 계획, 반사실적 추론(Counterfactual Reasoning), 위험 평가, 효율적인 학습이 가능해집니다.

월드 모델 자체가 곧 지능을 의미하는 것은 아닙니다. 월드 모델은 예측적 인지 구조(Predictive Cognitive Structure)를 제공하지만, 지능적인 시스템은 어떤 미래가 중요한지를 결정하고, 목표에 따라 이를 평가하고, 행동을 선택하고, 실제 결과를 관찰하고, 예측이 실패하면 모델을 수정해야 합니다. 따라서 지능은 월드 모델링(World Modeling)을 지각, 계획, 행동, 학습, 피드백과 폐루프 방식으로 통합하는 과정에서 나타납니다.

강화학습(Reinforcement Learning)은 행동을 결과 및 목표와 연결함으로써 또 다른 구성요소를 제공합니다. 에이전트는 상호작용을 통해 기대 결과를 향상시키는 정책을 학습합니다. 월드 모델과 결합하면 강화학습은 직접 경험뿐 아니라 상상된 궤적(Imagined Trajectories)도 평가할 수 있습니다. 이는 적응적 의사결정을 위한 계산 프레임워크를 제공하지만 여전히 신뢰할 수 있는 표현과 안전 제약조건이 필요합니다.

피지컬 AI(Physical AI)는 인지와 지능의 차이를 특히 명확하게 보여줍니다. 로봇이 객체를 인식하고 명령을 이해하더라도 물리적 작업을 신뢰성 있게 완료하지 못할 수 있습니다. 지능적인 물리적 행동을 위해서는 위치 추정(Localization), 기하학, 동역학(Dynamics), 행동 유도성, 모션 플래닝(Motion Planning), 제어(Control), 불확실성 처리, 안전, 지속적인 피드백이 함께 작동해야 합니다.

따라서 체화 지능(Embodied Intelligence)은 추상적인 인지를 물리적 현실에 기반시키는 것에 의존합니다. '컵(Cup)'이라는 개념만으로는 조작에 충분하지 않습니다. 시스템은 컵이 어디에 있는지, 도달할 수 있는지, 어떻게 파지할 수 있는지, 어느 정도의 힘이 적절한지, 어떤 장애물이 존재하는지, 관찰된 움직임이 예측된 결과와 일치하는지를 판단할 수 있어야 합니다.

지각 파운데이션 모델(Perception Foundation Models)은 풍부한 의미론적 이해(Semantic Understanding)를 제공할 수 있으며, 행동 파운데이션 모델(Action Foundation Models)은 재사용 가능한 행동 패턴을 제공할 수 있습니다. 그러나 어느 하나만으로 완전한 로봇 지능을 구성할 수는 없습니다. 더 광범위한 아키텍처는 지각, 월드 상태(World State), 기억, 월드 모델, 작업 추론(Task Reasoning), 행동 생성(Action Generation), 저수준 제어(Low-Level Control), 안전 모니터링(Safety Monitoring)을 지속적인 폐루프 시스템 안에서 연결해야 합니다.

로봇 지능은 시간적 통합(Temporal Integration)도 필요로 합니다. 행동은 시간에 따라 진행되고 미래의 관찰을 변화시키기 때문에 의사결정을 개별 센서 프레임에만 기반할 수 없습니다. 로봇은 상태를 유지하고, 움직이는 개체를 추적하고, 동역학을 추정하고, 이전 상호작용을 기억하고, 미래 조건을 예측하며, 물리적 세계가 변화함에 따라 지속적으로 계획을 수정해야 합니다.

실시간 제약조건(Real-Time Constraints)은 체화 지능을 많은 오프라인 인지 작업과 구분합니다. 이론적으로 뛰어난 계획이라도 로봇이 이미 행동했어야 하는 시점 이후에 생성된다면 의미가 없습니다. 따라서 지능에는 계산 복잡성을 이용 가능한 시간에 맞추는 능력도 포함됩니다. 빠른 반응형 메커니즘(Reactive Mechanisms), 중간 시간 범위 예측(Medium-Horizon Prediction), 느린 전략적 추론(Strategic Reasoning)이 서로 다른 수준에서 동시에 작동해야 할 수 있습니다.

엣지 컴퓨팅(Edge Computing)은 이러한 자원 문제를 명확하게 보여줍니다. 로봇은 제한된 GPU 성능, 메모리, 배터리 용량, 통신 대역폭, 열적 한계(Thermal Limits)를 가집니다. 지능적인 아키텍처는 모든 모델을 항상 최대 복잡도로 실행하기보다 현재 필요에 따라 계산 자원을 할당해야 합니다. 인지가 물리적 기계 내부에서 작동해야 할 때 자원 인식 지능(Resource-Aware Intelligence)은 필수적입니다.

온프레미스(On-Premise) 또는 클라우드 컴퓨팅(Cloud Computing)은 더 큰 모델, 플릿 수준 학습(Fleet-Level Learning), 장기 분석, 계산 비용이 높은 최적화를 제공하여 인지 능력을 확장할 수 있습니다. 그러나 네트워크 지연과 가용성 문제 때문에 원격 계산이 모든 온보드 지능(Onboard Intelligence)을 대체할 수는 없습니다. 따라서 실용적인 피지컬 AI는 실시간 엣지 시스템과 더욱 강력한 외부 인프라에 분산된 계층적 지능(Hierarchical Intelligence)을 활용하는 것이 효과적입니다.

멀티에이전트 시스템(Multi-Agent Systems)은 개별 인지에서 집단적 조정으로 지능을 확장합니다. 각각의 로봇은 지역적 지각과 목표를 유지하면서 지도, 작업, 관찰, 학습된 정보를 다른 로봇과 공유할 수 있습니다. 에이전트들이 효율적으로 조정하고, 중복 작업을 방지하고, 상충하는 계획을 해결하며, 분산된 정보를 이용하여 그룹 전체의 성능을 향상시킬 때 집단 지능(Collective Intelligence)이 나타납니다.

인간-AI 협업(Human-AI Collaboration)은 또 다른 형태의 분산 지능(Distributed Intelligence)을 제공합니다. 인간은 문맥적 이해, 가치 판단, 유연한 판단력, 광범위한 경험을 제공하고, 기계는 계산, 기억, 모니터링, 대규모 패턴 처리를 제공합니다. 효과적인 협업을 위해서는 양쪽이 목표, 책임, 불확실성, 시스템 상태에 대해 충분히 정렬된 모델을 유지해야 합니다.

지능을 평가할 때 신뢰성(Reliability)은 필수적입니다. 신뢰할 수 없는 행동을 보이는 능력은 실질적인 가치가 제한될 수 있기 때문입니다. 지능 시스템은 불확실성을 인식하고, 실패를 탐지하며, 안전한 운용을 유지하고, 오류에서 복구하며, 필요할 경우 도움을 요청할 수 있어야 합니다. 인지 능력의 한계를 아는 것은 그 능력의 정상 성능을 극대화하는 것만큼 중요할 수 있습니다.

강건성(Robustness)은 조건이 변화하더라도 유용한 성능을 유지하는 능력을 의미합니다. 좁은 데이터 분포에서 학습된 인지 시스템은 조명, 지형, 언어, 객체 또는 사용자 행동이 변하면 실패할 수 있습니다. 더 높은 수준의 지능은 분포 변화(Distribution Shifts)를 식별하고, 표현을 적응시키며, 대안 전략을 사용하고, 더 이상 현실과 일치하지 않는 가정을 높은 확신으로 적용하지 않아야 합니다.

자율성(Autonomy)은 지능과 관련되어 있지만 동일한 개념으로 취급해서는 안 됩니다. 단순한 온도조절기(Thermostat)는 매우 낮은 지능으로도 자율적으로 작동할 수 있으며, 강력한 추론 시스템은 인간의 통제 아래에서 작동할 수도 있습니다. 높은 자율성은 시스템에 위임된 의사결정 범위를 확대하는 것이며, 지능은 그러한 의사결정을 얼마나 능숙하게 수행할 수 있는지를 결정합니다.

에이전시(Agency)는 지속적인 목표 지향적 행동을 추가합니다. 에이전트는 환경에 영향을 주는 행동을 선택하고 목표를 향한 진행 상태를 평가합니다. 지능적 에이전시는 시간에 따라 목표를 유지하고, 충돌을 해결하고, 계획을 적응시키고, 자원을 관리하고, 결과에서 학습하며, 가능한 행동과 바람직한 행동, 안전한 행동, 필요한 행동을 구분하는 능력을 요구합니다.

의식(Consciousness) 역시 인지 및 지능과 구분해야 합니다. 인지 처리와 지능적 행동이 자동적으로 주관적 자각(Subjective Awareness)의 존재를 의미하지는 않습니다. 인간은 인지, 지능, 의식적 경험을 함께 가지지만, 공학적 시스템은 인간과 유사한 주관적 경험을 가지고 있다는 증거 없이도 정교한 지각, 추론, 학습, 계획을 수행할 수 있습니다.

이러한 구분은 고도화된 AI에 관한 논의에서 불필요한 혼란을 방지합니다. 모델 크기, 추론 성능, 자율성, 멀티모달 능력을 증가시키는 것은 기능적 지능(Functional Intelligence)을 향상시킬 수 있지만 의식에 관한 철학적 질문에 답하는 것은 아닙니다. 따라서 주관적 경험 자체를 연구하는 경우가 아니라면 공학적 평가는 관찰 가능한 능력, 한계, 신뢰성, 적응, 결과에 초점을 맞추어야 합니다.

유용한 아키텍처 관점에서는 인지를 서로 상호작용하는 기능적 계층(Functional Layers)의 집합으로 볼 수 있습니다. 지각은 표현을 구성하고, 주의는 자원을 할당하며, 기억은 정보를 보존하고, 학습은 모델을 수정하고, 추론은 지식을 변환하며, 예측(Prediction)은 미래를 추정하고, 계획은 행동을 조직하며, 제어는 행동을 실행합니다. 지능은 전체 아키텍처가 변화하는 조건에서 목표를 얼마나 효과적으로 달성하는지를 나타냅니다.

이러한 관점에서 지능은 하나의 신경망, 알고리즘 또는 모듈에 위치하지 않습니다. 지능은 구성요소들의 조정으로부터 나타나는 시스템 수준의 속성(System-Level Property)입니다. 매우 뛰어난 지각 모델도 잘못된 계획을 완전히 보완할 수 없으며, 정교한 추론 역시 센싱, 제어, 기억, 안전 메커니즘이 부적절하면 신뢰할 수 있는 물리적 행동을 만들어낼 수 없습니다.

동일한 원리는 단순히 모델 규모(Model Scale)를 증가시키는 것만으로 실용적인 지능이 비례하여 증가하지 않을 수 있는 이유를 설명합니다. 더 큰 모델은 표현과 추론 능력을 향상시킬 수 있지만 완전한 에이전트에는 여전히 기억 아키텍처(Memory Architectures), 도구 사용(Tool Use), 월드 모델, 피드백 루프, 계획 메커니즘, 안전 제약조건, 물리적 또는 디지털 환경과 연결되는 인터페이스가 필요합니다.

따라서 미래 AI 시스템은 파운데이션 모델이 광범위한 공유 표현을 제공하더라도 점차 모듈화(Modular)되고 계층화(Hierarchical)될 가능성이 높습니다. 특화된 지각, 예측, 계획, 제어, 검증, 기억 메커니즘이 범용 모델 주변에서 작동할 수 있습니다. 지능은 가장 큰 모델 자체의 능력뿐 아니라 이러한 구성요소들을 얼마나 효과적으로 오케스트레이션(Orchestration)하는지에 달려 있습니다.

인지과학(Cognitive Science)은 여러 불완전한 메커니즘이 효과적으로 협력하는 생물학적 지능(Biological Intelligence)을 보여주기 때문에 유용한 지침을 제공합니다. 인간의 지각은 불완전하고, 기억에는 오류가 있으며, 추론에는 편향이 있고, 주의는 제한적입니다. 그럼에도 인간은 학습, 외부 도구, 의사소통, 사회적 협력, 추상화, 예측, 적응형 제어를 통해 이러한 한계를 보완합니다.

인공지능은 인간의 인지를 정확하게 복제할 필요는 없습니다. 기계는 고차원 기억(High-Dimensional Memory), 정밀한 계산, 대규모 데이터베이스, 시뮬레이션, 분산 처리(Distributed Processing), 인간에게 없는 센서 양식을 사용할 수 있습니다. 그러나 선택적 주의, 계층적 조직, 예측, 피드백, 불확실성 관리, 적응과 같은 원리는 효과적인 지능을 구축하는 데 여전히 중요한 가치를 가집니다.

인지와 지능의 구분은 궁극적으로 개별 능력에서 통합(Integration)으로 관심의 초점을 이동시킵니다. 인지는 알고, 표현하고, 학습하고, 추론하고, 행동하기 위한 메커니즘을 제공합니다. 지능은 이러한 메커니즘을 사전에 모두 예측할 수 없는 다양한 상황에서 일관되고, 적응적이며, 효율적이고, 목표 지향적인 행동으로 조직하는 능력을 의미합니다.

피지컬 AI에서는 이러한 구분이 실질적인 아키텍처 원칙(Architecture Principle)이 됩니다. 지각 모델, 언어 모델, 월드 모델, 기억 시스템, 플래너(Planners), 제어기(Controllers), 안전 모듈(Safety Modules)은 각각 인지 능력을 제공합니다. 이러한 구성요소들이 상태를 공유하고, 결과를 예측하고, 의사결정을 조정하고, 물리적 피드백에서 학습하고, 제한된 자원을 관리하며, 변화하는 환경에서 신뢰할 수 있는 행동을 유지할 때 지능이 나타납니다.

따라서 장기적인 목표는 단순히 더 많은 인지 기능을 가진 기계를 만드는 것이 아니라 지각, 예측, 추론, 학습, 계획, 행동에 걸쳐 이러한 기능들을 통합할 수 있는 시스템을 구축하는 것입니다. 이러한 통합이 발전함에 따라 인공 시스템은 특화된 인지 도구(Specialized Cognitive Tools)에서 점차 더 일반적이고, 신뢰할 수 있으며, 물리적 현실에 기반한 지능(Physically Grounded Intelligence)을 갖춘 적응형 에이전트(Adaptive Agents)로 발전할 수 있습니다.

##  

## 01.08 Implications for AI [w/Code]

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

Cognitive science has major implications for artificial intelligence because it provides models of how intelligent agents perceive, attend, remember, learn, reason, predict, decide, and act under limited resources. Rather than treating intelligence as a single algorithm, cognitive science suggests that capable AI emerges from the coordinated interaction of multiple functions operating continuously within an environment.

One important implication is that perception should not be treated as passive recognition. Biological cognition actively selects information according to goals, expectations, uncertainty, and possible actions. AI systems similarly benefit when perception is connected with task context, memory, prediction, and action, allowing the system to determine not only what exists in the environment but also what information currently matters.

Attention provides a mechanism for managing limited computational resources. Real environments contain more information than any practical system can process at maximum resolution simultaneously. AI architectures can therefore use selective attention to prioritize relevant objects, spatial regions, sensor streams, memories, or reasoning steps according to goals, uncertainty, novelty, risk, and expected information value.

This principle is especially important for embodied and real-time AI. A robot processing multiple cameras, LiDAR, radar, audio, proprioception, and other sensor streams cannot always allocate equal computation to every signal. Adaptive attention allows processing capacity to move toward pedestrians, obstacles, manipulation targets, unusual events, or uncertain regions while reducing unnecessary computation elsewhere.

Memory is another central implication. Intelligent behavior requires more than processing the current input because present situations are often understandable only in relation to previous observations and actions. AI systems therefore need mechanisms for short-term context, episodic experience, semantic knowledge, procedural skills, and long-term information that can be retrieved and updated according to current goals.

Working memory provides a useful model for maintaining information required during an ongoing task. An artificial agent may need to remember temporary goals, intermediate reasoning results, recently observed objects, unresolved uncertainties, or steps already completed. Without such state, complex behavior can fragment into disconnected reactions even when individual perception and reasoning modules are highly capable.

Long-term memory enables knowledge accumulation across tasks and operating periods. Instead of repeatedly solving equivalent problems from the beginning, an AI system can preserve useful representations, successful strategies, environmental knowledge, and previous failures. Effective memory architecture must also support retrieval, consolidation, updating, forgetting, and conflict resolution rather than simply storing unlimited data.

Learning from experience is a fundamental requirement for adaptive AI. Cognitive science shows that learning occurs through multiple mechanisms, including association, prediction, reinforcement, imitation, abstraction, and interaction. Artificial systems can similarly combine supervised learning, weakly supervised learning, self-supervised learning, reinforcement learning, imitation learning, and continual learning according to available data and operational objectives.

Self-supervised learning is particularly important because intelligent agents encounter enormous amounts of unlabeled experience. Images, video, audio, robot trajectories, sensor sequences, and interaction histories contain structural information even when explicit labels are unavailable. Predicting missing information, future states, relationships, or transformations allows useful representations to emerge from the data itself.

Weakly supervised learning provides another practical strategy when precise annotation is expensive. Coarse labels, incomplete annotations, automatically generated descriptions, event metadata, task outcomes, or noisy human feedback can guide representation learning without requiring exhaustive manual labeling. This is especially valuable for robotics, where large-scale physical interaction data is difficult and expensive to annotate precisely.

Continual learning follows naturally from cognitive adaptation. Real intelligent systems cannot assume that training ends permanently before deployment. Environments, users, tasks, hardware, policies, and operating conditions change over time. AI therefore requires mechanisms that incorporate new knowledge while protecting important previous capabilities from catastrophic forgetting.

Transfer and generalization are essential because intelligence cannot depend on collecting a new dataset for every possible situation. Cognitive systems reuse concepts and strategies across related problems. Artificial intelligence should similarly learn representations that capture reusable structure, allowing knowledge acquired from one environment, robot platform, object category, or task to accelerate adaptation to another.

Abstraction provides the foundation for such transfer. Raw sensory data contains enormous detail, but intelligent decisions often depend on higher-level structure such as objects, relationships, affordances, intentions, constraints, and causal dependencies. AI architectures should therefore construct representations at multiple levels, moving from sensor features toward semantic, relational, task-oriented, and predictive world representations.

Hierarchical cognition suggests hierarchical AI architectures. Low-level processes can manage rapid sensor interpretation and motor control, intermediate processes can represent objects and local tasks, and higher levels can manage goals, strategies, long-term planning, and reasoning. Different levels may operate at different frequencies, allowing rapid reaction and slower deliberation to coexist within the same intelligent system.

This is particularly relevant for Physical AI, where millisecond-level control cannot wait for computationally expensive high-level reasoning. Fast control loops can stabilize motion and respond to immediate hazards, while medium-level systems perform localization, perception, and trajectory planning. Slower cognitive layers can reason about missions, future scenarios, task priorities, and long-term adaptation.

Mental models suggest that AI systems require internal representations of how their environments behave. Recognizing the current state is insufficient when actions have future consequences. An intelligent agent should represent entities, relationships, dynamics, constraints, and possible transitions so that it can anticipate how the world may change before committing to an action.

World models provide a computational implementation of this principle. A world model estimates how relevant environmental states evolve through time and how actions influence those transitions. By predicting possible futures, an AI agent can compare alternative actions, evaluate risks, simulate outcomes, and choose behavior using predicted consequences rather than relying entirely on reactive mappings.

For robotics, world models can integrate information from cameras, LiDAR, radar, IMU, GNSS, joint states, force sensors, maps, and previous actions into a temporally coherent representation. The objective is not necessarily to reconstruct every physical detail, but to preserve the information required for prediction, planning, control, interaction, and safety.

Prediction is therefore a central component of intelligent cognition. Humans constantly anticipate motion, consequences, intentions, and environmental changes. AI systems can similarly predict future observations, object trajectories, occupancy, agent behavior, task outcomes, or latent states. Prediction converts perception from a description of the present into a basis for reasoning about possible futures.

Prediction errors can also become learning signals. When the observed future differs from the predicted future, the discrepancy indicates that some part of the internal representation, dynamics model, or assumption is incomplete. Continuous comparison between prediction and observation can therefore support adaptation and improve the world model during long-term operation.

Causal reasoning extends prediction beyond statistical correlation. An intelligent system should ideally distinguish events that merely occur together from relationships in which actions or conditions actually influence outcomes. Causal representations can improve intervention planning, transfer across environments, explanation, and robustness when superficial statistical patterns change.

Counterfactual reasoning further expands intelligent decision making. An agent can ask what might happen if a different action were selected or if some condition changed. Combined with a world model, counterfactual simulation allows multiple candidate futures to be evaluated without physically executing every possibility, improving planning efficiency and reducing unnecessary risk.

Planning becomes more powerful when prediction, memory, goals, and uncertainty are integrated. Rather than generating a fixed action sequence, an intelligent planner can maintain alternatives, evaluate predicted consequences, monitor execution, and revise its plan when observations differ from expectations. Planning therefore becomes a continuous closed-loop cognitive process rather than a one-time computation.

Cognitive science also emphasizes bounded rationality. Intelligent agents operate with limited time, information, memory, and computational resources, so perfectly optimal decisions are often impossible. Practical AI should therefore seek sufficiently good decisions within available constraints rather than assuming unlimited computation. This principle is especially important for real-time autonomous systems.

Resource-aware intelligence can dynamically allocate computation according to task importance. A routine situation may require only lightweight perception and control, while an unusual or high-risk event may justify activating larger models, additional sensors, longer reasoning, or external computational resources. Such adaptive computation can improve both efficiency and reliability.

Cognitive load has direct implications for AI architecture. If too many tasks compete for the same computational resources, latency can increase and critical functions may be delayed. Intelligent systems therefore need scheduling, prioritization, memory management, model selection, and graceful degradation mechanisms that preserve essential capabilities when computational demand exceeds available capacity.

Human error research provides another important lesson. Intelligent systems should not be designed under the assumption that individual components will always be correct. Sensors fail, models misclassify, memories become inconsistent, predictions become inaccurate, and planners can choose inappropriate actions. Reliability must therefore emerge from architecture-level detection, containment, verification, and recovery.

Redundancy can reduce dependence on individual components. Multiple sensors, models, algorithms, or reasoning pathways can provide independent evidence about important states. However, effective redundancy requires diversity because identical components trained on similar data may fail in similar ways. Reliability improves when complementary information sources expose different failure modes.

Uncertainty estimation is essential for managing such failures. An AI system should distinguish between outputs supported by strong evidence and outputs produced under unfamiliar or ambiguous conditions. Confidence estimates can influence whether the system acts immediately, gathers more information, activates additional models, reduces speed, requests human assistance, or enters a safe operating mode.

Metacognition suggests that advanced AI should monitor its own reasoning and performance. Artificial metacognitive mechanisms can evaluate confidence, detect contradictions, estimate whether additional information is needed, compare alternative reasoning paths, and verify outputs before high-consequence actions. Intelligence therefore includes mechanisms for evaluating cognition rather than merely executing it.

This leads naturally to self-monitoring architectures. An autonomous system can compare predicted and observed states, track performance metrics, detect distribution shifts, identify abnormal sensor behavior, and estimate whether its current policy remains valid. Such monitoring provides a foundation for graceful degradation and safe adaptation when normal assumptions fail.

Error recovery should be considered a primary capability rather than an exceptional procedure. Real-world AI will inevitably encounter unexpected objects, unusual terrain, sensor degradation, communication loss, incorrect predictions, and incomplete instructions. Systems should therefore preserve safe states, maintain recovery options, and learn how to return from errors instead of assuming flawless execution.

Resilience extends this concept by emphasizing continued operation under disruption. A resilient AI system can detect changing conditions, reorganize resources, switch strategies, reduce functionality when necessary, and restore capabilities after failure. For Physical AI, resilience may involve changing sensors, reducing speed, replanning routes, switching controllers, or transferring selected tasks to another robot or human operator.

Human-AI interaction is strongly influenced by cognitive science. Users construct mental models of AI systems based on observed behavior, explanations, interfaces, and previous experience. If system behavior is unpredictable or hidden, users may develop incorrect expectations. Transparent state information and consistent interaction therefore help humans understand what the AI knows, intends, and cannot reliably determine.

Trust should be calibrated rather than maximized. Excessive trust can lead users to accept incorrect recommendations, while insufficient trust prevents useful automation from being used effectively. AI systems should communicate confidence, limitations, uncertainty, and reasons for important decisions in ways that support appropriate reliance rather than creating an artificial impression of certainty.

Explainability is most useful when it supports human cognition. Explanations should reveal information relevant to decisions, such as evidence, constraints, uncertainty, alternatives, or expected consequences. Extremely detailed explanations can increase cognitive load, while oversimplified explanations can hide important limitations. Effective explanation therefore depends on the user\'s task and information needs.

Human attention should also be treated as a limited resource. Autonomous systems that continuously produce low-value alerts can overwhelm operators and make important events harder to detect. Intelligent alerting should prioritize urgency, uncertainty, consequence, and required intervention, allowing human attention to be concentrated where it provides the greatest benefit.

Shared situation awareness becomes important when humans and AI cooperate. Both sides should maintain compatible representations of goals, system state, responsibilities, constraints, and expected next actions. When these representations diverge, humans may expect the AI to act while the AI waits for human input, or both may perform conflicting actions.

Human-AI teaming therefore requires explicit responsibility allocation. Some functions are well suited to machine computation, monitoring, memory, and pattern recognition, while humans remain valuable for contextual judgment, ethical interpretation, unusual situations, and goal revision. Responsibilities may also change dynamically depending on confidence, workload, environmental complexity, and system condition.

Embodied cognition has profound implications for robotics. Intelligence does not need to exist entirely inside an abstract reasoning module because physical interaction itself can provide information. A robot can move a camera to resolve ambiguity, touch an object to estimate its properties, reposition itself to improve geometry, or manipulate the environment to simplify a task.

This principle motivates active perception. Instead of passively accepting available observations, an intelligent robot chooses actions that improve future sensing. It may move toward an uncertain region, change viewpoint, illuminate an object, reposition a manipulator, or request another sensor measurement. Perception and action therefore become mutually dependent components of cognition.

Affordances provide another useful concept. Objects are not represented only by appearance but also by possible interactions. A handle affords pulling, a flat surface may afford placement, and an opening may afford passage if the robot\'s geometry permits it. Representing affordances connects semantic perception directly with planning and physical action.

Sensorimotor learning similarly connects perception with control. Rather than learning visual representations independently from behavior, an agent can learn how observations change as a consequence of its own actions. This creates representations grounded in interaction and may improve the ability to predict controllable aspects of the environment.

Foundation models can benefit from these cognitive principles. Perception foundation models can provide broad semantic representations, language foundation models can support reasoning and communication, and action foundation models can encode reusable behavior. Their greatest value emerges when they become components of a larger architecture rather than isolated universal solutions.

A perception foundation model can identify objects, scenes, relationships, and semantic concepts, but task-specific adaptation remains necessary. Fine-tuning, adapters, prompt conditioning, or task-specific heads can connect broad pretrained representations to particular sensors, environments, robots, and operational requirements while avoiding the cost of training every capability from the beginning.

Action foundation models can similarly provide general motion or manipulation priors learned across large collections of robot experience. A new robot may adapt these representations to its morphology, actuator limits, payload, sensors, and task requirements. This can reduce the amount of platform-specific training needed while preserving reusable behavioral knowledge.

However, foundation models should not replace deterministic safety mechanisms where physical consequences are severe. Learned models can generate candidate interpretations, predictions, plans, or actions, while independent constraints verify collision risk, joint limits, stability, speed, force, reachable space, and other safety conditions before execution.

World models can connect perception and action foundation models. Perception models provide semantic and geometric state information, the world model predicts how that state may evolve, and action models generate candidate behaviors. A planner can then evaluate predicted consequences and select actions while safety mechanisms enforce physical and operational constraints.

This architecture creates a continuous loop from sensing to representation, prediction, reasoning, planning, action, observation, and learning. Each action changes the environment and produces new sensory evidence. The new evidence updates the world state and tests previous predictions, allowing the system to continuously correct itself rather than relying on a static sequence of decisions.

Reinforcement learning can operate within this loop by associating actions and predicted futures with long-term objectives. Model-based reinforcement learning can use world-model simulations to evaluate many trajectories without executing all of them physically. This improves data efficiency and can reduce the cost and risk associated with learning directly through real-world trial and error.

Imitation learning can provide an efficient initial behavioral prior. Human demonstrations contain information about perception, task decomposition, movement, correction, and strategy. AI systems can learn from these demonstrations and later improve through self-supervised learning, reinforcement learning, simulation, or real-world experience rather than beginning entirely from random exploration.

Simulation is especially valuable for Physical AI because physical data collection is expensive and potentially dangerous. Large numbers of scenarios can be generated to train perception, prediction, planning, and control. However, simulation cannot perfectly reproduce reality, making domain randomization, real-world fine-tuning, adaptation, and continuous validation necessary.

Cognitive development suggests another useful direction for AI. Humans do not begin with expert-level competence but gradually acquire increasingly complex abilities through interaction. Artificial agents may similarly benefit from curricula in which basic perception and control are learned first, followed by object interaction, task composition, planning, social coordination, and increasingly autonomous behavior.

Curriculum learning can reduce the difficulty of complex tasks by organizing experience according to increasing complexity. Earlier capabilities become foundations for later learning. In robotics, navigation, localization, obstacle avoidance, manipulation, semantic reasoning, and mission planning can be progressively integrated rather than trained as one enormous problem from the beginning.

Development also highlights the importance of exploration. An intelligent agent should sometimes gather information even when no immediate reward is available. Curiosity, novelty detection, information gain, and uncertainty reduction can provide intrinsic objectives that encourage the system to discover useful structure before it becomes necessary for a specific task.

Social learning can further accelerate artificial intelligence. Robots and AI agents do not need to learn everything independently if they can learn from humans or other agents. Demonstrations, corrections, language instructions, shared maps, fleet experience, and transferred models can distribute knowledge across a population and dramatically reduce repeated learning.

Fleet learning is particularly important for robotics. Individual robots can collect local experience while centralized or on-premise infrastructure aggregates data, trains improved models, evaluates failures, and distributes validated updates. This creates a cycle in which experience from many robots contributes to the improvement of each individual robot.

Such architectures naturally divide intelligence between edge and external computation. Real-time perception, safety, localization, control, and immediate planning should remain available onboard, while computationally intensive training, fleet analysis, large-scale simulation, long-term memory consolidation, and large foundation models may operate on on-premise or cloud infrastructure.

This division resembles hierarchical cognition because different computational layers operate over different timescales and responsibilities. Edge systems manage immediate interaction, on-premise systems coordinate multiple robots and provide heavier reasoning, and larger infrastructure can support long-term learning and global optimization. Intelligence becomes distributed across a computational ecosystem.

Multi-agent cognition expands this architecture further. Robots can share observations, maps, task states, predictions, and learned representations. One robot\'s experience with a hazard or environmental change can inform others before they encounter it directly. Collective intelligence therefore emerges through communication, coordination, and shared learning rather than simply increasing the capability of each robot independently.

Language can serve as an interface between cognitive modules as well as between humans and AI. Natural-language representations can describe goals, constraints, observations, plans, explanations, and failures. However, physical systems should ground language in sensor observations and executable actions so that linguistic reasoning remains connected to the actual state of the environment.

Multimodal AI is particularly important for this grounding. Language, vision, audio, geometry, motion, proprioception, and physical interaction provide complementary information. Combining them allows AI systems to build richer representations than any single modality can provide and supports reasoning that connects semantic meaning with spatial and physical constraints.

The distinction between cognition and intelligence implies that simply increasing the performance of individual AI models is insufficient. A system may have excellent vision, language, prediction, and control components but still behave poorly if information cannot move effectively between them. System architecture and orchestration therefore become central problems in advanced AI engineering.

Shared representations can reduce fragmentation between components. A common world state can provide perception, memory, prediction, planning, and control with consistent information about relevant entities, relationships, uncertainty, and goals. However, the representation should support multiple levels of abstraction because different modules require different spatial, temporal, and semantic detail.

Temporal representation is particularly important. Intelligence must connect past observations, current state, and possible futures. Short-term dynamics support immediate control, medium-horizon predictions support local planning, and long-term models support strategy and mission reasoning. Multiple temporal scales may therefore need to coexist within the same world-model architecture.

The future of AI is likely to depend increasingly on closed-loop systems rather than isolated models. A model that generates one prediction or response performs a cognitive function, while an intelligent agent must observe consequences, maintain state, update beliefs, correct errors, and continue pursuing goals. Feedback transforms static capability into adaptive behavior.

For Physical AI, this means that intelligence should be designed around repeated cycles of perception, world-state estimation, prediction, reasoning, planning, action, verification, and learning. The architecture must remain connected to physical reality at every cycle so that internal representations are continually corrected by actual sensor evidence and interaction outcomes.

Safety must be integrated into this loop rather than added only after intelligent behavior has been generated. Risk estimation, uncertainty monitoring, constraint checking, fallback behaviors, emergency stopping, and human intervention mechanisms should operate continuously. More capable cognition increases the range of possible actions, making reliable safety architecture even more important.

Ethical and social considerations also become increasingly significant as AI receives greater autonomy. Intelligent systems may make decisions affecting people, resources, access, safety, and privacy. Cognitive capability alone does not determine appropriate goals. Human values, legal constraints, organizational policies, accountability, and governance must therefore shape how intelligence is deployed.

The broader implication is that artificial intelligence should be understood as a system-level discipline. Models remain essential, but intelligence emerges from the interaction among models, memory, sensors, tools, goals, world representations, planning, feedback, learning, safety mechanisms, humans, and computational infrastructure.

Cognitive science therefore offers more than biological inspiration. It provides architectural principles for building AI systems that operate under uncertainty and limited resources: selective attention, structured memory, predictive internal models, hierarchical processing, adaptive learning, metacognition, active perception, feedback, error recovery, and coordinated perception-action loops.

These principles become increasingly important as AI moves from digital prediction toward autonomous interaction with the physical world. Physical AI must not only recognize and reason but also predict consequences, manage computational resources, understand uncertainty, act safely, recover from mistakes, learn continuously, and cooperate with humans and other machines.

The long-term implication for AI is a transition from isolated task models toward integrated cognitive architectures. Foundation models can provide broad reusable capabilities, world models can provide predictive understanding, memory can preserve experience, planners can organize future behavior, and action models can connect decisions to the environment. Their coordinated operation produces increasingly capable intelligent agents.

Ultimately, progress toward more general artificial intelligence is likely to depend less on a single universal algorithm than on the successful integration of complementary cognitive capabilities. Intelligence emerges when perception, memory, learning, prediction, reasoning, planning, action, metacognition, and safety form a continuous adaptive system that can pursue goals reliably while learning from its interaction with the world.

인지과학(Cognitive Science)은 지능형 에이전트(Intelligent Agent)가 제한된 자원 아래에서 어떻게 지각하고, 주의를 기울이고, 기억하고, 학습하고, 추론하고, 예측하고, 의사결정하며, 행동하는지에 대한 모델을 제공하기 때문에 인공지능(Artificial Intelligence)에 중요한 시사점을 제공합니다. 인지과학은 지능을 하나의 알고리즘으로 보기보다 환경 안에서 지속적으로 작동하는 여러 기능의 조정된 상호작용을 통해 유능한 AI가 나타난다고 봅니다.

중요한 시사점 중 하나는 지각(Perception)을 수동적인 인식으로만 취급해서는 안 된다는 것입니다. 생물학적 인지(Biological Cognition)는 목표, 기대, 불확실성, 가능한 행동에 따라 능동적으로 정보를 선택합니다. AI 시스템 역시 지각을 작업 문맥(Task Context), 기억(Memory), 예측(Prediction), 행동(Action)과 연결함으로써 환경에 무엇이 존재하는지뿐 아니라 현재 어떤 정보가 중요한지를 판단할 수 있을 때 더 효과적으로 작동합니다.

주의(Attention)는 제한된 계산 자원(Computational Resources)을 관리하는 메커니즘을 제공합니다. 실제 환경에는 어떠한 실용적인 시스템도 모든 정보를 동시에 최대 해상도로 처리할 수 없을 정도로 많은 정보가 존재합니다. 따라서 AI 아키텍처는 선택적 주의(Selective Attention)를 사용하여 목표, 불확실성, 새로움(Novelty), 위험(Risk), 기대 정보 가치(Expected Information Value)에 따라 관련 객체, 공간 영역, 센서 스트림, 기억 또는 추론 단계를 우선적으로 처리할 수 있습니다.

이러한 원리는 체화형(Embodied) 및 실시간 AI(Real-Time AI)에서 특히 중요합니다. 여러 카메라, 라이다(LiDAR), 레이더(Radar), 오디오(Audio), 고유수용감각(Proprioception), 기타 센서 스트림을 처리하는 로봇은 모든 신호에 항상 동일한 계산량을 할당할 수 없습니다. 적응형 주의(Adaptive Attention)는 보행자, 장애물, 조작 대상, 비정상 사건, 불확실한 영역에 처리 능력을 집중하면서 다른 영역의 불필요한 계산을 줄일 수 있습니다.

기억은 또 다른 핵심적인 시사점을 제공합니다. 현재 상황은 이전의 관찰 및 행동과 연결해야 이해할 수 있는 경우가 많기 때문에 지능적 행동(Intelligent Behavior)은 현재 입력만을 처리하는 것 이상을 요구합니다. 따라서 AI 시스템은 단기 문맥(Short-Term Context), 일화적 경험(Episodic Experience), 의미론적 지식(Semantic Knowledge), 절차적 기술(Procedural Skills), 장기 정보(Long-Term Information)를 현재 목표에 따라 검색하고 갱신할 수 있는 메커니즘을 필요로 합니다.

작업 기억(Working Memory)은 진행 중인 작업에 필요한 정보를 유지하기 위한 유용한 모델을 제공합니다. 인공 에이전트(Artificial Agent)는 임시 목표, 중간 추론 결과, 최근 관찰한 객체, 해결되지 않은 불확실성 또는 이미 완료된 단계를 기억해야 할 수 있습니다. 이러한 상태가 없다면 개별 지각 및 추론 모듈이 매우 뛰어나더라도 복잡한 행동은 서로 연결되지 않은 반응으로 분절될 수 있습니다.

장기 기억(Long-Term Memory)은 여러 작업과 운영 기간에 걸쳐 지식을 축적할 수 있도록 합니다. AI 시스템은 동일한 문제를 매번 처음부터 다시 해결하는 대신 유용한 표현, 성공적인 전략, 환경 지식, 이전의 실패를 보존할 수 있습니다. 효과적인 기억 아키텍처(Memory Architecture)는 단순히 무제한 데이터를 저장하는 것이 아니라 검색, 통합(Consolidation), 갱신, 망각(Forgetting), 충돌 해결(Conflict Resolution)을 지원해야 합니다.

경험으로부터의 학습(Learning from Experience)은 적응형 AI(Adaptive AI)의 기본 요구사항입니다. 인지과학은 학습이 연합(Association), 예측, 강화(Reinforcement), 모방(Imitation), 추상화(Abstraction), 상호작용(Interaction) 등 다양한 메커니즘을 통해 이루어진다는 것을 보여줍니다. 인공 시스템도 이용 가능한 데이터와 운영 목표에 따라 지도학습(Supervised Learning), 약지도학습(Weakly Supervised Learning), 자기지도학습(Self-Supervised Learning), 강화학습(Reinforcement Learning), 모방학습(Imitation Learning), 지속학습(Continual Learning)을 결합할 수 있습니다.

자기지도학습(Self-Supervised Learning)은 지능형 에이전트가 방대한 양의 라벨이 없는 경험을 접하기 때문에 특히 중요합니다. 이미지, 비디오, 오디오, 로봇 궤적(Robot Trajectories), 센서 시퀀스(Sensor Sequences), 상호작용 기록에는 명시적인 라벨이 없어도 구조적인 정보가 포함되어 있습니다. 누락된 정보, 미래 상태, 관계 또는 변환을 예측함으로써 데이터 자체로부터 유용한 표현을 학습할 수 있습니다.

약지도학습(Weakly Supervised Learning)은 정밀한 주석(Annotation)을 생성하는 비용이 높은 경우에 사용할 수 있는 또 다른 실용적인 전략입니다. 거친 라벨(Coarse Labels), 불완전한 주석, 자동 생성 설명, 이벤트 메타데이터(Event Metadata), 작업 결과, 잡음이 포함된 인간 피드백을 활용하면 모든 데이터를 수작업으로 정밀하게 라벨링하지 않고도 표현 학습을 유도할 수 있습니다. 이는 대규모 물리적 상호작용 데이터를 정확하게 주석 처리하기 어려운 로보틱스(Robotics)에서 특히 유용합니다.

지속학습(Continual Learning)은 인지적 적응(Cognitive Adaptation)에서 자연스럽게 도출됩니다. 실제 지능형 시스템은 배포 전에 학습이 영구적으로 종료된다고 가정할 수 없습니다. 환경, 사용자, 작업, 하드웨어, 정책, 운영 조건은 시간에 따라 변화합니다. 따라서 AI는 치명적 망각(Catastrophic Forgetting)으로부터 중요한 기존 능력을 보호하면서 새로운 지식을 통합할 수 있는 메커니즘을 필요로 합니다.

전이(Transfer)와 일반화(Generalization)는 가능한 모든 상황마다 새로운 데이터셋을 수집하는 방식으로는 지능을 구현할 수 없기 때문에 필수적입니다. 인지 시스템은 관련 문제들 사이에서 개념과 전략을 재사용합니다. 인공지능 역시 하나의 환경, 로봇 플랫폼, 객체 범주 또는 작업에서 획득한 지식이 다른 환경이나 작업으로의 적응을 가속할 수 있도록 재사용 가능한 구조를 포착하는 표현을 학습해야 합니다.

추상화(Abstraction)는 이러한 전이의 기반을 제공합니다. 원시 감각 데이터(Raw Sensory Data)에는 방대한 세부 정보가 포함되어 있지만 지능적인 의사결정은 객체, 관계, 행동 유도성(Affordances), 의도(Intentions), 제약조건, 인과적 의존성(Causal Dependencies)과 같은 상위 수준 구조에 의존하는 경우가 많습니다. 따라서 AI 아키텍처는 센서 특징에서 의미론적, 관계적, 작업 지향적, 예측적 월드 표현(World Representation)으로 이동하는 다중 수준의 표현을 구성해야 합니다.

계층적 인지(Hierarchical Cognition)는 계층적 AI 아키텍처(Hierarchical AI Architecture)의 필요성을 시사합니다. 하위 수준 프로세스는 빠른 센서 해석과 모터 제어를 담당하고, 중간 수준 프로세스는 객체와 지역적 작업을 표현하며, 상위 수준에서는 목표, 전략, 장기 계획, 추론을 관리할 수 있습니다. 서로 다른 계층은 서로 다른 주기로 작동하여 빠른 반응과 느린 숙고(Deliberation)가 하나의 지능 시스템 안에서 공존할 수 있도록 합니다.

이는 밀리초 수준의 제어가 계산 비용이 높은 상위 수준 추론을 기다릴 수 없는 피지컬 AI(Physical AI)에서 특히 중요합니다. 빠른 제어 루프(Control Loops)는 움직임을 안정화하고 즉각적인 위험에 대응할 수 있으며, 중간 수준 시스템은 위치 추정(Localization), 지각, 궤적 계획(Trajectory Planning)을 수행할 수 있습니다. 더 느린 인지 계층은 임무, 미래 시나리오, 작업 우선순위, 장기 적응을 추론할 수 있습니다.

멘탈 모델(Mental Models)은 AI 시스템이 환경이 어떻게 행동하는지를 나타내는 내부 표현(Internal Representations)을 필요로 한다는 점을 시사합니다. 행동은 미래에 영향을 주기 때문에 현재 상태를 인식하는 것만으로는 충분하지 않습니다. 지능형 에이전트는 실제 행동을 실행하기 전에 세계가 어떻게 변화할 수 있는지를 예상할 수 있도록 개체, 관계, 동역학(Dynamics), 제약조건, 가능한 상태 전이(State Transitions)를 표현해야 합니다.

월드 모델(World Models)은 이러한 원리를 계산적으로 구현합니다. 월드 모델은 관련 환경 상태가 시간에 따라 어떻게 변화하고 행동이 이러한 전이에 어떤 영향을 미치는지를 추정합니다. 가능한 미래를 예측함으로써 AI 에이전트는 대안 행동을 비교하고, 위험을 평가하고, 결과를 시뮬레이션하며, 단순한 반응형 매핑(Reactive Mapping)에 전적으로 의존하지 않고 예측된 결과를 기반으로 행동을 선택할 수 있습니다.

로보틱스에서 월드 모델은 카메라, 라이다, 레이더, 관성 측정 장치(IMU), 위성항법시스템(GNSS), 관절 상태(Joint States), 힘 센서(Force Sensors), 지도, 이전 행동의 정보를 시간적으로 일관된 표현으로 통합할 수 있습니다. 목표는 모든 물리적 세부사항을 반드시 완벽하게 재구성하는 것이 아니라 예측, 계획, 제어, 상호작용, 안전에 필요한 정보를 유지하는 것입니다.

따라서 예측(Prediction)은 지능적 인지(Intelligent Cognition)의 핵심 구성요소입니다. 인간은 지속적으로 움직임, 결과, 의도, 환경 변화를 예상합니다. AI 시스템 역시 미래 관찰, 객체 궤적, 점유 상태(Occupancy), 에이전트 행동, 작업 결과 또는 잠재 상태(Latent States)를 예측할 수 있습니다. 예측은 지각을 현재 상태에 대한 설명에서 가능한 미래를 추론하기 위한 기반으로 변화시킵니다.

예측 오류(Prediction Errors)는 학습 신호로도 활용할 수 있습니다. 실제로 관찰된 미래가 예측된 미래와 다르면 내부 표현, 동역학 모델 또는 가정의 일부가 불완전하다는 것을 의미합니다. 따라서 예측과 관찰을 지속적으로 비교하면 장기 운영 과정에서 적응을 지원하고 월드 모델을 개선할 수 있습니다.

인과 추론(Causal Reasoning)은 예측을 통계적 상관관계 이상으로 확장합니다. 지능 시스템은 단순히 함께 발생하는 사건과 특정 행동이나 조건이 실제로 결과에 영향을 미치는 관계를 구분하는 것이 바람직합니다. 인과적 표현(Causal Representations)은 개입 계획(Intervention Planning), 환경 간 전이, 설명 가능성(Explainability), 표면적인 통계 패턴이 변화할 때의 강건성(Robustness)을 향상시킬 수 있습니다.

반사실적 추론(Counterfactual Reasoning)은 지능적인 의사결정을 더욱 확장합니다. 에이전트는 다른 행동을 선택했거나 특정 조건이 달라졌다면 어떤 일이 발생했을지를 추론할 수 있습니다. 월드 모델과 결합된 반사실적 시뮬레이션(Counterfactual Simulation)은 모든 가능성을 실제 물리 환경에서 실행하지 않고도 여러 후보 미래를 평가할 수 있게 하여 계획 효율성을 향상시키고 불필요한 위험을 줄입니다.

계획(Planning)은 예측, 기억, 목표, 불확실성이 통합될 때 더욱 강력해집니다. 고정된 행동 순서를 한 번 생성하는 대신 지능형 플래너(Intelligent Planner)는 여러 대안을 유지하고, 예측된 결과를 평가하고, 실행 상태를 모니터링하며, 관찰이 예상과 다르면 계획을 수정할 수 있습니다. 따라서 계획은 일회성 계산이 아니라 지속적인 폐루프 인지 과정(Closed-Loop Cognitive Process)이 됩니다.

인지과학은 제한된 합리성(Bounded Rationality)도 강조합니다. 지능형 에이전트는 제한된 시간, 정보, 기억, 계산 자원 아래에서 작동하므로 완전히 최적인 의사결정이 항상 가능한 것은 아닙니다. 따라서 실용적인 AI는 무제한 계산을 가정하기보다 이용 가능한 제약조건 안에서 충분히 좋은 결정을 추구해야 합니다. 이러한 원리는 실시간 자율 시스템(Real-Time Autonomous Systems)에서 특히 중요합니다.

자원 인식 지능(Resource-Aware Intelligence)은 작업 중요도에 따라 계산 자원을 동적으로 할당할 수 있습니다. 일상적인 상황에서는 경량 지각과 제어만 필요할 수 있지만 비정상적이거나 위험성이 높은 사건에서는 더 큰 모델, 추가 센서, 장시간 추론 또는 외부 계산 자원을 활성화하는 것이 타당할 수 있습니다. 이러한 적응형 계산(Adaptive Computation)은 효율성과 신뢰성을 동시에 향상시킬 수 있습니다.

인지 부하(Cognitive Load)는 AI 아키텍처에 직접적인 시사점을 제공합니다. 너무 많은 작업이 동일한 계산 자원을 두고 경쟁하면 지연시간(Latency)이 증가하고 중요한 기능의 처리가 늦어질 수 있습니다. 따라서 지능 시스템은 계산 수요가 이용 가능한 용량을 초과할 때 필수 기능을 유지하기 위한 스케줄링(Scheduling), 우선순위 설정, 기억 관리, 모델 선택, 점진적 성능 저하(Graceful Degradation) 메커니즘을 필요로 합니다.

인적 오류(Human Error)에 관한 연구는 또 다른 중요한 교훈을 제공합니다. 지능 시스템은 개별 구성요소가 항상 정확할 것이라는 가정 아래 설계되어서는 안 됩니다. 센서는 고장 날 수 있고, 모델은 잘못 분류할 수 있으며, 기억은 불일치할 수 있고, 예측은 부정확해질 수 있으며, 플래너는 부적절한 행동을 선택할 수 있습니다. 따라서 신뢰성(Reliability)은 아키텍처 수준의 탐지, 억제(Containment), 검증, 복구를 통해 형성되어야 합니다.

중복성(Redundancy)은 개별 구성요소에 대한 의존성을 줄일 수 있습니다. 여러 센서, 모델, 알고리즘 또는 추론 경로가 중요한 상태에 대해 독립적인 증거를 제공할 수 있습니다. 그러나 동일한 데이터로 학습된 유사한 구성요소들은 비슷한 방식으로 실패할 수 있으므로 효과적인 중복성을 위해서는 다양성(Diversity)이 필요합니다. 서로 보완적인 정보원이 서로 다른 고장 모드를 드러낼 때 신뢰성이 향상됩니다.

불확실성 추정(Uncertainty Estimation)은 이러한 실패를 관리하는 데 필수적입니다. AI 시스템은 강력한 증거로 뒷받침되는 출력과 익숙하지 않거나 모호한 조건에서 생성된 출력을 구분해야 합니다. 신뢰도 추정은 시스템이 즉시 행동할지, 추가 정보를 수집할지, 다른 모델을 활성화할지, 속도를 줄일지, 인간의 도움을 요청할지 또는 안전 운용 모드(Safe Operating Mode)로 전환할지를 결정하는 데 활용될 수 있습니다.

메타인지(Metacognition)는 고급 AI가 자신의 추론과 성능을 모니터링해야 함을 시사합니다. 인공 메타인지 메커니즘(Artificial Metacognitive Mechanisms)은 신뢰도를 평가하고, 모순을 탐지하고, 추가 정보의 필요성을 추정하고, 대안적 추론 경로를 비교하며, 중대한 결과를 초래할 수 있는 행동 전에 출력을 검증할 수 있습니다. 따라서 지능은 인지를 단순히 실행하는 것뿐 아니라 인지 자체를 평가하는 메커니즘도 포함합니다.

이는 자연스럽게 자기 모니터링 아키텍처(Self-Monitoring Architecture)로 이어집니다. 자율 시스템은 예측 상태와 관찰 상태를 비교하고, 성능 지표를 추적하며, 분포 변화(Distribution Shift)를 탐지하고, 비정상적인 센서 동작을 식별하며, 현재 정책이 여전히 유효한지를 평가할 수 있습니다. 이러한 모니터링은 정상적인 가정이 무너졌을 때 점진적인 성능 저하와 안전한 적응을 가능하게 하는 기반이 됩니다.

오류 복구(Error Recovery)는 예외적인 절차가 아니라 핵심 기능으로 고려되어야 합니다. 실제 환경의 AI는 예상하지 못한 객체, 비정상적인 지형, 센서 성능 저하, 통신 손실, 잘못된 예측, 불완전한 명령을 필연적으로 접하게 됩니다. 따라서 시스템은 완벽한 실행을 가정하기보다 안전 상태를 보존하고, 복구 선택지를 유지하며, 오류 상태에서 정상 상태로 돌아오는 방법을 학습해야 합니다.

회복탄력성(Resilience)은 이러한 개념을 확장하여 장애 상황에서도 운용을 지속하는 능력을 강조합니다. 회복탄력적인 AI 시스템은 변화된 조건을 탐지하고, 자원을 재구성하고, 전략을 전환하고, 필요하면 기능을 축소하며, 고장 이후 능력을 복원할 수 있습니다. 피지컬 AI에서는 센서 변경, 속도 감소, 경로 재계획(Replanning), 제어기 전환, 일부 작업을 다른 로봇이나 인간 운영자에게 이전하는 방식이 포함될 수 있습니다.

인간-AI 상호작용(Human-AI Interaction)은 인지과학의 영향을 크게 받습니다. 사용자는 관찰한 행동, 설명, 인터페이스, 이전 경험을 바탕으로 AI 시스템에 대한 멘탈 모델을 형성합니다. 시스템 행동이 예측하기 어렵거나 내부 상태가 숨겨져 있으면 사용자는 잘못된 기대를 형성할 수 있습니다. 따라서 투명한 상태 정보와 일관된 상호작용은 인간이 AI가 무엇을 알고 있고, 무엇을 하려 하며, 무엇을 신뢰성 있게 판단할 수 없는지를 이해하도록 지원합니다.

신뢰(Trust)는 최대화되는 것이 아니라 적절하게 보정되어야 합니다. 지나친 신뢰는 사용자가 잘못된 권고를 받아들이게 할 수 있으며, 지나치게 낮은 신뢰는 유용한 자동화를 효과적으로 활용하지 못하게 합니다. AI 시스템은 인위적으로 확실하다는 인상을 만드는 대신 신뢰도, 한계, 불확실성, 중요한 의사결정의 근거를 전달하여 적절한 의존(Appropriate Reliance)을 지원해야 합니다.

설명 가능성(Explainability)은 인간의 인지를 지원할 때 가장 유용합니다. 설명은 증거, 제약조건, 불확실성, 대안, 예상 결과 등 의사결정과 관련된 정보를 보여주어야 합니다. 지나치게 상세한 설명은 인지 부하를 증가시킬 수 있으며 지나치게 단순화된 설명은 중요한 한계를 숨길 수 있습니다. 따라서 효과적인 설명은 사용자의 작업과 정보 요구에 맞추어져야 합니다.

인간의 주의 역시 제한된 자원으로 취급해야 합니다. 낮은 가치의 경보를 지속적으로 생성하는 자율 시스템은 운영자를 과부하 상태로 만들고 중요한 사건을 탐지하기 어렵게 만들 수 있습니다. 지능적 경보(Intelligent Alerting)는 긴급성, 불확실성, 결과의 심각성, 개입 필요성을 기준으로 우선순위를 설정하여 인간의 주의가 가장 큰 가치를 제공하는 곳에 집중되도록 해야 합니다.

공유 상황 자각(Shared Situation Awareness)은 인간과 AI가 협력할 때 중요해집니다. 양쪽은 목표, 시스템 상태, 책임, 제약조건, 예상되는 다음 행동에 대해 서로 호환되는 표현을 유지해야 합니다. 이러한 표현이 달라지면 인간은 AI가 행동할 것으로 기대하는 동안 AI는 인간의 입력을 기다리거나, 양쪽이 서로 충돌하는 행동을 동시에 수행할 수 있습니다.

따라서 인간-AI 팀 구성(Human-AI Teaming)은 명확한 책임 할당을 필요로 합니다. 계산, 모니터링, 기억, 패턴 인식은 기계가 잘 수행할 수 있으며, 인간은 문맥적 판단, 윤리적 해석, 비정상 상황, 목표 수정에서 중요한 역할을 유지합니다. 또한 책임은 신뢰도, 작업 부하, 환경 복잡성, 시스템 상태에 따라 동적으로 변경될 수 있습니다.

체화된 인지(Embodied Cognition)는 로보틱스에 매우 중요한 시사점을 제공합니다. 지능은 추상적인 추론 모듈 내부에만 존재할 필요가 없으며 물리적 상호작용 자체가 정보를 제공할 수 있습니다. 로봇은 모호성을 해결하기 위해 카메라를 이동하고, 객체의 특성을 추정하기 위해 접촉하며, 기하학적 조건을 개선하기 위해 위치를 변경하거나, 작업을 단순화하기 위해 환경을 직접 조작할 수 있습니다.

이러한 원리는 능동적 지각(Active Perception)을 촉진합니다. 지능형 로봇은 주어진 관찰을 수동적으로 받아들이는 대신 미래의 센싱을 개선하는 행동을 선택합니다. 불확실한 영역으로 이동하거나, 관점을 변경하거나, 객체를 조명하거나, 매니퓰레이터(Manipulator)를 재배치하거나, 다른 센서 측정을 요청할 수 있습니다. 따라서 지각과 행동은 서로 의존하는 인지 구성요소가 됩니다.

행동 유도성(Affordances)은 또 다른 유용한 개념을 제공합니다. 객체는 외형만으로 표현되는 것이 아니라 가능한 상호작용의 관점에서도 표현됩니다. 손잡이는 당기기(Pulling)를 가능하게 하고, 평평한 표면은 물체 배치(Placement)를 가능하게 하며, 개구부(Opening)는 로봇의 기하학적 크기가 허용한다면 통과를 가능하게 합니다. 행동 유도성을 표현하면 의미론적 지각을 계획 및 물리적 행동과 직접 연결할 수 있습니다.

감각운동 학습(Sensorimotor Learning)은 마찬가지로 지각과 제어를 연결합니다. 에이전트는 시각적 표현을 행동과 독립적으로 학습하는 대신 자신의 행동 결과로 관찰이 어떻게 변화하는지를 학습할 수 있습니다. 이를 통해 상호작용에 기반한 표현(Grounded Representation)을 형성하고 환경에서 제어 가능한 요소를 예측하는 능력을 향상시킬 수 있습니다.

파운데이션 모델(Foundation Models)은 이러한 인지 원리를 활용할 수 있습니다. 지각 파운데이션 모델(Perception Foundation Models)은 광범위한 의미론적 표현을 제공하고, 언어 파운데이션 모델(Language Foundation Models)은 추론과 의사소통을 지원하며, 행동 파운데이션 모델(Action Foundation Models)은 재사용 가능한 행동을 인코딩할 수 있습니다. 이러한 모델은 고립된 범용 해결책이 아니라 더 큰 아키텍처의 구성요소가 될 때 가장 큰 가치를 제공합니다.

지각 파운데이션 모델은 객체, 장면, 관계, 의미론적 개념을 식별할 수 있지만 작업별 적응(Task-Specific Adaptation)은 여전히 필요합니다. 미세조정(Fine-Tuning), 어댑터(Adapters), 프롬프트 조건화(Prompt Conditioning), 작업별 헤드(Task-Specific Heads)는 모든 능력을 처음부터 학습하는 비용을 피하면서 광범위하게 사전학습된 표현을 특정 센서, 환경, 로봇, 운영 요구사항에 연결할 수 있습니다.

행동 파운데이션 모델 역시 대규모 로봇 경험에서 학습한 일반적인 움직임 또는 조작 사전지식(Motion or Manipulation Priors)을 제공할 수 있습니다. 새로운 로봇은 이러한 표현을 자신의 형태(Morphology), 액추에이터 한계(Actuator Limits), 페이로드(Payload), 센서, 작업 요구사항에 적응시킬 수 있습니다. 이를 통해 재사용 가능한 행동 지식을 유지하면서 플랫폼별 학습량을 줄일 수 있습니다.

그러나 물리적 결과가 심각할 수 있는 영역에서는 파운데이션 모델이 결정론적 안전 메커니즘(Deterministic Safety Mechanisms)을 대체해서는 안 됩니다. 학습된 모델은 후보 해석, 예측, 계획 또는 행동을 생성할 수 있지만 독립적인 제약조건 검증 메커니즘이 실행 전에 충돌 위험, 관절 한계(Joint Limits), 안정성, 속도, 힘, 도달 가능 공간(Reachable Space), 기타 안전 조건을 검증해야 합니다.

월드 모델은 지각 파운데이션 모델과 행동 파운데이션 모델을 연결할 수 있습니다. 지각 모델은 의미론적 및 기하학적 상태 정보를 제공하고, 월드 모델은 해당 상태가 어떻게 변화할 수 있는지를 예측하며, 행동 모델은 후보 행동을 생성합니다. 이후 플래너는 예측된 결과를 평가하고 행동을 선택하며, 안전 메커니즘은 물리적 및 운영적 제약조건을 강제할 수 있습니다.

이러한 아키텍처는 센싱(Sensing)에서 표현, 예측, 추론, 계획, 행동, 관찰, 학습으로 이어지는 지속적인 루프를 구성합니다. 각각의 행동은 환경을 변화시키고 새로운 감각 증거를 생성합니다. 새로운 증거는 월드 상태(World State)를 갱신하고 이전 예측을 검증하여 시스템이 정적인 의사결정 순서에 의존하지 않고 지속적으로 자신을 수정할 수 있도록 합니다.

강화학습은 행동 및 예측된 미래를 장기 목표와 연결함으로써 이러한 루프 안에서 작동할 수 있습니다. 모델 기반 강화학습(Model-Based Reinforcement Learning)은 모든 궤적을 실제로 실행하지 않고 월드 모델의 시뮬레이션을 이용하여 많은 궤적을 평가할 수 있습니다. 이를 통해 데이터 효율성을 향상시키고 실제 환경에서 시행착오를 통해 직접 학습할 때 발생하는 비용과 위험을 줄일 수 있습니다.

모방학습(Imitation Learning)은 효율적인 초기 행동 사전지식(Behavioral Prior)을 제공할 수 있습니다. 인간 시연(Human Demonstrations)에는 지각, 작업 분해(Task Decomposition), 움직임, 보정(Correction), 전략에 관한 정보가 포함됩니다. AI 시스템은 이러한 시연으로부터 학습한 후 무작위 탐색에서 완전히 시작하는 대신 자기지도학습, 강화학습, 시뮬레이션 또는 실제 경험을 통해 추가적으로 개선할 수 있습니다.

시뮬레이션(Simulation)은 물리적 데이터 수집에 높은 비용과 위험이 따르기 때문에 피지컬 AI에서 특히 중요합니다. 지각, 예측, 계획, 제어를 학습하기 위한 많은 시나리오를 생성할 수 있습니다. 그러나 시뮬레이션은 현실을 완벽하게 재현할 수 없으므로 도메인 랜덤화(Domain Randomization), 실제 환경 미세조정(Real-World Fine-Tuning), 적응, 지속적인 검증이 필요합니다.

인지 발달(Cognitive Development)은 AI에 또 다른 유용한 방향을 제시합니다. 인간은 처음부터 전문가 수준의 능력을 가지고 태어나는 것이 아니라 상호작용을 통해 점차 복잡한 능력을 습득합니다. 인공 에이전트도 기본적인 지각과 제어를 먼저 학습하고 이후 객체 상호작용, 작업 조합(Task Composition), 계획, 사회적 조정, 점차 높은 수준의 자율 행동을 학습하는 교육과정(Curriculum)의 혜택을 받을 수 있습니다.

커리큘럼 학습(Curriculum Learning)은 경험을 난이도가 점차 증가하도록 구성하여 복잡한 작업의 학습 난이도를 줄일 수 있습니다. 초기 능력은 이후 학습의 기반이 됩니다. 로보틱스에서는 내비게이션(Navigation), 위치 추정, 장애물 회피(Obstacle Avoidance), 조작(Manipulation), 의미론적 추론(Semantic Reasoning), 임무 계획(Mission Planning)을 처음부터 하나의 거대한 문제로 학습하기보다 점진적으로 통합할 수 있습니다.

발달은 탐색(Exploration)의 중요성도 강조합니다. 지능형 에이전트는 즉각적인 보상이 없더라도 때로는 정보를 수집해야 합니다. 호기심(Curiosity), 새로움 탐지(Novelty Detection), 정보 이득(Information Gain), 불확실성 감소(Uncertainty Reduction)는 특정 작업에서 필요해지기 전에 시스템이 유용한 구조를 발견하도록 유도하는 내재적 목표(Intrinsic Objectives)를 제공할 수 있습니다.

사회적 학습(Social Learning)은 인공지능의 학습을 더욱 가속할 수 있습니다. 로봇과 AI 에이전트는 인간이나 다른 에이전트로부터 학습할 수 있다면 모든 것을 독립적으로 학습할 필요가 없습니다. 시연, 수정(Corrections), 언어 지시(Language Instructions), 공유 지도, 플릿 경험(Fleet Experience), 전이된 모델은 여러 개체 사이에 지식을 분산시켜 반복 학습을 크게 줄일 수 있습니다.

플릿 학습(Fleet Learning)은 로보틱스에서 특히 중요합니다. 개별 로봇은 지역적 경험을 수집하고 중앙 또는 온프레미스(On-Premise) 인프라는 데이터를 통합하여 개선된 모델을 학습하고, 실패를 평가하며, 검증된 업데이트를 배포할 수 있습니다. 이를 통해 여러 로봇의 경험이 각각의 개별 로봇 성능 향상에 기여하는 순환 구조를 만들 수 있습니다.

이러한 아키텍처는 자연스럽게 지능을 엣지(Edge)와 외부 계산 자원 사이에 분배합니다. 실시간 지각, 안전, 위치 추정, 제어, 즉각적인 계획은 온보드(Onboard)에서 사용할 수 있어야 하며, 계산 비용이 높은 학습, 플릿 분석, 대규모 시뮬레이션, 장기 기억 통합(Long-Term Memory Consolidation), 대규모 파운데이션 모델은 온프레미스 또는 클라우드 인프라에서 작동할 수 있습니다.

이러한 분리는 서로 다른 계산 계층이 서로 다른 시간 규모와 책임으로 작동한다는 점에서 계층적 인지와 유사합니다. 엣지 시스템은 즉각적인 상호작용을 관리하고, 온프레미스 시스템은 여러 로봇을 조정하면서 더 무거운 추론을 제공하며, 더 큰 인프라는 장기 학습과 전역 최적화(Global Optimization)를 지원할 수 있습니다. 지능은 하나의 장치가 아니라 계산 생태계(Computational Ecosystem)에 분산됩니다.

멀티에이전트 인지(Multi-Agent Cognition)는 이러한 아키텍처를 더욱 확장합니다. 로봇은 관찰, 지도, 작업 상태, 예측, 학습된 표현을 공유할 수 있습니다. 한 로봇이 경험한 위험이나 환경 변화는 다른 로봇이 직접 경험하기 전에 정보를 제공할 수 있습니다. 따라서 집단 지능(Collective Intelligence)은 개별 로봇의 능력을 단순히 높이는 것이 아니라 의사소통, 조정, 공유 학습을 통해 나타납니다.

언어는 인간과 AI 사이뿐 아니라 인지 모듈 사이의 인터페이스로도 활용될 수 있습니다. 자연어 표현(Natural-Language Representations)은 목표, 제약조건, 관찰, 계획, 설명, 실패를 기술할 수 있습니다. 그러나 물리 시스템에서는 언어적 추론이 실제 환경 상태와 연결되도록 언어를 센서 관찰과 실행 가능한 행동에 기반시켜야 합니다.

멀티모달 AI(Multimodal AI)는 이러한 기반화(Grounding)를 위해 특히 중요합니다. 언어, 비전, 오디오, 기하학, 움직임, 고유수용감각, 물리적 상호작용은 상호보완적인 정보를 제공합니다. 이를 결합하면 단일 양식으로는 얻을 수 없는 풍부한 표현을 구성할 수 있으며 의미론적 의미를 공간적·물리적 제약조건과 연결하는 추론을 지원할 수 있습니다.

인지와 지능의 차이는 개별 AI 모델의 성능을 단순히 향상시키는 것만으로 충분하지 않음을 의미합니다. 시스템이 뛰어난 비전, 언어, 예측, 제어 구성요소를 보유하더라도 정보가 구성요소 사이에서 효과적으로 이동하지 못하면 전체 행동은 좋지 않을 수 있습니다. 따라서 시스템 아키텍처(System Architecture)와 오케스트레이션(Orchestration)은 고급 AI 공학의 핵심 문제가 됩니다.

공유 표현(Shared Representations)은 구성요소 사이의 분절을 줄일 수 있습니다. 공통 월드 상태(Common World State)는 지각, 기억, 예측, 계획, 제어에 관련 개체, 관계, 불확실성, 목표에 관한 일관된 정보를 제공할 수 있습니다. 그러나 서로 다른 모듈은 서로 다른 공간적, 시간적, 의미론적 세부 수준을 요구하므로 이러한 표현은 여러 추상화 수준을 지원해야 합니다.

시간적 표현(Temporal Representation)은 특히 중요합니다. 지능은 과거 관찰, 현재 상태, 가능한 미래를 연결해야 합니다. 단기 동역학(Short-Term Dynamics)은 즉각적인 제어를 지원하고, 중기 예측(Medium-Horizon Predictions)은 지역적 계획을 지원하며, 장기 모델(Long-Term Models)은 전략과 임무 추론을 지원합니다. 따라서 하나의 월드 모델 아키텍처 안에 여러 시간 척도(Temporal Scales)가 공존해야 할 수 있습니다.

AI의 미래는 고립된 모델보다 폐루프 시스템(Closed-Loop Systems)에 점점 더 의존할 가능성이 높습니다. 하나의 예측이나 응답을 생성하는 모델은 특정 인지 기능을 수행하지만, 지능형 에이전트는 결과를 관찰하고, 상태를 유지하고, 믿음(Beliefs)을 갱신하고, 오류를 수정하며, 지속적으로 목표를 추구해야 합니다. 피드백(Feedback)은 정적인 능력을 적응적 행동으로 전환합니다.

피지컬 AI에서는 지능이 지각, 월드 상태 추정(World-State Estimation), 예측, 추론, 계획, 행동, 검증, 학습의 반복적인 주기를 중심으로 설계되어야 함을 의미합니다. 내부 표현이 실제 센서 증거와 상호작용 결과에 의해 지속적으로 수정될 수 있도록 아키텍처는 모든 주기에서 물리적 현실과 연결되어 있어야 합니다.

안전(Safety)은 지능적 행동이 생성된 이후에만 추가되는 기능이 아니라 이 루프에 통합되어야 합니다. 위험 추정(Risk Estimation), 불확실성 모니터링, 제약조건 검사(Constraint Checking), 대체 행동(Fallback Behaviors), 비상 정지(Emergency Stopping), 인간 개입 메커니즘이 지속적으로 작동해야 합니다. 인지 능력이 향상될수록 가능한 행동의 범위도 확대되므로 신뢰성 높은 안전 아키텍처의 중요성은 더욱 커집니다.

AI가 더 높은 자율성을 부여받을수록 윤리적·사회적 고려사항(Ethical and Social Considerations)도 더욱 중요해집니다. 지능 시스템은 사람, 자원, 접근권, 안전, 개인정보에 영향을 미치는 의사결정을 수행할 수 있습니다. 인지 능력만으로 적절한 목표가 결정되는 것은 아닙니다. 따라서 인간의 가치, 법적 제약조건, 조직 정책, 책임성(Accountability), 거버넌스(Governance)가 지능이 어떻게 배치되고 사용되는지를 결정해야 합니다.

더 광범위한 시사점은 인공지능을 시스템 수준의 학문(System-Level Discipline)으로 이해해야 한다는 것입니다. 모델은 여전히 핵심적인 요소이지만 지능은 모델, 기억, 센서, 도구, 목표, 월드 표현, 계획, 피드백, 학습, 안전 메커니즘, 인간, 계산 인프라 사이의 상호작용으로부터 나타납니다.

따라서 인지과학은 단순한 생물학적 영감(Biological Inspiration) 이상의 가치를 제공합니다. 인지과학은 불확실성과 제한된 자원 아래에서 작동하는 AI 시스템을 구축하기 위한 선택적 주의, 구조화된 기억(Structured Memory), 예측적 내부 모델(Predictive Internal Models), 계층적 처리, 적응형 학습, 메타인지, 능동적 지각, 피드백, 오류 복구, 조정된 지각-행동 루프(Perception-Action Loops)와 같은 아키텍처 원리를 제공합니다.

이러한 원리는 AI가 디지털 예측에서 물리 세계와의 자율적 상호작용으로 이동할수록 더욱 중요해집니다. 피지컬 AI는 단순히 인식하고 추론하는 것뿐 아니라 결과를 예측하고, 계산 자원을 관리하고, 불확실성을 이해하고, 안전하게 행동하고, 실수에서 복구하고, 지속적으로 학습하며, 인간 및 다른 기계와 협력할 수 있어야 합니다.

AI의 장기적인 시사점은 고립된 작업 모델(Isolated Task Models)에서 통합 인지 아키텍처(Integrated Cognitive Architectures)로의 전환입니다. 파운데이션 모델은 광범위하고 재사용 가능한 능력을 제공하고, 월드 모델은 예측적 이해를 제공하며, 기억은 경험을 보존하고, 플래너는 미래 행동을 조직하며, 행동 모델은 의사결정을 환경과 연결할 수 있습니다. 이러한 요소들의 조정된 작동을 통해 점점 더 유능한 지능형 에이전트가 형성됩니다.

궁극적으로 더욱 일반적인 인공지능(General Artificial Intelligence)을 향한 발전은 하나의 범용 알고리즘보다 상호보완적인 인지 능력을 성공적으로 통합하는 데 더 크게 의존할 가능성이 있습니다. 지각, 기억, 학습, 예측, 추론, 계획, 행동, 메타인지, 안전이 세계와의 상호작용에서 지속적으로 학습하면서 목표를 신뢰성 있게 추구하는 하나의 연속적이고 적응적인 시스템을 형성할 때 지능이 나타납니다.

##  

## 01.09 Internal Representations and Cognitive State [w/Code]

![](images/image10.png){width="7.268055555555556in" height="7.268055555555556in"}

Internal representations are the information structures through which a cognitive system encodes aspects of itself, its environment, its goals, and its ongoing interaction with the world. Rather than responding directly to raw sensory inputs, an intelligent agent transforms observations into internal states that can support memory, prediction, reasoning, planning, decision making, and action across time.

A cognitive state describes the currently active configuration of information within such a system. It may include perceived objects, spatial relationships, current goals, task context, remembered events, predictions, uncertainty, attention priorities, emotional or motivational variables in biological agents, and planned actions. Cognitive state therefore represents more than sensory input at a particular instant.

The distinction between observation and internal representation is fundamental. An observation contains information directly available through sensors, while an internal representation is constructed through interpretation. A camera provides pixels, for example, but an intelligent system may represent those pixels as a person, vehicle, doorway, obstacle, manipulable object, or task-relevant entity depending on context.

Representations allow cognitive systems to operate on information that is no longer physically present. A person can reason about an object seen several minutes earlier, and a robot can continue navigating toward a destination temporarily hidden behind an obstacle. Internal state therefore provides continuity across gaps in perception and enables cognition to extend beyond immediate sensory stimulation.

Internal representations can exist at multiple levels of abstraction. Low-level representations may encode edges, textures, depth, motion, forces, or geometric features. Intermediate representations may describe objects, surfaces, trajectories, and spatial relationships. Higher-level representations can encode concepts, goals, intentions, causal relationships, task structures, and possible future situations.

This hierarchical organization is important because different cognitive operations require different forms of information. Motor control may depend on precise positions, velocities, and forces, while mission planning may require semantic concepts such as destination, priority, risk, or task completion. Intelligent systems must therefore maintain representations appropriate to several spatial, temporal, and semantic scales.

Representations may also be symbolic, distributed, continuous, discrete, or hybrid. Classical cognitive architectures often use explicit symbols and structured relationships, whereas neural networks commonly encode information as distributed numerical vectors. Modern AI increasingly combines these approaches so that continuous learned representations can interact with structured concepts, constraints, memory, and planning mechanisms.

Distributed representations are powerful because a large number of related properties can be encoded within high-dimensional patterns. Neural networks can learn representations that capture semantic similarity, geometry, temporal structure, or behavioral relevance without requiring every concept to be manually specified. Such representations support generalization by allowing similar situations to share internal structure.

Explicit representations remain useful when relationships must be interpreted, manipulated, verified, or communicated. Graphs, maps, object lists, scene structures, task states, rules, and symbolic constraints can make important information directly accessible to planning and reasoning. Hybrid cognitive architectures can therefore combine neural representations with explicit structures according to functional requirements.

The quality of an internal representation depends on whether it preserves information useful for future cognition and action. A representation does not need to reproduce every detail of the external world. Instead, it should retain the features necessary for relevant decisions, predictions, interactions, and safety while discarding unnecessary complexity that would consume computational resources.

This principle is closely related to abstraction. A robot navigating through a building may not need detailed visual textures of every wall, but it must represent free space, obstacles, doors, destinations, moving agents, and navigation constraints. For manipulation, however, detailed geometry, orientation, surface properties, and grasp affordances may become essential.

Task-dependent representation means that the same environment can be encoded differently according to the current objective. A table may be represented as an obstacle during navigation, as a support surface during object placement, or as a target structure during inspection. Cognitive state therefore reflects the interaction between environmental information and current goals rather than representing the world independently of purpose.

Attention influences which information enters and remains active within cognitive state. Because processing capacity is limited, cognitive systems cannot maintain every available detail with equal precision. Attention prioritizes representations according to relevance, novelty, uncertainty, expected value, danger, and current goals, allowing limited computational resources to focus on information that matters most.

Working memory maintains representations that are temporarily important for ongoing cognition. It can preserve intermediate reasoning results, recently observed events, temporary goals, instructions, unresolved questions, and partial plans. Without working memory, a cognitive system would repeatedly lose context and would struggle to execute tasks requiring multiple dependent steps.

Long-term memory complements working memory by preserving information beyond the current task. Semantic memory can store concepts and general knowledge, episodic memory can preserve specific experiences, and procedural memory can represent learned skills or policies. Cognitive state can retrieve relevant information from these memory systems and integrate it with current observations.

Memory retrieval is therefore an active component of state construction. The internal state of an intelligent agent is determined not only by what it currently perceives but also by what previous knowledge becomes activated. Two agents observing the same situation may construct different cognitive states because their experiences, expectations, goals, and learned representations differ.

Temporal representation is essential because intelligent behavior unfolds through time. Cognitive state should not be interpreted as an isolated snapshot but as part of a continuously evolving sequence. Previous states influence current interpretation, current actions influence future observations, and predictions connect present representations with possible future states.

State estimation provides a computational framework for maintaining this continuity. Because observations are incomplete and noisy, an agent estimates the underlying state of the environment by combining current sensor measurements with previous state estimates and models of how the world changes. This allows information to remain coherent even when individual observations are uncertain or temporarily unavailable.

Probabilistic state estimation explicitly represents uncertainty. Instead of assuming that every object position, classification, or environmental condition is known exactly, the system can maintain probability distributions, confidence values, or alternative hypotheses. This enables downstream reasoning and planning to consider both what is believed and how reliable that belief is.

Uncertainty is therefore part of cognitive state rather than merely an error associated with perception. An intelligent agent should know when an object classification is ambiguous, localization confidence is low, a prediction is unreliable, or a remembered fact may be outdated. Representing uncertainty allows behavior to change appropriately when knowledge is incomplete.

Belief state is a useful concept for environments that cannot be observed completely. A belief state represents the agent\'s current estimate of possible world states based on observations, memory, actions, and prior knowledge. Planning can then operate over these beliefs rather than assuming access to a perfectly known external state.

This is particularly important in partially observable environments. A robot may lose sight of a pedestrian behind a vehicle, but the pedestrian should not immediately disappear from its internal representation. The robot can maintain a belief about the person\'s likely position and motion until new evidence confirms, updates, or removes that hypothesis.

Prediction extends cognitive state into the future. Once an agent has an internal representation of the current situation, it can estimate how objects, agents, and environmental conditions may evolve. Predicted states allow the system to evaluate possible consequences before actions are physically executed and form an important foundation for intelligent planning.

A world model provides the dynamics that connect cognitive states across time. It describes or learns how the represented world changes naturally and how actions modify those changes. The combination of current cognitive state and world dynamics enables an agent to simulate future trajectories rather than reacting only after events have already occurred.

World models do not necessarily need to predict raw sensory data directly. For many intelligent tasks, prediction within a compact latent representation may be more efficient. A latent world model can encode task-relevant structure and predict how this representation changes, reducing the computational burden associated with generating complete high-resolution future observations.

However, latent representations introduce an important design challenge. If compression removes information that later becomes important, prediction and planning may fail even when the latent model is internally consistent. Representation learning must therefore balance compactness with preservation of information required for control, safety, generalization, and future tasks.

Predictive representations can be learned through self-supervised learning. An agent can learn useful internal structure by predicting future observations, masked information, temporal relationships, object motion, state transitions, or the effects of actions. This allows large quantities of unlabeled interaction data to contribute directly to the development of cognitive representations.

Prediction errors provide a mechanism for updating internal state and learned models. When expected observations differ from actual observations, the system receives evidence that its state estimate, dynamics model, assumptions, or predictions may be incorrect. The discrepancy can trigger state correction, model adaptation, attention shifts, or additional information gathering.

This creates a continuous cycle in which representation and prediction refine each other. Internal state generates expectations about future observations, the environment produces actual observations, and differences between expectation and reality modify the state. Cognitive representation is therefore dynamic rather than a static database describing the world.

Action must also be represented within cognitive state. An intelligent system needs information about what it is currently doing, what actions were recently executed, what actions are available, and what consequences are expected from them. Without action history, changes in observation may be difficult to distinguish between external events and effects caused by the agent itself.

Representing action enables agency and causal learning. When an agent knows which intervention it performed and observes the resulting state transition, it can learn relationships between actions and consequences. This is fundamentally different from learning only correlations between passively observed events and supports more reliable planning and control.

Goals are another essential component of cognitive state. The same perceived situation can lead to different actions depending on the objective. Representing goals allows perception, attention, memory retrieval, prediction, and planning to become task-directed rather than generic. Goals can also be hierarchical, ranging from long-term missions to immediate control objectives.

Task state describes progress within an ongoing activity. It can include completed subtasks, current procedures, remaining requirements, dependencies, constraints, and expected next steps. Maintaining task state is essential for long-horizon behavior because an agent must know not only where it is physically located but also where it is within the logical structure of the task.

Plans can themselves become internal representations. A plan may encode intended future actions, dependencies, alternative branches, checkpoints, and expected outcomes. During execution, observations can be compared with the expected plan state so that deviations are detected and replanning can occur when necessary.

Cognitive state may therefore include representations of the past, present, and future simultaneously. Memory provides information about previous states and actions, perception estimates the present, and prediction represents possible future states. Planning connects these temporal regions by selecting actions intended to transform the present toward desired future conditions.

Spatial representations are particularly important for embodied agents. Robots may maintain metric maps, topological maps, occupancy grids, voxel representations, point clouds, object-centric maps, semantic maps, or bird\'s-eye-view representations. Different forms provide different tradeoffs between geometric precision, semantic richness, computational efficiency, and planning utility.

Object-centric representations organize cognitive state around persistent entities rather than raw sensor measurements. An object can maintain identity, location, geometry, semantic category, velocity, uncertainty, properties, and interaction history across time. Such representations help reasoning systems understand that observations from different moments may refer to the same physical entity.

Scene graphs extend this idea by explicitly representing relationships among entities. Objects can be connected through spatial, semantic, functional, or causal relationships such as inside, near, supporting, blocking, attached to, moving toward, or belonging to. Graph representations provide useful structure for reasoning about complex environments containing many interacting elements.

Affordance representations describe possible interactions between an agent and entities in the environment. A surface may support placement, an object may be graspable, a doorway may permit passage, and a button may afford pressing. Affordances connect perception with action by representing not merely what something is but what can potentially be done with it.

For Physical AI, this transition from object recognition to affordance understanding is particularly important. A robot completing real tasks must reason about reachability, manipulability, traversability, support, collision, stability, and physical constraints. Cognitive state therefore needs representations that connect semantic understanding with geometry and dynamics.

Body representation is also necessary for embodied intelligence. A robot must represent its own configuration, dimensions, joint states, actuator limits, payload, velocity, energy state, sensor status, and reachable workspace. Intelligent behavior depends on understanding not only the external world but also the capabilities and limitations of the body interacting with it.

This self-representation supports capability-aware planning. A route that is traversable for one robot may be impossible for another because of width, ground clearance, turning radius, payload, traction, or energy limitations. Similarly, a manipulation action must be evaluated relative to reach, force capability, joint limits, and current configuration.

Internal representations should therefore include both world state and self-state. The interaction between them determines which actions are possible. An obstacle has meaning partly in relation to the robot\'s geometry, and an object is graspable only relative to the manipulator\'s capabilities. Intelligent state representation is inherently relational rather than purely environmental.

Multi-modal representation becomes necessary when information originates from different sensors and information sources. Vision provides appearance and semantics, LiDAR provides geometry, radar provides motion information, IMU provides inertial dynamics, GNSS provides global position, and proprioceptive sensors describe the robot\'s internal physical state.

Sensor fusion combines these modalities into representations that are more useful than isolated measurements. Fusion may occur at raw-data, feature, object, state, or decision levels. The appropriate strategy depends on synchronization, uncertainty, computational resources, sensor characteristics, and the requirements of downstream prediction and planning.

A shared world state can provide a common interface between perception, memory, world modeling, planning, and control. Instead of each module independently reconstructing the environment, relevant information can be maintained within a consistent state representation. This reduces fragmentation and allows changes discovered by one subsystem to become available to others.

However, a single representation format may not be sufficient for every cognitive function. High-frequency control requires compact numerical states, while semantic reasoning may require object and relationship structures. Long-term memory may require compressed episodic representations, while planning may need predicted trajectories. Effective architectures therefore support coordinated representations at multiple levels.

Representation alignment becomes important when several models operate together. A perception model, language model, world model, planner, and action model may encode information differently. Interfaces must translate or align these representations so that semantic meaning, spatial relationships, uncertainty, and temporal context remain consistent across components.

Foundation models provide powerful pretrained representation spaces. Vision and multimodal foundation models can encode semantic relationships learned from large datasets, while language models provide representations of concepts, instructions, and abstract knowledge. These models can significantly enrich cognitive state when their representations are grounded in current sensory and physical information.

Perception foundation models can transform raw sensory observations into reusable semantic features. Instead of training every robot perception capability from the beginning, pretrained representations can be adapted to recognize task-relevant entities and relationships. Fine-tuning or specialized heads can connect general representations with specific sensors, environments, and operational objectives.

Language foundation models can contribute high-level representations of goals, instructions, procedures, constraints, and conceptual relationships. However, language representations should not be treated as equivalent to physical state. A statement about the environment must be connected with current sensor evidence and world-state estimates before it can safely guide physical action.

Action foundation models provide representations of reusable behavior patterns. Motion sequences, manipulation skills, navigation behaviors, and interaction strategies can be encoded in forms that transfer across tasks or platforms. These action representations become most useful when conditioned on current cognitive state, robot capability, goals, and predicted consequences.

World models provide the temporal bridge among these representations. They can receive the current state constructed from perception and memory, incorporate candidate actions, and estimate future states. The planner can then compare these predicted futures with goals and constraints, turning internal representation into a basis for deliberate decision making.

The cognitive state should also represent safety-relevant variables explicitly. Collision probability, stability margins, localization confidence, sensor health, communication status, energy reserve, environmental hazards, and operational constraints may influence whether an otherwise desirable action is acceptable. Safety cannot depend solely on implicit features hidden within learned representations.

Explicit safety state supports independent verification. A learned planner may propose an action, while a safety layer checks whether predicted trajectories satisfy physical, operational, and regulatory constraints. Maintaining safety information separately from task objectives reduces the risk that optimization toward performance accidentally suppresses critical safety considerations.

Metacognitive state represents information about the system\'s own cognitive processes. It can include confidence, uncertainty, detected contradictions, model reliability, computational load, missing information, and whether additional reasoning is required. This allows an intelligent system to modify how it thinks rather than only what action it selects.

For example, high uncertainty in perception may cause the system to gather additional sensor information, while disagreement between models may trigger verification. High computational load may cause lower-priority processing to be postponed. Metacognitive state therefore supports adaptive allocation of attention, computation, memory, and reasoning resources.

Cognitive state can also include estimates of novelty and familiarity. Situations similar to previous experience may be handled using established policies, while unfamiliar states may require cautious behavior, exploration, additional sensing, or human assistance. Novelty detection provides an important mechanism for avoiding confident operation outside the system\'s learned experience.

Distribution-shift detection extends this concept to deployed AI. A model trained under particular environmental conditions may encounter new weather, terrain, objects, sensors, or operational patterns. Detecting that current inputs differ significantly from training experience allows the system to reduce confidence and activate adaptation or fallback mechanisms.

Internal state is therefore central to reliability. Many failures occur not because a system lacks an appropriate action but because it has an incorrect representation of the situation. A robot may plan perfectly relative to an inaccurate map or incorrectly estimated object position. Improving state estimation can therefore be as important as improving planning algorithms.

State consistency should be monitored across time and modalities. If camera perception indicates an object at one location while LiDAR indicates another, the disagreement should not simply be hidden through averaging. The system should represent the conflict, estimate possible causes, and determine whether recalibration, additional observation, or conservative behavior is required.

Time synchronization is essential for maintaining coherent multimodal cognitive state. Sensor measurements collected at different times can create false spatial relationships when objects or the robot are moving. Accurate timestamps, synchronization, motion compensation, and state propagation are therefore fundamental requirements for reliable sensor fusion and world representation.

For mobile robots, localization forms a core component of cognitive state because nearly every spatial relationship depends on the estimated robot pose. Localization uncertainty propagates into mapping, object tracking, path planning, and manipulation. A reliable cognitive architecture should therefore represent not only estimated pose but also confidence and possible localization failure.

Mapping extends state beyond the immediate sensor horizon. A map stores persistent spatial information that allows the agent to reason about locations not currently visible. Semantic and object-level maps can additionally preserve information about what exists in those locations, transforming mapping from geometric memory into a component of long-term cognitive representation.

Dynamic environments require cognitive state to distinguish persistent structure from temporary change. Buildings and fixed infrastructure may remain stable, while people, vehicles, movable objects, weather conditions, and temporary obstacles change continuously. Different update rates and memory policies are therefore appropriate for different components of the world representation.

Tracking provides temporal identity for dynamic entities. Instead of treating every sensor detection as a new object, tracking maintains hypotheses about which observations correspond to the same entity over time. This enables velocity estimation, trajectory prediction, behavioral interpretation, and more stable planning around moving agents.

Agent representations can include more than physical state. In environments containing humans or other robots, cognitive state may include estimated goals, intentions, likely trajectories, communication status, and expected behavior. These representations support socially aware navigation, cooperation, negotiation, and multi-agent planning.

Multi-agent systems introduce distributed cognitive state. Each agent has local observations and internal representations, while shared information can create a broader collective state. Communication allows robots to exchange maps, detected hazards, task progress, predictions, or learned knowledge, extending cognition beyond the sensory range and experience of any individual agent.

A shared fleet state can support coordination at a higher level. It may represent robot locations, capabilities, battery levels, assigned tasks, environmental conditions, congestion, and mission progress. Fleet-level reasoning can then allocate work and resources while individual robots maintain detailed local states required for real-time control.

Edge and on-premise architectures can divide cognitive state according to latency and scope. The robot should maintain the state required for immediate perception, safety, control, and local planning, while on-premise systems can maintain broader fleet state, long-term memory, large-scale maps, historical data, and computationally expensive predictive models.

The division must preserve autonomy during communication loss. Critical cognitive state should remain available onboard so that a robot can continue safe operation even when external infrastructure becomes temporarily unavailable. External systems should enhance intelligence without becoming a single point of failure for essential real-time behavior.

State compression becomes important when cognitive information must be communicated between robots or computational layers. Transmitting every raw sensor stream is often inefficient. Compact representations containing relevant objects, features, events, uncertainties, and state changes can reduce bandwidth while preserving information required for coordination and reasoning.

Event-based representation can further improve efficiency. Instead of continuously transmitting unchanged state, systems can communicate meaningful changes such as a newly detected obstacle, localization degradation, task completion, unexpected behavior, or a significant prediction error. This mirrors selective attention by prioritizing information according to cognitive relevance.

Persistent cognitive state enables continual learning because experience can be connected across time. The system can store important observations, decisions, predictions, outcomes, and errors for later analysis. Training processes can then identify recurring failures, improve representations, update world models, and distribute validated improvements back to deployed agents.

Not every experience should be stored permanently. Intelligent memory management requires deciding which events are novel, informative, uncertain, successful, dangerous, or representative enough to preserve. Selective memory reduces storage requirements while increasing the value of the data retained for future learning and evaluation.

Experience replay can use stored cognitive trajectories for learning. Sequences containing states, actions, predictions, rewards, and outcomes can be sampled later to improve policies or world models. Particularly important failures and rare events can receive greater attention because they may contain more useful information than routine successful operation.

Representation stability is important during continual learning. If internal representations change dramatically whenever a model is updated, memories, planners, and downstream modules may become incompatible. Continual learning architectures therefore need mechanisms that permit improvement while maintaining sufficient consistency across versions and protecting important previous knowledge.

Representation versioning can help manage this problem in deployed systems. Models, maps, schemas, and learned state encodings can be associated with explicit versions so that compatibility can be tested before updates are distributed. This is especially important for fleets where robots may temporarily operate with different software or model revisions.

Evaluation of cognitive representations should focus on their usefulness rather than only their visual or mathematical elegance. A good representation should improve prediction, planning, generalization, adaptation, reliability, and efficient action. It should preserve necessary information, expose uncertainty, support updates, and remain computationally practical for the target platform.

For Physical AI, representation quality can be evaluated through closed-loop performance. The relevant question is not merely whether an internal state reconstructs the environment accurately, but whether the robot can use that state to navigate, manipulate, predict, recover from errors, and complete tasks safely under changing real-world conditions.

This leads to the concept of action-relevant representation. Information is valuable when it helps distinguish states that require different actions or predict different consequences. Two visually different situations may be equivalent for a task, while two visually similar situations may require completely different behavior because of hidden physical or semantic constraints.

Predictive representation follows a similar principle. A useful state should contain enough information to estimate important future changes. If two observations appear similar but lead to different future outcomes, the representation should preserve whatever variables explain that difference. World-model learning can therefore shape representations around dynamics rather than appearance alone.

Causal representation goes further by encoding variables that explain how interventions affect outcomes. This can improve generalization when environmental correlations change because the system relies on relationships that remain meaningful under intervention. Causal state representations are particularly valuable when an autonomous agent must deliberately modify its environment.

Internal representation and cognitive state ultimately form the interface between sensing and intelligent behavior. Sensors provide observations, but cognition requires those observations to become persistent, structured, uncertain, predictive, goal-conditioned, and action-relevant information. The quality of this transformation strongly determines the quality of subsequent reasoning and control.

In an integrated AI architecture, perception updates the cognitive state, memory enriches it with previous knowledge, attention prioritizes relevant information, the world model predicts future states, reasoning interprets alternatives, planning selects actions, control changes the environment, and new observations correct the representation. Intelligence emerges through the continuous operation of this closed loop.

For advanced Physical AI, the cognitive state can therefore be understood as a continuously updated internal world-and-self model. It combines semantic meaning, geometry, dynamics, memory, uncertainty, goals, task progress, robot capability, safety constraints, and possible futures into representations that support action in real time.

The long-term objective is not to create a perfect digital copy of reality but to construct internal representations that are sufficiently accurate, compact, adaptable, and action-relevant for intelligent behavior. As AI systems become more autonomous, the ability to maintain coherent cognitive state across perception, memory, prediction, reasoning, and action will become one of the central foundations of reliable machine intelligence.

내부 표현(Internal Representations)은 인지 시스템(Cognitive System)이 자신, 환경, 목표, 그리고 세계와 진행 중인 상호작용의 여러 측면을 부호화하는 정보 구조(Information Structures)입니다. 지능형 에이전트(Intelligent Agent)는 원시 감각 입력(Raw Sensory Inputs)에 직접 반응하기보다 관찰을 내부 상태(Internal States)로 변환하며, 이러한 상태는 시간에 걸쳐 기억(Memory), 예측(Prediction), 추론(Reasoning), 계획(Planning), 의사결정(Decision Making), 행동(Action)을 지원합니다.

인지 상태(Cognitive State)는 이러한 시스템 내부에서 현재 활성화되어 있는 정보의 구성을 의미합니다. 인지 상태에는 지각된 객체, 공간적 관계, 현재 목표, 작업 문맥(Task Context), 기억된 사건, 예측, 불확실성(Uncertainty), 주의 우선순위(Attention Priorities), 생물학적 에이전트에서의 감정적 또는 동기적 변수, 계획된 행동 등이 포함될 수 있습니다. 따라서 인지 상태는 특정 순간의 감각 입력보다 훨씬 더 많은 내용을 나타냅니다.

관찰(Observation)과 내부 표현(Internal Representation)의 구분은 매우 중요합니다. 관찰은 센서를 통해 직접 이용할 수 있는 정보를 포함하지만, 내부 표현은 해석(Interpretation)을 통해 구성됩니다. 예를 들어 카메라는 픽셀(Pixels)을 제공하지만 지능 시스템은 문맥에 따라 동일한 픽셀을 사람, 차량, 출입구, 장애물, 조작 가능한 객체 또는 작업 관련 개체(Task-Relevant Entity)로 표현할 수 있습니다.

표현(Representations)은 인지 시스템이 더 이상 물리적으로 존재하지 않는 정보에 대해서도 작동할 수 있도록 합니다. 사람은 몇 분 전에 본 객체에 대해 추론할 수 있고, 로봇은 장애물 뒤에 일시적으로 가려진 목적지를 향해 계속 이동할 수 있습니다. 따라서 내부 상태는 지각의 공백을 넘어 연속성을 제공하고 인지가 즉각적인 감각 자극을 넘어 확장될 수 있도록 합니다.

내부 표현은 여러 추상화 수준(Levels of Abstraction)에서 존재할 수 있습니다. 저수준 표현은 경계, 질감, 깊이, 움직임, 힘 또는 기하학적 특징을 부호화할 수 있습니다. 중간 수준 표현은 객체, 표면, 궤적, 공간적 관계를 설명할 수 있습니다. 상위 수준 표현은 개념, 목표, 의도, 인과관계(Causal Relationships), 작업 구조(Task Structures), 가능한 미래 상황을 부호화할 수 있습니다.

이러한 계층적 구성(Hierarchical Organization)은 서로 다른 인지 연산이 서로 다른 형태의 정보를 필요로 하기 때문에 중요합니다. 모터 제어(Motor Control)는 정밀한 위치, 속도, 힘에 의존할 수 있지만 임무 계획(Mission Planning)은 목적지, 우선순위, 위험, 작업 완료와 같은 의미론적 개념을 필요로 할 수 있습니다. 따라서 지능 시스템은 여러 공간적, 시간적, 의미론적 규모에 적합한 표현을 유지해야 합니다.

표현은 기호적(Symbolic), 분산형(Distributed), 연속적(Continuous), 이산적(Discrete), 또는 하이브리드(Hybrid) 형태일 수 있습니다. 고전적 인지 아키텍처(Classical Cognitive Architectures)는 명시적인 기호와 구조화된 관계를 자주 사용하지만, 신경망(Neural Networks)은 일반적으로 정보를 분산된 수치 벡터로 부호화합니다. 현대 AI는 연속적으로 학습된 표현이 구조화된 개념, 제약조건, 기억, 계획 메커니즘과 상호작용할 수 있도록 이러한 접근법을 점점 더 결합하고 있습니다.

분산 표현(Distributed Representations)은 많은 관련 속성을 고차원 패턴(High-Dimensional Patterns) 안에 함께 부호화할 수 있기 때문에 강력합니다. 신경망은 모든 개념을 수동으로 정의하지 않아도 의미적 유사성, 기하학, 시간 구조, 행동 관련성을 포착하는 표현을 학습할 수 있습니다. 이러한 표현은 유사한 상황이 내부 구조를 공유할 수 있게 하여 일반화(Generalization)를 지원합니다.

명시적 표현(Explicit Representations)은 관계를 해석하고, 조작하고, 검증하고, 전달해야 할 때 여전히 유용합니다. 그래프(Graphs), 지도(Maps), 객체 목록(Object Lists), 장면 구조(Scene Structures), 작업 상태(Task States), 규칙(Rules), 기호 제약조건(Symbolic Constraints)은 중요한 정보를 계획 및 추론 과정에서 직접 이용할 수 있게 합니다. 따라서 하이브리드 인지 아키텍처(Hybrid Cognitive Architectures)는 기능적 요구사항에 따라 신경 표현과 명시적 구조를 결합할 수 있습니다.

내부 표현의 품질은 미래 인지와 행동에 유용한 정보를 얼마나 잘 보존하는지에 달려 있습니다. 표현이 외부 세계의 모든 세부사항을 완벽하게 재현할 필요는 없습니다. 대신 관련 의사결정, 예측, 상호작용, 안전에 필요한 특징은 유지하고 계산 자원을 소모하는 불필요한 복잡성은 제거해야 합니다.

이 원리는 추상화(Abstraction)와 밀접하게 관련됩니다. 건물 내부를 이동하는 로봇은 모든 벽의 세밀한 시각적 질감이 필요하지 않을 수 있지만 자유 공간(Free Space), 장애물, 출입구, 목적지, 이동하는 에이전트, 내비게이션 제약조건(Navigation Constraints)은 표현해야 합니다. 그러나 조작 작업에서는 세밀한 기하학, 방향(Orientation), 표면 특성, 파지 어포던스(Grasp Affordances)가 필수적일 수 있습니다.

작업 의존적 표현(Task-Dependent Representation)은 동일한 환경이라도 현재 목표에 따라 다르게 부호화될 수 있음을 의미합니다. 테이블은 내비게이션 중에는 장애물로 표현될 수 있고, 객체 배치 중에는 지지 표면(Support Surface)으로 표현될 수 있으며, 검사 작업 중에는 목표 구조(Target Structure)로 표현될 수 있습니다. 따라서 인지 상태는 목적과 독립적으로 세계를 나타내기보다 환경 정보와 현재 목표의 상호작용을 반영합니다.

주의(Attention)는 어떤 정보가 인지 상태에 들어오고 활성 상태로 유지되는지에 영향을 미칩니다. 처리 능력이 제한되어 있기 때문에 인지 시스템은 모든 세부사항을 동일한 정밀도로 유지할 수 없습니다. 주의는 관련성, 새로움, 불확실성, 기대 가치, 위험, 현재 목표에 따라 표현의 우선순위를 설정하여 제한된 계산 자원이 가장 중요한 정보에 집중되도록 합니다.

작업 기억(Working Memory)은 현재 인지 과정에서 일시적으로 중요한 표현을 유지합니다. 중간 추론 결과, 최근 관찰한 사건, 임시 목표, 지시사항, 해결되지 않은 질문, 부분적으로 완성된 계획을 보존할 수 있습니다. 작업 기억이 없다면 인지 시스템은 문맥을 반복적으로 잃고, 여러 단계가 서로 의존하는 복잡한 작업을 수행하는 데 어려움을 겪게 됩니다.

장기 기억(Long-Term Memory)은 현재 작업을 넘어 정보를 보존함으로써 작업 기억을 보완합니다. 의미 기억(Semantic Memory)은 개념과 일반 지식을 저장할 수 있고, 일화 기억(Episodic Memory)은 특정 경험을 보존할 수 있으며, 절차 기억(Procedural Memory)은 학습된 기술이나 정책을 나타낼 수 있습니다. 인지 상태는 이러한 기억 시스템에서 관련 정보를 검색하여 현재 관찰과 통합할 수 있습니다.

따라서 기억 검색(Memory Retrieval)은 상태 구성(State Construction)의 능동적인 구성요소입니다. 지능형 에이전트의 내부 상태는 현재 무엇을 지각하는지뿐 아니라 어떤 이전 지식이 활성화되는지에 의해서도 결정됩니다. 동일한 상황을 관찰하는 두 에이전트라도 경험, 기대, 목표, 학습된 표현이 다르면 서로 다른 인지 상태를 구성할 수 있습니다.

시간적 표현(Temporal Representation)은 지능적 행동이 시간에 걸쳐 진행되기 때문에 필수적입니다. 인지 상태를 고립된 스냅샷으로 해석해서는 안 되며 지속적으로 변화하는 시퀀스의 일부로 보아야 합니다. 이전 상태는 현재의 해석에 영향을 주고, 현재 행동은 미래 관찰을 변화시키며, 예측은 현재 표현을 가능한 미래 상태와 연결합니다.

상태 추정(State Estimation)은 이러한 연속성을 유지하는 계산적 프레임워크를 제공합니다. 관찰은 불완전하고 잡음이 포함되어 있기 때문에 에이전트는 현재 센서 측정값을 이전 상태 추정값 및 세계 변화 모델과 결합하여 환경의 기저 상태(Underlying State)를 추정합니다. 이를 통해 개별 관찰이 불확실하거나 일시적으로 사용할 수 없더라도 정보의 일관성을 유지할 수 있습니다.

확률적 상태 추정(Probabilistic State Estimation)은 불확실성을 명시적으로 표현합니다. 모든 객체 위치, 분류, 환경 조건이 정확히 알려져 있다고 가정하는 대신 시스템은 확률 분포(Probability Distributions), 신뢰도 값(Confidence Values), 또는 대안 가설(Alternative Hypotheses)을 유지할 수 있습니다. 이를 통해 이후의 추론과 계획은 무엇을 믿고 있는지뿐 아니라 그 믿음이 얼마나 신뢰할 수 있는지도 고려할 수 있습니다.

따라서 불확실성은 단순히 지각 오류에 부가되는 요소가 아니라 인지 상태의 일부입니다. 지능형 에이전트는 객체 분류가 모호한지, 위치 추정 신뢰도가 낮은지, 예측이 불안정한지, 기억된 사실이 오래되었을 가능성이 있는지를 알아야 합니다. 불확실성을 표현하면 지식이 불완전할 때 행동을 적절하게 변경할 수 있습니다.

신념 상태(Belief State)는 환경을 완전히 관찰할 수 없는 상황에서 유용한 개념입니다. 신념 상태는 관찰, 기억, 행동, 사전 지식(Prior Knowledge)을 기반으로 가능한 세계 상태에 대한 에이전트의 현재 추정을 나타냅니다. 이후 계획은 완벽하게 알려진 외부 상태를 가정하는 대신 이러한 신념을 기반으로 수행될 수 있습니다.

이는 부분 관측 환경(Partially Observable Environments)에서 특히 중요합니다. 로봇이 차량 뒤로 이동한 보행자를 잠시 보지 못하더라도 해당 보행자가 내부 표현에서 즉시 사라져서는 안 됩니다. 새로운 증거가 해당 가설을 확인하거나 갱신하거나 제거할 때까지 로봇은 사람의 예상 위치와 움직임에 대한 신념을 유지할 수 있습니다.

예측(Prediction)은 인지 상태를 미래로 확장합니다. 에이전트가 현재 상황에 대한 내부 표현을 가지면 객체, 다른 에이전트, 환경 조건이 어떻게 변화할지를 추정할 수 있습니다. 예측된 상태는 실제 행동을 수행하기 전에 가능한 결과를 평가할 수 있게 하며 지능적 계획의 중요한 기반을 형성합니다.

월드 모델(World Model)은 시간에 따라 인지 상태를 연결하는 동역학(Dynamics)을 제공합니다. 월드 모델은 표현된 세계가 자연스럽게 어떻게 변화하고 행동이 이러한 변화를 어떻게 수정하는지를 설명하거나 학습합니다. 현재 인지 상태와 월드 동역학을 결합하면 에이전트는 사건이 이미 발생한 후 반응하는 대신 미래 궤적을 시뮬레이션할 수 있습니다.

월드 모델이 반드시 원시 감각 데이터를 직접 예측할 필요는 없습니다. 많은 지능형 작업에서는 압축된 잠재 표현(Latent Representation) 안에서 예측하는 것이 더 효율적일 수 있습니다. 잠재 월드 모델(Latent World Model)은 작업 관련 구조를 부호화하고 이 표현이 어떻게 변화하는지를 예측하여 완전한 고해상도 미래 관찰을 생성하는 데 필요한 계산 부담을 줄일 수 있습니다.

그러나 잠재 표현은 중요한 설계 과제를 제기합니다. 압축 과정에서 나중에 중요해질 정보가 제거되면 잠재 모델 내부에서는 일관성이 있더라도 예측과 계획이 실패할 수 있습니다. 따라서 표현 학습(Representation Learning)은 압축성(Compactness)과 제어, 안전, 일반화, 미래 작업에 필요한 정보 보존 사이에서 균형을 유지해야 합니다.

예측적 표현(Predictive Representations)은 자기지도학습(Self-Supervised Learning)을 통해 학습할 수 있습니다. 에이전트는 미래 관찰, 마스킹된 정보(Masked Information), 시간적 관계, 객체 움직임, 상태 전이, 행동 효과를 예측함으로써 유용한 내부 구조를 학습할 수 있습니다. 이를 통해 방대한 양의 라벨 없는 상호작용 데이터가 인지 표현의 발전에 직접 기여할 수 있습니다.

예측 오류(Prediction Errors)는 내부 상태와 학습된 모델을 갱신하는 메커니즘을 제공합니다. 예상한 관찰과 실제 관찰이 다르면 상태 추정, 동역학 모델, 가정 또는 예측 중 일부가 잘못되었을 가능성이 있다는 증거가 됩니다. 이러한 차이는 상태 수정, 모델 적응, 주의 전환, 추가 정보 수집을 유발할 수 있습니다.

이로써 표현과 예측이 서로를 정교화하는 지속적인 순환 구조가 형성됩니다. 내부 상태는 미래 관찰에 대한 기대를 생성하고, 환경은 실제 관찰을 제공하며, 기대와 현실의 차이는 상태를 수정합니다. 따라서 인지 표현은 세계를 설명하는 정적인 데이터베이스가 아니라 동적으로 변화하는 구조입니다.

행동(Action) 역시 인지 상태 안에 표현되어야 합니다. 지능 시스템은 현재 무엇을 하고 있는지, 최근 어떤 행동을 수행했는지, 어떤 행동이 가능한지, 그 행동에서 어떤 결과를 예상하는지를 알아야 합니다. 행동 이력이 없다면 관찰 변화가 외부 사건 때문인지 에이전트 자신의 행동 결과인지 구분하기 어려울 수 있습니다.

행동 표현은 에이전시(Agency)와 인과 학습(Causal Learning)을 가능하게 합니다. 에이전트가 어떤 개입을 수행했는지 알고 그 결과 상태 전이를 관찰하면 행동과 결과 사이의 관계를 학습할 수 있습니다. 이는 수동적으로 관찰된 사건들의 상관관계만 학습하는 것과 근본적으로 다르며 더 신뢰할 수 있는 계획과 제어를 지원합니다.

목표(Goals)는 인지 상태의 또 다른 핵심 구성요소입니다. 동일한 지각 상황도 목표에 따라 서로 다른 행동으로 이어질 수 있습니다. 목표를 표현하면 지각, 주의, 기억 검색, 예측, 계획이 일반적인 처리에 머무르지 않고 작업 지향적으로 변합니다. 목표는 장기 임무(Long-Term Missions)부터 즉각적인 제어 목표까지 계층적으로 구성될 수도 있습니다.

작업 상태(Task State)는 진행 중인 활동에서 현재 진행 위치를 나타냅니다. 완료된 하위 작업, 현재 절차, 남은 요구사항, 의존성, 제약조건, 예상되는 다음 단계를 포함할 수 있습니다. 장기 행동(Long-Horizon Behavior)을 위해서는 에이전트가 물리적 위치뿐 아니라 작업의 논리적 구조에서 현재 어느 단계에 있는지도 알아야 하므로 작업 상태 유지가 필수적입니다.

계획(Plans) 자체도 내부 표현이 될 수 있습니다. 계획은 의도된 미래 행동, 의존 관계, 대안 분기(Alternative Branches), 체크포인트(Checkpoints), 예상 결과를 부호화할 수 있습니다. 실행 과정에서는 실제 관찰을 예상 계획 상태와 비교하여 편차를 탐지하고 필요할 경우 재계획(Replanning)을 수행할 수 있습니다.

따라서 인지 상태는 과거, 현재, 미래의 표현을 동시에 포함할 수 있습니다. 기억은 이전 상태와 행동에 대한 정보를 제공하고, 지각은 현재를 추정하며, 예측은 가능한 미래 상태를 나타냅니다. 계획은 현재를 원하는 미래 조건으로 변화시키기 위한 행동을 선택함으로써 이러한 시간 영역들을 연결합니다.

공간 표현(Spatial Representations)은 체화 에이전트(Embodied Agents)에서 특히 중요합니다. 로봇은 메트릭 지도(Metric Maps), 위상 지도(Topological Maps), 점유 격자(Occupancy Grids), 복셀 표현(Voxel Representations), 포인트 클라우드(Point Clouds), 객체 중심 지도(Object-Centric Maps), 의미 지도(Semantic Maps), 조감도 표현(Bird\'s-Eye-View Representations) 등을 유지할 수 있습니다. 각각은 기하학적 정밀도, 의미적 풍부함, 계산 효율성, 계획 유용성 사이에서 서로 다른 장단점을 가집니다.

객체 중심 표현(Object-Centric Representations)은 원시 센서 측정값이 아니라 지속적으로 존재하는 개체(Entity)를 중심으로 인지 상태를 구성합니다. 하나의 객체는 시간에 걸쳐 정체성(Identity), 위치, 기하학, 의미 범주, 속도, 불확실성, 특성, 상호작용 이력을 유지할 수 있습니다. 이러한 표현은 서로 다른 시점의 관찰이 동일한 물리적 개체를 가리킨다는 것을 추론하는 데 도움을 줍니다.

장면 그래프(Scene Graphs)는 개체들 사이의 관계를 명시적으로 표현함으로써 이러한 개념을 확장합니다. 객체는 내부(Inside), 근처(Near), 지지(Supporting), 차단(Blocking), 부착(Attached To), 접근(Moving Toward), 소속(Belonging To)과 같은 공간적, 의미적, 기능적, 인과적 관계로 연결될 수 있습니다. 그래프 표현은 많은 상호작용 요소가 존재하는 복잡한 환경을 추론하는 데 유용한 구조를 제공합니다.

어포던스 표현(Affordance Representations)은 에이전트와 환경 내 개체 사이에서 가능한 상호작용을 설명합니다. 표면은 배치를 지원할 수 있고, 객체는 파지 가능할 수 있으며, 출입구는 통과를 허용할 수 있고, 버튼은 누르는 행동을 허용할 수 있습니다. 어포던스는 어떤 것이 무엇인지뿐 아니라 그것으로 무엇을 할 수 있는지를 표현함으로써 지각을 행동과 연결합니다.

피지컬 AI(Physical AI)에서는 객체 인식(Object Recognition)에서 어포던스 이해(Affordance Understanding)로의 이러한 전환이 특히 중요합니다. 실제 작업을 완료하는 로봇은 도달 가능성(Reachability), 조작 가능성(Manipulability), 주행 가능성(Traversability), 지지, 충돌, 안정성, 물리적 제약조건을 추론해야 합니다. 따라서 인지 상태는 의미론적 이해를 기하학과 동역학에 연결하는 표현을 필요로 합니다.

신체 표현(Body Representation) 역시 체화 지능(Embodied Intelligence)에 필요합니다. 로봇은 자신의 구성(Configuration), 크기, 관절 상태, 액추에이터 한계, 페이로드(Payload), 속도, 에너지 상태, 센서 상태, 도달 가능 작업 공간(Reachable Workspace)을 표현해야 합니다. 지능적 행동은 외부 세계뿐 아니라 그 세계와 상호작용하는 자신의 신체 능력과 한계를 이해하는 데 의존합니다.

이러한 자기 표현(Self-Representation)은 능력 인식 계획(Capability-Aware Planning)을 지원합니다. 동일한 경로라도 폭, 지상고(Ground Clearance), 회전 반경(Turning Radius), 페이로드, 접지력(Traction), 에너지 한계 때문에 한 로봇에게는 통과 가능하지만 다른 로봇에게는 불가능할 수 있습니다. 마찬가지로 조작 행동은 도달 거리, 힘, 관절 한계, 현재 자세에 따라 평가되어야 합니다.

따라서 내부 표현은 세계 상태(World State)와 자기 상태(Self-State)를 모두 포함해야 합니다. 이 둘의 상호작용이 가능한 행동을 결정합니다. 장애물의 의미는 로봇의 기하학과의 관계에 따라 달라지고, 객체의 파지 가능성은 매니퓰레이터(Manipulator)의 능력에 따라 결정됩니다. 지능적 상태 표현은 본질적으로 관계적(Relational)이며 단순히 환경 자체만을 나타내지 않습니다.

멀티모달 표현(Multi-Modal Representation)은 정보가 여러 센서와 정보원에서 발생하기 때문에 필요합니다. 비전(Vision)은 외형과 의미 정보를 제공하고, 라이다는 기하학을 제공하며, 레이더는 움직임 정보를 제공하고, 관성 측정 장치(IMU)는 관성 동역학을 제공하며, 위성항법시스템(GNSS)은 전역 위치를 제공하고, 고유수용 센서는 로봇 내부의 물리 상태를 설명합니다.

센서 융합(Sensor Fusion)은 이러한 양식을 개별 측정값보다 더 유용한 표현으로 결합합니다. 융합은 원시 데이터, 특징, 객체, 상태 또는 의사결정 수준에서 이루어질 수 있습니다. 적절한 전략은 동기화(Synchronization), 불확실성, 계산 자원, 센서 특성, 이후 예측 및 계획 모듈의 요구사항에 따라 달라집니다.

공유 월드 상태(Shared World State)는 지각, 기억, 월드 모델링, 계획, 제어 사이의 공통 인터페이스를 제공할 수 있습니다. 각 모듈이 환경을 독립적으로 다시 구성하는 대신 관련 정보를 일관된 상태 표현 안에서 유지할 수 있습니다. 이를 통해 분절(Fragmentation)을 줄이고 한 서브시스템이 발견한 변화가 다른 서브시스템에서도 이용 가능하도록 합니다.

그러나 하나의 표현 형식만으로 모든 인지 기능을 지원하기는 어렵습니다. 고주파 제어(High-Frequency Control)는 압축된 수치 상태를 필요로 하지만, 의미 추론은 객체와 관계 구조를 필요로 할 수 있습니다. 장기 기억은 압축된 일화 표현을 요구할 수 있고, 계획은 예측 궤적을 필요로 할 수 있습니다. 따라서 효과적인 아키텍처는 여러 수준의 표현이 서로 조정되도록 지원해야 합니다.

여러 모델이 함께 작동할 때 표현 정렬(Representation Alignment)이 중요해집니다. 지각 모델, 언어 모델, 월드 모델, 플래너, 행동 모델은 서로 다른 방식으로 정보를 부호화할 수 있습니다. 인터페이스는 의미론적 의미, 공간 관계, 불확실성, 시간 문맥이 구성요소 사이에서 일관되게 유지되도록 이러한 표현을 변환하거나 정렬해야 합니다.

파운데이션 모델(Foundation Models)은 강력한 사전학습 표현 공간(Pretrained Representation Spaces)을 제공합니다. 비전 및 멀티모달 파운데이션 모델은 대규모 데이터셋에서 학습한 의미적 관계를 부호화할 수 있으며, 언어 모델은 개념, 지시, 추상 지식에 대한 표현을 제공합니다. 이러한 모델의 표현이 현재의 감각 정보와 물리적 정보에 그라운딩(Grounding)될 때 인지 상태를 크게 풍부하게 만들 수 있습니다.

지각 파운데이션 모델(Perception Foundation Models)은 원시 감각 관찰을 재사용 가능한 의미 특징(Semantic Features)으로 변환할 수 있습니다. 모든 로봇 지각 능력을 처음부터 학습하는 대신 사전학습 표현을 작업 관련 개체와 관계를 인식하도록 적응시킬 수 있습니다. 미세조정(Fine-Tuning)이나 특화 헤드(Specialized Heads)는 범용 표현을 특정 센서, 환경, 운영 목표와 연결할 수 있습니다.

언어 파운데이션 모델(Language Foundation Models)은 목표, 지시, 절차, 제약조건, 개념 관계에 대한 상위 수준 표현을 제공할 수 있습니다. 그러나 언어 표현을 물리적 상태와 동일한 것으로 간주해서는 안 됩니다. 환경에 대한 언어적 서술은 실제 물리적 행동을 안전하게 유도하기 전에 현재 센서 증거 및 월드 상태 추정과 연결되어야 합니다.

행동 파운데이션 모델(Action Foundation Models)은 재사용 가능한 행동 패턴을 표현할 수 있습니다. 움직임 시퀀스(Motion Sequences), 조작 기술, 내비게이션 행동, 상호작용 전략을 여러 작업이나 플랫폼으로 전이 가능한 형태로 부호화할 수 있습니다. 이러한 행동 표현은 현재 인지 상태, 로봇 능력, 목표, 예측된 결과에 조건화될 때 가장 유용해집니다.

월드 모델은 이러한 표현들 사이의 시간적 연결 고리를 제공합니다. 월드 모델은 지각과 기억을 통해 구성된 현재 상태를 입력받고, 후보 행동을 포함하여 미래 상태를 추정할 수 있습니다. 이후 플래너는 예측된 미래를 목표 및 제약조건과 비교하여 내부 표현을 숙고적 의사결정(Deliberate Decision Making)의 기반으로 변환합니다.

인지 상태는 안전 관련 변수(Safety-Relevant Variables)도 명시적으로 표현해야 합니다. 충돌 확률(Collision Probability), 안정성 여유(Stability Margins), 위치 추정 신뢰도, 센서 상태, 통신 상태, 에너지 잔량, 환경 위험, 운영 제약조건은 바람직해 보이는 행동이 실제로 허용 가능한지를 결정할 수 있습니다. 안전은 학습된 표현 안에 숨겨진 암묵적 특징에만 의존해서는 안 됩니다.

명시적 안전 상태(Explicit Safety State)는 독립적인 검증을 지원합니다. 학습된 플래너가 행동을 제안하면 안전 계층(Safety Layer)이 예측 궤적이 물리적, 운영적, 규제적 제약조건을 만족하는지 확인할 수 있습니다. 안전 정보를 작업 목표와 별도로 유지하면 성능 최적화 과정에서 중요한 안전 요소가 우연히 억제될 위험을 줄일 수 있습니다.

메타인지 상태(Metacognitive State)는 시스템 자신의 인지 과정에 대한 정보를 나타냅니다. 신뢰도, 불확실성, 탐지된 모순, 모델 신뢰성(Model Reliability), 계산 부하(Computational Load), 누락된 정보, 추가 추론 필요성 등을 포함할 수 있습니다. 이를 통해 지능 시스템은 어떤 행동을 선택할지만이 아니라 어떻게 사고할지를 변경할 수 있습니다.

예를 들어 지각 불확실성이 높으면 시스템은 추가 센서 정보를 수집할 수 있고, 모델 간 불일치가 발생하면 검증을 수행할 수 있습니다. 계산 부하가 높으면 낮은 우선순위 처리를 연기할 수 있습니다. 따라서 메타인지 상태는 주의, 계산, 기억, 추론 자원의 적응형 할당을 지원합니다.

인지 상태에는 새로움(Novelty)과 친숙성(Familiarity)에 대한 추정도 포함될 수 있습니다. 이전 경험과 유사한 상황은 기존 정책으로 처리할 수 있지만, 익숙하지 않은 상태에서는 더 신중한 행동, 탐색, 추가 센싱, 인간의 지원이 필요할 수 있습니다. 새로움 탐지(Novelty Detection)는 학습 경험의 범위를 벗어난 상황에서 과도한 확신으로 작동하는 것을 방지하는 중요한 메커니즘입니다.

분포 변화 탐지(Distribution-Shift Detection)는 이러한 개념을 실제 배포된 AI로 확장합니다. 특정 환경 조건에서 학습한 모델이 새로운 날씨, 지형, 객체, 센서, 운영 패턴을 만날 수 있습니다. 현재 입력이 학습 경험과 크게 다르다는 것을 탐지하면 시스템은 신뢰도를 낮추고 적응 또는 대체 메커니즘(Fallback Mechanisms)을 활성화할 수 있습니다.

따라서 내부 상태는 신뢰성(Reliability)의 핵심입니다. 많은 실패는 시스템에 적절한 행동이 없어서가 아니라 상황을 잘못 표현하고 있기 때문에 발생합니다. 로봇은 부정확한 지도나 잘못 추정된 객체 위치를 기준으로는 완벽하게 계획하더라도 실패할 수 있습니다. 따라서 상태 추정의 품질을 향상시키는 것은 계획 알고리즘을 개선하는 것만큼 중요할 수 있습니다.

상태 일관성(State Consistency)은 시간과 센서 양식 사이에서 모니터링되어야 합니다. 카메라 지각이 한 위치에 객체가 있다고 판단하고 라이다가 다른 위치를 나타낼 경우 이러한 불일치를 단순히 평균화하여 숨겨서는 안 됩니다. 시스템은 충돌 정보를 표현하고 가능한 원인을 추정하며 재보정(Recalibration), 추가 관찰 또는 보수적인 행동이 필요한지를 판단해야 합니다.

시간 동기화(Time Synchronization)는 일관된 멀티모달 인지 상태를 유지하는 데 필수적입니다. 서로 다른 시점에 수집된 센서 측정값은 객체나 로봇이 움직일 때 잘못된 공간 관계를 만들어낼 수 있습니다. 따라서 정확한 타임스탬프(Timestamps), 동기화, 움직임 보상(Motion Compensation), 상태 전파(State Propagation)는 신뢰할 수 있는 센서 융합과 월드 표현의 기본 요구사항입니다.

모바일 로봇(Mobile Robots)에서는 거의 모든 공간적 관계가 추정된 로봇 자세(Robot Pose)에 의존하기 때문에 위치 추정(Localization)이 인지 상태의 핵심 구성요소가 됩니다. 위치 추정 불확실성은 매핑, 객체 추적, 경로 계획, 조작으로 전파됩니다. 따라서 신뢰할 수 있는 인지 아키텍처는 추정 자세뿐 아니라 신뢰도와 위치 추정 실패 가능성도 표현해야 합니다.

매핑(Mapping)은 상태를 즉각적인 센서 범위를 넘어 확장합니다. 지도는 현재 보이지 않는 위치에 대해 추론할 수 있도록 지속적인 공간 정보를 저장합니다. 의미 지도와 객체 수준 지도는 특정 위치에 무엇이 존재하는지에 대한 정보도 저장할 수 있으며, 이를 통해 매핑은 단순한 기하학적 기억에서 장기 인지 표현의 구성요소로 발전합니다.

동적 환경(Dynamic Environments)에서는 인지 상태가 지속적인 구조와 일시적인 변화를 구분해야 합니다. 건물과 고정 인프라는 안정적으로 유지될 수 있지만 사람, 차량, 이동 가능한 객체, 날씨, 임시 장애물은 지속적으로 변화합니다. 따라서 월드 표현의 서로 다른 구성요소에는 서로 다른 갱신 속도(Update Rates)와 기억 정책(Memory Policies)이 적합합니다.

추적(Tracking)은 동적 개체에 시간적 정체성(Temporal Identity)을 부여합니다. 모든 센서 탐지를 새로운 객체로 취급하는 대신 추적은 시간이 지나도 어떤 관찰들이 동일한 개체를 의미하는지에 대한 가설을 유지합니다. 이를 통해 속도 추정, 궤적 예측, 행동 해석, 이동 에이전트 주변에서의 안정적인 계획이 가능해집니다.

에이전트 표현(Agent Representations)은 물리적 상태 이상을 포함할 수 있습니다. 사람이나 다른 로봇이 존재하는 환경에서는 목표, 의도, 예상 궤적, 통신 상태, 예상 행동을 인지 상태에 포함할 수 있습니다. 이러한 표현은 사회적 인식 내비게이션(Socially Aware Navigation), 협력, 협상, 멀티에이전트 계획을 지원합니다.

멀티에이전트 시스템(Multi-Agent Systems)은 분산 인지 상태(Distributed Cognitive State)를 도입합니다. 각 에이전트는 지역적 관찰과 내부 표현을 가지며, 공유 정보는 더 넓은 집단 상태(Collective State)를 형성할 수 있습니다. 통신을 통해 로봇은 지도, 탐지된 위험, 작업 진행 상황, 예측, 학습된 지식을 교환하여 개별 에이전트의 감각 범위와 경험을 넘어 인지를 확장할 수 있습니다.

공유 플릿 상태(Shared Fleet State)는 더 높은 수준의 조정을 지원할 수 있습니다. 로봇 위치, 능력, 배터리 수준, 할당된 작업, 환경 조건, 혼잡 상태, 임무 진행 상황을 표현할 수 있습니다. 이후 플릿 수준 추론(Fleet-Level Reasoning)은 작업과 자원을 할당하고, 각 로봇은 실시간 제어에 필요한 상세한 지역 상태를 유지할 수 있습니다.

엣지(Edge)와 온프레미스(On-Premise) 아키텍처는 지연시간과 범위에 따라 인지 상태를 분할할 수 있습니다. 로봇은 즉각적인 지각, 안전, 제어, 지역 계획에 필요한 상태를 온보드(Onboard)에 유지해야 하고, 온프레미스 시스템은 더 넓은 플릿 상태, 장기 기억, 대규모 지도, 역사 데이터, 계산 비용이 높은 예측 모델을 유지할 수 있습니다.

이러한 분할은 통신 손실 상황에서도 자율성을 유지해야 합니다. 중요한 인지 상태는 온보드에 남아 있어야 하며 외부 인프라가 일시적으로 사용할 수 없더라도 로봇이 안전하게 작동할 수 있어야 합니다. 외부 시스템은 핵심적인 실시간 행동의 단일 고장점(Single Point of Failure)이 되지 않으면서 지능을 향상시키는 역할을 해야 합니다.

로봇 또는 계산 계층 사이에서 인지 정보를 전달할 때 상태 압축(State Compression)이 중요해집니다. 모든 원시 센서 스트림을 전송하는 것은 비효율적인 경우가 많습니다. 관련 객체, 특징, 사건, 불확실성, 상태 변화만을 포함하는 압축 표현은 조정과 추론에 필요한 정보를 유지하면서 대역폭 요구를 줄일 수 있습니다.

이벤트 기반 표현(Event-Based Representation)은 효율성을 더욱 향상시킬 수 있습니다. 변하지 않은 상태를 지속적으로 전송하는 대신 새롭게 탐지된 장애물, 위치 추정 저하, 작업 완료, 예상하지 못한 행동, 중요한 예측 오류와 같은 의미 있는 변화만 전달할 수 있습니다. 이는 인지적 중요도에 따라 정보를 우선시한다는 점에서 선택적 주의와 유사합니다.

지속적인 인지 상태(Persistent Cognitive State)는 경험을 시간에 걸쳐 연결할 수 있기 때문에 지속학습(Continual Learning)을 가능하게 합니다. 시스템은 중요한 관찰, 의사결정, 예측, 결과, 오류를 저장하여 이후 분석에 활용할 수 있습니다. 학습 과정은 반복적인 실패를 식별하고, 표현을 개선하고, 월드 모델을 갱신하며, 검증된 개선 사항을 배포된 에이전트에 다시 전달할 수 있습니다.

모든 경험을 영구적으로 저장할 필요는 없습니다. 지능형 기억 관리(Intelligent Memory Management)는 어떤 사건이 새롭고, 정보 가치가 높고, 불확실하고, 성공적이고, 위험하며, 대표성이 있는지를 판단하여 보존해야 합니다. 선택적 기억은 저장 요구를 줄이면서 미래 학습과 평가를 위해 유지되는 데이터의 가치를 높입니다.

경험 리플레이(Experience Replay)는 저장된 인지 궤적(Cognitive Trajectories)을 학습에 사용할 수 있습니다. 상태, 행동, 예측, 보상, 결과가 포함된 시퀀스를 이후 다시 샘플링하여 정책이나 월드 모델을 개선할 수 있습니다. 특히 중요한 실패와 희귀 사건(Rare Events)은 일상적인 성공보다 더 많은 학습 정보를 포함할 수 있기 때문에 더 높은 우선순위를 받을 수 있습니다.

지속학습 과정에서는 표현 안정성(Representation Stability)이 중요합니다. 모델이 갱신될 때 내부 표현이 크게 변하면 기억, 플래너, 이후 모듈과의 호환성이 깨질 수 있습니다. 따라서 지속학습 아키텍처는 개선을 허용하면서도 버전 사이에 충분한 일관성을 유지하고 중요한 기존 지식을 보호하는 메커니즘을 필요로 합니다.

표현 버전 관리(Representation Versioning)는 배포 시스템에서 이러한 문제를 관리하는 데 도움을 줄 수 있습니다. 모델, 지도, 스키마(Schemas), 학습된 상태 인코딩에 명시적인 버전을 부여하면 업데이트를 배포하기 전에 호환성을 시험할 수 있습니다. 이는 여러 로봇이 일시적으로 서로 다른 소프트웨어 또는 모델 버전을 사용할 수 있는 플릿 환경에서 특히 중요합니다.

인지 표현의 평가는 시각적 또는 수학적 우아함이 아니라 실제 유용성을 중심으로 이루어져야 합니다. 좋은 표현은 예측, 계획, 일반화, 적응, 신뢰성, 효율적인 행동을 향상시켜야 합니다. 필요한 정보를 보존하고, 불확실성을 드러내며, 갱신을 지원하고, 목표 플랫폼에서 계산적으로 실용적이어야 합니다.

피지컬 AI에서는 표현 품질을 폐루프 성능(Closed-Loop Performance)을 통해 평가할 수 있습니다. 중요한 질문은 내부 상태가 환경을 얼마나 정확하게 재구성하는가만이 아니라 로봇이 그 상태를 이용하여 변화하는 실제 환경에서 안전하게 내비게이션하고, 조작하고, 예측하고, 오류에서 복구하고, 작업을 완료할 수 있는가입니다.

이는 행동 관련 표현(Action-Relevant Representation)의 개념으로 이어집니다. 서로 다른 행동이나 결과를 요구하는 상태를 구분하는 데 도움이 될 때 정보는 가치가 있습니다. 시각적으로 서로 다른 두 상황이 특정 작업에서는 동등할 수 있지만, 시각적으로 거의 같은 두 상황도 숨겨진 물리적 또는 의미적 제약조건 때문에 완전히 다른 행동을 요구할 수 있습니다.

예측적 표현(Predictive Representation)도 유사한 원리를 따릅니다. 유용한 상태는 중요한 미래 변화를 예측하는 데 충분한 정보를 포함해야 합니다. 두 관찰이 현재에는 비슷하게 보이지만 이후 결과가 다르다면 표현은 그 차이를 설명하는 변수를 보존해야 합니다. 따라서 월드 모델 학습은 외형만이 아니라 동역학을 중심으로 표현을 형성할 수 있습니다.

인과 표현(Causal Representation)은 한 단계 더 나아가 개입이 결과에 어떻게 영향을 미치는지를 설명하는 변수를 부호화합니다. 이는 환경의 상관관계가 변화하더라도 개입 아래에서 의미가 유지되는 관계를 활용하기 때문에 일반화를 향상시킬 수 있습니다. 자율 에이전트가 환경을 의도적으로 변화시켜야 하는 상황에서는 인과적 상태 표현이 특히 중요합니다.

내부 표현과 인지 상태는 궁극적으로 센싱(Sensing)과 지능적 행동 사이의 인터페이스를 형성합니다. 센서는 관찰을 제공하지만, 인지는 이러한 관찰을 지속적이고, 구조화되고, 불확실성을 포함하며, 예측 가능하고, 목표에 조건화되고, 행동과 관련된 정보로 변환해야 합니다. 이러한 변환의 품질은 이후 추론과 제어의 품질을 크게 결정합니다.

통합 AI 아키텍처(Integrated AI Architecture)에서는 지각이 인지 상태를 갱신하고, 기억이 이전 지식으로 이를 풍부하게 하며, 주의가 관련 정보를 우선시하고, 월드 모델이 미래 상태를 예측하고, 추론이 대안을 해석하고, 계획이 행동을 선택하고, 제어가 환경을 변화시키며, 새로운 관찰이 다시 표현을 수정합니다. 지능은 이러한 폐루프가 지속적으로 작동하는 과정에서 나타납니다.

고급 피지컬 AI(Advanced Physical AI)에서 인지 상태는 지속적으로 갱신되는 내부 세계-자기 모델(Internal World-and-Self Model)로 이해할 수 있습니다. 의미론적 의미, 기하학, 동역학, 기억, 불확실성, 목표, 작업 진행 상태, 로봇 능력, 안전 제약조건, 가능한 미래를 하나의 표현 체계 안에 결합하여 실시간 행동을 지원합니다.

장기적인 목표는 현실의 완벽한 디지털 복제본을 만드는 것이 아니라 지능적 행동에 충분히 정확하고, 압축되어 있으며, 적응 가능하고, 행동과 관련된 내부 표현을 만드는 것입니다. AI 시스템의 자율성이 높아질수록 지각, 기억, 예측, 추론, 행동에 걸쳐 일관된 인지 상태를 유지하는 능력은 신뢰할 수 있는 기계 지능(Reliable Machine Intelligence)의 핵심 기반 가운데 하나가 될 것입니다.

##  

## 01.10 Prediction and Anticipation [w/Code]

![](images/image11.png){width="7.268055555555556in" height="7.268055555555556in"}

Prediction is the cognitive process of estimating what is likely to happen next from current observations, prior knowledge, internal representations, and learned regularities. Anticipation extends prediction by preparing cognition and action for expected future conditions. Together, they allow intelligent agents to act before events fully unfold instead of responding only after changes have already occurred.

Prediction is fundamental because the sensory world is continuously changing and information always arrives with some delay. A moving object may change position before its current state has been completely processed, and an action may require time before its effect becomes visible. Cognitive systems therefore benefit from estimating future states so that perception and behavior remain aligned with dynamic environments.

Anticipation transforms prediction into preparation. If a person expects a vehicle to enter an intersection, attention can shift toward the possible conflict area and motor responses can be prepared in advance. The same principle applies to artificial agents, where predicted events can change sensing priorities, planning, resource allocation, and safety behavior before the expected event occurs.

Prediction depends on internal representations that summarize relevant aspects of the current situation. These representations may include object locations, velocities, semantic categories, goals, environmental constraints, uncertainty, previous actions, and relationships among entities. A richer and more accurate cognitive state generally provides a stronger foundation for estimating how the situation may evolve.

Temporal continuity is therefore essential. Prediction cannot rely only on isolated observations because many future states depend on trends that become visible only across time. Tracking an object\'s previous positions, for example, provides information about velocity and acceleration that cannot be inferred reliably from a single measurement. Memory and state estimation consequently contribute directly to predictive cognition.

Short-term prediction supports immediate perception and control. Estimating where a moving object will be a fraction of a second later allows an agent to compensate for sensor and control latency. Humans perform such anticipation naturally during reaching, catching, walking, and driving, while autonomous systems use similar principles for tracking, collision avoidance, and trajectory control.

Medium-horizon prediction supports planning over several seconds or minutes. A mobile robot may estimate how pedestrians, vehicles, doors, or obstacles will change while it approaches them. These predictions allow the planner to choose routes and actions that remain feasible when the robot reaches future locations rather than optimizing only for the current geometry.

Long-term anticipation operates over larger timescales and involves increasingly abstract representations. Instead of predicting exact trajectories, an intelligent system may estimate future task states, resource demands, environmental conditions, or likely intentions. Long-horizon prediction therefore often moves from detailed physical dynamics toward probabilistic, semantic, and strategic expectations.

Different prediction horizons require different levels of accuracy. Short-horizon physical predictions can often be relatively precise because fewer unknown events can intervene. Uncertainty generally increases as the prediction horizon extends because small errors accumulate and unobserved decisions or environmental changes can alter future trajectories. Intelligent systems should explicitly represent this growth in uncertainty.

Prediction should therefore rarely be treated as a single deterministic future. Complex environments usually permit multiple plausible developments. A pedestrian may continue walking, slow down, stop, or change direction. Maintaining several possible future trajectories allows planning systems to evaluate alternatives rather than becoming overconfident in one predicted outcome.

Probability provides a useful way to represent these alternatives. Instead of predicting that one future definitely will occur, a cognitive system can assign different likelihoods to several outcomes. Decisions can then consider both the probability and consequence of each possibility, allowing low-probability but high-risk events to influence behavior appropriately.

Prediction and uncertainty are closely connected because a useful prediction should communicate not only what is expected but also how strongly it is believed. Confidence can depend on observation quality, familiarity, model reliability, environmental variability, and prediction horizon. Systems that hide uncertainty may make precise-looking predictions that encourage unsafe decisions.

Anticipation also depends on expected consequences rather than probability alone. A highly probable but harmless event may require little attention, while an unlikely collision may require immediate preparation. Intelligent anticipation therefore combines likelihood, consequence, urgency, and available response time when determining which predicted futures deserve processing priority.

Prediction is strongly linked with attention. Expectations can guide attention toward locations, objects, or signals likely to become important. At the same time, unexpected observations can capture attention because they violate current predictions. This creates a dynamic interaction in which prediction directs sensing and surprising sensory evidence causes predictions to be revised.

Predictive attention can improve efficiency because computational resources do not need to be distributed uniformly. If an autonomous robot predicts that a pedestrian may enter its path, additional perception resources can be allocated to that region. Conversely, stable and well-understood parts of the environment may require less frequent or less detailed processing.

Active perception extends this relationship further. When predictions remain uncertain, an agent can perform actions specifically to improve future estimation. Moving to a different viewpoint, activating another sensor, approaching an object, or slowing down may reveal information that distinguishes competing hypotheses. Prediction therefore helps determine not only what to expect but also what should be sensed next.

Internal models provide the mechanisms required for such forecasting. A model encodes regularities describing how states change through time and how actions influence those transitions. When the current state and a candidate action are provided, the model can estimate possible next states, creating a computational bridge between perception, prediction, planning, and action.

Forward models are a classic example. A forward model predicts the sensory or state consequences that should result from a particular action. When a motor command is issued, the cognitive system can estimate the expected change before feedback arrives. This supports rapid control and allows unexpected deviations to be detected when actual observations differ from predictions.

Predictive control relies heavily on this idea. Instead of reacting only to current error, a controller estimates how the system will evolve and selects actions according to predicted future states. This can improve stability and performance in systems where delay, momentum, or dynamic constraints make purely reactive correction insufficient.

Model predictive control provides a formal engineering example. The controller evaluates candidate action sequences over a limited future horizon, predicts their consequences using a system model, selects an appropriate action, and then repeats the process after new observations arrive. Continuous replanning reduces the impact of prediction errors because the model is repeatedly corrected by reality.

Human cognition uses similar closed-loop prediction even though the underlying biological computation differs. During movement, people continuously anticipate expected visual, tactile, and proprioceptive consequences. Differences between prediction and actual feedback allow rapid correction, making skilled action a repeated sequence of forecasting, observation, comparison, and adjustment.

Prediction error is therefore a central signal in cognition. When reality differs from expectation, the discrepancy indicates that the current state estimate, model, assumption, or action may be inaccurate. Prediction errors can trigger attention, learning, replanning, or corrective control depending on their size, reliability, context, and potential consequences.

Not every prediction error should lead to major learning. Sensors contain noise, rare events occur by chance, and measurements can be temporarily unreliable. Intelligent systems must determine whether an unexpected observation reflects random variation or a meaningful change in the underlying environment. Uncertainty estimation helps prevent unstable adaptation to insignificant errors.

Repeated systematic errors provide stronger evidence that a model should be updated. If an agent continually predicts that a surface provides strong traction but repeatedly observes wheel slip, the internal dynamics representation is likely incomplete. Continual comparison of predicted and observed outcomes therefore allows world models to improve through operational experience.

Predictive processing offers a broader cognitive perspective in which the system continuously generates expectations and compares them with incoming sensory evidence. Perception then involves both bottom-up sensory information and top-down predictions. The internal model proposes what is likely to be observed, while prediction errors identify where additional processing or model revision is required.

This perspective does not imply that perception should ignore sensory data in favor of expectations. Excessive reliance on prior beliefs can produce systematic errors when the environment changes. Reliable cognition requires an appropriate balance between predictions derived from previous experience and evidence supplied by current observations.

The weighting between expectation and evidence can depend on estimated precision. Reliable sensory information should strongly influence the current state, while noisy measurements may deserve less weight. Similarly, a highly reliable predictive model can stabilize interpretation when observations are temporarily incomplete, but its influence should decrease when operating conditions differ from learned experience.

Prediction and memory are also deeply connected. Episodic memory provides examples of what happened in similar previous situations, semantic memory provides generalized knowledge, and procedural memory provides learned expectations about action consequences. These forms of memory can constrain predictions and reduce the amount of inference required in familiar circumstances.

Experience-based prediction can be extremely efficient. An expert driver, technician, or operator may anticipate likely problems from subtle patterns that a novice does not recognize. Expertise therefore includes not only faster perception but better expectations about what events are likely to occur and which early signals indicate future outcomes.

However, learned expectations can also create bias. A system may predict familiar outcomes even when the current situation differs in important ways. Overreliance on previous patterns can cause rare but critical events to be overlooked. Robust prediction therefore requires novelty detection and mechanisms for reducing confidence when observations fall outside familiar distributions.

Distribution-shift detection is especially important for deployed AI. A prediction model trained in particular environments may encounter unfamiliar weather, terrain, objects, behavior patterns, or hardware conditions. Detecting such shifts allows the system to reduce prediction confidence, increase sensing, activate alternative models, or move into a conservative operating mode.

World models provide a general framework for learned prediction in artificial intelligence. They represent how relevant aspects of the world evolve and how agent actions influence that evolution. A world model can operate on raw sensory observations, structured objects, semantic representations, or compact latent states depending on the requirements of the task.

Pixel-level prediction attempts to generate future visual observations directly. This can preserve rich information but may require substantial computational resources and may waste capacity predicting appearance details irrelevant to action. In many Physical AI systems, more abstract predictive representations can provide better efficiency by focusing on geometry, objects, motion, and task-relevant state.

Latent prediction addresses this problem by forecasting changes within a learned internal representation. Instead of generating complete future images, the model predicts how compact features will evolve. This approach can support efficient planning if the latent state contains the variables needed to distinguish future outcomes relevant to behavior.

Object-centric prediction provides another useful representation. Individual objects can maintain identity, position, velocity, semantic category, attributes, and uncertainty. The prediction system estimates how each entity may change and interact with others. Such structure can support more interpretable reasoning and improve transfer across scenes containing familiar types of objects in new arrangements.

Relational prediction focuses on interactions among entities. A moving vehicle may influence a pedestrian, an object may be supported by a table, or one robot may block another\'s route. Graph-based world models can represent these relationships explicitly and predict how both object states and relationships change through actions and environmental events.

Physical dynamics are particularly important for embodied prediction. An autonomous system may need to estimate velocity, acceleration, friction, collision response, stability, load transfer, contact, or force. Pure semantic understanding cannot replace these physical variables when future safety depends on how objects and machines actually move.

Semantic prediction complements physical dynamics by estimating changes in higher-level meaning. A person may be approaching a doorway, a robot may be completing a delivery, or a vehicle may be preparing to turn. These events cannot always be described adequately through geometry alone. Combining semantic and physical prediction produces richer anticipation.

Intent prediction is necessary when other intelligent agents influence the environment. Humans and robots do not move only according to passive physics; their actions reflect goals and decisions. Estimating likely intentions can improve prediction of future trajectories, although such estimates should remain probabilistic because another agent\'s internal goals cannot be observed directly.

Social anticipation enables intelligent systems to prepare for cooperative or conflicting behavior. A service robot can anticipate that a person may reach for an object, while an autonomous vehicle can estimate whether another road user may yield or proceed. Such predictions support safer and more natural interaction when combined with conservative uncertainty handling.

Prediction in multi-agent environments becomes more difficult because the actions of one agent can influence the decisions of another. Future states are therefore interactive rather than independent. Multi-agent prediction models may need to represent possible reactions, negotiation, coordination, or competition among several agents simultaneously.

This creates recursive prediction problems. An agent may predict what another agent will do while the other agent is also reacting to the first agent\'s expected behavior. Practical systems usually simplify this complexity using limited horizons, learned interaction patterns, game-theoretic approximations, or conservative safety assumptions.

Counterfactual prediction allows an agent to evaluate futures associated with actions that have not yet been executed. The system can ask what would happen if it moved left instead of right, slowed down, waited, grasped a different location, or assigned a task to another robot. This capability is fundamental to deliberate planning.

Simulation provides a practical environment for counterfactual prediction. A model can generate many hypothetical trajectories faster or more safely than they could be explored physically. In robotics, simulated futures can be used to estimate collisions, task completion, energy use, navigation efficiency, manipulation success, and other action consequences.

The reliability of counterfactual reasoning depends on model accuracy. A simulation may produce plausible but incorrect futures when it encounters states outside its training experience. Planning systems should therefore track model confidence and avoid relying heavily on long simulated trajectories when uncertainty becomes large.

Model error tends to accumulate with prediction horizon. Small errors in position, dynamics, or interaction can produce larger deviations after several prediction steps. This motivates receding-horizon approaches in which the agent predicts a limited future, performs only part of the plan, obtains new observations, and then predicts again.

Receding-horizon prediction is particularly suitable for Physical AI because physical environments provide frequent feedback. Rather than relying on one long open-loop forecast, the robot repeatedly updates its world state and replans. This combines predictive intelligence with reactive robustness and reduces dependence on perfect long-term models.

Hierarchical prediction can further manage complexity. Low-level models predict fast physical dynamics, intermediate models predict object interactions and local task progression, and high-level models anticipate mission states or strategic outcomes. Different models can therefore operate at different temporal resolutions while exchanging relevant information.

Multi-timescale prediction reflects the structure of intelligent behavior. Millisecond or sub-second predictions may support stabilization, several-second predictions may support obstacle avoidance and manipulation, and minute-level predictions may support task scheduling. Longer strategic horizons may operate over much more abstract states than immediate physical control.

Prediction frequency should also vary according to environmental dynamics. Slowly changing regions do not need to be predicted at the same rate as fast-moving objects. Event-driven prediction can allocate computational resources when significant changes, uncertainty, or risk appear, improving efficiency on resource-constrained systems.

This is important for edge AI because onboard compute, memory, energy, bandwidth, and thermal capacity are limited. A robot cannot continuously run every predictive model at maximum fidelity. Lightweight prediction can operate routinely while computationally expensive models activate when situations become complex, novel, or safety critical.

Foundation models can contribute broad prior knowledge to predictive systems. Vision and multimodal models can identify objects and relationships, while language models can provide knowledge about typical events and task structures. Such priors can help interpret context before sufficient platform-specific experience has been collected.

However, foundation-model knowledge should be grounded in current observations. A language model may know that pedestrians commonly cross at a crosswalk, but the physical system must still detect the actual pedestrian, estimate position and motion, and assess local conditions. Generic expectations cannot substitute for real-time state estimation.

Perception foundation models can support prediction by producing semantic and geometric representations that persist across time. These representations can feed tracking and world-model components rather than being used only for frame-level recognition. Fine-tuning can adapt them to the specific sensors, environments, and object classes relevant to deployment.

Action foundation models can contribute predictions about likely action consequences or reusable behavior patterns. If trained across many interactions, they may encode priors about manipulation, locomotion, or navigation. These priors must still be conditioned on the current robot morphology, state, payload, environment, and safety constraints.

World models can connect perception and action foundation models through predicted state transitions. Perception establishes what exists, candidate actions specify possible interventions, and the world model estimates their consequences. A planner then compares these futures according to goals, risk, uncertainty, energy, time, and other constraints.

Reinforcement learning can use prediction to improve decision making. Model-free reinforcement learning learns behavior largely from direct experience, whereas model-based reinforcement learning uses a predictive model to evaluate possible future outcomes. The latter can improve data efficiency because many candidate trajectories can be examined without physical execution.

Imagined experience generated by world models can supplement real experience during learning. An agent can simulate candidate actions and use predicted outcomes to improve its policy. However, imagined learning should be constrained by model confidence because inaccurate simulated states can reinforce behavior that performs well only inside the learned model.

Self-supervised learning is well suited to predictive models because temporal data naturally provides learning targets. Given present observations, the system can predict future representations, object motion, sensor measurements, or action outcomes. The actual future later becomes the training signal, reducing dependence on manually labeled predictive datasets.

Robot fleets create particularly large opportunities for predictive learning. Each robot produces sequences of observations, actions, predictions, and outcomes. These trajectories can be aggregated to identify systematic errors, rare situations, and environmental patterns. Improved predictive models can then be validated and distributed back to the fleet.

Prediction is closely related to anomaly detection. If an observation differs strongly from the expected state, the event may represent a sensor fault, environmental change, unexpected agent behavior, or system failure. Prediction-based anomaly detection identifies unusual events according to their deviation from learned temporal expectations.

For maintenance and reliability, anticipation can extend beyond immediate navigation and control. A robot can monitor motor current, vibration, temperature, battery behavior, and other signals to predict component degradation. Predictive maintenance allows service to occur before a failure disrupts operation and provides another practical use of cognitive anticipation.

Task-level anticipation can similarly predict delays, resource shortages, or mission failure. A fleet management system may estimate that a robot will not complete an assignment before its battery reaches a minimum reserve or that congestion will delay multiple robots. Such predictions allow proactive task reassignment rather than reactive recovery.

Energy prediction is important for mobile robots because future actions depend on remaining operational capacity. An agent can estimate energy consumption for routes, payloads, terrain, compute demand, or manipulation tasks. Planning can then consider whether enough energy remains to complete the task and reach a charging location safely.

Safety prediction requires special treatment because rare events may carry severe consequences. Collision probability, stability risk, human proximity, braking distance, and failure trajectories may need explicit predictive models. Safety systems should evaluate worst-case or conservative possibilities rather than relying only on the most probable predicted future.

Reachability analysis provides another form of safety anticipation. Instead of predicting one likely trajectory, the system estimates a set of states that an object, vehicle, or robot could possibly reach within a future interval. Such sets can support conservative collision checking when exact behavior of other agents is uncertain.

Planning under uncertainty therefore combines predicted outcomes with risk management. The lowest expected cost action is not always appropriate if it has a small probability of catastrophic failure. Risk-sensitive planning can penalize dangerous tails of the predicted distribution and prefer actions with safer future state ranges.

Anticipation also changes communication. A cooperative robot may inform a human about an expected problem before intervention becomes urgent. Instead of reporting only current faults, it can communicate predicted delays, uncertain object states, likely path conflicts, or declining energy reserves, allowing the human to prepare or modify the task.

Human-AI collaboration benefits when predictions are interpretable at the level needed for decisions. A user may not need raw probability distributions but should understand which future event is expected, why it matters, how uncertain the estimate is, and what actions remain available. Prediction communication should therefore avoid both false precision and unnecessary complexity.

Trust in prediction should remain calibrated. Highly confident forecasts that repeatedly fail cause inappropriate actions, while excessively conservative predictions can make autonomous systems inefficient or unusable. Calibration measures whether stated confidence corresponds to actual predictive accuracy and is therefore essential for reliable deployment.

Prediction evaluation should consider more than average numerical error. Different applications require trajectory accuracy, event detection, probability calibration, horizon-dependent error, rare-event recall, safety performance, computational latency, and downstream planning effectiveness. A model useful for one purpose may be unsuitable for another even if overall prediction loss is similar.

Closed-loop evaluation is especially important for robotics. A small prediction error may have little effect if replanning corrects it quickly, while another seemingly small error may direct the robot into a dangerous state. Predictive models should therefore be evaluated by how they influence actual planning, control, safety, and task completion.

Robustness testing should intentionally include unusual and changing conditions. New object types, sensor degradation, sudden motion, difficult weather, altered friction, communication loss, or unexpected human behavior can reveal whether predictions remain reliable outside nominal operation. Such tests also help determine when fallback strategies are required.

Anticipatory systems should know when prediction is unnecessary. Excessive forecasting wastes computation and may introduce complexity into situations adequately handled by simple reactive control. Intelligent architecture should allocate prediction depth according to the value that future information provides for the current decision.

Reactive and predictive mechanisms are therefore complementary rather than competing approaches. Reactive control provides rapid responses to immediate observations, while predictive processing allows preparation for expected future conditions. Strong autonomous systems combine both, using anticipation where delay and consequences matter while preserving fast feedback for unmodeled events.

The relationship between prediction and action ultimately forms a closed loop. The agent predicts future states, chooses an action based on those predictions, executes the action, observes what actually happens, measures prediction error, and updates its internal state or model. Each cycle provides new evidence that improves subsequent anticipation.

For cognitive science, this loop explains how organisms operate successfully despite delayed, noisy, and incomplete sensory information. Prediction allows cognition to remain ahead of events rather than constantly lagging behind them. Anticipation converts expectations into prepared attention, decision, and action, enabling more efficient and adaptive interaction.

For artificial intelligence, prediction transforms models from passive recognizers into components of goal-directed agents. Memory provides temporal context, state estimation defines the present, world models estimate possible futures, planners evaluate alternatives, and feedback corrects predictions. These mechanisms together support increasingly deliberate and adaptive intelligence.

For Physical AI, prediction and anticipation are foundational because every physical action consumes time and changes the future environment. Robots must anticipate motion, interaction, task progress, energy, uncertainty, and safety while maintaining real-time feedback. Predictive capability therefore links perception, world modeling, planning, control, continual learning, and reliable autonomous behavior.

The long-term objective is not perfect forecasting, which is impossible in complex partially observable worlds, but useful anticipation under uncertainty. An intelligent agent should predict the futures that matter, represent multiple possibilities when necessary, understand how confidence changes with horizon, gather information when uncertain, and continuously correct its expectations through real-world feedback.

예측(Prediction)은 현재 관찰(Current Observations), 사전 지식(Prior Knowledge), 내부 표현(Internal Representations), 학습된 규칙성(Learned Regularities)을 기반으로 다음에 어떤 일이 발생할 가능성이 높은지를 추정하는 인지 과정(Cognitive Process)입니다. 예기(Anticipation)는 예상되는 미래 조건에 대비하여 인지와 행동을 준비함으로써 예측을 확장합니다. 이 두 기능을 통해 지능형 에이전트(Intelligent Agents)는 변화가 이미 발생한 이후에만 대응하는 대신 사건이 완전히 전개되기 전에 행동할 수 있습니다.

예측은 감각 세계(Sensory World)가 지속적으로 변화하고 정보가 항상 일정한 지연을 가지고 도착하기 때문에 기본적으로 중요합니다. 움직이는 객체는 현재 상태의 처리가 완전히 끝나기 전에 위치를 변경할 수 있으며, 어떤 행동은 그 효과가 나타나기까지 시간이 필요할 수 있습니다. 따라서 인지 시스템(Cognitive Systems)은 지각과 행동이 동적 환경(Dynamic Environments)에 맞추어 유지될 수 있도록 미래 상태(Future States)를 추정하는 능력에서 이점을 얻습니다.

예기(Anticipation)는 예측을 실제 준비 과정으로 전환합니다. 사람이 차량이 교차로에 진입할 것으로 예상한다면 주의(Attention)를 잠재적인 충돌 영역으로 이동시키고 운동 반응(Motor Responses)을 사전에 준비할 수 있습니다. 동일한 원리는 인공 에이전트에도 적용되며, 예측된 사건은 실제 사건이 발생하기 전에 센싱 우선순위, 계획, 자원 할당, 안전 행동을 변화시킬 수 있습니다.

예측은 현재 상황의 관련 측면을 요약하는 내부 표현(Internal Representations)에 의존합니다. 이러한 표현에는 객체 위치, 속도, 의미 범주(Semantic Categories), 목표, 환경 제약조건(Environmental Constraints), 불확실성(Uncertainty), 이전 행동, 개체(Entity) 사이의 관계 등이 포함될 수 있습니다. 일반적으로 더욱 풍부하고 정확한 인지 상태(Cognitive State)는 상황이 어떻게 변화할지를 추정하기 위한 더 강력한 기반을 제공합니다.

따라서 시간적 연속성(Temporal Continuity)은 필수적입니다. 많은 미래 상태는 시간에 걸쳐 나타나는 추세에 의존하기 때문에 예측은 고립된 관찰만으로 이루어질 수 없습니다. 예를 들어 객체의 이전 위치를 추적하면 단일 측정값만으로는 신뢰성 있게 추론하기 어려운 속도와 가속도 정보를 얻을 수 있습니다. 따라서 기억(Memory)과 상태 추정(State Estimation)은 예측적 인지(Predictive Cognition)에 직접적으로 기여합니다.

단기 예측(Short-Term Prediction)은 즉각적인 지각과 제어를 지원합니다. 움직이는 객체가 수초 또는 그보다 짧은 시간 후에 어디에 있을지를 추정하면 에이전트가 센서 및 제어 지연시간(Latency)을 보상할 수 있습니다. 인간은 손 뻗기, 물체 잡기, 걷기, 운전 과정에서 이러한 예기를 자연스럽게 수행하며, 자율 시스템(Autonomous Systems)은 추적, 충돌 회피, 궤적 제어를 위해 유사한 원리를 사용합니다.

중기 예측(Medium-Horizon Prediction)은 수초에서 수분 정도의 시간 범위에 걸친 계획을 지원합니다. 모바일 로봇(Mobile Robot)은 보행자, 차량, 출입문 또는 장애물에 접근하는 동안 이들이 어떻게 변화할지를 추정할 수 있습니다. 이러한 예측을 통해 플래너(Planner)는 현재의 기하학적 상태만을 최적화하는 대신 로봇이 미래 위치에 도달했을 때에도 실행 가능한 경로와 행동을 선택할 수 있습니다.

장기 예기(Long-Term Anticipation)는 더 긴 시간 규모에서 작동하며 점점 더 추상적인 표현을 사용합니다. 정확한 궤적을 예측하는 대신 지능 시스템은 미래 작업 상태(Task States), 자원 요구량, 환경 조건 또는 예상되는 의도(Intentions)를 추정할 수 있습니다. 따라서 장기 예측은 세밀한 물리 동역학(Physical Dynamics)에서 확률적, 의미론적, 전략적 기대(Strategic Expectations)로 이동하는 경우가 많습니다.

서로 다른 예측 시간 범위(Prediction Horizons)는 서로 다른 수준의 정확도를 요구합니다. 단기 물리 예측은 개입할 수 있는 미지의 사건이 상대적으로 적기 때문에 비교적 정확할 수 있습니다. 그러나 예측 범위가 길어질수록 작은 오류가 누적되고 관찰되지 않은 의사결정이나 환경 변화가 미래 궤적을 변경할 수 있기 때문에 일반적으로 불확실성이 증가합니다. 지능 시스템은 이러한 불확실성 증가를 명시적으로 표현해야 합니다.

따라서 예측은 하나의 결정론적 미래(Deterministic Future)만으로 취급되어서는 안 됩니다. 복잡한 환경에서는 일반적으로 여러 개의 가능한 미래가 존재합니다. 보행자는 계속 걸을 수도 있고, 속도를 줄이거나, 멈추거나, 방향을 바꿀 수도 있습니다. 여러 가능한 미래 궤적(Future Trajectories)을 유지하면 계획 시스템은 하나의 예측 결과에 과도하게 확신하는 대신 다양한 대안을 평가할 수 있습니다.

확률(Probability)은 이러한 대안을 표현하는 유용한 방법을 제공합니다. 하나의 미래가 반드시 발생한다고 예측하는 대신 인지 시스템은 여러 결과에 서로 다른 발생 가능성을 할당할 수 있습니다. 이후 의사결정은 각 가능성의 확률과 결과를 모두 고려할 수 있으며, 이를 통해 발생 가능성은 낮지만 위험도가 높은 사건도 행동 결정에 적절하게 반영할 수 있습니다.

예측과 불확실성(Uncertainty)은 밀접하게 연결되어 있습니다. 유용한 예측은 무엇이 예상되는지만이 아니라 그 예측을 얼마나 강하게 신뢰할 수 있는지도 전달해야 합니다. 신뢰도(Confidence)는 관찰 품질, 친숙성(Familiarity), 모델 신뢰성, 환경 변동성, 예측 시간 범위 등에 따라 달라질 수 있습니다. 불확실성을 숨기는 시스템은 지나치게 정확해 보이는 예측을 생성하여 안전하지 않은 의사결정을 유도할 수 있습니다.

예기(Anticipation)는 확률뿐 아니라 예상 결과(Expected Consequences)에도 의존합니다. 발생 가능성이 매우 높지만 무해한 사건은 거의 주의를 필요로 하지 않을 수 있지만, 가능성이 낮은 충돌은 즉각적인 준비를 요구할 수 있습니다. 따라서 지능적 예기(Intelligent Anticipation)는 어떤 예측 미래에 처리 우선순위를 부여할지를 결정할 때 발생 가능성, 결과의 심각성, 긴급성, 이용 가능한 대응 시간을 함께 고려합니다.

예측은 주의(Attention)와 강하게 연결됩니다. 기대(Expectations)는 앞으로 중요해질 가능성이 높은 위치, 객체 또는 신호로 주의를 유도할 수 있습니다. 동시에 예상하지 못한 관찰은 현재 예측을 위반하기 때문에 주의를 강하게 끌 수 있습니다. 따라서 예측이 센싱을 유도하고 놀라운 감각 증거가 다시 예측을 수정하는 동적인 상호작용이 형성됩니다.

예측적 주의(Predictive Attention)는 계산 자원을 균등하게 분배할 필요가 없기 때문에 효율성을 향상시킬 수 있습니다. 자율 로봇이 보행자가 자신의 경로로 진입할 가능성을 예측한다면 해당 영역에 추가적인 지각 자원을 할당할 수 있습니다. 반대로 안정적이고 충분히 이해된 환경 영역에는 더 낮은 빈도 또는 낮은 세밀도의 처리를 적용할 수 있습니다.

능동적 지각(Active Perception)은 이러한 관계를 더욱 확장합니다. 예측의 불확실성이 높은 상태로 유지될 경우 에이전트는 미래 추정을 개선하기 위한 행동을 직접 수행할 수 있습니다. 다른 시점(Viewpoint)으로 이동하거나, 추가 센서를 활성화하거나, 객체에 접근하거나, 속도를 낮추는 행동을 통해 경쟁하는 여러 가설을 구분할 수 있는 정보를 획득할 수 있습니다. 따라서 예측은 무엇을 기대해야 하는지뿐 아니라 다음에 무엇을 감지해야 하는지도 결정하는 데 도움을 줍니다.

내부 모델(Internal Models)은 이러한 미래 예측에 필요한 메커니즘을 제공합니다. 모델은 상태가 시간에 따라 어떻게 변화하고 행동이 이러한 상태 전이(State Transitions)에 어떤 영향을 미치는지를 설명하는 규칙성을 부호화합니다. 현재 상태와 후보 행동(Candidate Action)이 제공되면 모델은 가능한 다음 상태를 추정하여 지각, 예측, 계획, 행동 사이에 계산적 연결 고리를 형성할 수 있습니다.

순방향 모델(Forward Models)은 대표적인 예입니다. 순방향 모델은 특정 행동으로 인해 발생해야 하는 감각 또는 상태 결과를 예측합니다. 모터 명령(Motor Command)이 발생하면 인지 시스템은 실제 피드백이 도착하기 전에 예상되는 변화를 추정할 수 있습니다. 이를 통해 빠른 제어가 가능하며 실제 관찰이 예측과 다를 경우 예상하지 못한 편차를 탐지할 수 있습니다.

예측 제어(Predictive Control)는 이러한 개념에 크게 의존합니다. 현재의 오류에만 반응하는 대신 제어기는 시스템이 어떻게 변화할지를 추정하고 예측된 미래 상태에 따라 행동을 선택합니다. 지연, 관성(Momentum), 동적 제약조건(Dynamic Constraints) 때문에 단순한 반응형 수정만으로 충분하지 않은 시스템에서 안정성과 성능을 향상시킬 수 있습니다.

모델 예측 제어(Model Predictive Control)는 이를 공식적으로 구현한 공학적 사례입니다. 제어기는 제한된 미래 시간 범위에서 후보 행동 시퀀스를 평가하고, 시스템 모델을 이용하여 결과를 예측하고, 적절한 행동을 선택한 후 새로운 관찰이 들어오면 동일한 과정을 반복합니다. 현실의 관찰을 이용하여 모델을 반복적으로 수정하기 때문에 지속적인 재계획(Continuous Replanning)은 예측 오류의 영향을 줄여줍니다.

인간의 인지 역시 기반이 되는 생물학적 계산 방식은 다르지만 이와 유사한 폐루프 예측(Closed-Loop Prediction)을 사용합니다. 인간은 움직이는 동안 예상되는 시각, 촉각, 고유수용감각(Proprioceptive) 결과를 지속적으로 예측합니다. 예측과 실제 피드백의 차이를 이용해 빠르게 수정할 수 있으며, 숙련된 행동은 예측, 관찰, 비교, 조정이 반복되는 과정으로 이해할 수 있습니다.

따라서 예측 오류(Prediction Error)는 인지의 핵심 신호입니다. 현실이 기대와 다르면 현재 상태 추정, 모델, 가정 또는 행동 중 일부가 부정확할 수 있다는 것을 의미합니다. 예측 오류의 크기, 신뢰성, 문맥, 잠재적 결과에 따라 주의 전환, 학습, 재계획 또는 수정 제어(Corrective Control)가 활성화될 수 있습니다.

모든 예측 오류가 대규모 학습으로 이어져야 하는 것은 아닙니다. 센서에는 잡음(Noise)이 존재하고, 희귀 사건은 우연히 발생할 수 있으며, 측정값이 일시적으로 불안정할 수도 있습니다. 지능 시스템은 예상하지 못한 관찰이 무작위 변동을 나타내는지 아니면 기저 환경의 의미 있는 변화를 나타내는지를 판단해야 합니다. 불확실성 추정은 중요하지 않은 오류에 불안정하게 적응하는 것을 방지합니다.

반복적이고 체계적인 오류(Systematic Errors)는 모델을 갱신해야 한다는 더 강력한 증거를 제공합니다. 에이전트가 특정 표면에서 높은 접지력(Traction)을 지속적으로 예측하지만 실제로는 반복적인 휠 슬립(Wheel Slip)이 발생한다면 내부 동역학 표현이 불완전할 가능성이 높습니다. 따라서 예측 결과와 실제 결과를 지속적으로 비교하면 운영 경험을 통해 월드 모델(World Model)을 개선할 수 있습니다.

예측 처리(Predictive Processing)는 시스템이 지속적으로 기대를 생성하고 이를 들어오는 감각 증거와 비교한다는 보다 광범위한 인지 관점을 제공합니다. 이 관점에서 지각은 상향식 감각 정보(Bottom-Up Sensory Information)와 하향식 예측(Top-Down Predictions)을 모두 포함합니다. 내부 모델은 관찰될 가능성이 높은 것을 제안하고 예측 오류는 추가적인 처리 또는 모델 수정이 필요한 부분을 식별합니다.

이러한 관점이 지각이 기대를 우선하고 감각 데이터를 무시해야 한다는 것을 의미하지는 않습니다. 사전 신념(Prior Beliefs)에 지나치게 의존하면 환경이 변화했을 때 체계적인 오류가 발생할 수 있습니다. 신뢰할 수 있는 인지는 이전 경험에서 도출된 예측과 현재 관찰에서 제공되는 증거 사이에 적절한 균형을 유지해야 합니다.

기대와 증거 사이의 가중치는 추정된 정밀도(Estimated Precision)에 따라 달라질 수 있습니다. 신뢰할 수 있는 감각 정보는 현재 상태에 강한 영향을 미쳐야 하지만 잡음이 많은 측정값에는 더 낮은 가중치를 부여할 수 있습니다. 마찬가지로 신뢰성이 높은 예측 모델은 관찰이 일시적으로 불완전할 때 해석을 안정화할 수 있지만 운영 조건이 학습 경험과 달라지면 그 영향력을 줄여야 합니다.

예측과 기억(Memory) 역시 깊게 연결되어 있습니다. 일화 기억(Episodic Memory)은 이전의 유사한 상황에서 어떤 일이 발생했는지에 대한 사례를 제공하고, 의미 기억(Semantic Memory)은 일반화된 지식을 제공하며, 절차 기억(Procedural Memory)은 행동 결과에 대한 학습된 기대를 제공합니다. 이러한 기억 형태는 예측 범위를 제한하고 익숙한 상황에서 필요한 추론량을 줄일 수 있습니다.

경험 기반 예측(Experience-Based Prediction)은 매우 효율적일 수 있습니다. 숙련된 운전자, 기술자 또는 운영자는 초보자가 인식하지 못하는 미세한 패턴에서 발생 가능성이 높은 문제를 미리 예상할 수 있습니다. 따라서 전문성(Expertise)은 단순히 더 빠른 지각뿐 아니라 어떤 사건이 발생할 가능성이 높은지, 어떤 초기 신호가 미래 결과를 나타내는지에 대한 더 나은 기대를 포함합니다.

그러나 학습된 기대는 편향(Bias)을 발생시킬 수도 있습니다. 시스템은 현재 상황이 중요한 측면에서 다르더라도 익숙한 결과를 예측할 수 있습니다. 이전 패턴에 지나치게 의존하면 드물지만 중요한 사건을 놓칠 수 있습니다. 따라서 강건한 예측(Robust Prediction)은 새로움 탐지(Novelty Detection)와 관찰이 익숙한 분포를 벗어날 때 신뢰도를 낮추는 메커니즘을 필요로 합니다.

분포 변화 탐지(Distribution-Shift Detection)는 실제 배포된 AI에서 특히 중요합니다. 특정 환경에서 학습된 예측 모델이 익숙하지 않은 날씨, 지형, 객체, 행동 패턴 또는 하드웨어 조건을 만날 수 있습니다. 이러한 변화를 탐지하면 시스템은 예측 신뢰도를 낮추고, 센싱을 강화하고, 대안 모델을 활성화하거나, 보수적 운용 모드(Conservative Operating Mode)로 전환할 수 있습니다.

월드 모델(World Models)은 인공지능에서 학습 기반 예측을 위한 일반적인 프레임워크를 제공합니다. 월드 모델은 세계의 관련 요소가 어떻게 변화하고 에이전트의 행동이 이러한 변화에 어떤 영향을 미치는지를 표현합니다. 작업 요구사항에 따라 원시 감각 관찰, 구조화된 객체, 의미 표현 또는 압축된 잠재 상태(Latent States)를 기반으로 작동할 수 있습니다.

픽셀 수준 예측(Pixel-Level Prediction)은 미래의 시각 관찰을 직접 생성하려는 방식입니다. 풍부한 정보를 보존할 수 있지만 상당한 계산 자원을 요구하고 행동과 관련 없는 외형 세부사항을 예측하는 데 계산 능력을 낭비할 수 있습니다. 많은 피지컬 AI(Physical AI) 시스템에서는 기하학, 객체, 움직임, 작업 관련 상태에 집중하는 더 추상적인 예측 표현이 높은 효율성을 제공할 수 있습니다.

잠재 예측(Latent Prediction)은 학습된 내부 표현에서 변화를 예측함으로써 이러한 문제를 해결합니다. 완전한 미래 이미지를 생성하는 대신 모델은 압축된 특징이 어떻게 변화할지를 예측합니다. 잠재 상태가 행동과 관련된 미래 결과를 구분하는 데 필요한 변수를 포함한다면 이러한 접근 방식은 효율적인 계획을 지원할 수 있습니다.

객체 중심 예측(Object-Centric Prediction)은 또 다른 유용한 표현 방식입니다. 개별 객체는 정체성(Identity), 위치, 속도, 의미 범주, 속성, 불확실성을 유지할 수 있습니다. 예측 시스템은 각 개체가 어떻게 변화하고 다른 개체와 어떻게 상호작용할지를 추정합니다. 이러한 구조는 보다 해석 가능한 추론을 지원하고 익숙한 종류의 객체가 새로운 배치로 등장하는 장면 사이의 전이(Transfer)를 향상시킬 수 있습니다.

관계적 예측(Relational Prediction)은 개체 사이의 상호작용에 초점을 맞춥니다. 이동 차량은 보행자에게 영향을 미칠 수 있고, 객체는 테이블에 의해 지지될 수 있으며, 한 로봇이 다른 로봇의 경로를 차단할 수도 있습니다. 그래프 기반 월드 모델(Graph-Based World Models)은 이러한 관계를 명시적으로 표현하고 행동 및 환경 사건에 따라 객체 상태와 관계가 어떻게 변화하는지를 예측할 수 있습니다.

물리 동역학(Physical Dynamics)은 체화형 예측(Embodied Prediction)에서 특히 중요합니다. 자율 시스템은 속도, 가속도, 마찰(Friction), 충돌 반응, 안정성, 하중 이동(Load Transfer), 접촉(Contact), 힘을 추정해야 할 수 있습니다. 미래의 안전이 객체와 기계가 실제로 어떻게 움직이는지에 달려 있을 때 순수한 의미론적 이해만으로 이러한 물리 변수를 대체할 수 없습니다.

의미론적 예측(Semantic Prediction)은 상위 수준 의미의 변화를 추정함으로써 물리 동역학을 보완합니다. 사람이 출입구에 접근하거나, 로봇이 배송 작업을 완료하는 중이거나, 차량이 회전을 준비하는 상황은 기하학만으로 충분히 설명하기 어려울 수 있습니다. 의미론적 예측과 물리적 예측을 결합하면 더욱 풍부한 예기 능력을 형성할 수 있습니다.

의도 예측(Intent Prediction)은 다른 지능형 에이전트가 환경에 영향을 미치는 상황에서 필요합니다. 인간과 로봇은 수동적인 물리 법칙에 따라서만 움직이지 않으며 행동에는 목표와 의사결정이 반영됩니다. 예상되는 의도를 추정하면 미래 궤적 예측을 향상시킬 수 있지만 다른 에이전트의 내부 목표를 직접 관찰할 수 없기 때문에 이러한 추정은 확률적으로 유지되어야 합니다.

사회적 예기(Social Anticipation)는 지능 시스템이 협력적 또는 충돌 가능성이 있는 행동에 대비하도록 합니다. 서비스 로봇은 사람이 물체에 손을 뻗을 가능성을 예상할 수 있고, 자율주행차는 다른 도로 사용자가 양보할지 또는 계속 진행할지를 추정할 수 있습니다. 이러한 예측은 보수적인 불확실성 처리와 결합될 때 더욱 안전하고 자연스러운 상호작용을 지원합니다.

멀티에이전트 환경(Multi-Agent Environments)의 예측은 한 에이전트의 행동이 다른 에이전트의 의사결정에 영향을 줄 수 있기 때문에 더욱 어렵습니다. 따라서 미래 상태는 독립적인 것이 아니라 상호작용적(Interactive)입니다. 멀티에이전트 예측 모델은 여러 에이전트 사이의 가능한 반응, 협상, 조정 또는 경쟁을 동시에 표현해야 할 수 있습니다.

이는 재귀적 예측 문제(Recursive Prediction Problems)를 만듭니다. 한 에이전트는 다른 에이전트가 무엇을 할지를 예측하지만 상대 에이전트 역시 첫 번째 에이전트의 예상 행동에 반응할 수 있습니다. 실제 시스템에서는 일반적으로 제한된 예측 범위, 학습된 상호작용 패턴, 게임 이론적 근사(Game-Theoretic Approximations), 보수적인 안전 가정을 이용하여 이러한 복잡성을 단순화합니다.

반사실적 예측(Counterfactual Prediction)은 아직 실행하지 않은 행동과 관련된 미래를 평가할 수 있도록 합니다. 시스템은 오른쪽 대신 왼쪽으로 이동하면 어떻게 되는지, 속도를 낮추거나 기다리면 어떻게 되는지, 다른 위치를 파지하거나 다른 로봇에 작업을 할당하면 어떤 결과가 발생하는지를 추정할 수 있습니다. 이러한 능력은 숙고적 계획(Deliberate Planning)의 기본 요소입니다.

시뮬레이션(Simulation)은 반사실적 예측을 수행하기 위한 실용적인 환경을 제공합니다. 모델은 실제 물리 환경에서 탐색하는 것보다 빠르고 안전하게 많은 가상의 궤적을 생성할 수 있습니다. 로보틱스에서는 시뮬레이션된 미래를 이용하여 충돌, 작업 완료, 에너지 소비, 내비게이션 효율, 조작 성공률, 기타 행동 결과를 추정할 수 있습니다.

반사실적 추론(Counterfactual Reasoning)의 신뢰성은 모델 정확도에 의존합니다. 시뮬레이션은 학습 경험을 벗어난 상태를 만날 경우 그럴듯하지만 잘못된 미래를 생성할 수 있습니다. 따라서 계획 시스템은 모델 신뢰도(Model Confidence)를 추적하고 불확실성이 커지는 상황에서는 긴 시뮬레이션 궤적에 지나치게 의존하지 않아야 합니다.

모델 오류(Model Error)는 예측 범위가 길어질수록 누적되는 경향이 있습니다. 위치, 동역학, 상호작용의 작은 오류가 여러 예측 단계를 거치면서 큰 편차를 만들 수 있습니다. 따라서 에이전트가 제한된 미래만 예측하고 계획의 일부만 수행한 후 새로운 관찰을 획득하여 다시 예측하는 이동 시간 범위 접근법(Receding-Horizon Approach)이 필요합니다.

이동 시간 범위 예측(Receding-Horizon Prediction)은 물리적 환경에서 빈번한 피드백을 얻을 수 있기 때문에 피지컬 AI에 특히 적합합니다. 하나의 긴 개루프 예측(Open-Loop Forecast)에 의존하는 대신 로봇은 월드 상태를 반복적으로 갱신하고 재계획합니다. 이를 통해 예측 지능과 반응형 강건성(Reactive Robustness)을 결합하고 완벽한 장기 모델에 대한 의존성을 줄일 수 있습니다.

계층적 예측(Hierarchical Prediction)은 복잡성을 더욱 효과적으로 관리할 수 있습니다. 저수준 모델은 빠른 물리 동역학을 예측하고, 중간 수준 모델은 객체 상호작용과 지역 작업 진행을 예측하며, 상위 수준 모델은 임무 상태 또는 전략적 결과를 예상합니다. 서로 다른 모델이 서로 다른 시간 해상도에서 작동하면서 필요한 정보를 교환할 수 있습니다.

다중 시간 규모 예측(Multi-Timescale Prediction)은 지능적 행동의 구조를 반영합니다. 밀리초 또는 1초 미만의 예측은 안정화를 지원하고, 수초 수준의 예측은 장애물 회피와 조작을 지원하며, 수분 수준의 예측은 작업 스케줄링을 지원할 수 있습니다. 더 긴 전략적 시간 범위에서는 즉각적인 물리 제어보다 훨씬 추상적인 상태를 사용할 수 있습니다.

예측 빈도(Prediction Frequency) 역시 환경 동역학에 따라 달라져야 합니다. 느리게 변화하는 영역은 빠르게 움직이는 객체와 동일한 빈도로 예측할 필요가 없습니다. 이벤트 기반 예측(Event-Driven Prediction)은 중요한 변화, 불확실성 또는 위험이 발생할 때 계산 자원을 집중하여 자원이 제한된 시스템에서 효율성을 향상시킬 수 있습니다.

이는 온보드 계산 능력, 메모리, 에너지, 대역폭, 열 용량(Thermal Capacity)이 제한된 엣지 AI(Edge AI)에서 중요합니다. 로봇은 모든 예측 모델을 항상 최대 정밀도로 실행할 수 없습니다. 경량 예측 모델은 일상적으로 작동하고 계산 비용이 높은 모델은 상황이 복잡하거나, 새롭거나, 안전에 중요한 경우에 활성화될 수 있습니다.

파운데이션 모델(Foundation Models)은 예측 시스템에 광범위한 사전 지식(Prior Knowledge)을 제공할 수 있습니다. 비전 및 멀티모달 모델은 객체와 관계를 식별할 수 있으며, 언어 모델은 일반적인 사건과 작업 구조에 대한 지식을 제공할 수 있습니다. 이러한 사전 지식은 플랫폼별 경험이 충분히 수집되기 전에도 문맥을 해석하는 데 도움을 줄 수 있습니다.

그러나 파운데이션 모델의 지식은 현재 관찰에 그라운딩(Grounding)되어야 합니다. 언어 모델은 보행자가 일반적으로 횡단보도를 건넌다는 사실을 알고 있을 수 있지만 물리 시스템은 여전히 실제 보행자를 탐지하고 위치와 움직임을 추정하며 지역 조건을 평가해야 합니다. 일반적인 기대가 실시간 상태 추정(Real-Time State Estimation)을 대체할 수는 없습니다.

지각 파운데이션 모델(Perception Foundation Models)은 시간에 걸쳐 유지되는 의미론적 및 기하학적 표현을 생성함으로써 예측을 지원할 수 있습니다. 이러한 표현은 프레임 단위 인식에만 사용하는 대신 추적 및 월드 모델 구성요소의 입력으로 사용할 수 있습니다. 미세조정(Fine-Tuning)을 통해 실제 배포에 관련된 특정 센서, 환경, 객체 클래스에 맞게 적응시킬 수 있습니다.

행동 파운데이션 모델(Action Foundation Models)은 예상되는 행동 결과 또는 재사용 가능한 행동 패턴에 대한 예측에 기여할 수 있습니다. 다양한 상호작용을 통해 학습되었다면 조작, 이동(Locomotion), 내비게이션에 대한 사전지식을 부호화할 수 있습니다. 그러나 이러한 사전지식은 현재 로봇 형태(Morphology), 상태, 페이로드(Payload), 환경, 안전 제약조건에 맞추어 조건화되어야 합니다.

월드 모델은 예측된 상태 전이를 통해 지각 파운데이션 모델과 행동 파운데이션 모델을 연결할 수 있습니다. 지각은 무엇이 존재하는지를 설정하고, 후보 행동은 가능한 개입(Interventions)을 정의하며, 월드 모델은 그 결과를 추정합니다. 이후 플래너는 목표, 위험, 불확실성, 에너지, 시간 및 기타 제약조건을 기준으로 이러한 미래를 비교합니다.

강화학습(Reinforcement Learning)은 예측을 이용하여 의사결정을 향상시킬 수 있습니다. 모델 프리 강화학습(Model-Free Reinforcement Learning)은 주로 직접 경험을 통해 행동을 학습하는 반면, 모델 기반 강화학습(Model-Based Reinforcement Learning)은 예측 모델을 이용하여 가능한 미래 결과를 평가합니다. 후자는 실제 실행 없이 많은 후보 궤적을 평가할 수 있기 때문에 데이터 효율성을 높일 수 있습니다.

월드 모델이 생성한 상상 경험(Imagined Experience)은 학습 과정에서 실제 경험을 보완할 수 있습니다. 에이전트는 후보 행동을 시뮬레이션하고 예측된 결과를 사용하여 정책(Policy)을 개선할 수 있습니다. 그러나 부정확한 시뮬레이션 상태가 학습 모델 내부에서만 잘 작동하는 행동을 강화할 수 있으므로 상상 기반 학습은 모델 신뢰도에 따라 제한되어야 합니다.

자기지도학습(Self-Supervised Learning)은 시간 데이터 자체가 자연스럽게 학습 목표를 제공하기 때문에 예측 모델에 매우 적합합니다. 현재 관찰을 기반으로 시스템은 미래 표현, 객체 움직임, 센서 측정값 또는 행동 결과를 예측할 수 있습니다. 이후 실제 미래가 학습 신호가 되므로 수작업으로 라벨링된 예측 데이터셋에 대한 의존성을 줄일 수 있습니다.

로봇 플릿(Robot Fleets)은 예측 학습을 위한 특히 큰 기회를 제공합니다. 각 로봇은 관찰, 행동, 예측, 결과의 시퀀스를 생성합니다. 이러한 궤적을 통합하여 체계적인 오류, 희귀 상황, 환경 패턴을 식별할 수 있습니다. 개선된 예측 모델은 검증된 후 다시 플릿에 배포될 수 있습니다.

예측은 이상 탐지(Anomaly Detection)와 밀접하게 관련됩니다. 관찰이 예상 상태와 크게 다르면 센서 고장, 환경 변화, 예상하지 못한 에이전트 행동 또는 시스템 장애를 나타낼 수 있습니다. 예측 기반 이상 탐지(Prediction-Based Anomaly Detection)는 학습된 시간적 기대에서 얼마나 벗어났는지를 기준으로 비정상 사건을 식별합니다.

유지보수와 신뢰성 측면에서 예기(Anticipation)는 즉각적인 내비게이션 및 제어를 넘어 확장될 수 있습니다. 로봇은 모터 전류, 진동, 온도, 배터리 동작, 기타 신호를 모니터링하여 구성요소의 성능 저하를 예측할 수 있습니다. 예측 유지보수(Predictive Maintenance)는 장애가 운영을 중단시키기 전에 정비를 수행할 수 있도록 하며 인지적 예기의 또 다른 실용적인 활용 사례를 제공합니다.

작업 수준 예기(Task-Level Anticipation)는 지연, 자원 부족 또는 임무 실패를 예측할 수도 있습니다. 플릿 관리 시스템(Fleet Management System)은 로봇이 배터리 최소 예비량에 도달하기 전에 할당 작업을 완료하지 못할 것으로 예상하거나 혼잡으로 여러 로봇이 지연될 것을 예측할 수 있습니다. 이러한 예측을 통해 문제가 발생한 이후 복구하는 대신 선제적으로 작업을 재할당할 수 있습니다.

에너지 예측(Energy Prediction)은 미래 행동이 남아 있는 운용 능력에 의존하기 때문에 모바일 로봇에서 중요합니다. 에이전트는 경로, 페이로드, 지형, 계산 부하, 조작 작업에 따른 에너지 소비량을 추정할 수 있습니다. 이후 계획은 작업을 완료하고 안전하게 충전 위치에 도달하기 위한 충분한 에너지가 남아 있는지를 고려할 수 있습니다.

안전 예측(Safety Prediction)은 발생 가능성이 낮은 사건도 심각한 결과를 초래할 수 있기 때문에 특별한 처리가 필요합니다. 충돌 확률, 안정성 위험, 인간과의 거리, 제동 거리(Braking Distance), 고장 궤적(Failure Trajectories) 등에 명시적인 예측 모델이 필요할 수 있습니다. 안전 시스템은 가장 가능성이 높은 미래만 사용하는 대신 최악 조건 또는 보수적인 가능성을 평가해야 합니다.

도달 가능성 분석(Reachability Analysis)은 또 다른 형태의 안전 예기입니다. 하나의 가능성 높은 궤적을 예측하는 대신 시스템은 객체, 차량 또는 로봇이 미래의 일정 시간 안에 도달할 가능성이 있는 상태의 집합을 추정합니다. 이러한 집합은 다른 에이전트의 정확한 행동이 불확실할 때 보수적인 충돌 검사(Conservative Collision Checking)를 지원할 수 있습니다.

따라서 불확실성 하의 계획(Planning Under Uncertainty)은 예측 결과와 위험 관리를 결합합니다. 기대 비용(Expected Cost)이 가장 낮은 행동이라도 작은 확률로 치명적인 실패를 일으킬 수 있다면 적절하지 않을 수 있습니다. 위험 민감 계획(Risk-Sensitive Planning)은 예측 분포의 위험한 꼬리 부분을 페널티화하고 더 안전한 미래 상태 범위를 가진 행동을 선호할 수 있습니다.

예기는 의사소통 방식도 변화시킵니다. 협력 로봇(Cooperative Robot)은 개입이 긴급해지기 전에 예상되는 문제를 인간에게 알려줄 수 있습니다. 현재 장애만 보고하는 대신 예상 지연, 불확실한 객체 상태, 예상되는 경로 충돌 또는 감소하는 에너지 예비량을 전달함으로써 인간이 미리 준비하거나 작업을 수정할 수 있도록 합니다.

인간-AI 협업(Human-AI Collaboration)은 의사결정에 필요한 수준에서 예측이 해석 가능할 때 더욱 효과적입니다. 사용자가 원시 확률 분포 자체를 이해할 필요는 없지만 어떤 미래 사건이 예상되는지, 왜 중요한지, 추정이 얼마나 불확실한지, 어떤 행동 선택지가 남아 있는지를 이해할 필요가 있습니다. 따라서 예측 정보 전달은 거짓 정밀성(False Precision)과 불필요한 복잡성을 모두 피해야 합니다.

예측에 대한 신뢰(Trust)는 적절하게 보정되어야 합니다. 높은 신뢰도를 가진 예측이 반복적으로 실패하면 부적절한 행동을 유도할 수 있으며, 지나치게 보수적인 예측은 자율 시스템을 비효율적이거나 사용할 수 없게 만들 수 있습니다. 보정(Calibration)은 표현된 신뢰도가 실제 예측 정확도와 일치하는지를 측정하며 신뢰할 수 있는 배포를 위해 필수적입니다.

예측 평가는 평균적인 수치 오류만을 고려해서는 안 됩니다. 응용 분야에 따라 궤적 정확도, 사건 탐지, 확률 보정, 예측 범위별 오류, 희귀 사건 재현율(Rare-Event Recall), 안전 성능, 계산 지연시간, 이후 계획의 효과 등을 평가해야 합니다. 전체적인 예측 손실(Prediction Loss)이 비슷하더라도 한 목적에 유용한 모델이 다른 목적에는 적합하지 않을 수 있습니다.

폐루프 평가(Closed-Loop Evaluation)는 로보틱스에서 특히 중요합니다. 작은 예측 오류라도 재계획을 통해 빠르게 수정된다면 영향이 거의 없을 수 있지만, 다른 작은 오류는 로봇을 위험한 상태로 유도할 수 있습니다. 따라서 예측 모델은 실제 계획, 제어, 안전, 작업 완료에 어떤 영향을 주는지를 중심으로 평가해야 합니다.

강건성 시험(Robustness Testing)은 비정상적이고 변화하는 조건을 의도적으로 포함해야 합니다. 새로운 객체 유형, 센서 성능 저하, 갑작스러운 움직임, 악천후, 변화된 마찰, 통신 손실, 예상하지 못한 인간 행동 등을 통해 정상적인 운용 범위를 벗어난 상황에서도 예측이 신뢰할 수 있는지를 확인할 수 있습니다. 이러한 시험은 대체 전략이 필요한 조건을 결정하는 데에도 도움을 줍니다.

예기 시스템(Anticipatory Systems)은 예측이 필요하지 않은 상황도 판단할 수 있어야 합니다. 과도한 미래 예측은 계산 자원을 낭비하고 단순한 반응형 제어만으로 충분히 처리할 수 있는 상황에 불필요한 복잡성을 추가할 수 있습니다. 지능형 아키텍처는 미래 정보가 현재 의사결정에 제공하는 가치에 따라 예측 깊이(Prediction Depth)를 할당해야 합니다.

따라서 반응형 메커니즘(Reactive Mechanisms)과 예측 메커니즘(Predictive Mechanisms)은 경쟁 관계가 아니라 상호보완적인 접근법입니다. 반응형 제어는 즉각적인 관찰에 빠르게 대응하며, 예측 처리는 예상되는 미래 조건에 미리 대비할 수 있도록 합니다. 강력한 자율 시스템은 지연과 결과가 중요한 곳에서는 예기를 활용하면서 모델링되지 않은 사건에 대해서는 빠른 피드백을 유지함으로써 두 방식을 결합합니다.

예측과 행동의 관계는 궁극적으로 폐루프(Closed Loop)를 형성합니다. 에이전트는 미래 상태를 예측하고, 예측을 기반으로 행동을 선택하고, 행동을 실행하고, 실제로 어떤 일이 발생했는지를 관찰하고, 예측 오류를 측정하며, 내부 상태 또는 모델을 갱신합니다. 각각의 주기는 이후의 예기 능력을 향상시키는 새로운 증거를 제공합니다.

인지과학(Cognitive Science)의 관점에서 이러한 루프는 생물체가 지연되고, 잡음이 많으며, 불완전한 감각 정보에도 불구하고 어떻게 성공적으로 행동할 수 있는지를 설명합니다. 예측을 통해 인지는 사건을 항상 뒤따라가는 대신 사건보다 앞선 상태를 유지할 수 있습니다. 예기는 기대를 준비된 주의, 의사결정, 행동으로 전환하여 더욱 효율적이고 적응적인 상호작용을 가능하게 합니다.

인공지능(Artificial Intelligence)에서 예측은 모델을 수동적인 인식기(Passive Recognizers)에서 목표 지향적 에이전트(Goal-Directed Agents)의 구성요소로 변화시킵니다. 기억은 시간적 문맥을 제공하고, 상태 추정은 현재를 정의하며, 월드 모델은 가능한 미래를 추정하고, 플래너는 대안을 평가하며, 피드백은 예측을 수정합니다. 이러한 메커니즘이 결합되어 점점 더 숙고적이고 적응적인 지능을 지원합니다.

피지컬 AI(Physical AI)에서 예측과 예기는 모든 물리적 행동이 시간을 소비하고 미래 환경을 변화시키기 때문에 기본적인 능력입니다. 로봇은 실시간 피드백을 유지하면서 움직임, 상호작용, 작업 진행, 에너지, 불확실성, 안전을 예상해야 합니다. 따라서 예측 능력은 지각, 월드 모델링(World Modeling), 계획, 제어, 지속학습(Continual Learning), 신뢰할 수 있는 자율 행동(Reliable Autonomous Behavior)을 연결합니다.

장기적인 목표는 복잡하고 부분 관측 가능한 세계(Partially Observable Worlds)에서 불가능한 완벽한 미래 예측을 달성하는 것이 아니라 불확실성 아래에서 유용한 예기(Useful Anticipation)를 수행하는 것입니다. 지능형 에이전트는 중요한 미래를 예측하고, 필요한 경우 여러 가능성을 표현하며, 예측 시간 범위에 따라 신뢰도가 어떻게 변하는지를 이해하고, 불확실할 때 추가 정보를 수집하며, 실제 세계의 피드백을 통해 자신의 기대를 지속적으로 수정할 수 있어야 합니다.

##  

## 01.11 Perception Action Loop [w/Code]

![](images/image12.png){width="7.268055555555556in" height="7.268055555555556in"}

The perception-action loop describes the continuous process through which an intelligent agent senses its environment, constructs an internal understanding of the current situation, selects an appropriate action, executes that action, and observes the resulting changes. Perception and action are therefore not independent functions but mutually dependent components of an ongoing closed-loop interaction with the world.

Traditional descriptions of intelligent systems sometimes present perception as a one-way pipeline in which sensory information is processed first and action is produced afterward. Real cognition is more dynamic. Every action changes either the environment, the agent, or the relationship between them, creating new sensory information that immediately becomes the input for the next cycle of perception and decision making.

The loop begins with sensing. Biological organisms use vision, hearing, touch, proprioception, and other sensory systems, while robots may use cameras, LiDAR, radar, ultrasonic sensors, microphones, IMUs, GNSS, force sensors, encoders, and internal telemetry. These sensors provide incomplete and noisy observations rather than a perfect description of the external world.

Raw sensor measurements must therefore be transformed into representations that are useful for behavior. Perception identifies features, objects, surfaces, motion, spatial relationships, events, and environmental conditions. For an embodied agent, perception also includes estimating its own position, orientation, velocity, configuration, physical condition, and relationship to surrounding entities.

Perception is task dependent. The same sensory observation can have different meanings according to the current goal. A chair may be represented as an obstacle during navigation, a target object during manipulation, a landmark during localization, or an available place to sit for a human. Perception therefore organizes sensory information according to behavioral relevance rather than simply reconstructing every physical detail.

Internal state connects perception with action. The system combines current observations with memory, previous state estimates, goals, uncertainty, and knowledge about the environment. This cognitive state provides a more stable representation than individual sensor measurements and allows the agent to continue reasoning when objects are temporarily occluded or measurements become unreliable.

State estimation is particularly important because sensory observations rarely reveal everything required for action. A mobile robot may not directly observe its exact global position, the intention of a nearby pedestrian, or the friction of the ground. It must estimate these hidden variables using current measurements, previous observations, models, and accumulated experience.

Uncertainty should remain part of this state rather than being discarded during perception. Object classifications may be ambiguous, localization may have limited accuracy, and sensor measurements may disagree. Representing confidence and alternative hypotheses allows the action system to choose cautious behavior when the perceptual state is uncertain.

Attention determines which parts of the sensory environment receive additional processing. Because perception and computation are limited, the agent cannot analyze every signal with equal detail. Goals, novelty, uncertainty, predicted risk, and task relevance can guide attention toward the information most likely to influence upcoming decisions.

Action can also guide perception. A robot may rotate its camera toward an uncertain object, move around an obstacle to obtain another viewpoint, approach a marker to improve localization, or slow down to collect more reliable sensor data. Such active perception demonstrates that sensing is not merely passive reception but can be deliberately shaped by behavior.

This interaction creates a perception-action cycle in which perception determines what actions appear possible while action determines what can be perceived next. The agent continuously changes its sensory conditions through movement and interaction. Intelligent behavior therefore emerges from repeated coupling between sensing, interpretation, decision, movement, and new observation.

Affordances provide an important bridge between perception and action. An affordance represents what actions the environment allows relative to the agent\'s capabilities. A doorway affords passage if the robot fits through it, a handle may afford grasping if it is reachable, and a surface may afford traversal if its geometry and friction are compatible with the robot.

Affordances are relational rather than purely properties of objects. A step that is traversable for a legged robot may be an obstacle for a low-clearance wheeled platform. An object that one manipulator can lift may exceed another robot\'s payload. Perception-action systems must therefore interpret the environment relative to body morphology, capability, and current operating state.

Body representation is consequently a fundamental part of the loop. An embodied system must know its dimensions, joint configuration, velocity, actuator limits, payload, energy state, sensor status, reachable workspace, and other physical constraints. Without self-state information, environmental perception cannot reliably determine which actions are feasible.

Goals further shape the relationship between perception and action. The system does not simply detect everything and then decide what to do. Current objectives influence which objects are important, which relationships require attention, and which sensory details can be ignored. Goal-directed perception reduces unnecessary processing and connects sensory understanding directly with purposeful behavior.

Memory provides temporal continuity across successive perception-action cycles. Working memory can maintain recent observations, temporary goals, unresolved uncertainties, and partial plans, while long-term memory provides previous experiences, semantic knowledge, and learned skills. Current perception can therefore be interpreted using information acquired before the present moment.

The previous action is also important for interpreting the next observation. If a robot commanded a forward movement, the subsequent change in camera or LiDAR measurements should partly reflect that motion. Knowledge of executed actions helps distinguish changes caused by the agent itself from changes caused independently by the environment.

This principle is related to forward models. A forward model predicts how the agent and environment should change when a particular action is executed. The expected sensory or state consequence can be generated before actual feedback arrives, allowing the system to anticipate the result of its own behavior.

When actual observations match predicted consequences, the system gains evidence that its state estimate and dynamics model are reasonable. When observations differ substantially from predictions, the resulting prediction error indicates that something unexpected occurred. The discrepancy may arise from model error, environmental change, sensor problems, action failure, or incorrect state estimation.

Prediction error therefore closes an important learning loop. Unexpected outcomes can trigger additional attention, state correction, replanning, or model adaptation. Instead of treating errors only as failures, an intelligent system can use them as information about where its understanding of the world or its own capabilities needs improvement.

Feedback control represents the fastest form of the perception-action loop. Sensors measure the current state, the controller compares it with a desired state, and actuators generate corrective actions. New measurements reveal the effect of those actions, allowing the controller to repeatedly reduce error. This process may operate hundreds or thousands of times per second.

Higher-level cognitive loops operate at slower timescales. Object perception, navigation planning, manipulation planning, task reasoning, and mission management may update over milliseconds, seconds, or longer intervals. Intelligent systems therefore contain multiple nested perception-action loops operating simultaneously at different temporal and functional levels.

At the lowest level, motor control maintains stability, force, velocity, or position. At an intermediate level, motion planning controls trajectories and interactions with nearby objects. At higher levels, task planning determines what should be accomplished next. Each layer receives feedback and modifies behavior according to its own representation and time horizon.

These loops should not be understood as completely separate. Higher-level goals constrain lower-level actions, while lower-level feedback can force higher-level plans to change. A mission planner may request movement to a destination, but local perception may detect an obstacle that requires trajectory modification or even a complete reconsideration of the mission plan.

Reactive behavior is one important component of this architecture. Reactive control maps current observations to immediate actions with minimal internal prediction. Such mechanisms are useful when fast responses are required, such as emergency stopping, collision avoidance, balance correction, or maintaining safe distance from a moving obstacle.

Purely reactive systems, however, may struggle when actions have delayed consequences or when temporary decisions affect future possibilities. A robot that only reacts to immediate obstacles may enter a dead end or choose a route that later becomes impossible. Prediction and planning extend the perception-action loop beyond the current moment.

Predictive behavior uses an internal model to estimate future states before an action is executed. The agent can compare several candidate actions according to their predicted consequences. This allows behavior to consider future collision risk, energy consumption, task progress, stability, interaction outcomes, or other criteria that cannot be determined from the current observation alone.

Model predictive control provides a clear example of predictive perception-action coupling. The system observes its current state, predicts several possible future trajectories, selects an action, executes only part of the planned sequence, observes the new state, and plans again. Repeated feedback prevents the controller from depending on a perfectly accurate long-term prediction.

This receding-horizon principle is particularly suitable for physical systems because real environments continually provide new evidence. Instead of committing to a long open-loop plan, an autonomous robot can repeatedly revise its behavior as new observations become available. Prediction provides foresight while feedback provides robustness to unexpected changes.

World models extend this principle by learning how relevant aspects of the environment evolve. A world model can predict how objects move, how physical interactions unfold, how tasks progress, and how actions change future states. It therefore provides an internal simulation mechanism connecting perception, cognition, planning, and action.

The world model receives a representation of the current state rather than necessarily operating directly on raw sensor data. This representation may contain geometry, objects, semantic relationships, motion, uncertainty, robot state, and task context. Candidate actions can then be applied to this state to generate possible future developments.

Latent world models perform prediction in compressed learned representations. Instead of generating complete future camera images or LiDAR scans, they predict changes in features relevant to behavior. This can substantially reduce computational requirements, although the latent state must preserve information required for safe planning and control.

Object-centric world models organize prediction around persistent entities. Each object can maintain identity, position, velocity, semantic category, physical properties, and uncertainty. Predicting object-level transitions can provide an interpretable connection between perception and planning, particularly when interactions among multiple entities are important.

Action selection converts perceived and predicted possibilities into behavior. The system may evaluate candidate actions according to expected task success, safety, time, energy, comfort, uncertainty, or other objectives. The selected action represents the system\'s current judgment about how the world should be changed to move toward the desired state.

Decision making under uncertainty is necessary because perception and prediction are never perfect. A planner should consider both expected outcomes and confidence in those outcomes. An action with excellent predicted performance may be inappropriate if the underlying perception is unreliable or if a low-probability failure would have severe consequences.

Risk-sensitive behavior therefore becomes part of the perception-action loop. When uncertainty or potential consequences increase, the system can reduce speed, increase safety distance, gather additional information, request human assistance, or choose a more conservative action. Behavior itself becomes a mechanism for managing uncertainty.

Information gathering can even become an explicit action objective. An agent may temporarily choose an action that does not directly advance the task but improves knowledge needed for later decisions. Moving to inspect an occluded region or testing contact with a surface can reduce uncertainty and enable safer subsequent behavior.

This creates a distinction between actions that change the world and actions that primarily improve knowledge about the world, although many actions accomplish both. Active sensing, exploration, and experimentation are therefore natural extensions of the perception-action loop rather than separate cognitive processes.

Learning modifies the loop across longer timescales. Every interaction produces sequences of observations, internal states, actions, and outcomes. These experiences can be used to improve perception models, state estimators, world models, planners, control policies, and representations of the agent\'s own capabilities.

Reinforcement learning directly connects action and consequence. The agent performs actions, receives resulting states and rewards, and gradually learns which behaviors produce desirable outcomes. This learning process is inherently closed loop because the policy changes the distribution of future observations from which additional learning occurs.

Model-based reinforcement learning adds explicit prediction. Instead of learning only which action tends to produce reward, the system learns a model of state transitions and can simulate candidate futures. This can improve data efficiency because many possible actions can be evaluated internally without physically executing each one.

Self-supervised learning can improve perception and world models using the natural temporal structure of interaction data. Current observations can be used to predict future features, object motion, masked information, or action consequences. The future observations produced by the perception-action loop automatically provide training targets without requiring complete manual labeling.

Weakly supervised learning can complement this process when partial, noisy, coarse, or indirectly generated labels are available. Operational logs, task outcomes, human corrections, robot events, map information, or existing detectors can provide imperfect supervision. Combining such signals with self-supervised temporal learning can reduce the cost of creating large robotic datasets.

Imitation learning introduces human demonstrations into the loop. A robot observes how a human or expert system maps perceived situations to actions and learns to reproduce similar behavior. Demonstrations can provide strong initial policies, particularly for complex tasks where random exploration would be inefficient or unsafe.

However, imitation alone may fail when the robot encounters states that were rarely present in demonstrations. Once its action differs slightly from the demonstrated trajectory, subsequent observations can move outside the training distribution. Closed-loop evaluation and corrective demonstrations are therefore important for robust imitation learning.

Continual learning extends adaptation throughout the operational lifetime of the system. New environments, objects, tasks, hardware configurations, and failure cases generate experiences that can improve future behavior. The perception-action loop becomes not only a mechanism for immediate control but also the primary source of data for long-term intelligence development.

Experience should be stored selectively. Routine successful behavior may require little retention, while novel events, large prediction errors, human interventions, safety incidents, rare objects, and unusual environmental conditions may be especially valuable. Event-driven memory can preserve informative experiences without storing every raw sensor stream indefinitely.

Episodic memory can retain specific interaction sequences, including what the agent perceived, what it believed, what action it selected, and what actually occurred. These episodes can later support debugging, learning, reasoning, and retrieval of similar previous situations when the agent encounters new problems.

Semantic memory can extract generalized knowledge from many episodes. Repeated interactions may teach the system that certain surfaces are slippery, particular locations become congested, or specific object types require special handling. Such knowledge influences future perception and action without requiring the original experiences to be replayed every time.

Procedural memory stores learned skills and action patterns. Navigation maneuvers, grasping strategies, docking procedures, recovery behaviors, and manipulation routines can become reusable capabilities. Perception identifies when a skill is appropriate, while feedback continuously adapts its execution to the current environment.

Foundation models can enrich multiple stages of the perception-action loop. Perception foundation models provide reusable semantic representations, language models contribute task knowledge and instruction understanding, and action foundation models provide transferable behavior priors. These components can reduce the amount of platform-specific learning required from the beginning.

Perception foundation models are particularly useful for converting high-dimensional sensor data into meaningful representations. Pretrained visual or multimodal encoders can identify objects, scenes, relationships, and semantic features. Task-specific heads or fine-tuning can then adapt these representations to the robot\'s sensors and operating environment.

Language foundation models can translate human instructions into goals, constraints, task structures, or candidate plans. However, language-generated interpretations must remain grounded in the current physical state. A language model may propose what should happen, but perception and world-state estimation must determine what is actually possible and safe.

Action foundation models can provide reusable policies or motion representations learned from large collections of robot interactions. Their output should be conditioned on current perception, robot morphology, capability, and task context. Closed-loop feedback remains essential because an action prior learned elsewhere cannot perfectly predict the current physical environment.

The combination of perception, world models, and action models creates a powerful architecture for Physical AI. Perception estimates the current world and self-state, the world model predicts possible consequences, and the action model generates feasible behavior. Planning selects among these possibilities while continuous feedback corrects errors during execution.

Multi-modal perception strengthens this architecture because different sensors provide complementary information. Cameras provide appearance and semantics, LiDAR provides geometry, radar contributes robust motion measurements, IMUs provide inertial state, GNSS supplies global positioning, and proprioceptive sensors describe the robot\'s physical condition.

Sensor fusion integrates these observations into a coherent state. Accurate synchronization is essential because measurements captured at different times may describe different physical configurations. Motion compensation, calibration, timestamp alignment, and uncertainty modeling therefore directly affect the quality of the subsequent actions.

Poor perception can produce poor action even when the planner itself is mathematically correct. A perfectly optimized trajectory based on an incorrect obstacle location is still dangerous. Reliability of the perception-action loop therefore depends on maintaining accurate, timely, and uncertainty-aware state estimates.

Likewise, poor action execution can corrupt perception. Wheel slip, actuator error, mechanical deformation, vibration, or unexpected contact can cause the actual robot state to differ from the commanded state. Proprioceptive feedback and state estimation must detect these differences so that the internal representation remains aligned with physical reality.

Calibration is therefore not a one-time concern. Sensor extrinsics, actuator response, wheel parameters, payload distribution, and other system characteristics can change during operation. Monitoring prediction errors and cross-sensor consistency can reveal when calibration has degraded enough to affect perception-action performance.

Safety requires dedicated loops operating alongside task behavior. Emergency stopping, collision monitoring, stability checks, joint limits, speed restrictions, geofencing, and other safety mechanisms should not depend entirely on high-level learned reasoning. Independent feedback pathways can provide deterministic protection when learned components behave unexpectedly.

A safety supervisor can evaluate proposed actions before execution and monitor actual behavior afterward. If perception confidence decreases, communication fails, localization becomes unreliable, or predicted risk exceeds an acceptable threshold, the supervisor can restrict actions or transition the robot to a safer operating state.

Human interaction adds another feedback channel. A human can provide instructions, corrections, demonstrations, approvals, or emergency intervention. The robot\'s actions also provide information to the human, who observes its behavior and updates expectations. Human-robot interaction therefore forms a coupled perception-action loop involving multiple intelligent participants.

Intent communication can make this loop safer and more understandable. A robot can signal its planned direction, expected action, uncertainty, or need for assistance before moving. Humans can then anticipate robot behavior rather than reacting only after motion begins, reducing ambiguity in shared environments.

Multi-agent robotic systems contain interacting perception-action loops. Each robot perceives the environment and other agents, selects actions, and changes the state observed by everyone else. Coordination therefore requires reasoning not only about static obstacles but about the likely behavior and goals of other autonomous agents.

Shared information can extend perception beyond the range of individual robots. Fleet members may exchange detected obstacles, maps, task progress, localization information, or environmental changes. A shared world representation can improve coordination while local onboard perception continues to provide the low-latency information required for immediate safety.

Fleet-level planning creates a slower perception-action loop above individual robots. The fleet system observes robot states, task demand, congestion, energy levels, and mission progress, then reallocates tasks or modifies routes. The resulting robot behavior changes the fleet state, producing new information for the next coordination cycle.

Edge computing is particularly important for the fastest parts of these loops. Immediate perception, state estimation, safety monitoring, motion planning, and control should remain close to the physical robot because network latency or communication loss can make remote dependence unsafe.

On-premise computing can support slower and broader cognitive functions. Large world models, fleet optimization, long-term memory, dataset management, model training, global map maintenance, and complex reasoning can operate using shared infrastructure. The architecture can therefore distribute cognition according to latency, computational demand, and operational scope.

Communication between edge and on-premise systems should use meaningful state representations when possible rather than continuously transmitting every raw sensor stream. Objects, trajectories, events, uncertainties, task states, and selected sensor segments can provide efficient summaries while raw data can be retained when required for learning or forensic analysis.

Autonomy should degrade gracefully when communication is lost. A robot that depends on remote intelligence for every decision may become unsafe or unusable during network interruption. Essential perception-action functions should remain onboard, while external computation enhances capability without becoming mandatory for immediate safe operation.

The perception-action loop is also closely related to embodiment. Intelligence in a physical agent is constrained and shaped by the body through which it acts. Sensor placement determines what can be observed, actuator configuration determines what can be changed, and mechanical design influences which control and perception problems must be solved computationally.

Better mechanical design can simplify cognition. Stable locomotion, predictable steering, appropriate sensor placement, sufficient traction, and accurate actuators reduce uncertainty and control difficulty. Physical AI should therefore treat mechanical, electrical, sensing, computational, and cognitive architecture as parts of one integrated system.

Conversely, intelligent control can compensate for some physical limitations. Perception can identify difficult terrain, prediction can estimate slip or instability, and planning can choose safer trajectories. The boundary between mechanical capability and computational intelligence is therefore flexible, with each influencing the requirements placed on the other.

The loop also provides a useful framework for understanding cognitive load in artificial systems. Computational resources are finite, so not every perception, prediction, and planning process can operate at maximum complexity simultaneously. Attention and task priority determine where processing resources should be allocated.

Adaptive computation can modify the depth of reasoning according to the situation. Routine navigation in a stable corridor may require lightweight processing, while a crowded intersection or complex manipulation task may activate richer perception, longer prediction horizons, and more detailed planning. Computational effort becomes part of the control strategy.

Event-driven architectures can further improve efficiency. Instead of recomputing every representation continuously, significant changes such as new obstacles, prediction errors, task transitions, localization degradation, or safety warnings can trigger additional processing. This allows the cognitive system to concentrate resources where new information is most valuable.

The perception-action loop therefore includes both external and internal feedback. External feedback describes how the environment changed after an action, while internal feedback describes changes in confidence, computational load, memory, prediction quality, and model reliability. Both influence what the agent should do next.

Metacognition can supervise these internal conditions. A system may recognize that its perception is uncertain, its world model is operating outside familiar conditions, or its planner cannot find a safe solution. Instead of blindly continuing, it can gather information, simplify the task, invoke another model, request assistance, or stop.

Such behavior is especially important in open-world environments where not every situation can be anticipated during development. Robust autonomy does not require the system to know everything. It requires the system to recognize when its current knowledge is insufficient and to choose actions that preserve safety while reducing uncertainty.

Evaluation of perception-action systems should therefore use closed-loop testing rather than evaluating components only in isolation. High object-detection accuracy does not guarantee good navigation, and low trajectory prediction error does not automatically guarantee safe control. The important measure is how component performance affects actual behavior.

Simulation provides a scalable environment for closed-loop evaluation. Robots can interact with diverse scenarios, experience failures, and test alternative actions without physical risk. Simulation is particularly useful for rare events, although differences between simulation and reality must be considered when transferring learned behavior.

Real-world testing remains essential because physical interaction exposes effects that are difficult to model completely. Sensor noise, mechanical wear, lighting changes, friction, vibration, human unpredictability, communication problems, and unexpected environmental structure reveal weaknesses that may remain hidden in simulation.

Digital twins can connect simulation with operational systems by maintaining virtual representations of robots and environments. Real sensor data can update the digital state, while simulation can evaluate possible actions or maintenance conditions. This creates another feedback pathway between physical operation and predictive computation.

Data collected from real perception-action cycles can continuously improve the digital model. Conversely, improved simulation and learned models can generate better policies for deployment. The physical system and its computational representation can therefore co-evolve through repeated observation, modeling, testing, and action.

For cognitive science, the perception-action loop emphasizes that cognition is not simply internal information processing separated from behavior. Perception is shaped by possible action, action changes perception, and cognition develops through repeated interaction between organism and environment. Intelligence is therefore deeply connected with embodiment and feedback.

For artificial intelligence, the same principle shifts emphasis from static input-output prediction toward interactive agents. A model operating on a fixed dataset does not experience the consequences of its predictions, whereas an autonomous agent changes the future data it will receive through its own actions. This makes closed-loop learning fundamentally different from passive inference.

For robotics and Physical AI, the perception-action loop provides the core architecture connecting sensors, internal representations, world models, planning, control, memory, and learning. Every autonomous capability ultimately participates in this cycle by helping the robot understand its current situation, determine what to do, execute behavior, and interpret what happens next.

Advanced systems will increasingly combine several loops rather than rely on a single monolithic model. Fast deterministic safety and control loops can coexist with learned perception, predictive world models, foundation models, deliberative planning, fleet intelligence, and continual learning. Their coordination determines the overall quality of autonomous behavior.

The objective is therefore not merely to create better perception or more sophisticated action policies independently. The goal is to create a coherent system in which perception provides action-relevant state, action actively improves perception when necessary, prediction anticipates consequences, feedback corrects errors, and learning continuously improves the entire interaction cycle.

A mature perception-action architecture ultimately behaves as a continuously adapting closed-loop intelligence system. It senses the world and itself, constructs a cognitive state, predicts possible futures, selects goal-directed actions, monitors physical outcomes, detects discrepancies, updates knowledge, and immediately begins the cycle again. Through this repeated coupling of perception and action, an autonomous agent can progressively achieve more robust, adaptive, and reliable behavior in the real world.

지각-행동 루프(Perception-Action Loop)는 지능형 에이전트(Intelligent Agent)가 환경을 감지하고, 현재 상황에 대한 내부적 이해를 구성하고, 적절한 행동을 선택하고, 그 행동을 실행하고, 그 결과로 발생한 변화를 다시 관찰하는 지속적인 과정을 설명합니다. 따라서 지각(Perception)과 행동(Action)은 서로 독립적인 기능이 아니라 세계와 지속적으로 상호작용하는 폐루프(Closed Loop)의 상호의존적인 구성요소입니다.

지능형 시스템에 대한 전통적인 설명에서는 감각 정보가 먼저 처리되고 이후 행동이 생성되는 일방향 파이프라인(One-Way Pipeline)으로 지각을 설명하는 경우가 있습니다. 그러나 실제 인지는 훨씬 더 동적입니다. 모든 행동은 환경, 에이전트 자신, 또는 둘 사이의 관계를 변화시키며 새로운 감각 정보를 생성하고, 이 정보는 즉시 다음 지각 및 의사결정 주기의 입력이 됩니다.

루프는 센싱(Sensing)에서 시작됩니다. 생물학적 유기체는 시각, 청각, 촉각, 고유수용감각(Proprioception), 기타 감각 시스템을 사용하며, 로봇은 카메라, 라이다(LiDAR), 레이더(Radar), 초음파 센서(Ultrasonic Sensors), 마이크, 관성 측정 장치(IMU), 위성항법시스템(GNSS), 힘 센서(Force Sensors), 엔코더(Encoders), 내부 텔레메트리(Internal Telemetry)를 사용할 수 있습니다. 이러한 센서들은 외부 세계의 완벽한 설명이 아니라 불완전하고 잡음이 포함된 관찰을 제공합니다.

따라서 원시 센서 측정값(Raw Sensor Measurements)은 행동에 유용한 표현으로 변환되어야 합니다. 지각은 특징, 객체, 표면, 움직임, 공간적 관계, 사건, 환경 조건을 식별합니다. 체화 에이전트(Embodied Agent)의 경우 지각에는 자신의 위치, 방향, 속도, 구성(Configuration), 물리적 상태, 주변 개체와의 관계를 추정하는 과정도 포함됩니다.

지각은 작업 의존적(Task Dependent)입니다. 동일한 감각 관찰이라도 현재 목표에 따라 서로 다른 의미를 가질 수 있습니다. 의자는 내비게이션 중에는 장애물로, 조작 작업에서는 목표 객체로, 위치 추정에서는 랜드마크(Landmark)로, 인간에게는 앉을 수 있는 장소로 표현될 수 있습니다. 따라서 지각은 모든 물리적 세부사항을 단순히 재구성하기보다 행동 관련성(Behavioral Relevance)에 따라 감각 정보를 조직합니다.

내부 상태(Internal State)는 지각과 행동을 연결합니다. 시스템은 현재 관찰을 기억(Memory), 이전 상태 추정, 목표, 불확실성(Uncertainty), 환경에 대한 지식과 결합합니다. 이러한 인지 상태(Cognitive State)는 개별 센서 측정값보다 안정적인 표현을 제공하며, 객체가 일시적으로 가려지거나 측정값의 신뢰도가 낮아져도 에이전트가 계속 추론할 수 있도록 합니다.

상태 추정(State Estimation)은 감각 관찰만으로 행동에 필요한 모든 정보를 직접 알 수 없는 경우가 많기 때문에 특히 중요합니다. 모바일 로봇은 자신의 정확한 전역 위치, 주변 보행자의 의도, 지면의 마찰계수를 직접 관찰하지 못할 수 있습니다. 이러한 숨겨진 변수(Hidden Variables)를 현재 측정값, 이전 관찰, 모델, 축적된 경험을 이용해 추정해야 합니다.

불확실성은 지각 과정에서 제거되기보다 상태의 일부로 유지되어야 합니다. 객체 분류가 모호하거나, 위치 추정 정확도가 제한되거나, 여러 센서가 서로 다른 결과를 제공할 수 있습니다. 신뢰도(Confidence)와 대안 가설(Alternative Hypotheses)을 표현하면 행동 시스템이 지각 상태가 불확실한 경우 더 신중한 행동을 선택할 수 있습니다.

주의(Attention)는 감각 환경의 어떤 부분에 추가적인 처리 자원을 할당할지를 결정합니다. 지각과 계산 능력에는 한계가 있기 때문에 에이전트는 모든 신호를 동일한 세부 수준으로 분석할 수 없습니다. 목표, 새로움(Novelty), 불확실성, 예측 위험, 작업 관련성은 앞으로의 의사결정에 가장 큰 영향을 미칠 가능성이 높은 정보로 주의를 유도할 수 있습니다.

행동 역시 지각을 유도할 수 있습니다. 로봇은 불확실한 객체를 향해 카메라를 회전시키거나, 다른 관점을 얻기 위해 장애물 주변으로 이동하거나, 위치 추정을 개선하기 위해 마커에 접근하거나, 더 신뢰할 수 있는 센서 데이터를 얻기 위해 속도를 낮출 수 있습니다. 이러한 능동적 지각(Active Perception)은 센싱이 단순한 수동적 수신이 아니라 행동에 의해 의도적으로 형성될 수 있음을 보여줍니다.

이러한 상호작용은 지각이 어떤 행동이 가능해 보이는지를 결정하고, 행동이 다음에 무엇을 지각할 수 있는지를 결정하는 지각-행동 주기(Perception-Action Cycle)를 형성합니다. 에이전트는 이동과 상호작용을 통해 감각 조건을 지속적으로 변화시킵니다. 따라서 지능적 행동은 센싱, 해석, 의사결정, 움직임, 새로운 관찰 사이의 반복적인 결합에서 나타납니다.

어포던스(Affordances)는 지각과 행동 사이의 중요한 연결 고리를 제공합니다. 어포던스는 에이전트의 능력에 비추어 환경이 허용하는 행동을 나타냅니다. 로봇의 크기가 출입구보다 작으면 출입구는 통과 가능성을 제공하고, 손잡이가 도달 범위 안에 있으면 파지 가능성을 제공하며, 표면의 기하학과 마찰이 로봇에 적합하면 주행 가능성을 제공합니다.

어포던스는 단순히 객체 자체의 속성이 아니라 관계적(Relational)입니다. 4족 보행 로봇이 넘을 수 있는 계단이 낮은 지상고의 휠 로봇에게는 장애물이 될 수 있습니다. 한 매니퓰레이터가 들어 올릴 수 있는 물체가 다른 로봇의 페이로드 한계를 초과할 수도 있습니다. 따라서 지각-행동 시스템은 환경을 로봇의 형태(Morphology), 능력, 현재 운영 상태와의 관계 속에서 해석해야 합니다.

따라서 신체 표현(Body Representation)은 이 루프의 기본 요소입니다. 체화 시스템은 자신의 크기, 관절 구성, 속도, 액추에이터 한계, 페이로드(Payload), 에너지 상태, 센서 상태, 도달 가능 작업 공간(Reachable Workspace), 기타 물리적 제약조건을 알아야 합니다. 자기 상태(Self-State)에 대한 정보가 없다면 환경 지각만으로 어떤 행동이 실행 가능한지를 신뢰성 있게 판단할 수 없습니다.

목표(Goals)는 지각과 행동의 관계를 더욱 형성합니다. 시스템은 모든 것을 감지한 후 무엇을 할지 결정하는 것이 아닙니다. 현재 목표가 어떤 객체가 중요한지, 어떤 관계에 주의를 기울여야 하는지, 어떤 감각 세부사항을 무시할 수 있는지를 결정합니다. 목표 지향적 지각(Goal-Directed Perception)은 불필요한 처리를 줄이고 감각적 이해를 목적 지향적 행동과 직접 연결합니다.

기억은 연속적인 지각-행동 주기 사이의 시간적 연속성(Temporal Continuity)을 제공합니다. 작업 기억(Working Memory)은 최근 관찰, 임시 목표, 해결되지 않은 불확실성, 부분 계획을 유지할 수 있으며, 장기 기억(Long-Term Memory)은 이전 경험, 의미론적 지식(Semantic Knowledge), 학습된 기술을 제공합니다. 따라서 현재 지각은 현재 순간 이전에 습득한 정보를 이용하여 해석될 수 있습니다.

이전 행동은 다음 관찰을 해석하는 데에도 중요합니다. 로봇이 전진 명령을 실행했다면 이후 카메라나 라이다 측정값의 변화는 부분적으로 그 움직임의 결과여야 합니다. 실행된 행동에 대한 지식은 에이전트 자신이 발생시킨 변화와 환경에서 독립적으로 발생한 변화를 구분하는 데 도움을 줍니다.

이 원리는 순방향 모델(Forward Models)과 관련됩니다. 순방향 모델은 특정 행동이 실행될 때 에이전트와 환경이 어떻게 변화해야 하는지를 예측합니다. 실제 피드백이 도착하기 전에 예상되는 감각 또는 상태 결과를 생성할 수 있으므로 시스템은 자신의 행동 결과를 사전에 예상할 수 있습니다.

실제 관찰이 예측된 결과와 일치하면 시스템은 현재 상태 추정과 동역학 모델(Dynamics Model)이 타당하다는 증거를 얻습니다. 반대로 실제 관찰이 예측과 크게 다르면 예측 오류(Prediction Error)가 발생하며, 이는 예상하지 못한 상황이 발생했음을 의미합니다. 그 원인은 모델 오류, 환경 변화, 센서 문제, 행동 실패, 잘못된 상태 추정일 수 있습니다.

따라서 예측 오류는 중요한 학습 루프를 완성합니다. 예상하지 못한 결과는 추가적인 주의, 상태 수정, 재계획(Replanning), 모델 적응을 유발할 수 있습니다. 지능 시스템은 오류를 단순한 실패로만 처리하는 대신 세계 또는 자신의 능력에 대한 이해를 개선해야 하는 위치를 알려주는 정보로 활용할 수 있습니다.

피드백 제어(Feedback Control)는 지각-행동 루프의 가장 빠른 형태를 나타냅니다. 센서는 현재 상태를 측정하고, 제어기는 이를 원하는 상태와 비교하며, 액추에이터는 오차를 줄이기 위한 수정 행동을 생성합니다. 새로운 측정값은 해당 행동의 효과를 보여주며, 제어기는 반복적으로 오차를 감소시킬 수 있습니다. 이러한 과정은 초당 수백 또는 수천 번 실행될 수 있습니다.

상위 수준 인지 루프(Higher-Level Cognitive Loops)는 더 느린 시간 규모에서 작동합니다. 객체 지각, 내비게이션 계획, 조작 계획, 작업 추론, 임무 관리(Mission Management)는 밀리초, 수초, 또는 더 긴 주기로 갱신될 수 있습니다. 따라서 지능 시스템에는 서로 다른 시간적·기능적 수준에서 동시에 작동하는 여러 개의 중첩된 지각-행동 루프가 존재합니다.

가장 하위 수준에서는 모터 제어가 안정성, 힘, 속도, 위치를 유지합니다. 중간 수준에서는 모션 플래닝(Motion Planning)이 궤적과 주변 객체와의 상호작용을 제어합니다. 상위 수준에서는 작업 계획(Task Planning)이 다음에 무엇을 수행해야 하는지를 결정합니다. 각 계층은 피드백을 받고 자체 표현과 시간 범위에 따라 행동을 수정합니다.

이러한 루프들을 완전히 독립된 것으로 이해해서는 안 됩니다. 상위 수준 목표는 하위 수준 행동을 제약하고, 하위 수준 피드백은 상위 수준 계획을 변경하도록 만들 수 있습니다. 임무 플래너가 특정 목적지로 이동을 요청하더라도 지역 지각(Local Perception)이 장애물을 탐지하면 궤적 수정이나 전체 임무 계획의 재검토가 필요할 수 있습니다.

반응형 행동(Reactive Behavior)은 이러한 아키텍처의 중요한 구성요소입니다. 반응형 제어는 최소한의 내부 예측으로 현재 관찰을 즉각적인 행동으로 매핑합니다. 비상 정지, 충돌 회피, 균형 보정, 이동 장애물과의 안전 거리 유지와 같이 매우 빠른 반응이 필요한 상황에서 유용합니다.

그러나 순수한 반응형 시스템은 행동의 결과가 지연되거나 현재 결정이 미래 가능성에 영향을 줄 때 어려움을 겪을 수 있습니다. 즉각적인 장애물에만 반응하는 로봇은 막다른 길에 들어가거나 이후에 통과할 수 없는 경로를 선택할 수 있습니다. 예측과 계획은 지각-행동 루프를 현재 순간을 넘어 미래로 확장합니다.

예측적 행동(Predictive Behavior)은 행동 실행 전에 내부 모델을 이용해 미래 상태를 추정합니다. 에이전트는 여러 후보 행동을 예측 결과에 따라 비교할 수 있습니다. 이를 통해 현재 관찰만으로는 판단하기 어려운 미래 충돌 위험, 에너지 소비, 작업 진행, 안정성, 상호작용 결과 등을 행동 결정에 포함할 수 있습니다.

모델 예측 제어(Model Predictive Control)는 예측적 지각-행동 결합의 명확한 사례입니다. 시스템은 현재 상태를 관찰하고, 여러 미래 궤적을 예측하고, 행동을 선택하고, 계획된 시퀀스의 일부만 실행한 후 새로운 상태를 관찰하고 다시 계획합니다. 반복적인 피드백을 통해 제어기는 완벽한 장기 예측에 의존하지 않을 수 있습니다.

이러한 이동 시간 범위 원리(Receding-Horizon Principle)는 실제 환경이 지속적으로 새로운 증거를 제공하기 때문에 물리 시스템에 특히 적합합니다. 자율 로봇은 긴 개루프 계획(Open-Loop Plan)에 고정되는 대신 새로운 관찰이 들어올 때마다 자신의 행동을 반복적으로 수정할 수 있습니다. 예측은 미래에 대한 선견성을 제공하고 피드백은 예상하지 못한 변화에 대한 강건성(Robustness)을 제공합니다.

월드 모델(World Models)은 환경의 관련 요소가 어떻게 변화하는지를 학습함으로써 이러한 원리를 확장합니다. 월드 모델은 객체가 어떻게 움직이고, 물리적 상호작용이 어떻게 전개되며, 작업이 어떻게 진행되고, 행동이 미래 상태를 어떻게 바꾸는지를 예측할 수 있습니다. 따라서 지각, 인지, 계획, 행동을 연결하는 내부 시뮬레이션 메커니즘을 제공합니다.

월드 모델은 반드시 원시 센서 데이터를 직접 처리하기보다 현재 상태의 표현을 입력으로 사용할 수 있습니다. 이러한 표현에는 기하학, 객체, 의미적 관계, 움직임, 불확실성, 로봇 상태, 작업 문맥이 포함될 수 있습니다. 이후 후보 행동을 이 상태에 적용하여 가능한 미래 전개를 생성할 수 있습니다.

잠재 월드 모델(Latent World Models)은 압축된 학습 표현에서 예측을 수행합니다. 완전한 미래 카메라 이미지나 라이다 스캔을 생성하는 대신 행동에 중요한 특징의 변화를 예측합니다. 이를 통해 계산 요구량을 크게 줄일 수 있지만, 잠재 상태가 안전한 계획과 제어에 필요한 정보를 충분히 보존해야 합니다.

객체 중심 월드 모델(Object-Centric World Models)은 지속적으로 존재하는 개체를 중심으로 예측을 구성합니다. 각 객체는 정체성, 위치, 속도, 의미 범주, 물리 특성, 불확실성을 유지할 수 있습니다. 객체 수준의 상태 전이를 예측하면 특히 여러 개체의 상호작용이 중요한 상황에서 지각과 계획 사이에 더 해석 가능한 연결을 제공할 수 있습니다.

행동 선택(Action Selection)은 지각되고 예측된 가능성을 실제 행동으로 변환합니다. 시스템은 작업 성공 가능성, 안전, 시간, 에너지, 편안함, 불확실성, 기타 목표를 기준으로 후보 행동을 평가할 수 있습니다. 선택된 행동은 원하는 상태로 세계를 변화시키기 위해 무엇을 해야 하는지에 대한 시스템의 현재 판단을 나타냅니다.

불확실성 하의 의사결정(Decision Making Under Uncertainty)은 지각과 예측이 완벽하지 않기 때문에 필요합니다. 플래너는 기대 결과뿐 아니라 그 결과에 대한 신뢰도도 고려해야 합니다. 예측 성능이 매우 좋아 보이는 행동이라도 기반 지각의 신뢰도가 낮거나 낮은 확률의 실패가 심각한 결과를 초래한다면 적절하지 않을 수 있습니다.

따라서 위험 민감 행동(Risk-Sensitive Behavior)은 지각-행동 루프의 일부가 됩니다. 불확실성이나 잠재적 결과의 심각성이 증가하면 시스템은 속도를 줄이고, 안전거리를 늘리고, 추가 정보를 수집하고, 인간의 지원을 요청하거나, 더 보수적인 행동을 선택할 수 있습니다. 행동 자체가 불확실성을 관리하는 메커니즘이 됩니다.

정보 수집(Information Gathering) 자체가 명시적인 행동 목표가 될 수도 있습니다. 에이전트는 작업을 즉시 진전시키지는 않더라도 이후 의사결정에 필요한 지식을 개선하는 행동을 일시적으로 선택할 수 있습니다. 가려진 영역을 확인하기 위해 이동하거나 표면에 접촉해 특성을 시험하는 행동은 불확실성을 줄이고 이후 행동을 더 안전하게 만들 수 있습니다.

이로써 세계를 직접 변화시키는 행동과 세계에 대한 지식을 주로 향상시키는 행동을 구분할 수 있지만, 많은 행동은 두 목적을 동시에 수행합니다. 능동 센싱(Active Sensing), 탐색(Exploration), 실험(Experimentation)은 따라서 지각-행동 루프와 분리된 별도 과정이 아니라 자연스러운 확장으로 볼 수 있습니다.

학습(Learning)은 더 긴 시간 규모에서 루프 자체를 변화시킵니다. 모든 상호작용은 관찰, 내부 상태, 행동, 결과의 시퀀스를 생성합니다. 이러한 경험은 지각 모델, 상태 추정기(State Estimator), 월드 모델, 플래너, 제어 정책, 그리고 에이전트 자신의 능력에 대한 표현을 개선하는 데 사용될 수 있습니다.

강화학습(Reinforcement Learning)은 행동과 결과를 직접 연결합니다. 에이전트는 행동을 수행하고, 그 결과 발생한 상태와 보상을 경험하며, 어떤 행동이 원하는 결과를 만드는지를 점차 학습합니다. 정책이 미래에 관찰하게 될 데이터 분포 자체를 변화시키기 때문에 이러한 학습 과정은 본질적으로 폐루프입니다.

모델 기반 강화학습(Model-Based Reinforcement Learning)은 명시적인 예측을 추가합니다. 단순히 어떤 행동이 보상을 만드는지를 학습하는 것에 그치지 않고 상태 전이 모델을 학습하여 후보 미래를 시뮬레이션할 수 있습니다. 이를 통해 모든 행동을 실제로 실행하지 않고도 많은 가능성을 내부적으로 평가할 수 있으므로 데이터 효율성이 향상될 수 있습니다.

자기지도학습(Self-Supervised Learning)은 상호작용 데이터의 자연스러운 시간 구조를 이용하여 지각 및 월드 모델을 향상시킬 수 있습니다. 현재 관찰로부터 미래 특징, 객체 움직임, 마스킹 정보, 행동 결과를 예측할 수 있습니다. 이후 지각-행동 루프가 실제로 생성한 미래 관찰이 자동으로 학습 목표가 되므로 완전한 수작업 라벨링이 필요하지 않습니다.

약지도학습(Weakly Supervised Learning)은 부분적, 잡음이 포함된, 거친 또는 간접적으로 생성된 라벨이 존재할 때 이를 보완할 수 있습니다. 운영 로그, 작업 결과, 인간 수정, 로봇 이벤트, 지도 정보, 기존 탐지기 등이 불완전한 지도 신호를 제공할 수 있습니다. 이러한 신호를 자기지도형 시간 학습과 결합하면 대규모 로봇 데이터셋 구축 비용을 줄일 수 있습니다.

모방학습(Imitation Learning)은 인간 시연(Human Demonstrations)을 루프에 도입합니다. 로봇은 인간 또는 전문가 시스템이 지각한 상황을 어떻게 행동으로 변환하는지를 관찰하고 유사한 행동을 재현하도록 학습합니다. 무작위 탐색이 비효율적이거나 위험한 복잡한 작업에서는 시연이 강력한 초기 정책을 제공할 수 있습니다.

그러나 모방학습만으로는 시연에서 거의 나타나지 않았던 상태를 만날 때 실패할 수 있습니다. 로봇의 행동이 시연 궤적에서 조금만 벗어나도 이후 관찰이 학습 분포 밖으로 이동할 수 있습니다. 따라서 강건한 모방학습을 위해서는 폐루프 평가와 수정 시연(Corrective Demonstrations)이 중요합니다.

지속학습(Continual Learning)은 시스템의 전체 운영 수명 동안 적응을 확장합니다. 새로운 환경, 객체, 작업, 하드웨어 구성, 실패 사례는 미래 행동을 개선하는 경험을 생성합니다. 지각-행동 루프는 즉각적인 제어 메커니즘일 뿐 아니라 장기적인 지능 발전을 위한 주요 데이터 생성원이 됩니다.

경험은 선택적으로 저장해야 합니다. 일상적이고 성공적인 행동은 장기 보존 가치가 낮을 수 있지만, 새로운 사건, 큰 예측 오류, 인간 개입, 안전 사고, 희귀 객체, 비정상적인 환경 조건은 특히 높은 가치를 가질 수 있습니다. 이벤트 기반 기억(Event-Driven Memory)은 모든 원시 센서 스트림을 무기한 저장하지 않고도 정보 가치가 높은 경험을 보존할 수 있습니다.

일화 기억(Episodic Memory)은 에이전트가 무엇을 지각했고, 무엇을 믿었으며, 어떤 행동을 선택했고, 실제로 무엇이 발생했는지를 포함한 특정 상호작용 시퀀스를 보존할 수 있습니다. 이러한 에피소드는 이후 디버깅, 학습, 추론, 그리고 새로운 문제를 만났을 때 유사한 과거 상황을 검색하는 데 활용될 수 있습니다.

의미 기억(Semantic Memory)은 많은 에피소드에서 일반화된 지식을 추출할 수 있습니다. 반복적인 상호작용을 통해 특정 표면이 미끄럽거나, 특정 위치가 혼잡해지거나, 특정 객체 유형이 특별한 취급을 필요로 한다는 사실을 학습할 수 있습니다. 이러한 지식은 원래 경험을 매번 다시 재생하지 않아도 미래 지각과 행동에 영향을 줍니다.

절차 기억(Procedural Memory)은 학습된 기술과 행동 패턴을 저장합니다. 내비게이션 기동, 파지 전략, 도킹 절차, 복구 행동, 조작 루틴은 재사용 가능한 능력이 될 수 있습니다. 지각은 어떤 기술이 적절한지를 식별하고, 피드백은 현재 환경에 맞추어 실행을 지속적으로 조정합니다.

파운데이션 모델(Foundation Models)은 지각-행동 루프의 여러 단계를 강화할 수 있습니다. 지각 파운데이션 모델(Perception Foundation Models)은 재사용 가능한 의미 표현을 제공하고, 언어 모델은 작업 지식과 지시 이해를 지원하며, 행동 파운데이션 모델(Action Foundation Models)은 전이 가능한 행동 사전지식(Behavior Priors)을 제공합니다. 이러한 구성요소는 처음부터 플랫폼별 학습을 모두 수행해야 하는 부담을 줄일 수 있습니다.

지각 파운데이션 모델은 특히 고차원 센서 데이터를 의미 있는 표현으로 변환하는 데 유용합니다. 사전학습된 시각 또는 멀티모달 인코더는 객체, 장면, 관계, 의미 특징을 식별할 수 있습니다. 이후 작업별 헤드(Task-Specific Heads)나 미세조정(Fine-Tuning)을 통해 로봇의 센서와 운영 환경에 맞게 이러한 표현을 적응시킬 수 있습니다.

언어 파운데이션 모델(Language Foundation Models)은 인간의 지시를 목표, 제약조건, 작업 구조 또는 후보 계획으로 변환할 수 있습니다. 그러나 언어로 생성된 해석은 현재 물리 상태에 기반해야 합니다. 언어 모델은 무엇을 해야 하는지를 제안할 수 있지만, 실제로 무엇이 가능하고 안전한지는 지각 및 월드 상태 추정이 결정해야 합니다.

행동 파운데이션 모델은 대규모 로봇 상호작용에서 학습한 재사용 가능한 정책 또는 움직임 표현을 제공할 수 있습니다. 그 출력은 현재 지각, 로봇 형태, 능력, 작업 문맥에 조건화되어야 합니다. 다른 환경에서 학습한 행동 사전지식이 현재 물리 환경을 완벽하게 예측할 수는 없기 때문에 폐루프 피드백은 여전히 필수적입니다.

지각, 월드 모델, 행동 모델의 결합은 피지컬 AI(Physical AI)를 위한 강력한 아키텍처를 형성합니다. 지각은 현재 세계와 자기 상태를 추정하고, 월드 모델은 가능한 결과를 예측하며, 행동 모델은 실행 가능한 행동을 생성합니다. 이후 계획은 이러한 가능성 중에서 선택하고, 지속적인 피드백은 실행 과정에서 발생하는 오류를 수정합니다.

멀티모달 지각(Multi-Modal Perception)은 서로 다른 센서가 상호보완적인 정보를 제공하기 때문에 이러한 아키텍처를 강화합니다. 카메라는 외형과 의미를 제공하고, 라이다는 기하학 정보를 제공하며, 레이더는 강건한 움직임 측정값을 제공하고, IMU는 관성 상태를 제공하며, GNSS는 전역 위치를 제공하고, 고유수용 센서는 로봇의 물리적 상태를 설명합니다.

센서 융합(Sensor Fusion)은 이러한 관찰을 일관된 상태로 통합합니다. 서로 다른 시간에 수집된 측정값은 서로 다른 물리적 구성을 나타낼 수 있기 때문에 정확한 동기화가 필수적입니다. 움직임 보상(Motion Compensation), 보정(Calibration), 타임스탬프 정렬(Timestamp Alignment), 불확실성 모델링은 이후 행동의 품질에 직접 영향을 줍니다.

플래너 자체가 수학적으로 정확하더라도 잘못된 지각은 잘못된 행동을 만들어낼 수 있습니다. 장애물 위치가 잘못 추정된 상태에서 완벽하게 최적화된 궤적이라도 여전히 위험합니다. 따라서 지각-행동 루프의 신뢰성은 정확하고, 시의적절하며, 불확실성을 고려한 상태 추정을 유지하는 능력에 달려 있습니다.

마찬가지로 잘못된 행동 실행은 지각을 오염시킬 수 있습니다. 휠 슬립, 액추에이터 오류, 기계 변형, 진동, 예상하지 못한 접촉으로 인해 실제 로봇 상태가 명령된 상태와 달라질 수 있습니다. 고유수용 피드백과 상태 추정은 이러한 차이를 탐지하여 내부 표현이 물리적 현실과 일치하도록 유지해야 합니다.

따라서 보정(Calibration)은 일회성 작업이 아닙니다. 센서 외부 파라미터(Extrinsics), 액추에이터 응답, 휠 파라미터, 페이로드 분포, 기타 시스템 특성은 운영 중 변화할 수 있습니다. 예측 오류와 센서 간 일관성을 모니터링하면 보정 품질이 지각-행동 성능에 영향을 줄 정도로 저하되는 시점을 탐지할 수 있습니다.

안전(Safety)은 작업 행동과 병렬로 동작하는 전용 루프를 필요로 합니다. 비상 정지, 충돌 모니터링, 안정성 검사, 관절 한계, 속도 제한, 지오펜싱(Geofencing), 기타 안전 메커니즘은 고수준 학습 추론에 전적으로 의존해서는 안 됩니다. 독립적인 피드백 경로는 학습 구성요소가 예상과 다르게 작동할 때 결정론적인 보호를 제공할 수 있습니다.

안전 감독기(Safety Supervisor)는 실행 전에 제안된 행동을 평가하고 실행 후 실제 행동을 모니터링할 수 있습니다. 지각 신뢰도가 감소하거나, 통신이 실패하거나, 위치 추정 신뢰성이 낮아지거나, 예측 위험이 허용 가능한 임계값을 초과하면 감독기는 행동을 제한하거나 로봇을 더 안전한 운영 상태로 전환할 수 있습니다.

인간 상호작용(Human Interaction)은 또 다른 피드백 채널을 추가합니다. 인간은 지시, 수정, 시연, 승인, 비상 개입을 제공할 수 있습니다. 로봇의 행동 역시 인간에게 정보를 제공하며, 인간은 이를 관찰하고 로봇에 대한 기대를 갱신합니다. 따라서 인간-로봇 상호작용(Human-Robot Interaction)은 여러 지능적 참여자가 결합된 지각-행동 루프를 형성합니다.

의도 전달(Intent Communication)은 이러한 루프를 더 안전하고 이해하기 쉽게 만들 수 있습니다. 로봇은 움직이기 전에 계획된 방향, 예상 행동, 불확실성, 지원 필요성을 알릴 수 있습니다. 인간은 로봇이 움직인 후에야 반응하는 대신 사전에 행동을 예상할 수 있으므로 공유 환경에서의 모호성을 줄일 수 있습니다.

멀티에이전트 로봇 시스템(Multi-Agent Robotic Systems)에는 서로 상호작용하는 여러 지각-행동 루프가 존재합니다. 각 로봇은 환경과 다른 에이전트를 지각하고, 행동을 선택하며, 그 행동을 통해 다른 모든 에이전트가 관찰하는 상태를 변화시킵니다. 따라서 조정을 위해서는 정적인 장애물뿐 아니라 다른 자율 에이전트의 예상 행동과 목표도 추론해야 합니다.

공유 정보는 개별 로봇의 지각 범위를 확장할 수 있습니다. 플릿 구성원은 탐지된 장애물, 지도, 작업 진행 상태, 위치 추정 정보, 환경 변화를 교환할 수 있습니다. 공유 월드 표현(Shared World Representation)은 조정 능력을 향상시키며, 로컬 온보드 지각은 즉각적인 안전에 필요한 낮은 지연시간 정보를 계속 제공합니다.

플릿 수준 계획(Fleet-Level Planning)은 개별 로봇보다 상위에 존재하는 더 느린 지각-행동 루프를 형성합니다. 플릿 시스템은 로봇 상태, 작업 수요, 혼잡, 에너지 수준, 임무 진행 상황을 관찰한 후 작업을 재할당하거나 경로를 변경합니다. 그 결과 로봇 행동이 플릿 상태를 변화시키고, 이는 다음 조정 주기에 새로운 정보를 제공합니다.

엣지 컴퓨팅(Edge Computing)은 이러한 루프 중 가장 빠른 부분에서 특히 중요합니다. 네트워크 지연이나 통신 손실이 원격 의존성을 위험하게 만들 수 있기 때문에 즉각적인 지각, 상태 추정, 안전 모니터링, 모션 플래닝, 제어는 물리 로봇과 가까운 위치에서 실행되어야 합니다.

온프레미스 컴퓨팅(On-Premise Computing)은 더 느리고 광범위한 인지 기능을 지원할 수 있습니다. 대규모 월드 모델, 플릿 최적화(Fleet Optimization), 장기 기억, 데이터셋 관리, 모델 학습, 전역 지도 유지, 복잡한 추론은 공유 인프라를 사용하여 수행할 수 있습니다. 따라서 지연시간, 계산 요구량, 운영 범위에 따라 인지를 분산시키는 아키텍처를 구성할 수 있습니다.

엣지와 온프레미스 시스템 사이의 통신은 가능하면 모든 원시 센서 스트림을 지속적으로 전송하기보다 의미 있는 상태 표현을 사용해야 합니다. 객체, 궤적, 이벤트, 불확실성, 작업 상태, 선택된 센서 구간은 효율적인 요약을 제공할 수 있으며, 원시 데이터는 학습 또는 사후 분석이 필요한 경우에 보존할 수 있습니다.

통신이 끊어져도 자율성은 점진적으로 저하되어야 합니다. 모든 의사결정을 원격 지능에 의존하는 로봇은 네트워크 중단 시 안전하지 않거나 사용할 수 없는 상태가 될 수 있습니다. 필수적인 지각-행동 기능은 온보드에 유지되어야 하며 외부 계산은 즉각적인 안전 운용에 필수적이지 않은 방식으로 능력을 향상시켜야 합니다.

지각-행동 루프는 체화(Embodiment)와도 밀접하게 관련됩니다. 물리적 에이전트의 지능은 행동이 이루어지는 신체에 의해 제약되고 형성됩니다. 센서 배치는 무엇을 관찰할 수 있는지를 결정하고, 액추에이터 구성은 무엇을 변화시킬 수 있는지를 결정하며, 기계 설계는 어떤 제어 및 지각 문제를 계산적으로 해결해야 하는지를 결정합니다.

더 나은 기계 설계는 인지 문제를 단순화할 수 있습니다. 안정적인 이동, 예측 가능한 조향, 적절한 센서 배치, 충분한 접지력, 정확한 액추에이터는 불확실성과 제어 난이도를 줄입니다. 따라서 피지컬 AI는 기계, 전기, 센싱, 계산, 인지 아키텍처를 하나의 통합 시스템으로 다루어야 합니다.

반대로 지능적 제어는 일부 물리적 한계를 보완할 수 있습니다. 지각은 어려운 지형을 식별하고, 예측은 슬립이나 불안정을 추정하며, 계획은 더 안전한 궤적을 선택할 수 있습니다. 따라서 기계적 능력과 계산 지능 사이의 경계는 고정되어 있지 않으며, 서로가 상대방에게 요구되는 성능을 변화시킵니다.

이 루프는 인공 시스템의 인지 부하(Cognitive Load)를 이해하기 위한 유용한 프레임워크이기도 합니다. 계산 자원에는 한계가 있기 때문에 모든 지각, 예측, 계획 프로세스를 항상 최대 복잡도로 실행할 수 없습니다. 주의와 작업 우선순위가 처리 자원을 어디에 할당해야 하는지를 결정합니다.

적응형 계산(Adaptive Computation)은 상황에 따라 추론 깊이를 변경할 수 있습니다. 안정적인 복도에서의 일상적인 내비게이션은 경량 처리를 사용해도 충분할 수 있지만, 혼잡한 교차로나 복잡한 조작 작업에서는 더 풍부한 지각, 더 긴 예측 시간 범위, 더 상세한 계획을 활성화할 수 있습니다. 계산 노력 자체가 제어 전략의 일부가 됩니다.

이벤트 기반 아키텍처(Event-Driven Architectures)는 효율성을 더욱 향상시킬 수 있습니다. 모든 표현을 지속적으로 다시 계산하기보다 새로운 장애물, 예측 오류, 작업 전환, 위치 추정 성능 저하, 안전 경고와 같은 중요한 변화가 추가 처리를 활성화하도록 할 수 있습니다. 이를 통해 인지 시스템은 새로운 정보의 가치가 높은 영역에 자원을 집중할 수 있습니다.

따라서 지각-행동 루프에는 외부 피드백과 내부 피드백이 모두 포함됩니다. 외부 피드백은 행동 이후 환경이 어떻게 변화했는지를 나타내고, 내부 피드백은 신뢰도, 계산 부하, 기억, 예측 품질, 모델 신뢰성 변화 등을 나타냅니다. 이 두 종류의 피드백 모두 에이전트가 다음에 무엇을 해야 하는지에 영향을 줍니다.

메타인지(Metacognition)는 이러한 내부 조건을 감독할 수 있습니다. 시스템은 자신의 지각이 불확실하거나, 월드 모델이 익숙하지 않은 조건에서 작동하고 있거나, 플래너가 안전한 해결책을 찾지 못하고 있음을 인식할 수 있습니다. 무작정 계속 진행하는 대신 추가 정보를 수집하고, 작업을 단순화하고, 다른 모델을 호출하고, 도움을 요청하거나, 정지할 수 있습니다.

이러한 행동은 개발 과정에서 모든 상황을 사전에 예측할 수 없는 오픈월드 환경(Open-World Environments)에서 특히 중요합니다. 강건한 자율성(Robust Autonomy)은 시스템이 모든 것을 알고 있어야 한다는 것을 의미하지 않습니다. 현재 지식이 충분하지 않은 시점을 인식하고 안전을 유지하면서 불확실성을 줄이는 행동을 선택할 수 있어야 합니다.

따라서 지각-행동 시스템의 평가는 개별 구성요소만 분리하여 평가하는 것이 아니라 폐루프 시험(Closed-Loop Testing)을 사용해야 합니다. 높은 객체 탐지 정확도가 좋은 내비게이션을 보장하지 않으며, 낮은 궤적 예측 오류가 자동으로 안전한 제어를 보장하지도 않습니다. 중요한 것은 각 구성요소의 성능이 실제 행동에 어떤 영향을 미치는지입니다.

시뮬레이션(Simulation)은 폐루프 평가를 확장 가능한 방식으로 수행할 수 있는 환경을 제공합니다. 로봇은 다양한 시나리오와 상호작용하고, 실패를 경험하며, 물리적 위험 없이 대안 행동을 시험할 수 있습니다. 시뮬레이션은 특히 희귀 사건 시험에 유용하지만 학습된 행동을 현실로 전이할 때 시뮬레이션과 현실 사이의 차이를 고려해야 합니다.

실제 환경 시험(Real-World Testing)은 물리적 상호작용이 완벽하게 모델링하기 어려운 효과를 드러내기 때문에 여전히 필수적입니다. 센서 잡음, 기계 마모, 조명 변화, 마찰, 진동, 인간 행동의 불확실성, 통신 문제, 예상하지 못한 환경 구조는 시뮬레이션에서는 드러나지 않았던 취약점을 발견하게 합니다.

디지털 트윈(Digital Twins)은 로봇과 환경의 가상 표현을 유지함으로써 시뮬레이션과 운영 시스템을 연결할 수 있습니다. 실제 센서 데이터가 디지털 상태를 갱신하고, 시뮬레이션은 가능한 행동이나 유지보수 조건을 평가할 수 있습니다. 이를 통해 물리적 운영과 예측 계산 사이에 또 다른 피드백 경로가 형성됩니다.

실제 지각-행동 주기에서 수집된 데이터는 디지털 모델을 지속적으로 개선할 수 있습니다. 반대로 개선된 시뮬레이션과 학습 모델은 더 나은 정책을 생성하여 실제 시스템에 배포할 수 있습니다. 따라서 물리 시스템과 계산 표현은 관찰, 모델링, 시험, 행동의 반복을 통해 함께 발전할 수 있습니다.

인지과학(Cognitive Science)의 관점에서 지각-행동 루프는 인지가 행동과 분리된 내부 정보 처리만으로 구성되지 않는다는 점을 강조합니다. 가능한 행동이 지각을 형성하고, 행동은 다시 지각을 변화시키며, 인지는 유기체와 환경 사이의 반복적인 상호작용을 통해 발전합니다. 따라서 지능은 체화와 피드백에 깊게 연결되어 있습니다.

인공지능(Artificial Intelligence)의 관점에서도 동일한 원리는 정적인 입력-출력 예측에서 상호작용형 에이전트(Interactive Agents)로 관심의 초점을 이동시킵니다. 고정된 데이터셋을 처리하는 모델은 자신의 예측 결과를 경험하지 않지만, 자율 에이전트는 자신의 행동을 통해 앞으로 받게 될 데이터 자체를 변화시킵니다. 이 때문에 폐루프 학습은 수동적 추론과 근본적으로 다릅니다.

로보틱스(Robotics)와 피지컬 AI에서 지각-행동 루프는 센서, 내부 표현, 월드 모델, 계획, 제어, 기억, 학습을 연결하는 핵심 아키텍처를 제공합니다. 모든 자율 기능은 결국 로봇이 현재 상황을 이해하고, 무엇을 할지 결정하고, 행동을 실행하며, 다음에 무엇이 발생했는지를 해석하도록 지원함으로써 이 주기에 참여합니다.

고급 시스템은 하나의 단일 거대 모델(Monolithic Model)에 의존하기보다 여러 루프를 결합할 가능성이 높습니다. 빠른 결정론적 안전 및 제어 루프는 학습 기반 지각, 예측형 월드 모델, 파운데이션 모델, 숙고적 계획(Deliberative Planning), 플릿 지능(Fleet Intelligence), 지속학습과 동시에 작동할 수 있습니다. 이러한 루프들의 조정이 전체 자율 행동의 품질을 결정합니다.

따라서 목표는 단순히 지각 성능이나 행동 정책을 각각 독립적으로 개선하는 것이 아닙니다. 지각이 행동에 필요한 상태를 제공하고, 필요할 때 행동이 지각을 능동적으로 개선하며, 예측이 결과를 사전에 추정하고, 피드백이 오류를 수정하며, 학습이 전체 상호작용 주기를 지속적으로 향상시키는 일관된 시스템을 구축하는 것이 목표입니다.

성숙한 지각-행동 아키텍처(Perception-Action Architecture)는 궁극적으로 지속적으로 적응하는 폐루프 지능 시스템으로 동작합니다. 세계와 자신을 감지하고, 인지 상태를 구성하며, 가능한 미래를 예측하고, 목표 지향적 행동을 선택하고, 물리적 결과를 모니터링하고, 불일치를 탐지하고, 지식을 갱신한 후 즉시 다시 다음 주기를 시작합니다. 이러한 지각과 행동의 반복적인 결합을 통해 자율 에이전트는 실제 세계에서 점점 더 강건하고, 적응적이며, 신뢰할 수 있는 행동을 달성할 수 있습니다.
