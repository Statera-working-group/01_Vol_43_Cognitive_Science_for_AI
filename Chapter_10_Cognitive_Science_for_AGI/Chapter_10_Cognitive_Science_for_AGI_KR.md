**Volume 43 Cognitive Science for AI**

# Chapter 10. Cognitive Science for AGI

## 10.00 AGI Context

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

인공일반지능(Artificial General Intelligence, AGI)은 하나의 좁은 영역에 제한되지 않고 유연성(Flexibility), 전이(Transfer), 적응(Adaptation), 추론(Reasoning)을 바탕으로 광범위한 인지 작업(Cognitive Tasks)을 수행할 수 있는 인공 시스템의 개념을 의미합니다. 인지과학(Cognitive Science)의 맥락에서 AGI는 하나의 알고리즘이나 벤치마크로 이해하기보다 지각(Perception), 기억(Memory), 추론, 학습(Learning), 언어(Language), 계획(Planning), 행동(Action)의 통합을 요구하는 시스템 수준의 목표(Systems-Level Objective)로 이해하는 것이 적절합니다.

현재의 AI 시스템은 언어, 비전(Vision), 검색(Retrieval), 예측(Prediction), 코딩(Coding), 계획, 도구 사용(Tool Use)에서 인상적인 능력을 보여줄 수 있지만, 이러한 능력은 작업과 맥락에 따라 불균등한 경우가 많습니다. 하나의 영역에서 높은 성능을 보인다고 해서 자동적으로 일반지능(General Intelligence)을 의미하는 것은 아닙니다. 따라서 AGI는 낯선 상황에서도 지능을 안정적으로 전이하기 위해 어떠한 표현(Representations), 학습 메커니즘(Learning Mechanisms), 기억 구조(Memory Structures), 추론 과정(Reasoning Processes), 적응적 행동(Adaptive Behaviors)이 필요한가라는 질문을 제기합니다.

인지과학은 인간 지능(Human Intelligence) 자체가 서로 상호작용하는 인지 하위시스템(Cognitive Subsystems)의 결과이기 때문에 이러한 질문을 탐구하는 중요한 기반을 제공합니다. 인간은 지각, 주의(Attention), 작업기억(Working Memory), 장기기억(Long-Term Memory), 일화적 경험(Episodic Experience), 의미 지식(Semantic Knowledge), 절차적 기술(Procedural Skills), 추론, 언어, 감정(Emotion), 행동을 결합합니다. 따라서 AGI 연구는 하나의 고립된 능력을 확장하면 일반지능이 자연스럽게 출현할 것이라고 가정하기보다 이러한 기능들이 어떻게 협력하는지에서 통찰을 얻을 수 있습니다.

일반성(Generality)을 확보하기 위해서는 단순히 방대한 양의 정보를 저장하는 것만으로는 충분하지 않습니다. 지능형 시스템(Intelligent System)은 어떤 지식이 관련성이 있는지를 판단하고, 적절한 시점에 이를 검색하며, 현재의 관측(Current Observations)과 결합하여 새로운 문제에 적용할 수 있어야 합니다. 이는 AGI를 표현학습(Representation Learning), 의미기억(Semantic Memory), 일화기억(Episodic Memory), 추상화(Abstraction), 전이(Transfer)와 직접 연결합니다. 유용한 내부 표현(Internal Representation)은 하나의 학습 분포(Training Distribution)에 강하게 결합된 형태로 지식을 부호화하기보다 여러 작업에서 재사용할 수 있어야 합니다.

작업기억(Working Memory) 역시 일반적인 문제 해결(General Problem Solving)에 작업과 관련된 정보를 일시적으로 유지하고 조작하는 능력이 필요하기 때문에 중요합니다. 인간은 작업기억을 이용하여 중간 목표(Intermediate Goals)를 유지하고, 대안을 비교하며, 다단계 추론(Multi-Step Reasoning)을 수행하고, 새로운 정보가 들어오면 계획을 업데이트합니다. AGI 아키텍처 역시 장시간 지속되는 상호작용에서 임시 상태(Temporary State)를 유지할 수 있는 메커니즘을 필요로 하며, 이를 통해 추론이 연속성을 갖지 못한 개별적인 응답의 집합으로 붕괴되는 것을 방지해야 합니다.

장기기억(Long-Term Memory)은 현재 작업을 넘어서는 연속성(Continuity)을 제공합니다. AGI 시스템은 사실(Facts), 학습된 개념(Learned Concepts), 과거 경험, 성공적인 절차, 실패, 사용자나 환경에 관한 지식을 보존해야 할 수 있습니다. 서로 다른 형태의 기억은 서로 다른 기능을 지원할 수 있습니다. 의미기억은 일반화된 지식을 제공하고, 일화기억은 구체적인 경험으로부터의 학습을 지원하며, 절차기억(Procedural Memory)은 재사용 가능한 기술을 보존합니다. 이러한 기억들의 개별적인 용량만큼이나 서로를 조정하는 능력이 중요할 가능성이 높습니다.

추론(Reasoning)은 또 다른 핵심 요구사항입니다. 일반지능은 직접적인 패턴 매칭(Pattern Matching)만으로 충분하지 않은 상황과 결론이 관계, 제약조건, 불확실성(Uncertainty), 원인(Causes), 가상적인 대안에 의존하는 상황에서도 작동해야 합니다. 연역적 추론(Deductive Reasoning), 귀납적 추론(Inductive Reasoning), 귀추적 추론(Abductive Reasoning), 유추적 추론(Analogical Reasoning), 인과적 추론(Causal Reasoning), 반사실적 추론(Counterfactual Reasoning)은 서로 상호보완적인 메커니즘을 제공합니다. 따라서 AGI에는 하나의 보편적 절차에 의존하기보다 문제 구조에 따라 추론 전략을 선택하거나 결합하는 능력이 필요합니다.

계획(Planning)은 추론을 미래 지향적 행동(Future-Oriented Behavior)과 연결합니다. 일반적인 지능형 시스템은 목표를 표현하고, 가능한 행동 시퀀스(Action Sequences)를 생성하고, 결과를 평가하며, 조건이 변화하면 계획을 수정하고, 여러 시간 규모(Multiple Timescales)를 관리할 수 있어야 합니다. 계획에는 명시적 탐색(Explicit Search), 학습된 정책(Learned Policies), 시뮬레이션(Simulation), 월드 모델(World Models) 또는 이들의 조합이 사용될 수 있습니다. 중요한 능력은 고정된 계획을 생성하는 것이 아니라 새로운 증거와 제약조건이 나타날 때 행동을 지속적으로 수정하는 것입니다.

학습(Learning) 역시 기존의 오프라인 학습(Offline Training)을 넘어 확장되어야 합니다. AGI는 제한된 경험, 피드백, 시연(Demonstrations), 상호작용, 자체 생성 데이터(Self-Generated Data)로부터 새로운 지식과 기술을 습득하는 능력을 의미합니다. 메타학습(Meta-Learning), 소수샷 적응(Few-Shot Adaptation), 지속학습(Continual Learning), 강화학습(Reinforcement Learning), 자기지도학습(Self-Supervised Learning)은 이러한 목표와 관련된 메커니즘을 제공합니다. 일반 시스템은 처음부터 전체 재학습을 반복적으로 수행하지 않고도 경험을 통해 향상될 수 있어야 합니다.

지속학습(Continual Learning)은 새로운 능력을 습득하면서 기존 능력을 유지해야 하는 문제를 제기합니다. 새로운 작업을 학습할 때 이전에 획득한 지식이 파괴된다면 시스템은 장기간에 걸쳐 능력을 축적할 수 없습니다. 기억 통합(Memory Consolidation), 리플레이(Replay), 모듈성(Modularity), 파라미터 격리(Parameter Isolation), 검색, 적응형 표현(Adaptive Representations)은 치명적 망각(Catastrophic Forgetting)을 줄이는 데 도움을 줄 수 있습니다. 따라서 일반지능에는 빠른 학습뿐만 아니라 새로운 지식을 확장되는 내부 구조에 안정적으로 통합하는 능력도 필요합니다.

언어(Language)는 개념, 지시, 목표, 설명, 추상적인 관계를 표현하는 강력한 매체를 제공하기 때문에 중요합니다. 대규모 언어 모델(Large Language Models)은 광범위한 언어 학습이 폭넓은 능력을 만들어낼 수 있음을 보여주지만, 언어만으로 물리적·사회적 세계에 대한 완전한 그라운딩(Grounding)을 반드시 제공하는 것은 아닙니다. 따라서 AGI는 언어적 표현(Linguistic Representations)이 지각, 행동, 기억, 인과성(Causality), 경험(Experience)과 어떻게 연결되는지를 다루어야 합니다.

다중모달 인지(Multimodal Cognition)는 시각, 청각(Auditory), 공간(Spatial), 감각운동(Sensorimotor), 기타 형태의 정보를 통합함으로써 지능을 텍스트의 범위를 넘어 확장합니다. 인간은 여러 지각 채널(Perceptual Channels)을 활용하여 객체, 사건, 사람, 공간, 행동에 대해 추론합니다. AGI 시스템 역시 하나의 모달리티(Modality)를 통해 학습한 정보가 다른 모달리티의 추론에 영향을 줄 수 있도록 통합된 표현(Unified Representations)을 필요로 할 수 있습니다. 따라서 교차모달 그라운딩(Cross-Modal Grounding)은 하나의 입력 형식을 넘어 의미를 유지하는 개념을 구축하는 데 중요합니다.

체화된 인지(Embodied Cognition)는 지능이 환경과의 상호작용을 통해 발달한다는 점을 강조함으로써 또 다른 관점을 제공합니다. 지각과 행동은 에이전트가 환경 조건을 관측하고, 결과를 예측하며, 행동하고, 그 결과로부터 학습하는 연속적인 루프(Continuous Loop)를 형성합니다. 피지컬 AI(Physical AI)는 지능형 로봇이 추상적인 목표를 현실 세계의 동역학(Real-World Dynamics), 불확실성, 물리적 제약조건, 안전(Safety), 감각운동 피드백(Sensorimotor Feedback)과 연결해야 하기 때문에 이러한 관계를 명확하게 보여줍니다.

월드 모델(World Models)은 지각, 예측, 추론, 계획을 연결하는 가교를 제공할 수 있습니다. 환경이 어떻게 변화하는지를 표현하는 방법을 학습함으로써 지능형 시스템은 실제로 행동하기 전에 가능한 미래를 내부적으로 시뮬레이션(Mental Simulation)할 수 있습니다. 이러한 내부 모델(Internal Models)은 예측, 반사실적 추론, 탐색(Exploration), 장기 계획(Long-Horizon Planning)을 지원할 수 있습니다. AGI를 위한 월드 모델은 물리적 동역학뿐만 아니라 객체, 에이전트, 의도(Intentions), 인과관계(Causal Relationships), 불확실성, 변화하는 맥락까지 포착해야 할 수 있습니다.

메타인지(Metacognition)는 자신의 인지 과정 자체에 대해 추론하는 능력을 추가합니다. 일반적인 지능형 시스템은 이상적으로 자신이 무엇을 알고 있는지를 추정하고, 불확실성을 인식하며, 실패를 탐지하고, 계산 자원(Computational Effort)을 배분하며, 추가적인 정보나 외부 지원이 필요한 시점을 판단할 수 있어야 합니다. 이러한 능력은 신뢰도 보정(Confidence Calibration), 자기 모니터링(Self-Monitoring), 성찰(Reflection), 적응형 추론(Adaptive Reasoning)과 밀접하게 연결됩니다. 시스템이 자신의 능력 경계를 인식할 수 있을 때 일반지능은 더욱 신뢰성 있게 작동할 수 있습니다.

이중과정 관점(Dual-Process Perspectives)은 또 다른 유용한 프레임워크를 제공합니다. 빠르고 학습된 직관적 처리(Fast, Learned, Intuitive Processing)는 익숙한 패턴을 효율적으로 처리할 수 있으며, 느리고 숙고적인 추론(Slower Deliberative Reasoning)은 어렵거나 새로운 문제를 처리할 수 있습니다. AGI 아키텍처는 빠른 신경망 추론(Neural Inference)을 탐색, 계획, 검증(Verification), 시뮬레이션, 테스트 시간 계산(Test-Time Computation)과 결합할 수 있습니다. 핵심 과제는 언제 비용이 높은 숙고 과정이 필요한지를 판단하고 그 결과를 이후의 빠른 응답에 어떻게 반영할 것인지를 결정하는 것입니다.

사회적 지능(Social Intelligence) 역시 중요합니다. 인간 지능의 많은 형태가 사회적 환경에서 발달하고 작동하기 때문입니다. AI가 인간 또는 다른 에이전트와 상호작용할 때 의도, 믿음(Beliefs), 의사소통, 협력(Cooperation), 규범(Norms), 충돌하는 목표를 이해하는 능력이 필수적이 됩니다. 따라서 인간-AI 상호작용(Human--AI Interaction), 협력 지능(Collaborative Intelligence), 인간-에이전트 팀워크(Human--Agent Teamwork)는 일반지능이 개별적인 문제 해결뿐만 아니라 효과적인 조정(Coordination) 능력을 입증해야 하는 실질적인 맥락을 제공합니다.

시스템이 더 폭넓은 능력과 자율성(Autonomy)을 획득할수록 정렬(Alignment)과 안전(Safety)은 더욱 중요해집니다. 일반적인 능력을 가진 AI는 인간의 목표를 해석하고, 불완전한 지시 아래에서 작동하며, 제약조건을 준수하고, 인간의 수정을 받아들이며, 인간 감독(Human Oversight)에 지속적으로 반응할 수 있어야 합니다. 신뢰할 수 있는 목표 해석이나 제어가능성(Controllability)이 결여된 일반지능은 명세 오류(Specification Errors)를 증폭시킬 수 있습니다. 따라서 AGI 연구에서는 정렬을 능력 개발 이후에 추가되는 외부 계층이 아니라 아키텍처 수준의 요구사항(Architectural Requirement)으로 다루어야 합니다.

AGI의 평가(Evaluation)는 좁은 벤치마크(Narrow Benchmarks)가 진정한 일반성을 측정하지 못하면서 특화된 능력에 높은 점수를 부여할 수 있기 때문에 어렵습니다. 유용한 평가는 보지 못한 작업으로의 전이(Transfer to Unseen Tasks), 제한된 사례를 통한 적응, 불확실성 하에서의 추론, 시간에 걸친 기억, 구성성(Compositionality), 인과적 이해(Causal Understanding), 강건성(Robustness), 학습 효율성(Learning Efficiency), 여러 영역에 걸친 성능을 함께 검토해야 합니다. 핵심 질문은 시스템이 학습 과정에서 직접적으로 경험한 패턴을 벗어난 상황에서도 이러한 능력들이 일관성을 유지하는가입니다.

인지과학의 관점에서 AGI는 하나의 단일한 목적지라기보다 여러 형태의 인지 능력을 하나의 적응형 아키텍처(Adaptive Architecture)로 통합하는 문제로 이해할 수 있습니다. 지각, 기억, 추론, 학습, 언어, 월드 모델, 메타인지, 체화(Embodiment), 상호작용(Interaction)은 시간의 흐름 속에서 서로 협력해야 합니다. 핵심적인 과제는 환경과 목표가 변화하는 상황에서도 능력이 일반화(Generalize)되고, 축적(Accumulate)되고, 조정(Coordinate)되며, 정렬된 상태를 유지할 수 있는 시스템을 구축하여 점점 더 일반적인 인공지능(General Artificial Intelligence)을 위한 기반을 형성하는 것입니다.

## 10.01 General Intelligence and Cognition [w/Code]

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

일반지능(General Intelligence)은 하나의 좁은 기능에만 최적화되는 것이 아니라 다양한 작업, 환경, 문제 유형에 걸쳐 효과적으로 수행할 수 있는 지능형 시스템(Intelligent System)의 능력을 의미합니다. 인지적 관점(Cognitive Perspective)에서 일반성(Generality)은 지각(Perception), 기억(Memory), 학습(Learning), 추론(Reasoning), 계획(Planning), 언어(Language), 행동(Action)의 조정된 활용을 통해 나타납니다. 따라서 지능은 개별 능력뿐만 아니라 이러한 능력을 얼마나 유연하게 결합할 수 있는지에 의해 결정됩니다.

인간 인지(Human Cognition)는 사람들이 표면적인 모습이 크게 다른 상황 사이에서도 일상적으로 지식을 전이하기 때문에 일반지능을 이해하는 중요한 기준을 제공합니다. 하나의 맥락에서 학습된 개념은 다른 맥락의 추론에 영향을 줄 수 있으며, 이전 경험은 익숙하지 않은 환경에서의 행동을 안내할 수 있습니다. 이러한 능력은 추상화(Abstraction), 표현(Representation), 유추(Analogy), 기억 검색(Memory Retrieval), 그리고 변화하는 조건에서도 안정적으로 유지되는 관계를 식별하는 능력에 의존합니다.

일반지능은 개별적인 관측을 단순히 암기하는 것이 아니라 의미 있는 구조를 포착하는 표현(Representations)을 필요로 합니다. 유용한 표현은 객체, 속성(Properties), 관계(Relationships), 사건(Events), 목표(Goals), 원인(Causes), 가능한 행동을 여러 인지 기능에서 활용할 수 있는 형태로 기술합니다. 지식이 적절한 추상화 수준(Level of Abstraction)으로 표현되면 특정 작업에 종속되지 않고 예측, 추론, 계획, 의사소통, 학습에 재사용될 수 있습니다.

지각(Perception)은 감각 정보(Sensory Information)를 구조화된 내부 표현(Structured Internal Representations)으로 변환함으로써 일반 인지(General Cognition)에 기여합니다. 지능형 시스템은 관련성이 없는 변화를 무시하면서 중요한 개체, 사건, 공간적 관계(Spatial Relationships), 변화, 불확실성(Uncertainty)을 식별해야 합니다. 따라서 일반적인 지각은 단순한 분류(Classification)를 넘어섭니다. 관측을 지속적인 개념과 연결하고 여러 모달리티(Modality)의 정보를 통합하여 변화하는 환경에서 추론과 행동을 지원해야 합니다.

