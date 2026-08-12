**Volume 43 Cognitive Science for AI**

# Chapter 01. Human Cognition

## 01.00 Overview of Cognitive Science

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.01 Perception and Action [w/Code]

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.02 Attention and Awareness [w/Code]

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.03 Learning and Adaptation [w/Code]

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.04 Mental Models

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.05 Cognitive Load

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.06 Human Error and Reliability [w/Code]

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.07 Cognition vs Intelligence

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.08 Implications for AI [w/Code]

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.09 Internal Representations and Cognitive State [w/Code]

![](images/image10.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.10 Prediction and Anticipation [w/Code]

![](images/image11.png){width="7.268055555555556in" height="7.268055555555556in"}

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

## 01.11 Perception Action Loop [w/Code]

![](images/image12.png){width="7.268055555555556in" height="7.268055555555556in"}

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