주의(Attention)는 어떤 정보에 인지 자원(Cognitive Resources)을 할당해야 하는지를 선택하는 메커니즘을 제공합니다. 생물학적 시스템과 인공 시스템 모두 모든 순간에 동일한 깊이로 처리할 수 있는 양보다 더 많은 정보에 직면합니다. 주의는 관련성에 따라 관측, 기억, 목표, 중간 추론 상태(Intermediate Reasoning States)의 우선순위를 결정합니다. 작업, 환경, 목표가 변화함에 따라 중요한 정보도 빠르게 달라질 수 있기 때문에 일반지능에는 유연한 주의(Flexible Attention)가 필요합니다.

작업기억(Working Memory)은 현재 진행 중인 작업과 직접적으로 관련된 정보를 유지함으로써 인지 과정을 지원합니다. 작업기억을 통해 지능형 시스템은 중간 결과(Intermediate Results)를 보존하고, 대안을 비교하며, 목표를 추적하고, 여러 추론 단계에 걸쳐 증거를 통합할 수 있습니다. 효과적인 작업기억 메커니즘이 없다면 복잡한 인지는 서로 단절된 연산으로 분해될 수 있습니다. 따라서 일반지능은 추론이 진행됨에 따라 동적으로 업데이트할 수 있는 임시 표현(Temporary Representations)을 필요로 합니다.

장기기억(Long-Term Memory)은 지능이 경험을 통해 지속적으로 축적될 수 있도록 합니다. 의미기억(Semantic Memory)은 일반화된 개념과 지식을 저장하고, 일화기억(Episodic Memory)은 구체적인 경험과 맥락적 사건을 보존하며, 절차기억(Procedural Memory)은 재사용 가능한 기술과 행동 패턴을 지원합니다. 일반 인지는 기억을 수동적인 데이터베이스로 취급하는 것이 아니라 적절한 시점에 적절한 형태의 기억을 검색하고 이를 현재 관측과 통합하는 능력에 의존합니다.

학습(Learning)은 인지 시스템이 경험에 따라 자신의 표현과 행동을 수정할 수 있도록 합니다. 일반지능에는 입력에서 출력으로 이어지는 고정된 매핑(Fixed Mapping)을 학습하는 것 이상의 능력이 필요합니다. 여기에는 개념을 발견하고, 기술을 습득하며, 규칙성(Regularities)을 식별하고, 새로운 작업에 적응하며, 증거가 변화할 때 기존 믿음(Beliefs)을 업데이트하는 과정이 포함됩니다. 따라서 학습은 고립된 훈련 단계가 아니라 지각, 기억, 추론, 행동과 지속적으로 상호작용해야 합니다.

전이학습(Transfer Learning)은 하나의 작업에서 습득한 지식이 관련성이 있으면서도 이전에 경험하지 못한 문제의 성능을 향상시켜야 한다는 점에서 일반지능의 핵심적인 특징입니다. 효과적인 전이는 기존 지식 가운데 어떤 부분이 여전히 관련성이 있으며 어떤 부분을 수정해야 하는지를 식별하는 능력에 의존합니다. 지나치게 구체적인 표현은 전이를 제한하지만, 지나치게 추상적인 표현은 중요한 세부사항을 잃을 수 있습니다. 일반 인지는 재사용 가능한 구조와 작업별 적응(Task-Specific Adaptation) 사이의 균형을 필요로 합니다.

추론(Reasoning)은 지능형 시스템이 즉각적인 관측에서 직접 얻을 수 없는 결론을 도출할 수 있도록 합니다. 서로 다른 문제에는 연역(Deduction), 귀납(Induction), 유추(Analogy), 인과적 추론(Causal Reasoning), 귀추(Abduction), 반사실적 사고(Counterfactual Thinking)가 필요할 수 있습니다. 일반지능은 하나의 추론 전략이 모든 상황에서 최적이라고 가정할 수 없습니다. 문제 구조를 인식하고 이용 가능한 증거, 목표, 불확실성, 계산 자원에 따라 추론 과정을 선택하고 결합하거나 수정할 수 있어야 합니다.

인과적 인지(Causal Cognition)는 통계적 상관관계(Statistical Correlation)만으로는 환경이 변화할 때 제대로 대응하지 못할 수 있기 때문에 일반화(Generalization)에 특히 중요합니다. 하나의 사건이 다른 사건에 영향을 준다는 것을 이해하면 지능형 시스템은 개입(Intervention)의 효과를 예측하고 인과 메커니즘(Causal Mechanisms)을 우연한 연관성(Incidental Associations)과 구분할 수 있습니다. 인과 모델(Causal Models)은 설명, 계획, 진단(Diagnosis), 반사실적 추론도 지원하여 학습 과정에서 관찰한 표면적 패턴이 변화하더라도 지식이 계속 유용하게 활용되도록 합니다.

계획(Planning)은 목표를 가능한 행동의 시퀀스(Sequences of Possible Actions)와 연결함으로써 인지를 미래로 확장합니다. 일반적인 지능형 시스템은 대안적인 미래를 고려하고, 결과를 평가하고, 제약조건을 관리하며, 새로운 정보가 나타날 때 계획을 수정할 수 있어야 합니다. 계획에는 명시적 탐색(Explicit Search), 학습된 정책(Learned Policies), 계층적 분해(Hierarchical Decomposition), 시뮬레이션(Simulation) 또는 이러한 접근방식의 조합이 포함될 수 있습니다. 특정 계획 메커니즘에 고정되는 것보다 유연성이 더 중요합니다.

문제 해결(Problem Solving)은 여러 인지 과정을 목표 지향적 활동(Goal-Directed Activity)으로 통합합니다. 시스템은 문제를 표현하고, 관련 지식을 식별하고, 후보 전략(Candidate Strategies)을 생성하고, 진행상황을 평가하며, 실패를 탐지하고, 필요한 경우 접근방식을 변경해야 합니다. 따라서 일반적인 문제 해결에는 익숙한 절차를 반복적으로 적용하는 것이 아니라 인지적 유연성(Cognitive Flexibility)이 필요합니다. 새로운 문제는 이전에 학습한 개념과 기술을 학습 과정에서 경험하지 못한 새로운 구성으로 재결합해야 하는 경우가 많습니다.

메타인지(Metacognition)는 지능형 시스템이 자신의 인지 과정을 모니터링하고 조절할 수 있도록 합니다. 여기에는 불확실성을 인식하고, 해결책의 신뢰성을 평가하며, 모순(Contradictions)을 탐지하고, 추가적인 추론이 필요한지를 판단하며, 외부 정보를 요청해야 하는 시점을 결정하는 능력이 포함됩니다. 일반지능은 이러한 자기 모니터링(Self-Monitoring)을 통해 모든 문제에 동일한 방식으로 인지 자원을 사용하는 대신 문제의 난이도에 따라 자원을 적절하게 배분할 수 있습니다.

인지적 유연성(Cognitive Flexibility)은 메타인지 및 적응(Adaptation)과 밀접하게 관련되어 있습니다. 지능적인 행동을 위해서는 전략을 전환하고, 가정을 수정하며, 실패한 계획을 포기하고, 상황이 변화하면 지식을 재구성할 수 있어야 합니다. 초기 가정이 유효한 동안에만 높은 성능을 보이는 시스템은 진정한 일반성(Generality)을 갖추었다고 보기 어렵습니다. 유연한 인지는 내부 모델(Internal Models)을 고정된 구조가 아니라 관측이 기존 예상과 충돌할 때 수정할 수 있는 구조로 취급합니다.

언어(Language)는 추상적인 개념, 관계, 지시, 설명을 표현할 수 있는 상징적 매체(Symbolic Medium)를 제공함으로써 일반 인지를 확장합니다. 언어를 통해 직접적인 물리적 경험 없이도 지식을 전달할 수 있으며 복잡한 목표를 효율적으로 의사소통할 수 있습니다. 그러나 언어 능력은 지각, 기억, 행동, 세계 지식(World Knowledge)에 기반을 둘 때 더욱 유용해집니다. 이를 통해 언어의 기호(Symbols)가 언어 자체를 넘어 실제 개체, 사건, 결과와 연결될 수 있습니다.

다중모달 인지(Multimodal Cognition)는 시각(Vision), 소리(Sound), 언어, 공간적 관계, 감각운동 상호작용(Sensorimotor Interaction)의 정보를 결합하여 일반지능을 강화합니다. 서로 다른 모달리티는 동일한 세계에 대해 상호보완적인 증거를 제공합니다. 이러한 정보를 통합하면 하나의 채널에만 의존하는 것보다 더욱 강건한 표현(Robust Representations)을 생성할 수 있습니다. 교차모달 학습(Cross-Modal Learning)은 한 형태의 경험을 통해 습득한 지식이 다른 형태의 이해와 행동에도 영향을 줄 수 있도록 합니다.

체화된 인지(Embodied Cognition)는 지능이 에이전트(Agent)와 환경 사이의 관계를 통해 형성된다는 점을 강조합니다. 행동은 세계를 변화시키고, 새로운 관측은 그러한 행동의 결과를 보여주며, 그 결과로 얻은 경험은 미래의 행동을 수정합니다. 이러한 지각-행동 순환(Perception--Action Cycle)은 공간, 객체, 인과성(Causality), 행동유도성(Affordances), 행위주체성(Agency)과 같은 개념에 현실적인 기반을 제공합니다. 피지컬 AI(Physical AI)에서는 인지가 실제 세계의 동역학과 제약조건 아래에서 작동해야 하기 때문에 이러한 관계가 핵심적인 요소가 됩니다.

월드 모델(World Models)은 환경, 객체, 에이전트, 사건이 시간에 따라 어떻게 변화하는지를 표현함으로써 일반 인지를 지원할 수 있습니다. 내부 예측 모델(Internal Predictive Model)은 지능형 시스템이 행동을 실제로 실행하기 전에 가능한 결과를 시뮬레이션할 수 있도록 합니다. 따라서 월드 모델은 지각을 기억, 인과적 이해, 계획, 의사결정(Decision Making)과 연결할 수 있습니다. 월드 모델의 일반성은 익숙한 시퀀스를 단순히 재현하는 것이 아니라 여러 상황에서 재사용 가능한 구조를 얼마나 잘 표현하는지에 달려 있습니다.

사회적 인지(Social Cognition)는 일반지능에 또 다른 차원을 추가합니다. 인간과 함께 활동하는 지능형 에이전트는 의도(Intentions), 믿음(Beliefs), 선호(Preferences), 의사소통(Communication), 협력(Cooperation), 사회적 제약조건(Social Constraints)을 해석해야 합니다. 다른 에이전트의 행동은 내부 목표와 보유 정보에 따라 달라지기 때문에 이들을 단순한 수동적 물리 객체로 취급할 수 없습니다. 따라서 일반 인지는 다른 의사결정 주체에 대한 모델과 상호작용 및 협력 과정에서 자신의 행동을 적응시키는 메커니즘을 포함합니다.

일반지능은 빠른 인지 과정(Fast Cognitive Processes)과 느린 인지 과정(Slow Cognitive Processes)의 통합에도 의존합니다. 익숙한 상황은 학습된 패턴과 빠른 추론(Rapid Inference)을 통해 효율적으로 처리할 수 있지만, 익숙하지 않거나 중요한 결과를 초래할 수 있는 문제는 숙고적 탐색(Deliberate Search), 검증(Verification), 시뮬레이션, 확장된 추론(Extended Reasoning)을 필요로 할 수 있습니다. 유능한 인지 아키텍처(Cognitive Architecture)는 상황에 따라 계산량을 적응적으로 배분하여 적절할 때는 빠른 응답을 사용하고, 불확실성, 새로움(Novelty), 위험이 추가적인 노력을 정당화할 때는 더 깊은 처리를 수행해야 합니다.

궁극적으로 일반지능(General Intelligence)은 하나의 지배적인 능력이 아니라 조정된 인지(Coordinated Cognition)로부터 나타납니다. 지각은 구조화된 관측을 제공하고, 주의는 관련 정보를 선택하며, 기억은 지식과 경험을 보존하고, 학습은 적응을 가능하게 하며, 추론은 관계를 발견하고, 계획은 미래 행동을 구성하며, 메타인지는 전체 과정을 조절합니다. 일반성은 이러한 기능들이 유연하게 협력함으로써 지능이 변화하는 작업과 환경 전반에 걸쳐 전이(Transfer)되고, 적응하며, 지속적으로 효과적인 성능을 유지할 수 있을 때 형성됩니다.

## 10.02 Compositionality [w/Code]

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

구성성(Compositionality)은 복잡한 표현(Representations), 개념(Concepts), 표현식(Expressions), 행동(Behaviors)이 더 단순한 구성요소(Components)로부터 만들어질 수 있으며, 이러한 구성요소의 의미와 기능이 전체와 체계적인 관계를 유지한다는 원리입니다. 인지(Cognition)에서 구성성은 제한된 수의 재사용 가능한 요소를 이용하여 매우 광범위한 사고와 행동을 생성할 수 있도록 합니다. 일반지능(General Intelligence)에서 구성성은 가능한 모든 조합을 개별적으로 학습하지 않고도 새로운 능력을 만들어내는 메커니즘을 제공합니다.

인간 인지(Human Cognition)에서 구성성이 가장 명확하게 나타나는 영역은 언어(Language)입니다. 유한한 어휘와 제한된 수의 문법 구조(Grammatical Structures)를 이용하여 사실상 무한한 수의 의미 있는 문장을 생성할 수 있습니다. 인간은 개별 단어, 관계, 구조적 규칙에 관한 지식을 결합하기 때문에 이전에 한 번도 접하지 못한 문장도 이해할 수 있습니다. 익숙한 구성요소를 이러한 방식으로 체계적으로 재사용하는 능력은 생산적이고 유연한 지능(Productive and Flexible Intelligence)의 중요한 기반입니다.

구성성은 언어를 넘어 개념과 추론(Reasoning)으로 확장됩니다. 복잡한 개념은 보다 단순한 속성(Properties), 객체(Objects), 관계(Relations), 사건(Events)의 조합을 통해 이해할 수 있는 경우가 많습니다. 빨간색 객체, 컨테이너(Container), 공간적 포함(Spatial Inclusion)의 개념을 이해하는 사람은 정확히 동일한 구성을 이전에 경험하지 않았더라도 컨테이너 안에 있는 빨간색 객체라는 새로운 표현을 이해할 수 있습니다. 기존 지식이 재결합되어 새로운 표현을 구성하는 것입니다.

따라서 표현(Representation)은 구성적 지능(Compositional Intelligence)의 핵심입니다. 내부 표현(Internal Representations)은 구성요소를 식별하고, 조작하고, 재결합할 수 있을 만큼 충분한 구조를 보존해야 합니다. 정보가 분해할 수 없는 하나의 패턴으로만 부호화되면 체계적인 재결합(Systematic Recombination)이 어려워집니다. 반면 구조화된 표현(Structured Representations)은 개체 사이의 관계를 명시적으로 나타내어 중요한 의미적 관계(Semantic Relationships)를 유지하면서 알려진 요소들을 새로운 구성으로 변환할 수 있도록 합니다.

체계적 일반화(Systematic Generalization)는 구성성과 밀접하게 연결되어 있습니다. 하나의 맥락에서 특정 관계를 학습한 지능형 시스템(Intelligent System)은 익숙한 구성요소가 새로운 배열로 나타날 때에도 동일한 관계를 적용할 수 있는 것이 이상적입니다. 예를 들어 하나의 행동이 특정 객체 유형에 어떤 영향을 주는지를 학습하면 관련 객체나 환경으로 해당 지식을 전이할 수 있습니다. 이러한 일반화는 모든 가능한 학습 사례에 대한 의존성을 줄이고 이전에 관찰되지 않은 조합에서도 성능을 발휘하도록 합니다.

생산성(Productivity)은 구성적 구조가 만들어내는 또 다른 결과입니다. 상대적으로 적은 수의 원시 요소(Primitives)라도 재귀적으로 결합(Recursively Combined)할 수 있다면 매우 큰 표현과 행동의 가능 공간을 지원할 수 있습니다. 이러한 원리는 언어, 수학(Mathematics), 프로그래밍(Programming), 계획(Planning), 운동 행동(Motor Behavior)에서 나타납니다. 따라서 일반지능은 가능한 모든 상황에 대해 별도의 해결책을 저장하는 대신 재사용 가능한 구조를 통해 높은 표현력(Expressive Power)을 확보할 수 있습니다.

계층적 표현(Hierarchical Representation)은 정보를 여러 추상화 수준(Levels of Abstraction)으로 구성함으로써 구성성을 강화합니다. 하위 수준 특징(Low-Level Features)은 객체로 결합되고, 객체는 관계로, 관계는 사건으로, 사건은 더 큰 상황이나 계획으로 결합될 수 있습니다. 이와 유사하게 행동은 기술(Skills)로, 기술은 하위 작업(Subtasks)으로, 하위 작업은 임무(Missions)로 구성될 수 있습니다. 계층적 구성(Hierarchical Composition)은 현재 문제에 가장 적절한 수준에서 추론할 수 있도록 합니다.

추상화(Abstraction)는 구성요소가 서로 다른 맥락으로 전이될 수 있도록 합니다. 지지(Support), 포함(Containment), 이동(Movement), 소유(Ownership), 인과관계(Causation)와 같은 개념은 다양한 개체와 환경에 적용될 수 있습니다. 관계적 구조(Relational Structure)를 구체적인 표면적 세부사항(Surface Details)과 분리함으로써 인지 시스템은 익숙하지 않은 상황에서도 지식을 재사용할 수 있습니다. 효과적인 추상화는 세부사항을 완전히 제거하는 것이 아니라 관련성이 없는 변화를 무시하면서 개념이 유용성을 유지하는 데 필요한 정보를 보존합니다.

변수 바인딩(Variable Binding)은 구성적 표현에 서로 다른 개체가 채울 수 있는 역할(Roles)이 포함될 때 중요합니다. "A가 B를 C에게 준다"와 같은 관계는 서로 다른 사람이나 객체가 각각의 역할을 차지하더라도 그 구조를 유지합니다. 인지 시스템은 관계적 패턴(Relational Pattern)과 해당 패턴에 할당된 구체적인 값(Values)을 구별할 수 있어야 합니다. 따라서 유연한 변수 바인딩(Flexible Variable Binding)은 관계적 추론(Relational Reasoning), 언어 이해(Language Understanding), 계획, 구조적으로 유사한 상황 사이의 전이를 지원합니다.

관계적 추론(Relational Reasoning)은 구성적 표현을 직접적으로 기반으로 합니다. 많은 문제에서는 개별 객체를 인식하는 것만으로 충분하지 않으며 객체들이 어떻게 연결되어 있는지가 핵심 정보가 됩니다. 공간적 관계(Spatial Relationships), 시간적 순서(Temporal Order), 인과적 의존관계(Causal Dependencies), 사회적 역할(Social Roles), 논리적 관계(Logical Relations)는 모두 구조화된 추론을 필요로 합니다. 구성적 인지는 이러한 관계를 관련된 특정 개체와 분리하여 표현하고 조작할 수 있도록 합니다.

유추적 추론(Analogical Reasoning)은 구성적 일반화(Compositional Generalization)를 보여주는 강력한 사례입니다. 유추(Analogy)는 표면적으로 매우 다르게 보일 수 있는 상황 사이에서 구조적 유사성(Structural Similarity)을 식별합니다. 구성요소 사이의 관계가 명시적으로 표현되어 있다면 익숙한 영역의 지식을 새로운 영역으로 매핑(Mapping)할 수 있습니다. 이를 통해 객체와 상황이 달라지더라도 이전의 해결책, 인과 모델(Causal Models), 전략을 새로운 문제의 추론에 활용할 수 있습니다.

인과적 추론(Causal Reasoning) 역시 복잡한 사건을 상호작용하는 원인(Causes), 메커니즘(Mechanisms), 조건(Conditions), 결과(Effects)로 분해할 수 있기 때문에 구성적 구조의 이점을 얻습니다. 지능형 시스템은 전체 사건 시퀀스를 암기하는 대신 재사용 가능한 인과관계를 학습하고 새로운 상황을 분석할 때 이를 다시 결합할 수 있습니다. 이러한 표현은 환경이 이전에 관찰한 사례와 달라지더라도 개입(Intervention), 진단(Diagnosis), 예측(Prediction), 반사실적 추론(Counterfactual Reasoning)을 지원할 수 있습니다.

계획(Planning)은 복잡한 목표가 일반적으로 더 작은 행동과 하위 목표(Subgoals)의 조합을 통해 달성되기 때문에 본질적으로 구성적입니다. 장기 작업(Long-Horizon Task)은 관리 가능한 여러 단계로 분해될 수 있으며 각 단계에서는 재사용 가능한 기술이나 정책(Policies)을 활용할 수 있습니다. 계층적 계획(Hierarchical Planning)은 가능한 모든 하위 수준 행동을 직접 탐색하는 복잡성을 줄입니다. 또한 목표나 환경 조건이 변화할 때 이전에 학습된 기술을 새로운 계획으로 재구성할 수 있도록 합니다.

절차적 지식(Procedural Knowledge)도 이와 유사하게 재사용 가능한 기술의 조합으로 구성될 수 있습니다. 내비게이션(Navigation), 파지(Grasping), 객체 인식(Object Recognition), 문 조작(Door Manipulation), 배치(Placement)를 각각 학습한 로봇은 이러한 능력을 조합하여 학습 과정에서 하나의 시연(Demonstration)으로 제공되지 않았던 작업을 수행할 수 있습니다. 따라서 기술 구성(Skill Composition)은 가능한 작업과 환경 구성이 너무 많아 모든 경우를 종단간 학습(End-to-End Training)하는 것이 현실적으로 어려운 피지컬 AI(Physical AI)에서 특히 중요합니다.

구성적 학습(Compositional Learning)은 모든 작업을 서로 관련이 없는 것으로 취급하기보다 재사용 가능한 구성요소를 발견하려고 합니다. 이러한 구성요소에는 개념, 특징(Features), 기술, 정책, 서브루틴(Subroutines), 객체 표현(Object Representations), 관계적 구조 등이 포함될 수 있습니다. 기존에 습득한 구성요소를 처음부터 다시 구축하는 대신 재사용할 수 있다면 학습 효율성이 향상됩니다. 새로운 작업은 기존 지식의 새로운 조합과 실제로 새롭게 습득해야 하는 정보의 결합으로 표현될 수 있습니다.

신경망(Neural Networks)은 일부 구성적 특성을 나타내는 분산 표현(Distributed Representations)을 학습할 수 있지만 체계적인 구성(Systematic Composition)은 여전히 어려운 문제입니다. 모델은 학습 과정에서 나타난 것과 유사한 조합에서는 높은 성능을 보이지만 익숙한 요소들이 새로운 구조로 등장할 경우 실패할 수 있습니다. 이러한 차이는 통계적 보간(Statistical Interpolation)과 더욱 강력한 구성적 일반화 사이의 차이를 보여줍니다. 아키텍처(Architecture), 학습 데이터, 목적함수(Objectives), 기억, 추론 메커니즘 모두 이러한 능력에 영향을 줄 수 있습니다.

신경-기호 접근법(Neuro-Symbolic Approaches)은 유연하게 학습된 표현과 명시적인 구조적 연산(Structured Operations)을 결합하는 하나의 방법을 탐구합니다. 신경망 구성요소는 지각, 표현학습(Representation Learning), 패턴 인식(Pattern Recognition)을 지원하고, 기호적 또는 구조화된 메커니즘은 변수, 규칙(Rules), 관계, 체계적인 조작을 지원할 수 있습니다. 목표는 반드시 고전적 기호 AI(Classical Symbolic AI)를 그대로 재현하는 것이 아니라 통계적 학습과 재사용 가능하고 해석 가능한 구조를 결합하는 표현을 확보하는 것입니다.

언어 모델(Language Models)은 개념, 지시, 언어 구조의 새로운 조합을 생성하고 해석할 수 있기 때문에 상당한 구성적 능력을 보여줍니다. 그러나 성공적인 언어적 구성(Linguistic Composition)이 모든 영역에서 신뢰할 수 있는 구성적 추론을 보장하는 것은 아닙니다. 모델은 여전히 표면적 패턴, 익숙하지 않은 조합, 문제 구조의 변화에 민감할 수 있습니다. 따라서 구성성을 평가하려면 학습 과정에서 강조된 조합과 의도적으로 다른 새로운 조합을 시험해야 합니다.

월드 모델(World Models)은 객체, 에이전트(Agents), 관계, 동역학(Dynamics), 사건에 대한 구성적 표현을 통해 이점을 얻을 수 있습니다. 환경을 하나의 구분되지 않은 상태(Undifferentiated State)로 표현하는 대신 구조화된 월드 모델(Structured World Model)은 개체와 그 상호작용을 각각 분리하여 표현할 수 있습니다. 이러한 요인화(Factorization)는 익숙한 객체가 새로운 구성으로 등장할 때 예측의 전이를 지원할 수 있습니다. 또한 재사용 가능한 상호작용과 변화 모델을 이용하여 시뮬레이션된 미래를 구성함으로써 계획을 지원할 수 있습니다.

다중모달 인지(Multimodal Cognition)는 서로 다른 모달리티에 걸쳐 정보를 구성해야 한다는 추가적인 과제를 제시합니다. 하나의 개념은 언어적 설명(Linguistic Description), 시각적 외형(Visual Appearance), 공간적 위치(Spatial Location), 소리(Sound), 물리적 속성(Physical Properties), 가능한 행동과 연결될 수 있습니다. 교차모달 구성(Cross-Modal Composition)은 지능형 시스템이 이러한 서로 다른 정보원을 하나의 일관된 표현(Coherent Representation)으로 결합하도록 합니다. 이는 언어 지시를 지각, 계획, 물리적 행동으로 변환해야 하는 체화된 에이전트(Embodied Agents)에서 특히 중요합니다.

구성성은 현실 세계에 존재하는 가능한 상황의 수가 어떠한 학습 데이터셋도 모두 열거할 수 없을 정도로 방대하기 때문에 일반지능에서 특히 중요합니다. 따라서 지능형 시스템은 이전에 획득한 지식을 재구성하여 새로운 문제를 해결해야 합니다. 개념, 관계, 기억(Memories), 기술, 계획은 재사용 가능한 인지적 구성요소(Cognitive Building Blocks)가 됩니다. 이에 따라 일반화는 익숙한 패턴을 인식하는 것뿐만 아니라 익숙한 구성요소로부터 적절한 새로운 조합을 만들어내는 능력에 의존합니다.

구성성의 평가(Evaluation)는 일반적인 홀드아웃 사례(Held-Out Examples)만이 아니라 체계적인 새로움(Systematic Novelty)을 시험해야 합니다. 유용한 평가는 익숙한 구성요소와 익숙하지 않은 조합을 분리하고 구조가 변화했을 때에도 시스템이 학습한 관계를 유지하는지를 확인할 수 있습니다. 평가에는 새로운 언어적 구조, 새로운 객체-관계 조합(Object--Relation Combinations), 관찰되지 않은 기술 시퀀스(Unseen Sequences of Skills), 변경된 인과 구조(Causal Structures), 기존 능력을 이전에 관찰되지 않은 방식으로 조립해야 하는 작업 등이 포함될 수 있습니다.

궁극적으로 구성성(Compositionality)은 제한된 경험(Limited Experience)과 개방형 지능(Open-Ended Intelligence)을 연결하는 가교를 제공합니다. 지식을 재사용 가능한 구성요소와 관계로 표현함으로써 인지 시스템은 모든 가능성을 개별적으로 학습하지 않고도 새로운 개념, 해석, 계획, 행동을 생성할 수 있습니다. AGI(Artificial General Intelligence)에서 이러한 능력은 추상화, 전이, 체계적 일반화, 추론, 계획, 지속학습(Continual Learning)의 핵심 기반이며, 학습 과정에서 명시적으로 표현된 적이 없는 상황에서도 지능이 새로운 해결책을 구성할 수 있도록 합니다.

## 10.03 Causal Modeling [w/Code]

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

인과 모델링(Causal Modeling)은 사건, 변수, 행동, 환경 조건이 원인과 결과의 관계(Cause-and-Effect Relationships)를 통해 서로에게 어떠한 영향을 미치는지를 표현하는 과정입니다. 관측 사이의 연관성(Associations)을 식별하는 순수한 통계적 모델링(Statistical Modeling)과 달리, 인과 모델링은 변화가 발생하는 원인이 되는 메커니즘(Mechanisms)을 설명하려고 합니다. 일반지능(General Intelligence)에서 이러한 구분은 매우 중요합니다. 지능적 행동(Intelligent Behavior)은 에이전트가 세계에 능동적으로 개입(Intervention)할 때 어떤 일이 발생할지를 예측해야 하는 경우가 많기 때문입니다.

상관관계(Correlation)만으로는 하나의 변수를 변화시키는 것이 다른 변수의 변화를 발생시키는지를 판단할 수 없습니다. 두 변수는 하나가 다른 하나의 원인이기 때문에 함께 나타날 수도 있고, 인과 방향(Causal Direction)이 반대일 수도 있으며, 두 변수 모두 숨겨진 요인(Hidden Factor)의 영향을 받을 수도 있습니다. 따라서 인과적 추론(Causal Reasoning)은 변수들이 서로 관련되어 있는지를 넘어서는 더 강력한 질문을 제기합니다. 즉 시스템의 관련 요소들을 통제하면서 특정 변수를 의도적으로 변경한다면 어떤 일이 발생할 것인지를 묻습니다.

인과 모델(Causal Model)은 변수들과 함께 이들이 서로에게 어떠한 영향을 미치는지를 설명하는 방향성 관계(Directional Relationships)를 표현합니다. 이러한 관계는 일반적으로 인과 그래프(Causal Graphs)를 사용하여 표현할 수 있으며, 여기에서 노드(Nodes)는 변수를 나타내고 방향성 간선(Directed Edges)은 인과적 의존관계(Causal Dependencies)를 나타냅니다. 이러한 구조를 통해 지능형 시스템(Intelligent System)은 원인과 결과를 구분하고 하나의 개입이 더 큰 시스템 전체에 어떠한 경로를 통해 전파될 수 있는지를 추론할 수 있습니다.

구조적 인과 모델(Structural Causal Models)은 이러한 관계를 기술하기 위한 형식적 프레임워크(Formal Framework)를 제공합니다. 변수들은 각 변수가 직접적인 원인(Direct Causes)과 기타 관련 요인으로부터 어떻게 생성되는지를 정의하는 구조 방정식(Structural Equations)을 통해 연결됩니다. 이러한 표현은 인과 메커니즘(Causal Mechanism)을 시스템에서 수집된 특정 관측과 분리합니다. 그 결과 모델은 관측 데이터(Observational Data)에 직접적으로 표현되지 않은 상황에 대해서도 추론을 지원할 수 있습니다.

개입(Intervention)은 인과 모델링의 핵심 개념입니다. 두 사건이 함께 발생하는 것을 관찰하는 것과 그중 하나를 능동적으로 변화시키고 그 결과를 측정하는 것은 근본적으로 다릅니다. 개입 기반 추론(Intervention-Based Reasoning)은 에이전트가 변수를 수정하거나, 행동을 선택하거나, 새로운 조건을 부과했을 때 시스템이 어떻게 작동할 것인지를 질문합니다. 이러한 능력은 인과 모델링을 의사결정(Decision Making), 실험(Experimentation), 계획(Planning), 제어(Control)와 직접적으로 연결합니다.

반사실적 추론(Counterfactual Reasoning)은 이미 발생한 사건의 대안적인 형태를 고려함으로써 인과 분석을 확장합니다. 시스템은 다른 행동을 선택했다면 어떤 일이 발생했을지, 환경 조건이 달라졌다면 결과가 어떻게 변화했을지, 또는 특정 원인이 존재하지 않았다면 어떤 결과가 나타났을지를 질문할 수 있습니다. 반사실(Counterfactuals)은 관찰된 결과를 인과 모델이 생성한 가능한 대안과 비교하기 때문에 설명(Explanation), 진단(Diagnosis), 책임 분석(Responsibility Analysis), 경험으로부터의 학습을 지원합니다.

인과 발견(Causal Discovery)은 데이터, 개입, 사전 지식(Prior Knowledge), 또는 이러한 정보원의 조합으로부터 인과 구조(Causal Structure)를 추론하려고 합니다. 관측 데이터만으로는 여러 서로 다른 인과적 설명이 동일하게 가능할 수 있기 때문에 이는 어려운 작업입니다. 시간적 순서(Temporal Ordering), 독립성 관계(Independence Relationships), 도메인 제약조건(Domain Constraints), 실험, 능동적 탐색(Active Exploration)을 통해 이러한 모호성을 줄일 수 있습니다. 따라서 지능형 시스템은 발견된 모든 관계를 확실한 것으로 간주하기보다 인과 구조에 대한 불확실성(Uncertainty)을 표현해야 합니다.

교란(Confounding)은 인과 추론(Causal Inference)의 주요 문제 가운데 하나입니다. 숨겨져 있거나 통제되지 않은 변수가 겉으로 보이는 원인과 관찰된 결과 모두에 영향을 주어 오해를 일으키는 연관성을 생성할 수 있습니다. 이러한 교란 요인(Confounding Factors)을 무시하면 지능형 시스템은 실제 배포(Deployment) 환경에서 효과가 없는 개입을 선택할 수 있습니다. 따라서 인과 모델링에서는 어떤 변수가 관찰되고, 어떤 변수가 통제되며, 어떤 변수가 잠재 변수(Latent Variables)로 남아 있을 수 있는지를 신중하게 고려해야 합니다.

시간적 추론(Temporal Reasoning)은 원인이 일반적으로 결과보다 먼저 발생하기 때문에 중요한 정보를 제공합니다. 그러나 시간적 순서만으로 인과성을 확립할 수 있는 것은 아닙니다. 동적 시스템(Dynamic Systems)은 지연된 효과(Delayed Effects), 피드백 루프(Feedback Loops), 누적 영향(Accumulated Influences), 여러 시간 규모(Multiple Timescales)에서 작동하는 상호작용을 포함할 수 있습니다. 따라서 지능형 에이전트를 위한 인과 모델은 어떤 변수들이 서로에게 영향을 미치는지뿐만 아니라 그러한 영향이 언제, 어느 정도의 기간에 걸쳐 중요해지는지도 표현해야 합니다.

메커니즘적 이해(Mechanistic Understanding)는 인과적 일반화(Causal Generalization)를 강화합니다. 지능형 시스템이 특정 관계가 왜 발생하는지를 이해한다면 주변 환경이 변화했을 때에도 해당 메커니즘이 계속 유효할 가능성이 있는지를 판단할 수 있습니다. 통계적 패턴(Statistical Patterns)은 분포 변화(Distribution Shift)에서 사라질 수 있지만 근본적인 물리적 또는 기능적 메커니즘은 안정적으로 유지될 수 있습니다. 따라서 인과적 표현(Causal Representations)은 표면적인 규칙성에만 기반한 연관성보다 환경 사이에서 더욱 강건한 전이(Robust Transfer)를 지원할 수 있습니다.

인과적 추상화(Causal Abstraction)는 복잡한 시스템을 서로 다른 세부 수준(Levels of Detail)에서 표현할 수 있도록 합니다. 하위 수준의 물리적 상호작용은 상위 수준의 사건으로 요약될 수 있으며, 세부적인 행동 시퀀스는 기능적 인과관계(Functional Causal Relationships)로 표현될 수 있습니다. 적절한 추상화 수준은 작업에 따라 달라집니다. 효과적인 지능은 모든 미시적인 세부사항을 모델링하지 않으면서도 예측과 개입에 필요한 인과 정보를 보존하고 필요에 따라 서로 다른 수준 사이를 이동할 수 있어야 합니다.

인과적 추론은 복잡한 인과 시스템을 재사용 가능한 메커니즘으로 분해할 수 있기 때문에 구성성(Compositionality)과 밀접하게 관련되어 있습니다. 지능형 시스템은 개별 구성요소가 어떻게 작동하는지를 학습한 다음 이러한 구성요소의 새로운 조합에 대해 추론할 수 있습니다. 인과 메커니즘이 충분히 안정적으로 유지된다면 이전에 학습한 관계를 익숙하지 않은 구성에서 다시 결합할 수 있으며, 이를 통해 학습 과정에서 직접 경험하지 않은 상황으로 체계적 일반화(Systematic Generalization)를 수행할 수 있습니다.

월드 모델(World Models)은 수동적인 예측을 넘어가기 위해 인과 구조를 포함할 수 있습니다. 예측 모델(Predictive Model)은 이전 관측으로부터 다음 상태를 추정할 수 있지만, 인과적 월드 모델(Causal World Model)은 행동, 상호작용, 환경 메커니즘으로 인해 상태가 어떻게 변화하는지를 표현하려고 합니다. 이러한 차이는 에이전트가 가능한 행동 중 하나를 선택해야 할 때 중요합니다. 계획에는 단순히 가능성이 높은 관측을 예측하는 것이 아니라 개입이 가져올 결과를 추정하는 능력이 필요하기 때문입니다.

계획(Planning)은 행동이 예상되는 효과에 따라 선택되기 때문에 자연스럽게 인과 모델에 의존합니다. 목표를 달성하기 위해 에이전트는 원하는 결과에서 해당 결과를 만들어낼 수 있는 행동으로 역방향 추론(Backward Reasoning)을 수행하고, 후보 행동에서 가능한 결과로 순방향 추론(Forward Reasoning)을 수행해야 합니다. 인과 구조는 어떤 변수가 목표에 영향을 줄 수 있는지와 어떤 행동이 원하는 결과에 영향을 미칠 가능성이 낮은지를 식별함으로써 탐색 공간(Search Space)을 줄여줍니다.

강화학습(Reinforcement Learning) 역시 인과 모델링과 상호작용합니다. 전통적인 강화학습은 인과 구조를 명시적으로 표현하지 않고도 반복적인 상호작용을 통해 성공적인 정책(Policies)을 학습할 수 있습니다. 그러나 인과 지식(Causal Knowledge)은 에이전트가 행동이 왜 성공하거나 실패하는지를 이해하도록 지원함으로써 샘플 효율성(Sample Efficiency), 전이(Transfer), 탐색(Exploration), 적응(Adaptation)을 향상시킬 수 있습니다. 에이전트는 각각의 새로운 환경을 완전히 별개의 문제로 취급하는 대신 작업 간에 안정적으로 유지되는 메커니즘을 재사용할 수 있습니다.

능동학습(Active Learning)과 실험(Experimentation)은 인과 지식을 획득하는 강력한 방법을 제공합니다. 지능형 에이전트는 즉각적인 보상(Immediate Rewards)을 얻기 위해서뿐만 아니라 환경이 어떻게 작동하는지에 대한 불확실성을 줄이기 위해 행동을 선택할 수 있습니다. 신중하게 선택된 개입은 수동적 관찰보다 서로 경쟁하는 인과 가설(Causal Hypotheses)을 더욱 효율적으로 구별할 수 있습니다. 이는 호기심(Curiosity), 탐색, 과학적 추론(Scientific Reasoning), 자율학습(Autonomous Learning) 사이의 연결을 형성합니다.

인과 모델은 로봇이 지속적으로 물리적 세계에 개입하기 때문에 피지컬 AI(Physical AI)에서 특히 중요합니다. 로봇은 밀기(Pushing), 파지(Grasping), 가속(Accelerating), 제동(Braking), 회전(Turning), 객체 조작(Manipulation)이 환경을 어떻게 변화시킬지를 예측해야 합니다. 이러한 효과는 물리적 속성(Physical Properties), 접촉 관계(Contact Relationships), 기하학(Geometry), 동역학(Dynamics), 불확실성에 따라 달라집니다. 따라서 신뢰할 수 있는 행동을 위해서는 행동과 그 행동이 발생시킬 가능성이 높은 물리적 결과를 연결하는 모델이 필요합니다.

행동유도성(Affordances)은 행동, 객체, 결과 사이의 인과관계를 통해 부분적으로 이해할 수 있습니다. 특정 객체를 파지하거나, 이동하거나, 열거나, 통과할 수 있는 것은 적절한 조건에서 특정 행동이 특정 상태 변화(State Changes)를 만들어낼 수 있기 때문입니다. 이러한 관계를 학습하면 로봇은 익숙하지 않은 객체나 환경에서 무엇을 할 수 있는지를 추론할 수 있습니다. 따라서 인과적 행동유도성 모델(Causal Affordance Models)은 지각을 행동 가능성(Action Possibilities) 및 계획과 직접적으로 연결합니다.

다중 에이전트 환경(Multi-Agent Environments)은 다른 의사결정 주체와 관련된 인과관계를 추가합니다. 하나의 에이전트 행동은 다른 에이전트가 무엇을 관측하고, 믿고, 의도하고, 다음에 행동하는지를 변화시킬 수 있습니다. 다른 에이전트는 자신의 목표와 정보에 따라 반응하기 때문에 이러한 상호작용을 모델링하려면 물리적 동역학 이상의 것이 필요합니다. 인과적 추론은 직접적인 물리 효과(Physical Effects)와 상호작용을 통해 발생하는 전략적 또는 사회적 효과(Strategic or Social Effects)를 구분하는 데 도움을 줄 수 있습니다.

인과 모델은 설명이 일반적으로 어떤 요인이 결과를 발생시켰는지를 식별하는 과정과 관련되기 때문에 설명가능성(Explainability)도 향상시킬 수 있습니다. 시스템은 단순히 예측이 생성되었다고 보고하는 대신 결과에 영향을 준 조건, 관련 인과 경로(Causal Pathways), 결과를 변화시킬 수 있는 가능한 개입을 설명할 수 있습니다. 반사실적 설명(Counterfactual Explanations)은 특정 조건이나 행동이 달라졌을 때 결과가 어떻게 변화할 수 있는지를 보여주기 때문에 특히 유용합니다.

인과 모델링의 평가(Evaluation)는 동일한 분포에서 추출된 데이터에 대한 예측 정확도(Predictive Accuracy)만을 시험해서는 안 됩니다. 모델은 익숙한 관측을 정확하게 예측하면서도 근본적인 인과 구조를 잘못 표현할 수 있습니다. 보다 강력한 평가는 개입 결과 예측(Intervention Prediction), 반사실적 추론, 분포 변화에서의 전이, 인과관계 복원(Recovery of Causal Relationships), 변화된 메커니즘에 대한 적응, 그리고 학습 과정의 상관관계가 더 이상 신뢰할 수 없는 상황에서의 계획 능력을 포함합니다.

실제 환경에서는 모든 메커니즘에 관한 완전한 증거를 얻기 어렵기 때문에 인과 지식 역시 불확실성과 함께 표현되어야 합니다. 여러 인과 가설이 동시에 타당할 수 있고, 숨겨진 변수가 존재할 수 있으며, 메커니즘 자체가 시간에 따라 변화할 수도 있습니다. 따라서 지능형 시스템은 하나의 설명에 성급하게 확정적으로 의존하기보다 인과적 추론을 확률적 추론(Probabilistic Inference), 불확실성 추정(Uncertainty Estimation), 추가적인 관측, 실험과 결합해야 합니다.

AGI(Artificial General Intelligence)에서 인과 모델링은 단순한 패턴 인식(Pattern Recognition)에서 행동과 사건이 세계를 어떻게 변화시키는지를 이해하는 방향으로 발전하기 위한 기반을 제공합니다. 일반지능은 일반적으로 어떤 일이 발생하는지를 인식하는 것뿐만 아니라 왜 그러한 일이 발생하는지, 개입한다면 어떤 일이 발생할지, 다른 조건이었다면 어떤 일이 발생했을지를 추론할 수 있어야 합니다. 인과 모델은 지각(Perception), 기억(Memory), 추론, 월드 모델, 계획, 학습, 행동(Action)을 적응형 지능(Adaptive Intelligence)을 위한 하나의 통합된 프레임워크로 연결합니다.

## 10.04 Common Sense Reasoning [w/Code]

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

상식 추론(Common Sense Reasoning)은 사람들이 일반적으로 명시하지 않는 배경 지식(Background Knowledge)을 활용하여 일상적인 상황에 대해 타당한 판단을 내리는 능력을 의미합니다. 인간은 지지되지 않은 물체가 떨어질 수 있고, 용기가 물건을 담을 수 있으며, 사람은 일반적으로 목표에 따라 행동하고, 사건에는 통상적인 결과가 따른다는 사실을 자연스럽게 이해합니다. AGI(Artificial General Intelligence)에서 상식은 모든 사실을 명시적으로 지정하지 않아도 불완전한 지시와 익숙하지 않은 상황을 해석하는 데 필요한 암묵적 지식(Implicit Knowledge)을 제공합니다.

상식 지식(Common Sense Knowledge)의 상당 부분은 물리적·사회적 세계와 반복적으로 상호작용하면서 점진적으로 학습됩니다. 인간은 이러한 원리를 공식적으로 설명할 수 있게 되기 훨씬 전부터 객체, 공간, 시간, 행동, 의도(Intentions), 수량(Quantities), 원인(Causes), 사회적 행동에 관한 기대를 습득합니다. 이러한 지식은 빠른 추론을 지원하는 배경 모델(Background Model)이 됩니다. 인공 시스템이 좁게 정의된 작업을 벗어나 효과적으로 추론하려면 이와 유사한 메커니즘이 필요합니다.

상식은 전문적인 사실보다 일상적인 규칙성(Ordinary Regularities)을 다룬다는 점에서 백과사전적 지식(Encyclopedic Knowledge)과 다릅니다. 물의 화학적 조성을 아는 것은 사실적 지식(Factual Knowledge)이지만, 쏟아진 물이 바닥을 젖게 하고 미끄럽게 만들 수 있다는 것을 이해하는 것은 상식입니다. 따라서 지능형 시스템(Intelligent Systems)은 명시적인 사실뿐만 아니라 가능성이 높은 결과, 일반적인 조건, 행동유도성(Affordances), 예외(Exception), 그리고 문서에 거의 명시되지 않는 관계도 표현할 수 있어야 합니다.

물리적 상식(Physical Common Sense)은 객체와 환경이 일반적으로 어떻게 행동하는지에 관한 지식을 다룹니다. 여기에는 중력(Gravity), 고체성(Solidity), 지지(Support), 포함(Containment), 운동(Motion), 충돌(Collision), 균형(Balance), 거리(Distance), 물질 특성(Material Properties)에 관한 기대가 포함됩니다. 안정적인 테이블 위에 놓인 컵은 일반적으로 그 위치에 유지되지만 지지되지 않은 객체는 떨어질 수 있습니다. 피지컬 AI(Physical AI)는 로봇이 객체를 조작하거나 환경을 탐색하기 전에 현실 세계에서 발생할 결과를 예상해야 하기 때문에 이러한 추론에 크게 의존합니다.

공간적 상식(Spatial Common Sense)은 지능형 시스템이 위치, 방향, 포함 관계, 접근 가능성(Accessibility), 가시성(Visibility), 이동에 대해 추론할 수 있도록 합니다. 닫힌 캐비닛 내부에 있는 객체에 즉시 접근하기 어려울 수 있다는 사실을 이해하려면 객체 자체를 인식하는 것 이상의 능력이 필요합니다. 공간 추론(Spatial Reasoning)은 기하학적 정보(Geometric Information)를 장애물, 개구부(Openings), 경로(Paths), 방향(Orientation), 공간 관계를 변경하는 데 필요한 행동과 같은 실질적인 제약조건과 결합해야 합니다.

시간적 상식(Temporal Common Sense)은 시간에 따른 사건 사이의 일반적인 관계를 다룹니다. 원인은 일반적으로 결과보다 먼저 발생하고, 행동에는 일정한 시간이 필요하며, 일부 사건은 동시에 발생할 수 없고, 상태는 변화가 일어나기 전까지 지속될 수 있습니다. 지능형 시스템은 이전에 무엇이 발생했는지, 현재 무엇이 발생하고 있는지, 다음에 무엇이 발생할 가능성이 있는지를 추론해야 합니다. 시간적 기대(Temporal Expectations)는 현재 행동과 지연되거나 장기적인 결과를 연결함으로써 계획(Planning)도 지원합니다.

인과적 상식(Causal Common Sense)은 시스템이 일상적인 사건이 왜 발생하고 어떤 행동이 이를 변화시킬 가능성이 있는지를 이해하도록 합니다. 손잡이를 돌리면 문이 열릴 수 있고, 불안정한 객체를 밀면 이동하거나 넘어질 수 있으며, 지지대를 제거하면 다른 객체의 위치가 변할 수 있습니다. 이러한 추론에 모든 경우마다 완전한 물리 시뮬레이션(Physical Simulation)이 필요한 것은 아닙니다. 근사적인 인과 지식(Approximate Causal Knowledge)만으로도 빠른 의사결정(Decision Making)에 충분히 유용한 예측을 제공할 수 있습니다.

객체 상식(Object Common Sense)은 익숙한 개체(Entity)의 일반적인 속성(Properties), 기능(Functions), 행동유도성에 관한 지식을 포함합니다. 의자는 일반적으로 사람이 앉는 것을 지지할 수 있고, 용기는 객체를 담을 수 있으며, 문은 공간 사이의 접근을 제공할 수 있고, 도구(Tool)는 특정 행동을 가능하게 할 수 있습니다. 이러한 기대를 통해 명시적인 지시가 불완전하더라도 지능은 가능한 사용 방법을 추론할 수 있습니다. 또한 익숙하지 않은 객체가 알려진 범주와 기능적 속성을 공유할 때 지식을 전이(Transfer)하는 데에도 도움이 됩니다.

사회적 상식(Social Common Sense)은 사람들이 다른 사람들과 상호작용할 때 일반적으로 어떻게 행동하는지를 다룹니다. 인간은 의도, 믿음(Beliefs), 감정(Emotions), 관습(Conventions), 협력(Cooperation), 소유권(Ownership), 예의(Politeness), 약속(Promises), 사회적 기대(Social Expectations)에 대해 추론합니다. 인간과 상호작용하는 시스템은 사람이 무엇을 알고, 원하고, 적절하다고 생각할 가능성이 있는지를 추론해야 하는 경우가 많습니다. 이러한 추론은 불확실하며 문화에 따라 달라질 수 있으므로 사회적 상식은 경직된 보편적 규칙보다 유연한 기대를 지원해야 합니다.

목표 추론(Goal Reasoning)은 인간의 행동이 일반적으로 목적(Purpose)과 관련하여 해석되기 때문에 사회적 상식과 밀접하게 연결됩니다. 사람이 컵을 향해 손을 뻗으면 관찰자는 그 움직임을 임의의 궤적(Arbitrary Trajectory)으로 취급하기보다 컵을 잡거나 사용하려는 의도로 추론할 수 있습니다. 지능형 시스템 역시 목표를 이용하여 관측을 설명하고 미래 행동을 예측할 수 있습니다. 이러한 추론은 협업(Collaboration), 지원(Assistance), 인간-에이전트 팀워크(Human--Agent Teamwork)에서 중요합니다.

기본값 추론(Default Reasoning)은 완전한 정보를 이용할 수 없을 때에도 상식 시스템이 유용한 결론을 내릴 수 있도록 합니다. 기본값(Default)은 반대되는 증거가 존재하지 않는 한 일반적으로 참이라고 가정하는 것을 의미합니다. 예를 들어 닫힌 용기는 일반적으로 내부의 내용물을 유지한다고 가정할 수 있지만 구멍이 발견되면 이러한 기대를 수정해야 합니다. 따라서 상식에는 새로운 증거가 기존 결론과 모순될 경우 결론을 철회할 수 있는 취소 가능한 추론(Defeasible Reasoning)이 필요합니다.

비단조 추론(Non-Monotonic Reasoning)은 이러한 결론 수정 능력을 형식화합니다. 고전적인 단조 논리(Monotonic Logic)에서는 새로운 정보를 추가해도 이전의 추론 결과가 무효화되지 않습니다. 그러나 일상적인 추론은 새로운 관측이 기존의 믿음을 자주 변화시키기 때문에 다르게 작동합니다. 지능형 에이전트(Intelligent Agent)는 처음에는 특정 경로를 이용할 수 있다고 추론했다가 장애물을 발견하면 해당 결론을 철회할 수 있습니다. 일반지능에는 전체 지식 구조를 처음부터 다시 구축하지 않고도 믿음을 업데이트하는 이러한 능력이 필요합니다.

불확실성(Uncertainty)은 일상적인 지식이 절대적인 법칙보다 경향(Tendencies)을 설명하는 경우가 많기 때문에 상식의 기본적인 특성입니다. 사람은 일반적으로 문을 통해 이동하고, 객체는 대체로 놓인 위치에 유지되며, 개인은 흔히 일관된 목표를 추구하지만 예외는 발생합니다. 따라서 상식 추론은 정성적인 기대(Qualitative Expectations)를 불확실성 추정(Uncertainty Estimates)과 결합하여 시스템이 확실한 것, 가능성이 높은 것, 단지 개연성이 있는 것, 근거가 없는 것을 구별할 수 있도록 해야 합니다.

귀추(Abduction)는 상식이 관측에 대한 가장 타당한 설명을 추론해야 하는 경우가 많기 때문에 중요한 역할을 합니다. 바닥이 젖어 있다면 물을 쏟았거나, 청소했거나, 열린 공간을 통해 빗물이 들어오는 등 여러 설명이 가능할 수 있습니다. 귀추적 추론(Abductive Reasoning)은 후보 설명(Candidate Explanations)을 생성하고 맥락적 지식(Contextual Knowledge)을 활용하여 이를 평가합니다. 이러한 과정은 사건이 예상과 다르게 전개될 때 진단(Diagnosis), 해석(Interpretation), 복구(Recovery)를 지원합니다.

유추적 추론(Analogical Reasoning) 역시 익숙한 상황의 관계적 지식(Relational Knowledge)을 새로운 상황으로 전이함으로써 상식을 지원합니다. 익숙하지 않은 도구는 이전에 경험한 도구와의 유사성을 통해 이해할 수 있으며, 새로운 환경은 다른 환경에서 학습한 구조적 관계(Structural Relationships)를 활용하여 탐색할 수 있습니다. 유추(Analogies)는 저장된 사례와 정확하게 일치하지 않더라도 관계의 패턴을 재사용하기 때문에 제한된 경험만으로도 시스템이 추론할 수 있도록 합니다.

구성성(Compositionality)은 단순한 개념과 관계를 새로운 상황으로 결합할 수 있도록 함으로써 상식 추론을 강화합니다. 용기, 깨지기 쉬운 객체, 이동, 지지에 관한 지식을 조합하여 섬세한 물건을 상자 안에 넣는 새로운 작업에 대해 추론할 수 있습니다. 가능한 일상 상황의 수는 어떠한 학습 데이터셋도 개별적으로 모두 열거할 수 없을 만큼 방대하기 때문에 일반지능에는 이러한 능력이 필요합니다.

월드 모델(World Models)은 상식을 위한 중요한 계산적 기반(Computational Foundation)을 제공할 수 있습니다. 월드 모델은 개체, 속성, 관계, 에이전트(Agents), 가능한 동역학(Likely Dynamics)을 표현하여 지능형 시스템이 서로 다른 행동에서 어떤 일이 발생할 수 있는지를 예측할 수 있도록 합니다. 상식은 이러한 모델에 사전 지식(Priors)과 구조적 가정(Structural Assumptions)을 제공하고 관측을 통해 이를 정교화할 수 있습니다. 두 요소를 결합하면 모든 세부사항을 완전히 시뮬레이션하지 않고도 빠른 예측을 수행할 수 있습니다.

기억(Memory)은 상식이 축적된 경험을 통해 발달하기 때문에 또 다른 필수 구성요소입니다. 의미기억(Semantic Memory)은 객체, 행동, 관계에 관한 일반화된 지식을 보존할 수 있으며, 일화기억(Episodic Memory)은 예외적이거나 특이한 상황을 보여주는 구체적인 사례를 유지할 수 있습니다. 기억 검색(Memory Retrieval)은 현재의 관측을 통해 관련된 과거 지식을 활성화합니다. 효과적인 추론을 위해서는 관련성이 없는 경험이 현재 맥락을 지배하지 않도록 적절한 기억을 선택해야 합니다.

언어 모델(Language Models)은 언어에 일상적인 사건, 의도, 결과에 대한 설명이 포함되어 있기 때문에 대규모 텍스트 말뭉치(Text Corpora)로부터 상당한 상식 지식을 습득할 수 있습니다. 그러나 텍스트 패턴은 불완전하거나 일관성이 없을 수 있으며 물리적 경험에 대한 그라운딩(Grounding)이 부족할 수 있습니다. 따라서 신뢰할 수 있는 상식은 언어를 지각(Perception), 행동(Action), 다중모달 데이터(Multimodal Data), 상호작용(Interaction)과 연결함으로써 강화될 수 있습니다. 그라운딩을 통해 상징적 설명(Symbolic Descriptions)을 세계가 실제로 어떻게 작동하는지와 비교할 수 있습니다.

체화된 경험(Embodied Experience)은 많은 상식적 관계가 행동과 그 결과에서 직접 발생하기 때문에 피지컬 AI에서 특히 중요합니다. 로봇은 특정 표면을 통과하기 어렵다는 것, 객체마다 특정 파지 전략(Grasp Strategies)이 필요하다는 것, 또는 밀기(Pushing)가 질량(Mass)과 마찰(Friction)에 따라 서로 다른 결과를 발생시킨다는 것을 학습할 수 있습니다. 이러한 상호작용은 추상적인 상관관계를 실제 감각운동 결과(Sensorimotor Outcomes)와 연결된 운영 가능한 지식(Operational Knowledge)으로 변환합니다.

상식 추론은 계획 과정에서 탐색 공간(Search Space)을 줄일 수 있습니다. 지능형 시스템은 이론적으로 가능한 모든 행동을 평가하는 대신 일반적인 물리적, 공간적, 사회적 또는 목표 관련 기대에 위배되는 선택지를 제거할 수 있습니다. 이를 통해 추론 효율성이 향상되고 인간에게도 일관성 있게 보이는 계획을 생성할 수 있습니다. 그러나 비정상적인 상황에서는 일반적으로 가능성이 낮다고 간주되는 행동이 필요할 수 있기 때문에 상식적 가정(Common Sense Assumptions)은 수정 가능한 상태로 유지되어야 합니다.

상식의 실패(Failure of Common Sense)는 현재 AI 시스템의 주요 한계 가운데 하나입니다. 모델은 언어적으로 유창한 답변을 생성하면서도 기본적인 물리적 제약조건, 서로 모순되는 가정, 실행 불가능한 행동, 사회적으로 개연성이 낮은 결과를 간과할 수 있습니다. 따라서 벤치마크(Benchmark)에서 높은 성능을 보인다고 해서 신뢰할 수 있는 일상적 추론 능력이 보장되는 것은 아닙니다. 평가에서는 상황이 익숙하지 않은 방식으로 표현되거나 여러 유형의 지식을 동시에 요구할 때에도 시스템이 일상적인 관계를 유지할 수 있는지를 검증해야 합니다.

상식 평가(Common Sense Evaluation)는 새로운 상황, 숨겨진 가정(Hidden Assumptions), 예외 처리(Exception Handling), 물리적 결과, 사회적 의도, 시간적 관계, 인과적 의존관계(Causal Dependencies)를 포함해야 합니다. 평가는 근본적인 구조를 유지하면서 표면적인 세부사항을 변경함으로써 암기된 연관성과 진정한 일반화(Generalization)를 구분해야 합니다. 강건한 성능(Robust Performance)을 위해서는 AI 시스템이 명시되지 않은 정보를 추론하고, 개연성이 낮은 결론을 탐지하며, 새로운 증거가 맥락을 변화시킬 때 기존 믿음을 수정할 수 있어야 합니다.

AGI에서 상식 추론(Common Sense Reasoning)은 지각, 기억, 인과 모델링(Causal Modeling), 구성성, 계획, 언어, 행동을 연결하는 계층(Connective Layer)으로 기능합니다. 상식은 불완전한 정보를 해석 가능하게 하고 가능한 행동을 이해할 수 있도록 하는 배경 기대(Background Expectations)를 제공합니다. 일반지능에는 모든 상황에 대한 완벽한 지식이 필요한 것이 아니라, 세계가 필요한 모든 정보를 명시적으로 제공하지 않는 상황에서도 에이전트가 합리적으로 추론할 수 있도록 충분히 그라운딩되고(Grounded), 유연하며(Flexible), 수정 가능한(Revisable) 일상 세계 모델(Everyday World Models)이 필요합니다.

## 10.05 Self Modeling [w/Code]

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

자기 모델링(Self-Modeling)은 지능형 시스템(Intelligent System)이 자신의 상태(State), 능력(Capabilities), 한계(Limitations), 목표(Goals), 지식(Knowledge), 현재 진행 중인 인지 과정(Cognitive Processes)에 대한 내부 표현(Internal Representations)을 유지하고 업데이트하는 능력입니다. 시스템은 외부 세계만 모델링하는 것이 아니라 그 세계 안에서 활동하는 에이전트(Agent)로서 자기 자신도 표현합니다. AGI(Artificial General Intelligence)에서 자기 모델링은 환경 조건과 이에 대응할 수 있는 시스템 자신의 능력을 함께 추론에 반영함으로써 적응적 행동(Adaptive Behavior)을 지원할 수 있습니다.

자기 모델(Self-Model)이 반드시 의식(Consciousness)이나 주관적인 자기인식(Subjective Self-Awareness)을 의미하는 것은 아닙니다. 계산적 관점(Computational Terms)에서는 예측(Prediction), 제어(Control), 추론(Reasoning), 의사결정(Decision Making)에 필요한 특성을 설명하는 기능적 표현(Functional Representation)으로 이해할 수 있습니다. 자율 시스템(Autonomous System)은 인간과 같은 주관적 경험 없이도 사용 가능한 자원, 현재 작업 상태, 신뢰도(Confidence), 센서 상태, 기억 내용, 행동 능력, 잔여 에너지 등을 모델링할 수 있습니다.

자기 모델링은 두 개념 모두 내부 과정에 관한 정보를 다룬다는 점에서 메타인지(Metacognition)와 밀접하게 연결됩니다. 메타인지는 인지를 모니터링하고 조절하는 데 초점을 두는 반면, 자기 모델링은 이러한 모니터링을 가능하게 하는 표현을 제공합니다. 시스템은 자신의 인지 상태와 성능에 대한 일정한 표현을 가지고 있어야 문제를 이해하고 있는지, 현재 전략이 효과적인지, 추가적인 추론이 필요한지를 평가할 수 있습니다.

지식 모니터링(Knowledge Monitoring)은 자기 모델링의 중요한 구성요소입니다. 지능형 시스템은 자신이 신뢰성 있게 알고 있는 정보, 부분적으로만 이해하고 있는 정보, 충분한 근거가 없는 정보를 구별할 수 있어야 합니다. 이러한 구분은 근거가 부족한 결론을 방지하고 적절한 정보 탐색 행동(Information-Seeking Behavior)을 가능하게 합니다. 따라서 불확실성(Uncertainty)을 인식하는 것은 단순한 출력 특성이 아니라 내부 지식에 대한 정확한 모델을 유지하는 과정의 일부입니다.

신뢰도 추정(Confidence Estimation)은 예측, 결정 또는 추론 결과에 대한 불확실성을 표현하는 하나의 메커니즘을 제공합니다. 적절하게 보정된 시스템(Well-Calibrated System)은 증거가 부족하거나 모호하고, 익숙하지 않거나, 서로 모순될 때 더 낮은 신뢰도를 부여해야 합니다. 이러한 신뢰도는 시스템이 즉시 행동할지, 추가 계산을 수행할지, 정보를 요청할지, 기억을 검색할지, 외부 도구를 활용할지, 또는 다른 에이전트나 인간 운영자(Human Operator)에게 제어권을 넘길지를 결정하는 데 영향을 줄 수 있습니다.

능력 모델링(Capability Modeling)은 시스템이 현재 무엇을 수행할 수 있고 무엇을 수행할 수 없는지를 다룹니다. 지능형 에이전트는 구성(Configuration)과 환경에 따라 서로 다른 기술(Skills), 도구(Tools), 센서(Sensors), 계산 자원(Computational Resources), 행동 가능성(Action Possibilities)을 보유할 수 있습니다. 이러한 능력에 대한 명시적 또는 암묵적 표현을 유지하면 계획이 실제로 사용할 수 없는 기능을 전제로 하는 것을 방지할 수 있습니다. 또한 이상적으로 정의된 자기 모습이 아니라 실제 보유 자원에 적합한 전략을 선택할 수 있도록 합니다.

한계 모델링(Limitation Modeling) 역시 중요합니다. 신뢰할 수 있는 지능에는 자신의 경계(Boundaries)를 인식하는 능력이 필요하기 때문입니다. 시스템은 불충분한 지각(Perception), 제한된 기억(Memory), 불확실한 위치추정(Localization), 불완전한 지식, 제한된 계산 능력, 물리적 제약조건(Physical Constraints)에 직면할 수 있습니다. 이러한 한계가 내부적으로 표현되어 있다면 시스템은 추가적인 증거를 수집하거나, 작업을 단순화하거나, 전략을 변경하거나, 도움을 요청하거나, 현재 능력을 초과하는 위험한 행동을 회피함으로써 이를 보완할 수 있습니다.

목표 표현(Goal Representation)은 자기 모델의 또 다른 주요 부분을 구성합니다. 지능적 행동에는 에이전트가 무엇을 달성하려 하는지, 어떤 목표가 우선순위를 가지는지, 현재 행동이 이러한 목표 달성에 어떻게 기여하는지에 관한 정보를 유지하는 능력이 필요합니다. 여러 목표가 주의나 자원을 놓고 경쟁할 수 있으므로 우선순위 결정(Prioritization)과 충돌 해결(Conflict Resolution)을 위한 메커니즘이 필요합니다. 자기 모델링을 통해 목표를 단순한 외부 명령이 아니라 에이전트 내부 상태의 일부로 다룰 수 있습니다.

의도(Intentions)는 목표와 특정 행동 과정에 대한 실행 약속(Commitments)을 연결합니다. 시스템은 여러 가능한 계획을 고려할 수 있지만 조건이 적절하게 유지되는 동안에는 그중 하나에만 전념할 수 있습니다. 현재 의도를 표현하면 시간에 걸친 행동 연속성(Behavioral Continuity)을 유지하고 대안 사이에서 불필요하게 전환하는 것을 방지할 수 있습니다. 동시에 새로운 증거가 계획이 비효율적이거나, 안전하지 않거나, 불가능하거나, 상위 목표와 일치하지 않는다는 것을 보여준다면 의도를 수정할 수 있어야 합니다.

기억(Memory)은 이전 행동, 결정, 성공, 실패, 학습 경험에 관한 정보를 보존함으로써 자기 모델링에 기여합니다. 일화기억(Episodic Memory)은 특정 상황에서 시스템이 어떻게 행동했는지에 대한 사례를 제공할 수 있으며, 의미기억(Semantic Memory)은 시스템의 능력과 운영 조건에 관한 일반화된 지식을 보존할 수 있습니다. 이러한 기억을 통해 자기 모델은 배포(Deployment) 이전에 만들어진 정적인 사양(Static Specification)에 머무르지 않고 축적된 경험에 따라 지속적으로 발전할 수 있습니다.

자기 예측(Self-Prediction)은 자기 모델링을 미래로 확장합니다. 지능형 시스템은 서로 다른 행동, 작업부하(Workloads), 환경 조건, 자원 제약조건 아래에서 자신의 상태가 어떻게 변화할지를 추정할 수 있습니다. 로봇은 배터리 소비(Battery Consumption), 계산 부하(Computational Load), 위치추정 성능 저하(Localization Degradation), 기계적 한계(Mechanical Limitations), 작업 완료 확률(Task Completion Probability)을 예측할 수 있습니다. 이러한 예측을 통해 계획 과정에서 외부 환경뿐만 아니라 에이전트 자신에게 행동이 미치는 결과까지 고려할 수 있습니다.

체화된 에이전트(Embodied Agents)는 물리적 신체가 지각과 행동을 제한하기 때문에 특히 풍부한 자기 모델을 필요로 합니다. 로봇은 자신의 기하학(Geometry), 관절 한계(Joint Limits), 페이로드(Payload), 도달 가능성(Reachability), 센서 배치(Sensor Placement), 이동성(Mobility), 에너지 상태(Energy State), 동적 능력(Dynamic Capabilities)을 표현해야 할 수 있습니다. 이러한 요소들은 페이로드 변화, 손상(Damage), 부품 성능 저하(Component Degradation), 환경 조건에 따라 변화할 수 있습니다. 따라서 적응형 피지컬 AI(Adaptive Physical AI)는 운영 중에도 업데이트할 수 있는 자기 모델로부터 이점을 얻을 수 있습니다.

신체 도식(Body Schema)은 지각과 행동에 사용되는 신체의 내부 표현을 설명하는 관련 개념입니다. 인간은 자신의 신체 위치와 구성을 지속적으로 추정하며, 로봇 역시 관절, 링크(Links), 도구, 접촉 상태(Contact States)에 대한 유사한 표현을 유지할 수 있습니다. 신체 도식은 에이전트 자신의 물리적 구조를 기준으로 행동을 계획할 수 있게 하며, 도구나 부착물(Attachments)이 일시적으로 신체 구조를 확장할 때 이에 적응하는 것도 지원할 수 있습니다.

자기 모델링은 고장 탐지(Fault Detection)도 지원할 수 있습니다. 지능형 시스템이 센서, 액추에이터(Actuators), 내부 과정 또는 행동이 정상적으로 어떻게 작동해야 하는지를 예측할 수 있다면 이러한 예상과의 차이는 고장을 나타낼 수 있습니다. 예상된 내부 상태와 실제로 관측된 내부 상태를 비교하면 센서 성능 저하, 액추에이터 문제, 계산 이상(Computational Anomalies), 예상하지 못한 성능 저하를 발견할 수 있습니다. 따라서 자기 모델은 일반적인 제어뿐만 아니라 진단(Diagnosis)을 위한 기준으로도 기능합니다.

탐지된 불일치(Discrepancies)가 행동이나 내부 표현의 변화로 이어질 때 적응(Adaptation)이 가능해집니다. 액추에이터 성능이 저하된 로봇은 동작 전략(Motion Strategy)을 변경할 수 있으며, 특정 작업에서 낮은 성능을 감지한 AI 시스템은 더 많은 추론 자원을 할당하거나 외부 정보를 탐색할 수 있습니다. 따라서 효과적인 자기 모델링은 동적(Dynamic)이어야 하며, 경험을 통해 시스템에 관한 기존 가정이 더 이상 정확하지 않다는 사실이 확인되면 이를 업데이트해야 합니다.

자기 자신에 대한 학습(Learning About Oneself)은 에이전트가 환경을 학습하는 것과 유사하게 상호작용을 통해 이루어질 수 있습니다. 시스템은 자신의 행동 결과를 관찰함으로써 어떤 기술이 신뢰할 수 있는지, 어디에서 실패가 발생하는지, 서로 다른 조건에서 성능이 어떻게 변화하는지를 추정할 수 있습니다. 이를 통해 능력이 전적으로 설계 사양(Design Specifications)에 의해 가정되는 것이 아니라 증거를 통해 추론되는 경험적 자기지식(Empirical Self-Knowledge)이 형성됩니다.

자기 모델은 월드 모델(World Models)과 상호작용하여 에이전트-환경 동역학(Agent--Environment Dynamics)에 대한 통합된 표현을 형성할 수 있습니다. 월드 모델은 외부 상태가 어떻게 변화할지를 예측하고, 자기 모델은 이러한 상태를 관측하고 영향을 미치는 에이전트를 표현합니다. 이에 따라 계획은 세계가 어떻게 변화할지, 에이전트가 무엇을 할 수 있는지, 행동이 양쪽 모두를 어떻게 변화시킬지, 그리고 그 결과로 생성되는 궤적(Trajectory)이 의도한 목표를 충족할 수 있는지를 함께 추론하는 과정이 됩니다.

인과 모델링(Causal Modeling)은 내부 상태나 능력이 왜 변화하는지를 표현함으로써 자기 모델링을 강화할 수 있습니다. 단순히 성능이 저하되었다는 사실을 감지하는 것을 넘어 에이전트는 센서가 가려져 지각 품질이 낮아졌거나 페이로드 증가로 이동 속도가 감소했다고 추론할 수 있습니다. 인과적 자기 모델(Causal Self-Models)은 근본적인 메커니즘을 일시적인 상관관계(Temporary Correlations)와 구별함으로써 진단, 개입(Intervention), 전이(Transfer)를 지원할 수 있습니다.

반사실적 추론(Counterfactual Reasoning)은 또 다른 유용한 능력을 제공합니다. 시스템은 다른 전략을 사용했다면 더 나은 결과가 발생했을지, 추가 정보가 있었다면 오류를 방지할 수 있었을지, 또는 다른 자원을 보유했다면 실패한 작업을 성공시킬 수 있었을지를 질문할 수 있습니다. 이러한 비교는 경험을 에이전트의 결정, 능력, 결과 사이의 관계에 대한 구조화된 지식(Structured Knowledge)으로 변환함으로써 미래 행동을 개선할 수 있습니다.

자기 모델링은 설명가능성(Explainability)에도 기여합니다. 시스템이 자신의 추론 상태, 불확실성, 목표, 제약조건과 관련된 요소를 표현할 수 있다면 자신의 결정에 대해 더욱 유용한 설명을 제공할 수 있습니다. 예를 들어 지각 신뢰도가 낮아 특정 행동을 회피했거나, 자원을 더 이상 사용할 수 없어 계획을 변경했거나, 작업이 추정된 능력을 초과했기 때문에 인간의 지원을 요청했다는 사실을 설명할 수 있습니다.

인간-AI 협업(Human--AI Collaboration)은 효과적인 팀워크가 능력과 한계에 관한 의사소통에 의존하기 때문에 정확한 자기 모델링으로부터 이점을 얻습니다. AI 에이전트가 불확실성, 사용할 수 없는 기능, 예상 완료 시간(Expected Completion Time), 지원 필요성을 신뢰성 있게 전달한다면 인간은 작업을 더욱 효과적으로 배분할 수 있습니다. 과도한 자신감(Overconfidence)은 부적절한 의존으로 이어질 수 있고 지나친 불확실성은 유용성을 감소시킬 수 있습니다. 따라서 적절하게 보정된 자기표현(Calibrated Self-Representation)은 적절한 인간 신뢰(Human Trust)에 직접적으로 기여합니다.

다중 에이전트 시스템(Multi-Agent Systems)에서는 자기 모델과 다른 에이전트에 대한 모델을 구별할 필요가 있습니다. 각각의 에이전트는 자신의 능력과 목표를 표현하는 동시에 협력자 또는 경쟁자의 능력과 목표를 추정해야 합니다. 이를 통해 작업 할당(Task Allocation)에서는 어떤 에이전트가 각각의 역할에 가장 적합한지를 고려할 수 있습니다. 모든 참여자가 동일한 능력을 가지고 있다고 가정하는 대신 자신의 상태, 자원, 진행상황, 한계에 관한 정확한 정보를 전달할 때 조정(Coordination) 성능이 향상됩니다.

자기 모델링의 평가(Evaluation)는 내부 추정(Internal Estimates)이 실제 행동 및 능력과 일치하는지를 검증해야 합니다. 유용한 평가에는 신뢰도 보정(Confidence Calibration), 성공과 실패의 예측, 사용할 수 없는 기술의 인식, 내부 고장 탐지, 변화하는 자원에 대한 적응, 적절한 지원 요청 등이 포함됩니다. 자기 모델은 의사결정을 개선하고 시스템과 환경이 변화함에 따라 충분한 정확성을 지속적으로 유지할 때에만 실질적인 가치를 가집니다.

AGI에서 자기 모델링(Self-Modeling)은 세계에 대한 지능과 그 세계 안에서 행동하는 에이전트 자신에 대한 지능을 연결하는 가교를 제공합니다. 일반적인 능력을 가진 시스템은 객체, 사건, 원인, 다른 에이전트뿐만 아니라 자신의 지식, 목표, 자원, 능력, 한계에 대해서도 추론할 수 있어야 합니다. 자기 모델링은 메타인지, 기억, 인과적 추론(Causal Reasoning), 월드 모델, 계획(Planning), 학습(Learning)과 통합됨으로써 적응적이고(Adaptive), 적절하게 보정되며(Calibrated), 점차 높은 자율성을 갖는 지능(Autonomous Intelligence)을 지원합니다.

## 10.06 Meta Learning [w/Code]

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

메타학습(Meta-Learning)은 지능형 시스템(Intelligent System)이 하나의 특정 작업에 대한 성능만 향상시키는 것이 아니라 학습하는 과정 자체를 개선하는 능력을 의미합니다. 흔히 '학습하는 방법을 학습(Learning to Learn)'하는 것으로 설명되며, 이전 학습 경험으로부터 재사용 가능한 전략(Strategies), 표현(Representations), 사전 지식(Priors), 적응 메커니즘(Adaptation Mechanisms)을 획득하는 데 초점을 둡니다. AGI(Artificial General Intelligence)에서 메타학습은 지능형 시스템이 새로운 문제마다 대규모 재학습을 수행하지 않고도 새로운 능력을 빠르게 습득해야 하기 때문에 중요합니다.

전통적인 머신러닝(Conventional Machine Learning)은 일반적으로 고정된 학습 절차(Training Procedure)를 사용하여 사전에 정의된 작업에 맞게 모델을 최적화합니다. 반면 메타학습은 학습 자체를 최적화의 대상으로 취급합니다. 여러 작업에서 축적된 경험을 통해 어떤 표현이 효과적으로 전이되는지, 어떤 파라미터(Parameters)를 빠르게 변경해야 하는지, 어떤 사례가 유용한 정보를 제공하는지, 어떤 학습 전략이 효과적인지를 학습할 수 있습니다. 그 결과 시스템은 단순히 작업을 수행하는 것뿐만 아니라 효율적으로 적응하도록 설계됩니다.

핵심적인 개념은 이전의 학습 경험이 미래의 학습을 더욱 쉽게 만들어야 한다는 것입니다. 인간은 익숙하지 않은 모든 문제를 아무런 사전 구조 없이 처음부터 접근하지 않습니다. 이전 경험을 통해 발전시킨 개념, 전략, 기대(Expectations), 문제 해결 패턴(Problem-Solving Patterns)을 재사용합니다. 메타학습은 특정 데이터셋이나 목적에 종속되지 않고 여러 작업에서 공통적으로 작동할 수 있는 지식을 추출함으로써 이러한 능력의 계산적 대응물(Computational Analogue)을 구현하려고 합니다.

메타학습 시스템은 일반적으로 서로 상호작용하는 두 개의 수준에서 작동합니다. 내부 학습 과정(Inner Learning Process)은 작업별 관측이나 피드백을 이용하여 특정 작업에 적응하고, 외부 과정(Outer Process)은 여러 작업의 분포(Task Distribution)에 걸쳐 이러한 적응 과정 자체를 개선합니다. 외부 과정은 초기화(Initialization), 표현, 학습 규칙(Learning Rules), 기억 메커니즘(Memory Mechanisms), 탐색 전략(Exploration Strategies)을 최적화하여 미래의 내부 루프 적응(Inner-Loop Adaptation)이 더욱 빠르고 신뢰성 있게 이루어지도록 할 수 있습니다.

따라서 작업 분포(Task Distributions)는 메타학습에서 매우 중요합니다. 학습 사례가 하나의 고정된 작업에서 독립적으로 추출된 샘플이라고 가정하는 대신 시스템은 서로 관련된 여러 학습 문제로부터 학습합니다. 이러한 작업의 다양성과 구조는 시스템이 어떠한 종류의 적응 능력을 습득할 수 있는지를 결정합니다. 메타훈련 분포(Meta-Training Distribution)가 지나치게 좁으면 학습된 적응 전략은 상당히 다른 환경이나 목표에 직면했을 때 실패할 수 있습니다.

퓨샷 학습(Few-Shot Learning)은 메타학습의 가장 대표적인 응용 분야 가운데 하나입니다. 메타학습된 시스템은 매우 적은 수의 사례만을 사용하여 새로운 작업을 인식하거나 해결하려고 합니다. 시스템은 이러한 사례만으로 작업 전체를 처음부터 학습하는 것이 아니라 이전의 여러 작업에서 축적된 지식과 새로운 사례를 결합합니다. 이를 통해 제한된 증거만으로도 의미 있는 적응을 수행할 수 있으며 충분한 성능을 달성하기 위해 필요한 작업별 데이터(Task-Specific Data)의 양을 줄일 수 있습니다.

메타학습 접근법 가운데 하나는 유용한 파라미터 초기화(Parameter Initialization)를 학습하는 것입니다. 목표는 적은 수의 최적화 단계(Optimization Steps)만으로 새로운 작업에서 높은 성능을 얻을 수 있는 시작 구성을 발견하는 것입니다. 하나의 학습 문제에 최적인 파라미터를 찾는 대신 다양한 작업에 폭넓게 적응할 수 있는 파라미터를 찾습니다. 이러한 접근법에서는 학습된 파라미터 공간(Parameter Space)의 기하학적 구조 자체가 메타학습 과정의 일부가 됩니다.

메트릭 기반 메타학습(Metric-Based Meta-Learning)은 새로운 작업에 빠르게 적응하는 데 유용하도록 유사성(Similarity)을 표현할 수 있는 표현 공간을 학습하는 다른 접근방식을 사용합니다. 새로운 사례를 임베딩 공간(Embedding Space)에서 이전에 관찰한 사례 또는 학습된 프로토타입(Prototypes)과 비교할 수 있습니다. 이후 비교적 적은 추가 최적화만으로 분류(Classification)나 의사결정을 수행할 수 있습니다. 제한된 새로운 데이터만 사용할 수 있을 때에도 작업과 관련된 관계를 유지할 수 있는지는 표현의 품질에 따라 결정됩니다.

기억 기반 메타학습(Memory-Based Meta-Learning)은 순환신경망(Recurrent Networks), 외부 기억(External Memory), 어텐션(Attention) 또는 관련 메커니즘을 사용하여 이전 관측과 학습 에피소드(Learning Episodes)에 관한 정보를 보존합니다. 적응을 파라미터 업데이트에만 완전히 의존하지 않고 관련 경험을 기억에서 검색하여 행동을 변화시킬 수 있습니다. 이는 빠른 적응 경로(Fast Adaptation Pathway)를 제공하며 메타학습을 일화기억(Episodic Memory), 맥락적 추론(Contextual Reasoning), 인컨텍스트 학습(In-Context Learning)과 밀접하게 연결합니다.

학습 규칙(Learning Rules) 자체도 학습할 수 있습니다. 수동으로 지정된 옵티마이저(Optimizer)에만 의존하는 대신 시스템은 경험에 따라 파라미터, 표현 또는 내부 상태(Internal States)를 어떻게 변화시켜야 하는지를 결정하는 메커니즘을 획득할 수 있습니다. 이러한 학습된 옵티마이저(Learned Optimizers)는 일반적인 최적화 알고리즘이 활용하지 못하는 작업 간 규칙성을 이용할 가능성이 있습니다. 그러나 학습 규칙이 처음 훈련된 조건을 넘어서는 상황에서도 일반화(Generalization)할 수 있어야 합니다.

메타학습은 전이학습(Transfer Learning)과 밀접하게 관련되어 있지만 두 개념은 서로 다른 목표를 강조합니다. 전이학습은 하나 이상의 원천 작업(Source Tasks)에서 얻은 지식을 재사용하여 목표 작업(Target Task)의 성능을 향상시키는 반면, 메타학습은 이러한 적응 능력을 반복적으로 수행할 수 있도록 명시적으로 최적화합니다. 따라서 메타학습기(Meta-Learner)는 전이 자체를 더욱 효과적으로 수행하도록 훈련되며 미래의 작업 습득을 더욱 빠르고, 데이터 효율적이며, 체계적으로 만드는 구조를 학습합니다.

지속학습(Continual Learning) 역시 메타학습과 강하게 상호작용합니다. 지속적으로 학습하는 에이전트는 시간에 따라 새로운 작업이나 환경을 경험하며 기존의 유용한 능력을 파괴하지 않으면서 새로운 지식을 통합해야 합니다. 메타학습은 어떤 지식을 안정적으로 유지해야 하는지, 어떤 구성요소를 빠르게 적응시켜야 하는지, 새로운 경험을 어떻게 통합해야 하는지를 결정하는 데 도움을 줄 수 있습니다. 이를 통해 학습을 위한 가소성(Plasticity)과 기존 지식 보존을 위한 안정성(Stability) 사이의 균형을 지원할 수 있습니다.

표현학습(Representation Learning)은 빠른 적응이 재사용 가능한 구조를 포착하는 특징(Features)을 확보하는 데 의존하기 때문에 매우 중요합니다. 새로운 작업마다 지각과 개념적 구성을 처음부터 다시 구축해야 한다면 퓨샷 적응(Few-Shot Adaptation)은 어려워집니다. 메타학습은 여러 작업에서 공유되는 요인을 드러내면서 작업별 차이에 대응할 수 있는 적응 가능한 구성요소를 유지하도록 표현을 학습할 수 있습니다. 이러한 요인화(Factorization)는 전이 효율성과 일반화 모두를 향상시킬 수 있습니다.

구성성(Compositionality)은 이전에 획득한 개념, 관계, 기술(Skills)을 새로운 작업에 맞게 재구성할 수 있도록 함으로써 메타학습을 더욱 강화할 수 있습니다. 지능형 에이전트는 전체 시스템을 하나의 분리할 수 없는 단위로 적응시키는 대신 어떤 재사용 가능한 구성요소가 관련되어 있는지를 식별하고 이를 새로운 해결책으로 구성할 수 있습니다. 이에 따라 메타학습은 기존의 인지적 또는 행동적 모듈(Behavioral Modules)을 선택하고, 결합하고, 수정하고, 조정하는 방법을 학습하는 과정으로도 작동할 수 있습니다.

인과 지식(Causal Knowledge)은 환경 변화에서 메타학습을 더욱 강건하게 만들 수 있습니다. 학습 과정에서 적응을 지원했던 통계적 규칙성(Statistical Regularities)은 표면적인 상관관계가 변화하면 실패할 수 있지만 인과 메커니즘(Causal Mechanisms)은 여러 작업에 걸쳐 안정적으로 유지될 수 있습니다. 재사용 가능한 인과 구조(Causal Structure)를 식별하는 메타학습기는 어떤 메커니즘이 그대로 유지되고 어떤 메커니즘이 변화했는지를 판단하여 적응할 수 있습니다. 이는 표면적인 유사성에 대한 의존도를 낮춘 적응으로 발전할 수 있는 경로를 제공합니다.

메타학습은 탐색(Exploration) 능력도 향상시킬 수 있습니다. 익숙하지 않은 환경에서 에이전트는 빠른 학습을 위해 어떤 관측이나 행동이 가장 유용한 정보를 제공할 것인지를 결정해야 합니다. 이전 작업에서 얻은 경험을 통해 불확실성을 효율적으로 감소시키는 탐색 전략을 학습할 수 있습니다. 따라서 시스템은 작업을 이해한 이후 어떻게 행동해야 하는지만 학습하는 것이 아니라 작업 구조, 동역학(Dynamics), 목표, 제약조건을 가능한 빠르게 파악하기 위해 어떻게 증거를 수집해야 하는지도 학습합니다.

강화학습(Reinforcement Learning)은 에이전트가 상호작용을 통해 유용한 행동을 발견해야 하는 작업을 반복적으로 경험하기 때문에 이러한 능력을 구현하기 위한 자연스러운 환경을 제공합니다. 메타강화학습(Meta-Reinforcement Learning)은 서로 관련된 환경에서 얻은 경험을 활용하여 행동, 보상(Rewards), 동역학, 탐색에 관한 사전 지식을 획득할 수 있습니다. 새로운 작업이 나타나면 에이전트는 강화학습을 완전히 처음부터 시작하는 대신 비교적 적은 상호작용만으로 정책(Policy)을 적응시킬 수 있습니다.

월드 모델(World Models)은 새로운 환경에 맞게 예측을 적응시킴으로써 메타학습에 참여할 수 있습니다. 시스템은 객체, 동역학, 상호작용, 인과관계에 대한 일반적인 표현을 학습하면서 환경별 파라미터(Environment-Specific Parameters)를 빠르게 업데이트할 수 있습니다. 이러한 재사용 가능한 구조와 적응 가능한 세부사항의 분리를 통해 에이전트는 제한된 경험만으로도 유용한 예측 모델(Predictive Models)을 구축하고 이를 계획(Planning)과 의사결정에 활용할 수 있습니다.

자기 모델링(Self-Modeling)은 지능형 시스템이 작업에 따라 자신의 능력이 어떻게 변화하는지를 학습할 수 있기 때문에 또 다른 차원을 제공합니다. 반복적인 경험을 통해 어떤 문제에 더 많은 계산이 필요한지, 어떤 기술이 안정적으로 전이되는지, 어떤 상황에서 불확실성이 증가하는지, 언제 외부 지원(External Assistance)이 유용한지를 발견할 수 있습니다. 따라서 메타학습은 환경 모델뿐만 아니라 시스템 자신의 인지적·물리적 자원(Cognitive and Physical Resources)을 배분하는 전략도 개선할 수 있습니다.

피지컬 AI(Physical AI)에서 메타학습은 로봇이 변화하는 객체, 지형(Terrains), 페이로드(Payloads), 사용자, 작업, 환경 조건에서 작동해야 하기 때문에 특히 중요합니다. 하나의 요소가 변화할 때마다 로봇을 처음부터 재훈련하는 것은 현실적이지 않습니다. 메타학습된 로봇은 이전 상호작용 경험을 활용하여 비교적 적은 양의 새로운 데이터와 물리적 상호작용만으로 지각, 제어(Control), 조작(Manipulation), 내비게이션(Navigation), 계획을 적응시킬 수 있습니다.

시뮬레이션-현실 적응(Sim-to-Real Adaptation) 역시 메타학습의 이점을 얻을 수 있습니다. 시뮬레이션(Simulation)은 실제 배포 이전에 에이전트가 다양한 동역학, 센서 조건, 객체 속성, 환경 변화에 노출되도록 할 수 있습니다. 메타학습은 이러한 다양성을 이용하여 하나의 고정된 정책이 아니라 적응 메커니즘을 학습할 수 있습니다. 실제 환경이 시뮬레이션과 다를 경우 에이전트는 제한된 관측으로 관련 차이를 추론하고 내부 모델이나 행동을 이에 맞게 조정할 수 있습니다.

인간 상호작용(Human Interaction)은 빠른 적응을 위한 또 다른 정보원을 제공합니다. 서로 다른 사용자는 목표, 선호(Preferences), 지시(Instructions), 수정사항(Corrections)을 서로 다른 방식으로 표현할 수 있습니다. 메타학습 시스템은 많은 상호작용에서 얻은 경험을 활용하여 제한된 증거만으로 사용자별 패턴(User-Specific Patterns)을 추론하는 방법을 학습할 수 있습니다. 이는 완전한 재학습 없이 개인화(Personalization)를 지원하고 사용자 선호나 작업 조건이 시간에 따라 변화할 때 인간-AI 협업(Human--AI Collaboration)을 향상시킬 수 있습니다.

메타학습의 평가(Evaluation)는 빠른 적응과 단순한 암기(Memorization)를 구별해야 합니다. 새로운 사례에서 높은 성능을 보이는 것만으로는 충분하지 않으며, 특히 이러한 사례가 메타훈련 과정에서 경험한 작업과 매우 유사한 경우에는 더욱 그렇습니다. 평가에는 실제로 경험하지 않은 새로운 작업, 제한된 적응 데이터, 분포 변화(Distribution Shifts), 변화하는 동역학, 익숙한 구성요소의 새로운 조합이 포함되어야 합니다. 최종 성능뿐만 아니라 적응의 속도, 안정성, 데이터 효율성(Data Efficiency)도 함께 측정해야 합니다.

메타학습에는 여러 과제도 존재합니다. 시스템이 메타훈련 작업 분포에 과적합(Overfitting)하거나, 더 큰 환경 변화에서 실패하는 지름길(Shortcuts)을 학습하거나, 노이즈가 포함된 증거에 지나치게 공격적으로 적응할 수 있습니다. 많은 작업을 대상으로 훈련하는 데 필요한 계산 비용(Computational Cost)도 상당할 수 있습니다. 따라서 신뢰할 수 있는 메타학습에는 적절한 작업 다양성, 불확실성 추정(Uncertainty Estimation), 정규화(Regularization), 기억 관리(Memory Management), 그리고 언제 적응해야 하고 언제 기존 지식을 유지해야 하는지를 결정하는 메커니즘이 필요합니다.

AGI에서 메타학습(Meta-Learning)은 축적된 경험을 미래의 학습 능력 향상으로 전환하는 메커니즘을 제공합니다. 지능을 고정된 능력의 집합으로 취급하는 대신 학습 과정 자체가 점차 더욱 효과적으로 발전하도록 합니다. 메타학습은 기억, 구성성, 인과 모델링(Causal Modeling), 월드 모델, 강화학습, 자기 모델링, 지속학습과 통합됨으로써 작업, 환경, 목표가 변화하더라도 새로운 지식과 기술을 빠르게 습득할 수 있는 지능을 지원합니다.

## 10.07 Embodied Cognition [w/Code]

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

체화된 인지(Embodied Cognition)는 지능(Intelligence)이 내부 계산(Internal Computation)만으로 발생하는 것이 아니라 뇌 또는 제어기(Controller), 신체(Body), 주변 환경(Environment) 사이의 지속적인 상호작용을 통해 형성된다는 관점입니다. 따라서 지각(Perception), 행동(Action), 추론(Reasoning)은 서로 분리된 단계가 아니라 깊이 연결되어 있습니다. 인공지능(Artificial Intelligence)의 관점에서 이는 시스템이 추상적 기호(Abstract Symbols)나 정적인 데이터에만 의존하지 않고 감각운동 경험(Sensorimotor Experience)을 통해 학습할 때 일반적인 인지 능력을 더욱 강화할 수 있음을 의미합니다.

신체는 무엇을 지각할 수 있고 행동을 어떻게 수행할 수 있는지를 그 구조가 결정하기 때문에 인지에 영향을 미칩니다. 인간의 손은 파지(Grasping)와 조작(Manipulation)을 가능하게 하고, 눈은 시각적 관점(Visual Perspective)을 제한하며, 이동(Locomotion) 능력은 환경의 어느 영역을 탐색할 수 있는지를 결정합니다. 인공 에이전트(Artificial Agents) 역시 특정한 센서(Sensors), 액추에이터(Actuators), 관절(Joints), 바퀴(Wheels), 매니퓰레이터(Manipulators), 물리적 한계(Physical Limits)를 통해 추론하며, 이러한 요소들이 이용 가능한 정보와 행동의 범위를 형성합니다.

체화된 인지에서 지각은 수동적(Passive)이 아니라 능동적(Active)입니다. 에이전트는 단순히 감각 데이터를 받아들이는 것이 아니라 유용한 정보를 획득하기 위해 이동하고, 바라보고, 접촉하고, 탐색하며, 자신의 시점을 변화시킵니다. 따라서 행동은 실질적인 목적뿐만 아니라 정보 획득의 목적도 가질 수 있습니다. 로봇은 가시성(Visibility)을 향상시키기 위해 위치를 변경하거나 수동적인 관찰만으로 충분하지 않을 때 객체와 물리적으로 상호작용하여 무게, 이동 가능성(Mobility), 행동유도성(Affordances)을 파악할 수 있습니다.

지각-행동 루프(Perception--Action Loop)는 체화된 지능(Embodied Intelligence)의 핵심 메커니즘입니다. 에이전트는 환경을 지각하고, 현재 상태를 해석하고, 행동을 선택하고, 그 결과 발생한 변화를 관찰한 다음 내부 표현(Internal Representations)을 업데이트합니다. 이러한 지속적인 순환을 통해 새로운 정보가 들어올 때마다 행동을 수정할 수 있습니다. 지능은 지각이 끝난 후 계획과 행동이 시작되는 순차적인 과정이 아니라 지속적으로 작동하는 폐루프 과정(Closed-Loop Process)이 됩니다.

감각운동 그라운딩(Sensorimotor Grounding)은 추상적인 표현을 물리적 경험과 연결합니다. 거리(Distance), 지지(Support), 포함(Containment), 저항(Resistance), 도달 가능성(Reachability), 균형(Balance)과 같은 개념은 상호작용을 통해 실제적인 의미를 갖게 됩니다. 시스템은 시각적 또는 언어적 설명을 실제 행동의 결과와 연결할 수 있습니다. 그라운딩된 표현(Grounded Representations)은 예측과 계획이 궁극적으로 물리 세계에서 실제로 발생 가능한 상태와 일치해야 하기 때문에 피지컬 AI(Physical AI)에서 특히 중요합니다.

행동유도성(Affordances)은 에이전트, 객체(Object), 환경 사이의 관계에서 발생하는 행동 가능성(Action Possibilities)을 설명합니다. 어떤 표면은 특정 로봇에게는 주행 가능(Traversable)하지만 다른 로봇에게는 그렇지 않을 수 있으며, 어떤 객체는 특정 방향이나 특정 엔드 이펙터(End Effectors)를 사용할 때만 파지할 수 있습니다. 따라서 행동유도성 추론(Affordance Reasoning)은 세계의 특성과 에이전트 자신의 능력 모두에 의존하며, 지각과 행동을 연결하는 중요한 가교 역할을 합니다.

체화된 인지는 객체를 가능한 상호작용과 관련하여 표현해야 하는 경우가 많다는 점을 강조합니다. 문(Door)을 인식하는 것도 유용하지만, 문을 열거나 통과하거나 차단하거나 공간의 경계로 사용할 수 있다는 것을 이해하면 더욱 풍부한 기능적 지식(Functional Knowledge)을 얻을 수 있습니다. 마찬가지로 용기(Container)를 식별하는 것은 객체를 넣고, 꺼내고, 운반하거나, 보호하기 위해 용기와 상호작용할 수 있다는 사실을 시스템이 이해할 때 더욱 유용해집니다.

운동 제어(Motor Control) 자체도 복잡한 행동에 지속적인 예측과 수정이 필요하기 때문에 인지에 기여할 수 있습니다. 움직임은 위치(Position), 힘(Force), 접촉(Contact), 균형, 환경 변화에 관한 피드백(Feedback)의 영향을 받습니다. 지능형 시스템은 모든 미세한 행동을 사전에 계획하는 대신 상위 수준 목표(High-Level Goals)와 빠른 피드백 제어(Feedback Control)를 결합할 수 있습니다. 이를 통해 계산 부담을 줄이고 실행 중 발생하는 외란(Disturbances)에 행동을 적응시킬 수 있습니다.

신체 도식(Body Schema)은 에이전트의 물리적 구조와 구성(Configuration)에 대한 내부 표현을 제공합니다. 여기에는 크기(Dimensions), 관절, 도달 가능성, 센서 배치(Sensor Placement), 접촉 상태(Contact States), 페이로드(Payload), 이동성 제약조건(Mobility Constraints)이 포함될 수 있습니다. 이러한 모델을 통해 에이전트 자신을 기준으로 행동을 계획할 수 있습니다. 도구(Tools), 부착물(Attachments), 손상(Damage), 페이로드 변화로 물리적 능력이 달라질 경우 정확한 제어를 유지하기 위해 신체 도식도 적응해야 할 수 있습니다.

고유수용감각(Proprioception)은 에이전트 자신의 물리적 상태에 관한 정보를 제공함으로써 체화된 지능에 기여합니다. 관절 각도(Joint Angles), 속도(Velocity), 방향(Orientation), 힘, 가속도(Acceleration), 액추에이터 상태(Actuator Condition)는 시스템이 현재 자신의 신체가 어떻게 구성되어 있는지를 추정하도록 합니다. 고유수용감각을 카메라(Camera)나 라이다(LiDAR)와 같은 외수용 센서(Exteroceptive Sensors)와 결합하면 에이전트는 상호작용 과정에서 자기 자신과 외부 환경을 동시에 추론할 수 있습니다.

공간 인지(Spatial Cognition)는 위치와 방향이 에이전트의 신체 및 가능한 움직임을 기준으로 이해되는 경우가 많기 때문에 체화와 강하게 연결됩니다. 가까움(Near), 멂(Far), 도달 가능(Reachable), 뒤쪽(Behind), 위쪽(Above), 통과 가능(Traversable), 차단됨(Obstructed)은 순수하게 추상적인 속성이 아닙니다. 이러한 개념의 실질적인 의미는 신체의 기하학적 구조(Body Geometry), 방향, 이동 능력, 환경 구조에 따라 달라집니다. 따라서 체화된 에이전트는 가능한 행동과 직접적으로 연결된 공간 표현(Spatial Representations)을 필요로 합니다.

시간 인지(Temporal Cognition) 역시 행동이 시간에 따라 전개되고 그 결과가 즉각적이거나 지연되어 나타날 수 있기 때문에 상호작용을 통해 형성됩니다. 에이전트는 가속이 속도를 점진적으로 변화시키고, 조작에는 순서가 있는 여러 단계가 필요하며, 일부 행동은 일정 시간을 기다린 이후에야 결과를 발생시킨다는 것을 학습합니다. 이러한 시간적 관계(Temporal Relationships)에 대한 경험은 장기 행동(Long-Horizon Behavior)에서 예측, 순서화(Sequencing), 계획(Planning), 미래 상태에 대한 예상(Anticipation)을 지원합니다.

인과적 이해(Causal Understanding)는 행동이 가설(Hypotheses)을 직접 검증할 수 있는 기회를 제공하기 때문에 체화를 통해 강화될 수 있습니다. 에이전트가 객체를 밀고 움직임을 관찰하면 힘과 상태 변화(State Change)의 관계에 관한 증거를 얻을 수 있습니다. 반복적인 개입(Intervention)을 통해 질량(Mass), 마찰(Friction), 지지, 기하학(Geometry)이 결과를 어떻게 변화시키는지를 파악할 수 있습니다. 따라서 체화된 상호작용은 인과적 추론(Causal Reasoning)을 수동적인 관찰에서 능동적인 실험(Active Experimentation)으로 전환합니다.

상호작용을 통한 학습(Learning through Interaction)은 정적인 데이터셋(Static Datasets)만으로는 획득하기 어려운 지식을 생성할 수 있습니다. 로봇은 표면이 견인력(Traction)에 어떤 영향을 미치는지, 객체가 서로 다른 파지에 어떻게 반응하는지, 시점과 조명(Lighting)에 따라 센서 측정값이 어떻게 달라지는지를 발견할 수 있습니다. 이러한 경험은 수동 주석(Manual Annotation)이 아니라 행동의 결과를 통해 학습 신호를 제공합니다. 자기지도학습(Self-Supervised Learning)과 강화학습(Reinforcement Learning)은 상호작용에서 생성된 이러한 신호를 활용하여 체화된 표현을 향상시킬 수 있습니다.

따라서 탐색(Exploration)은 내비게이션(Navigation)의 문제인 동시에 인지 과정(Cognitive Process)이기도 합니다. 체화된 에이전트는 세계의 불확실한 속성을 파악하기 위해 의도적으로 행동을 선택할 수 있습니다. 가려진 영역(Occluded Region)을 조사하거나, 익숙하지 않은 객체에 접근하거나, 특정 경로를 통과할 수 있는지를 시험할 수 있습니다. 효과적인 탐색은 즉각적인 작업 진행과 정보 수집(Information Gathering) 사이의 균형을 유지하여 중요한 행동을 수행하기 전에 불확실성을 감소시킬 수 있도록 합니다.

월드 모델(World Models)은 행동에 따라 물리적 상태가 어떻게 변화하는지를 표현하기 때문에 체화된 인지에서 특히 중요합니다. 월드 모델은 미래 관측(Future Observations)과 결과를 예측함으로써 에이전트가 실제 실행 전에 가능한 행동을 내부적으로 평가할 수 있도록 합니다. 체화된 월드 모델(Embodied World Model)은 객체, 기하학, 동역학(Dynamics), 행동유도성, 에이전트 상태, 불확실성(Uncertainty), 인과관계를 통합하여 상호작용 환경에서의 계획을 지원할 수 있습니다.

자기 모델링(Self-Modeling)은 에이전트가 세계를 예측하는 동시에 자신의 신체와 능력에 대해서도 추론해야 하기 때문에 체화된 인지를 자연스럽게 보완합니다. 로봇은 특정 개구부(Opening)를 통과할 수 있는지, 객체를 운반할 수 있는지, 목표 지점에 도달할 수 있는지, 사용 가능한 에너지로 경로를 완료할 수 있는지를 판단해야 할 수 있습니다. 따라서 체화된 지능은 환경을 설명하는 월드 모델과 행동 주체를 설명하는 자기 모델(Self-Model) 사이의 상호작용에 의존합니다.

상식 추론(Common Sense Reasoning) 역시 축적된 체화 경험(Embodied Experience)으로부터 형성될 수 있습니다. 지지, 충돌(Collision), 포함, 운동, 도구 사용에 관한 기대는 물리적 환경과 반복적으로 상호작용하면서 그라운딩됩니다. 상식을 단순히 텍스트 지식(Textual Knowledge)으로 취급하는 대신 체화된 시스템은 행동을 통해 실제로 적용 가능한 규칙성(Operational Regularities)을 습득할 수 있습니다. 이러한 그라운딩은 언어적 설명이 불완전하거나 모호할 때 강건성(Robustness)을 향상시킬 수 있습니다.

언어(Language)는 체화된 경험과 연결될 때 더욱 의미를 갖게 됩니다. "객체를 상자 뒤에 놓아라" 또는 "미끄러운 표면을 조심스럽게 이동하라"와 같은 지시는 공간적·물리적·행동 관련 그라운딩을 필요로 합니다. 다중모달 시스템(Multimodal Systems)은 단어를 시각적 관측, 고유수용감각, 궤적(Trajectories), 힘, 결과와 연결할 수 있습니다. 이를 통해 언어는 단순한 상징적 설명을 넘어 피지컬 AI를 위한 제어 및 추론 인터페이스(Control and Reasoning Interface)로 기능할 수 있습니다.

사회적 상호작용(Social Interaction) 역시 인간이 언어뿐만 아니라 위치, 움직임, 시선(Gaze), 제스처(Gesture), 근접성(Proximity), 타이밍(Timing), 물리적 조정(Physical Coordination)을 통해 의사소통하기 때문에 체화되어 있습니다. 인간 주변에서 작동하는 로봇은 이러한 신호를 해석하고 다른 사람이 예상할 수 있는 행동을 생성해야 합니다. 속도, 궤적, 정지거리(Stopping Distance), 방향은 의도를 전달할 수 있으므로 움직임 자체가 인간-로봇 상호작용(Human--Robot Interaction)과 협업에서 중요한 의사소통 채널이 됩니다.

공유 자율성(Shared Autonomy)은 체화된 지능이 인간과 기계 사이에 분산될 수 있는 방식을 보여줍니다. 인간은 목표를 지정하거나 수정사항을 제공하고, 자율 시스템은 세부적인 지각, 내비게이션, 조작, 제어를 담당할 수 있습니다. 물리적 피드백(Physical Feedback)을 통해 양측은 지속적으로 적응할 수 있습니다. 공유 자율성의 효과는 명확한 제어 권한(Control Authority)을 유지하고 자율성 전환 과정에서도 자율 행동이 예측 가능하도록 보장하는 데 달려 있습니다.

시뮬레이션-현실 학습(Sim-to-Real Learning)은 체화된 시스템이 실제 세계와 상호작용하기 전에 부분적으로 시뮬레이션(Simulation)에서 학습되는 경우가 많기 때문에 중요합니다. 시뮬레이션은 다양한 경험을 낮은 비용으로 생성할 수 있지만 동역학, 센싱(Sensing), 접촉(Contact), 환경의 차이로 인해 현실 격차(Reality Gap)가 발생할 수 있습니다. 체화된 적응(Embodied Adaptation)을 위해서는 시스템이 실제 상호작용으로부터 모델을 업데이트하고, 물리적 피드백을 이용하여 시뮬레이션에서 학습한 가정을 수정하며, 배포 이후의 강건성을 향상시켜야 합니다.

체화된 인지의 평가(Evaluation)는 독립된 데이터셋에서의 지각 정확도(Perception Accuracy)만을 측정해서는 안 됩니다. 유용한 평가는 새로운 객체와 환경에 대한 적응, 물리적 작업 성공률(Physical Task Success), 외란에 대한 강건성, 행동유도성 이해, 감각운동 협응(Sensorimotor Coordination), 오류 복구(Error Recovery), 학습된 기술의 전이(Transfer), 상호작용을 이용한 불확실성 감소 능력을 포함합니다. 성능은 서로 분리된 구성요소의 정확도가 아니라 폐루프 수행 능력(Closed-Loop Competence)을 반영해야 합니다.

AGI에서 체화된 인지(Embodied Cognition)는 추상적 지능(Abstract Intelligence)에서 세계와의 상호작용을 통해 결과를 이해하는 에이전트로 발전하기 위한 경로를 제공합니다. 지능은 무엇을 지각하고, 변화시키고, 도달하고, 조작하고, 행동을 통해 학습할 수 있는지에 그라운딩됩니다. 체화는 월드 모델, 자기 모델링, 인과적 추론, 상식, 기억(Memory), 계획, 메타학습(Meta-Learning)과 통합됨으로써 내부 인지와 실제 물리적 경험을 연결할 수 있는 적응형 지능(Adaptive Intelligence)을 지원합니다.

## 10.08 Cognitive Limitations of Current AI [w/Code]

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

현재의 AI 시스템(Current AI Systems)은 언어(Language), 비전(Vision), 예측(Prediction), 생성(Generation), 계획(Planning), 전문화된 의사결정(Specialized Decision Making)에서 뛰어난 성능을 보여주지만, 이러한 능력을 완전한 인간 수준의 인지(Human-Like Cognition)와 동일하게 간주해서는 안 됩니다. AI의 능력은 작업과 맥락에 따라 불균형하게 나타나는 경우가 많습니다. 복잡한 벤치마크(Benchmarks)에서는 매우 뛰어난 성능을 보이면서도 일상적인 배경 지식, 유연한 적응, 지속적 기억(Persistent Memory), 물리적 결과에 대한 신뢰할 수 있는 이해가 필요한 상황에서는 실패할 수 있습니다.

주요 한계 가운데 하나는 현재 AI가 학습 데이터(Training Data)에 포함된 통계적 규칙성(Statistical Regularities)에 크게 의존한다는 것입니다. 현대 AI 모델은 매우 정교한 패턴을 발견할 수 있지만 상관관계(Correlation)만으로는 그러한 패턴을 만들어내는 메커니즘을 이해한다고 보장할 수 없습니다. 익숙한 상관관계가 사라지거나 환경이 크게 변화하면 성능이 저하될 수 있습니다. 강건한 지능(Robust Intelligence)을 위해서는 안정적인 구조와 학습 과정에서 우연히 나타난 관계를 구별할 수 있어야 합니다.

일반화(Generalization)는 특히 분포 변화(Distribution Shift) 상황에서 여전히 어렵습니다. AI 모델은 일반적으로 새로운 입력이 학습 과정에서 경험한 조건과 유사할 때 가장 높은 성능을 나타냅니다. 익숙하지 않은 환경, 알려진 개념의 특이한 조합, 새로운 물리적 구성, 작업 규칙의 변화는 모델의 약점을 드러낼 수 있습니다. 인간 지능은 기존 지식을 구성적으로 재사용할 수 있는 경우가 많지만 현재 시스템은 신뢰할 수 있는 성능을 회복하기 위해 추가 사례, 미세조정(Fine-Tuning), 프롬프팅(Prompting), 외부 지원(External Support)을 필요로 할 수 있습니다.

상식 추론(Common Sense Reasoning) 역시 지속적인 한계 가운데 하나입니다. 일상적인 지능은 객체, 사람, 공간, 시간, 물리적 과정, 일반적인 결과에 관한 방대한 암묵적 지식(Implicit Knowledge)에 의존합니다. 이러한 정보의 상당 부분은 인간이 다른 사람도 이미 알고 있다고 가정하기 때문에 명시적으로 표현되는 경우가 거의 없습니다. AI 시스템은 데이터로부터 상식의 일부를 습득할 수 있지만 여전히 단순한 물리적, 인과적, 시간적 또는 사회적 기대에 위배되는 결론을 생성할 수 있습니다.

인과적 추론(Causal Reasoning)은 패턴 인식(Pattern Recognition)에 비해 아직 충분히 성숙하지 않았습니다. 두 사건이 자주 함께 발생한다고 예측하는 것과 하나가 다른 하나의 원인인지, 어떤 메커니즘이 둘을 연결하는지, 개입(Intervention)했을 때 어떤 일이 발생할지를 이해하는 것은 서로 다른 문제입니다. 현재 AI는 적절한 구조나 사례가 제공되면 일정한 형태의 인과 추론을 수행할 수 있지만 복잡한 환경에서 강건한 인과 모델(Causal Models)을 자율적으로 발견하는 것은 여전히 어렵습니다. 이는 표면적인 상관관계가 변화할 때 신뢰할 수 있는 전이(Transfer)를 제한합니다.

구성적 일반화(Compositional Generalization) 역시 완전하지 않습니다. 지능은 익숙한 개념, 기술(Skills), 관계를 학습 과정에서 명시적으로 경험하지 않은 새로운 구성으로 결합할 수 있어야 합니다. 현재 모델은 특히 대규모 사전학습(Large-Scale Pretraining)의 지원을 받을 때 뛰어난 구성적 행동을 보여주기도 하지만 조합이 더욱 새로워지거나 제약조건이 복잡해질수록 신뢰성이 감소할 수 있습니다. 진정한 체계성(Systematicity)을 위해서는 다양한 맥락에서 안정적으로 재사용할 수 있는 구성요소가 필요합니다.

장기 추론(Long-Horizon Reasoning)은 여러 단계에 걸쳐 오류가 누적될 수 있기 때문에 추가적인 어려움을 발생시킵니다. 모델은 초기에는 타당한 추론을 생성하더라도 점차 원래 목표에서 벗어나거나, 제약조건을 간과하거나, 근거가 없는 가정을 도입할 수 있습니다. 복잡한 작업에는 장시간에 걸쳐 목표, 중간 상태(Intermediate States), 의존관계(Dependencies), 증거를 유지하는 능력이 필요합니다. 따라서 신뢰할 수 있는 AGI(Artificial General Intelligence)는 중간 추론이 현실과 계속 일치하는지를 지속적으로 검증하면서 일관성(Coherence)을 유지하는 메커니즘을 필요로 합니다.

계획(Planning) 역시 이와 관련된 문제를 가지고 있습니다. 그럴듯한 행동 시퀀스(Action Sequence)를 생성하는 것과 실제 실행 과정에서 계속 실행 가능한 계획을 만드는 것은 동일하지 않습니다. 현실 환경에는 불확실성(Uncertainty), 지연(Delays), 외란(Disturbances), 자원 한계(Resource Limitations), 예상하지 못한 사건이 존재합니다. 현재 AI는 구조화된 환경에서 효과적으로 계획을 지원할 수 있지만 강건한 자율 계획(Robust Autonomous Planning)을 위해서는 하나의 개방루프 시퀀스(Open-Loop Sequence)가 아니라 예측, 행동, 모니터링, 재계획(Replanning), 복구(Recovery)가 지속적으로 상호작용해야 합니다.

기억의 한계(Memory Limitations) 역시 현재의 인지 능력을 제한합니다. 많은 AI 시스템은 주로 유한한 컨텍스트(Finite Context) 안에서 작동하며 장기간에 걸쳐 지속적이고 구조화된 기억을 자연스럽게 유지하지 못합니다. 효과적인 지능을 위해서는 무엇을 기억하고, 무엇을 잊으며, 경험을 어떻게 통합(Consolidation)하고, 언제 관련 기억을 검색해야 하는지를 결정해야 합니다. 단순히 컨텍스트 길이(Context Length)를 증가시키는 것만으로는 이러한 문제가 완전히 해결되지 않습니다. 기억에는 조직화, 선택, 업데이트, 관련성을 고려한 검색(Relevance-Aware Retrieval)이 필요하기 때문입니다.

지속학습(Continual Learning)은 새로운 정보를 학습하는 과정이 이전에 획득한 능력을 방해할 수 있기 때문에 여전히 어렵습니다. 이러한 문제는 일반적으로 치명적 망각(Catastrophic Forgetting)과 관련되지만 현대 아키텍처는 리플레이(Replay), 모듈성(Modularity), 파라미터 효율적 적응(Parameter-Efficient Adaptation), 외부 기억(External Memory)을 통해 이를 완화할 수 있습니다. 일반지능 시스템은 중요한 기존 기술을 보존하면서 새로운 지식을 지속적으로 습득하고, 기존 지식을 단순히 유지하는 것이 아니라 언제 수정해야 하는지도 판단할 수 있어야 합니다.

메타인지(Metacognition)는 현재 시스템이 여전히 제한적인 또 다른 영역입니다. 신뢰할 수 있는 지능은 자신의 추론을 모니터링하고, 불확실성을 탐지하며, 충분한 정보가 부족한 상황을 인식하고, 추가적인 계산이나 지원이 필요한지를 결정할 수 있어야 합니다. 현재 모델은 때때로 불확실성을 표현하거나 자신의 출력을 비판할 수 있지만 언어적으로 표현된 신뢰도(Verbal Confidence)가 실제 정확성과 항상 일치하는 것은 아닙니다. 효과적인 메타인지를 위해서는 단순히 그럴듯한 신뢰도 표현을 생성하는 것이 아니라 내부적으로 보정된 모니터링(Calibrated Monitoring)이 필요합니다.

자기 모델링(Self-Modeling) 역시 아직 불완전합니다. 자율 시스템(Autonomous System)은 자신의 능력, 한계, 사용 가능한 도구, 지식, 자원, 현재 상태를 정확하게 표현할 수 있어야 합니다. 현재 AI는 실제로 사용할 수 없는 행동을 수행할 수 있는 것처럼 잘못 표현하거나 작업이 자신의 능력을 넘어선다는 사실을 인식하지 못할 수 있습니다. 강건한 자기 모델(Self-Model)은 에이전트가 달성 가능한 전략을 선택하고, 적절한 상황에서 도움을 요청하며, 자기 자신에 대한 비현실적인 가정에 기반한 계획을 회피할 수 있도록 합니다.

그라운딩(Grounding)은 주로 상징적 또는 디지털 정보(Symbolic or Digital Information)를 기반으로 학습된 시스템에서 근본적인 과제를 나타냅니다. 언어는 무게(Weight), 마찰(Friction), 균형(Balance), 거리(Distance), 위험(Danger), 노력(Effort), 접촉(Contact)을 설명할 수 있지만 텍스트 설명은 행동을 통해 이러한 속성을 직접 경험하는 것과 동일하지 않습니다. 다중모달 학습(Multimodal Learning)은 언어를 이미지, 비디오, 오디오 등의 신호와 연결하여 그라운딩을 향상시키지만 피지컬 AI(Physical AI)는 여기에 더하여 환경과의 직접적인 상호작용을 통한 감각운동 그라운딩(Sensorimotor Grounding)을 필요로 합니다.

체화(Embodiment)는 순수한 디지털 작업에서는 드러나지 않을 수 있는 한계를 노출합니다. 로봇은 기하학(Geometry), 동역학(Dynamics), 지연시간(Latency), 불확실성, 에너지(Energy), 마모(Wear), 접촉, 안전(Safety)과 관련된 물리적 제약조건 아래에서 작동해야 합니다. 잘못된 텍스트 예측은 쉽게 수정할 수 있지만 잘못된 물리적 행동은 되돌릴 수 없는 결과를 초래할 수 있습니다. 따라서 체화된 지능(Embodied Intelligence)은 많은 현재 AI 벤치마크가 요구하는 수준보다 더욱 강력한 보정(Calibration), 예측, 피드백 제어(Feedback Control), 고장 탐지(Failure Detection), 복구 능력을 필요로 합니다.

월드 모델링(World Modeling) 역시 아직 불완전합니다. 지능형 에이전트(Intelligent Agents)는 환경이 어떻게 변화하고 행동이 미래 상태(Future States)에 어떤 영향을 미치는지를 예측하는 내부 표현(Internal Representations)을 필요로 합니다. 현재 시스템은 강력한 예측 표현(Predictive Representations)을 학습할 수 있지만 환경이 부분 관측 가능(Partially Observable)하거나, 확률적(Stochastic)이거나, 상호작용적이거나, 다른 에이전트를 포함할 경우 장기 예측은 어려워집니다. 작은 예측 오류도 시간이 지나면서 누적될 수 있으므로 장기 지능에는 불확실성을 고려하는 계층적 월드 모델(Hierarchical World Models)이 중요합니다.

시간적 이해(Temporal Understanding)에도 이와 관련된 문제가 존재합니다. AI 시스템은 시간적 패턴(Temporal Patterns)을 식별하고 사건 시퀀스(Event Sequences)에 대해 추론할 수 있지만 장기간에 걸쳐 변화하는 상태의 일관된 표현을 유지하는 것은 여전히 어렵습니다. 현실 세계의 작업에서는 무엇이 변화했는지, 무엇이 여전히 참인지, 어떤 행동이 아직 완료되지 않았는지, 이전 사건이 미래 가능성을 어떻게 제한하는지를 알아야 합니다. 따라서 시간 인지(Temporal Cognition)는 단순히 관측 시퀀스를 처리하는 것을 넘어 지속적인 상태 추적(Persistent State Tracking)을 필요로 합니다.

사회적 인지(Social Cognition)는 인간 행동이 믿음(Beliefs), 의도(Intentions), 감정(Emotions), 관습(Conventions), 관계(Relationships), 문화적 맥락(Cultural Context)에 따라 달라지기 때문에 추가적인 불확실성을 발생시킵니다. AI는 많은 언어적·행동적 패턴을 모델링할 수 있지만 다른 사람의 내부 상태를 신뢰성 있게 추론하는 것은 본질적으로 불확실합니다. 인간과 상호작용하는 시스템은 사회적 예측을 사실로 간주해서는 안 되며 목표, 선호, 기대 또는 미래 행동을 해석할 때 불확실성을 유지해야 합니다.

인간 가치(Human Values)는 목표가 불완전하고, 모호하며, 서로 충돌하거나, 맥락에 따라 달라지는 경우가 많기 때문에 더욱 근본적인 과제를 제기합니다. 지시를 문자 그대로 해석한 결과가 실제 인간의 의도와 일치하지 않을 수 있습니다. 따라서 정렬(Alignment)을 위해서는 명시적인 목표, 암묵적인 선호(Implicit Preferences), 제약조건, 사회적 규범(Social Norms), 잠재적인 결과를 함께 추론해야 합니다. 현재 AI는 다양한 형태의 인간 지침(Human Guidance)을 따를 수 있지만 익숙하지 않은 상황까지 포함하는 강건한 정렬(Robust Alignment)은 해결된 능력이 아니라 여전히 개방된 문제(Open Problem)입니다.

데이터 의존성(Data Dependence)은 또 다른 구조적 한계를 만듭니다. 대규모 모델은 방대한 데이터셋으로부터 이점을 얻지만 이용 가능한 데이터에는 오류(Errors), 편향(Biases), 중복(Duplication), 누락된 관점(Missing Perspectives), 오래된 정보(Outdated Information), 일관되지 않은 라벨(Inconsistent Labels)이 포함될 수 있습니다. 데이터셋의 크기를 증가시키는 것만으로 이러한 문제가 자동으로 제거되지는 않습니다. 지능형 시스템은 증거의 품질을 평가하고, 신뢰할 수 있는 정보와 노이즈(Noise)를 구별하고, 정보원 사이의 충돌을 인식하며, 더 나은 증거를 얻었을 때 자신의 믿음을 업데이트할 수 있어야 합니다.

계산 효율성(Computational Efficiency) 역시 인지 능력을 제한합니다. 더 큰 모델과 추가적인 추론 시점 계산(Inference-Time Computation)은 성능을 향상시킬 수 있지만 지나치게 많은 에너지, 메모리, 지연시간, 하드웨어를 요구하는 지능은 많은 응용 분야에서 실용적이지 않을 수 있습니다. 피지컬 AI에서는 로봇이 전력(Power)과 열(Thermal) 제약조건 아래에서 작동하기 때문에 이러한 한계가 특히 명확하게 나타납니다. 효율적인 지능은 언제 단순한 응답으로 충분한지, 언제 비용이 높은 추론이 필요한지를 판단할 수 있어야 합니다.

강건성(Robustness)과 신뢰성(Reliability)은 높은 평균 벤치마크 성능이 드물지만 중대한 실패를 숨길 수 있기 때문에 핵심적인 문제로 남아 있습니다. AI 시스템은 수천 개의 일반적인 사례에서 성공하면서도 특이한 조합이나 적대적 조건(Adversarial Conditions)에서 예측하기 어렵게 실패할 수 있습니다. 안전 중요 응용(Safety-Critical Applications)에서는 평균 정확도뿐만 아니라 실패 분포(Failure Distributions), 불확실성, 경계 조건(Boundary Conditions), 그리고 시스템이 자신의 능력 밖에 있는 상황을 만났을 때의 복구 행동까지 이해해야 합니다.

따라서 평가(Evaluation) 자체도 현재 AI 생태계(Current AI Ecosystem)의 인지적 한계와 관련됩니다. 정적인 벤치마크(Static Benchmarks)는 알려진 테스트 분포에 대한 최적화를 유도할 수 있으며 적응, 인과적 이해, 지속적 기억, 체화된 수행 능력(Embodied Competence), 장기 자율성(Long-Term Autonomy)을 충분히 측정하지 못할 수 있습니다. 보다 포괄적인 평가는 새로운 환경, 상호작용형 작업(Interactive Tasks), 분포 변화, 변화하는 목표, 제한된 데이터, 불확실성, 그리고 시스템이 자신의 오류를 인식하고 복구할 수 있는 기회를 포함해야 합니다.

이러한 한계가 현재 AI에 의미 있는 지능이 존재하지 않는다는 것을 의미하지는 않습니다. 오히려 지능이 다차원적(Multidimensional)이며 언어 생성이나 패턴 인식에서의 높은 성능이 자동으로 인과적 이해, 그라운딩된 상식(Grounded Common Sense), 적응형 계획(Adaptive Planning), 자기지식(Self-Knowledge), 지속학습을 제공하지 않는다는 것을 보여줍니다. 서로 다른 능력은 각기 다른 속도로 발전할 수 있으며 미래의 시스템은 여러 아키텍처(Architectures), 기억, 도구(Tools), 모델, 학습 메커니즘을 결합할 가능성이 높습니다.

AGI에서 핵심 과제는 결국 통합(Integration)입니다. 일반지능은 지각(Perception), 기억, 추론, 인과 모델링(Causal Modeling), 상식, 계획, 메타학습(Meta-Learning), 자기 모델링, 체화, 상호작용(Interaction)이 하나의 일관된 적응형 시스템(Coherent Adaptive System)으로 작동하도록 요구합니다. AGI를 향한 발전은 하나의 독립된 능력을 극대화하는 것보다 이러한 기능을 조정하면서 불확실성을 인식하고, 경험으로부터 학습하며, 현실 세계가 학습 환경과 달라지는 경우에도 강건성을 유지할 수 있는 아키텍처를 구축하는 데 더욱 크게 의존할 수 있습니다.
