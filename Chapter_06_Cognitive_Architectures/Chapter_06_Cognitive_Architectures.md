**Volume 43 Cognitive Science for AI**


# Chapter 06. Cognitive Architectures

##  

## 06.00 Cognitive Architecture Overview

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

Cognitive architecture refers to the organized computational structure through which an intelligent system integrates perception, memory, attention, reasoning, learning, decision making, and action. Rather than treating intelligence as a collection of isolated abilities, cognitive architecture examines how these functions interact over time to produce coherent behavior. It therefore provides a system-level framework for understanding both natural and artificial intelligence.

A cognitive architecture defines not only which cognitive components exist but also how information moves among them. Sensory inputs may enter through perceptual processes, become selectively prioritized by attention, interact with working memory and stored knowledge, contribute to reasoning and prediction, and eventually influence decisions and actions. Feedback from those actions then changes subsequent perception, memory, and learning.

Perception provides the architecture with information about external and internal states. Visual, auditory, tactile, proprioceptive, linguistic, and other signals must be transformed from raw sensory patterns into representations that can support higher-level cognition. Perception is therefore not merely an input interface but an active interpretation process that continuously connects the cognitive system with its environment.

Attention regulates which information receives limited processing resources. Real environments contain more sensory and internal information than a cognitive system can analyze with equal depth. Attention selects relevant signals, suppresses distractions, shifts according to goals or unexpected events, and helps determine what enters working memory. It consequently acts as an important control mechanism connecting perception with higher cognitive processes.

Working memory maintains information that is immediately relevant to current cognition. It can preserve temporary goals, intermediate reasoning results, recent observations, instructions, and task context while operations are being performed. Because working memory has limited capacity, cognitive architectures require mechanisms for prioritizing, compressing, retrieving, and replacing information as tasks develop over time.

Long-term memory provides persistent knowledge beyond the immediate processing cycle. Episodic memory can preserve experiences and events, semantic memory can represent facts and concepts, and procedural memory can encode skills and action patterns. These memory systems allow current cognition to benefit from previous learning, enabling recognition, prediction, reasoning, planning, and behavior to build upon accumulated experience.

Learning changes the architecture through experience. New observations can modify representations, strengthen associations, create concepts, improve policies, update world knowledge, and refine strategies. Learning may occur gradually through repeated exposure or rapidly from important individual experiences. A cognitive architecture must therefore support both immediate information processing and longer-term adaptation of the mechanisms that produce behavior.

Reasoning operates on available representations to derive conclusions that are not directly present in current sensory input. It can combine prior knowledge with observations, compare alternatives, infer hidden causes, evaluate relationships, and solve unfamiliar problems. Reasoning may range from rapid associative processing to explicit multi-step deliberation, depending on task complexity, uncertainty, and available cognitive resources.

Prediction allows cognition to extend beyond the present state. An intelligent system continuously anticipates what may happen next, how objects or agents may behave, and what consequences different actions could produce. Prediction supports perception by creating expectations and supports planning by providing estimates of future states. Prediction errors can then drive attention, learning, belief revision, and adaptation.

Decision making converts competing possibilities into selected commitments. The architecture may evaluate goals, expected outcomes, costs, risks, uncertainty, social constraints, and previous experience before choosing an action. Some decisions can be generated rapidly through learned policies or heuristics, whereas others require deliberate comparison. Effective architectures must determine when immediate action is sufficient and when deeper evaluation is justified.

Dual-process organization provides one framework for coordinating these different computational demands. Fast processing can support familiar perception, intuitive judgment, routine language processing, and practiced actions. Slow processing can support planning, verification, complex reasoning, and unfamiliar problems. A supervisory mechanism can allocate computation between these modes according to confidence, novelty, uncertainty, risk, and task difficulty.

Metacognition adds another control layer by allowing the system to evaluate its own cognitive state. It can estimate confidence, detect uncertainty, recognize errors, monitor progress, and determine whether additional reasoning is required. Metacognitive signals can trigger memory retrieval, deeper analysis, strategy changes, external information gathering, or requests for assistance, making cognition more adaptive than a fixed processing pipeline.

Goals organize cognition around desired future states. They influence attention, memory retrieval, reasoning, planning, and action selection by defining what information and outcomes are currently relevant. Complex systems may maintain multiple goals simultaneously and resolve conflicts among them according to priorities and constraints. Goal management therefore provides direction across otherwise separate cognitive functions.

Planning connects goals with future action sequences. Rather than selecting only the next immediate response, a cognitive system can construct intermediate objectives, examine dependencies, predict consequences, and organize actions across time. Hierarchical planning can separate abstract strategic objectives from detailed operational actions, allowing cognition to reason across multiple temporal and conceptual scales.

Action closes the cognitive loop by allowing internal representations and decisions to influence the environment. Actions may include physical movement, communication, tool use, information search, or modification of internal computational states. Once an action occurs, its consequences become new observations. Cognition therefore operates as a continuous perception--reasoning--action cycle rather than a one-directional sequence from input to output.

Feedback enables the architecture to compare expected and actual outcomes. Successful predictions can reinforce models and strategies, while unexpected outcomes generate prediction errors that indicate incomplete knowledge or inappropriate assumptions. Feedback can modify confidence, redirect attention, update memory, initiate learning, and trigger replanning. Closed-loop feedback is therefore fundamental to adaptive intelligent behavior.

Emotion and motivational processes also influence cognitive architecture by assigning significance and urgency to events, goals, and possible outcomes. In biological cognition, these processes affect attention, memory, learning, risk evaluation, and action selection. Computational architectures may implement analogous functional mechanisms through reward signals, priorities, utility functions, drives, or dynamically changing goal values without reproducing biological emotion itself.

Cognitive architectures must also address the problem of representation. Information may be represented through symbols, distributed neural patterns, spatial structures, probabilistic states, language, sensory features, or combinations of these forms. Different representations support different operations, so integrated intelligence may require mechanisms that translate or align information across symbolic, neural, linguistic, perceptual, and action-oriented representations.

Classical cognitive architectures often emphasize explicit symbolic representations and structured rules for manipulating knowledge. Connectionist approaches instead emphasize distributed representations learned through networks of interacting computational units. Modern architectures increasingly combine these traditions, using learned neural representations for perception and prediction while incorporating memory, planning, tools, constraints, or structured reasoning for higher-level control.

Artificial intelligence provides a practical environment for implementing cognitive architectural principles. Foundation models can supply broad perceptual, linguistic, and reasoning capabilities, while external memory, retrieval systems, planners, tools, evaluators, and controllers provide complementary functions. The resulting architecture can transform a powerful predictive model into a larger system capable of persistent, adaptive, goal-directed behavior.

Agentic AI illustrates this architectural integration particularly clearly. An agent maintains goals and state, observes its environment, retrieves relevant knowledge, reasons about alternatives, selects tools or actions, evaluates outcomes, and updates future behavior. Agency therefore emerges not from a single cognitive component but from coordinated interactions among multiple functions operating within repeated closed-loop decision cycles.

World models can serve as internal predictive components of cognitive architectures. They represent aspects of the environment and estimate how states may evolve through time or under different actions. By simulating possible futures, a cognitive system can evaluate candidate plans before execution. Differences between predicted and observed states then provide signals for updating beliefs, models, strategies, and confidence.

For Physical AI, cognitive architecture must connect high-level intelligence with real-time embodied control. Perception, localization, world modeling, memory, task reasoning, motion planning, manipulation, safety monitoring, and low-level control operate at different frequencies and computational scales. The architecture must coordinate these processes while preserving rapid responses to immediate hazards and deeper reasoning for complex goals.

An embodied cognitive architecture must remain grounded in continuous interaction with the physical world. Internal beliefs can become outdated as objects move, people act, sensors drift, or environmental conditions change. Consequently, perception must repeatedly correct internal representations, actions must be evaluated through feedback, and plans must remain revisable. Intelligence becomes a continuous process of maintaining useful alignment between internal models and external reality.

Cognitive architecture ultimately provides the organizational foundation through which separate cognitive capabilities become an integrated intelligent system. Perception supplies evidence, attention prioritizes it, memory preserves experience, reasoning interprets possibilities, prediction anticipates futures, planning organizes actions, metacognition supervises processing, and feedback supports learning. Their coordinated interaction creates adaptive cognition capable of pursuing goals in changing environments.

인지 아키텍처(Cognitive Architecture)는 지능형 시스템이 지각(Perception), 기억(Memory), 주의(Attention), 추론(Reasoning), 학습(Learning), 의사결정(Decision Making), 행동(Action)을 통합하는 조직화된 계산 구조(Computational Structure)를 의미합니다. 지능을 서로 분리된 능력들의 집합으로 취급하는 대신, 인지 아키텍처는 이러한 기능들이 시간에 따라 어떻게 상호작용하여 일관된 행동(Coherent Behavior)을 만들어내는지를 다룹니다. 따라서 자연 지능(Natural Intelligence)과 인공지능(Artificial Intelligence)을 모두 이해하기 위한 시스템 수준 프레임워크(System-level Framework)를 제공합니다.

인지 아키텍처는 어떤 인지 구성 요소(Cognitive Components)가 존재하는지만 정의하는 것이 아니라 정보가 이들 사이에서 어떻게 이동하는지도 정의합니다. 감각 입력(Sensory Inputs)은 지각 과정을 통해 들어오고, 주의에 의해 선택적으로 우선순위가 결정되며, 작업 기억(Working Memory) 및 저장된 지식과 상호작용하고, 추론과 예측(Prediction)에 기여한 후 최종적으로 의사결정과 행동에 영향을 줄 수 있습니다. 이러한 행동에서 발생한 피드백(Feedback)은 이후의 지각, 기억, 학습을 다시 변화시킵니다.

지각(Perception)은 외부 및 내부 상태에 대한 정보를 아키텍처에 제공합니다. 시각(Visual), 청각(Auditory), 촉각(Tactile), 고유수용감각(Proprioceptive), 언어적(Linguistic) 신호와 기타 신호는 원시 감각 패턴(Raw Sensory Patterns)에서 상위 수준 인지를 지원할 수 있는 표상(Representations)으로 변환되어야 합니다. 따라서 지각은 단순한 입력 인터페이스(Input Interface)가 아니라 인지 시스템을 환경과 지속적으로 연결하는 능동적인 해석 과정(Active Interpretation Process)입니다.

주의(Attention)는 어떤 정보에 제한된 처리 자원(Processing Resources)을 할당할지를 조절합니다. 실제 환경에는 인지 시스템이 동일한 깊이로 분석할 수 있는 양보다 훨씬 많은 감각 정보와 내부 정보가 존재합니다. 주의는 관련 신호를 선택하고, 방해 요소를 억제하며, 목표나 예상하지 못한 사건에 따라 이동하고, 어떤 정보가 작업 기억에 들어갈지를 결정하는 데 도움을 줍니다. 따라서 주의는 지각과 상위 인지 과정(Higher Cognitive Processes)을 연결하는 중요한 제어 메커니즘(Control Mechanism)으로 기능합니다.

작업 기억(Working Memory)은 현재의 인지 활동과 직접적으로 관련된 정보를 유지합니다. 작업이 수행되는 동안 임시 목표(Temporary Goals), 중간 추론 결과(Intermediate Reasoning Results), 최근 관찰, 명령(Instructions), 과제 문맥(Task Context)을 보존할 수 있습니다. 작업 기억의 용량은 제한되어 있기 때문에 인지 아키텍처는 과제가 시간에 따라 진행됨에 따라 정보를 우선순위화하고, 압축하고, 검색(Retrieval)하고, 교체하기 위한 메커니즘을 필요로 합니다.

장기 기억(Long-term Memory)은 즉각적인 처리 주기를 넘어 지속적인 지식을 제공합니다. 일화 기억(Episodic Memory)은 경험과 사건을 보존하고, 의미 기억(Semantic Memory)은 사실과 개념을 표현하며, 절차 기억(Procedural Memory)은 기술과 행동 패턴(Action Patterns)을 인코딩할 수 있습니다. 이러한 기억 시스템을 통해 현재의 인지는 이전의 학습을 활용할 수 있으며, 인식(Recognition), 예측, 추론, 계획(Planning), 행동이 축적된 경험을 기반으로 수행될 수 있습니다.

학습(Learning)은 경험을 통해 아키텍처를 변화시킵니다. 새로운 관찰은 표상을 수정하고, 연관성(Associations)을 강화하고, 개념을 형성하고, 정책(Policies)을 개선하고, 세계 지식(World Knowledge)을 업데이트하고, 전략을 정교화할 수 있습니다. 학습은 반복적인 노출을 통해 점진적으로 이루어질 수도 있고 중요한 개별 경험을 통해 빠르게 발생할 수도 있습니다. 따라서 인지 아키텍처는 즉각적인 정보 처리뿐 아니라 행동을 생성하는 메커니즘의 장기적인 적응(Long-term Adaptation)도 지원해야 합니다.

추론(Reasoning)은 이용 가능한 표상을 기반으로 현재의 감각 입력에 직접적으로 존재하지 않는 결론을 도출합니다. 사전 지식(Prior Knowledge)과 관찰을 결합하고, 대안을 비교하며, 숨겨진 원인(Hidden Causes)을 추론하고, 관계를 평가하며, 익숙하지 않은 문제를 해결할 수 있습니다. 추론은 과제 복잡도(Task Complexity), 불확실성(Uncertainty), 이용 가능한 인지 자원에 따라 빠른 연상 처리(Associative Processing)에서부터 명시적인 다단계 숙고(Multi-step Deliberation)에 이르기까지 다양한 형태를 가질 수 있습니다.

예측(Prediction)은 인지가 현재 상태를 넘어 미래로 확장될 수 있도록 합니다. 지능형 시스템은 다음에 무엇이 발생할 수 있는지, 객체나 에이전트(Agent)가 어떻게 행동할지, 서로 다른 행동이 어떤 결과를 발생시킬지를 지속적으로 예상합니다. 예측은 기대(Expectations)를 생성함으로써 지각을 지원하고 미래 상태를 추정함으로써 계획을 지원합니다. 이후 발생하는 예측 오류(Prediction Errors)는 주의, 학습, 믿음 수정(Belief Revision), 적응(Adaptation)을 촉진할 수 있습니다.

의사결정(Decision Making)은 서로 경쟁하는 여러 가능성을 하나의 선택된 결정으로 변환합니다. 아키텍처는 행동을 선택하기 전에 목표, 예상 결과(Expected Outcomes), 비용, 위험(Risk), 불확실성, 사회적 제약(Social Constraints), 이전 경험을 평가할 수 있습니다. 일부 결정은 학습된 정책이나 휴리스틱(Heuristics)을 통해 빠르게 생성될 수 있지만 다른 결정은 숙고적인 비교를 필요로 합니다. 효과적인 아키텍처는 언제 즉각적인 행동으로 충분한지와 언제 더 깊은 평가가 필요한지를 결정해야 합니다.

이중 처리 조직(Dual-process Organization)은 서로 다른 계산 요구를 조정하기 위한 하나의 프레임워크를 제공합니다. 빠른 처리(Fast Processing)는 익숙한 지각, 직관적 판단(Intuitive Judgment), 일상적인 언어 처리, 숙련된 행동을 지원할 수 있습니다. 느린 처리(Slow Processing)는 계획, 검증(Verification), 복잡한 추론, 익숙하지 않은 문제를 지원할 수 있습니다. 감독 메커니즘(Supervisory Mechanism)은 자신감(Confidence), 새로움(Novelty), 불확실성, 위험, 과제 난이도에 따라 두 처리 방식 사이에 계산 자원을 할당할 수 있습니다.

메타인지(Metacognition)는 시스템이 자신의 인지 상태를 평가할 수 있도록 함으로써 또 하나의 제어 계층(Control Layer)을 추가합니다. 자신감을 추정하고, 불확실성을 감지하고, 오류를 인식하고, 진행 상황을 모니터링하며, 추가적인 추론이 필요한지를 결정할 수 있습니다. 메타인지적 신호(Metacognitive Signals)는 기억 검색, 더 깊은 분석, 전략 변경, 외부 정보 수집(External Information Gathering), 지원 요청을 활성화할 수 있으며, 이를 통해 인지가 고정된 처리 파이프라인보다 더욱 적응적으로 작동하도록 합니다.

목표(Goals)는 원하는 미래 상태(Desired Future States)를 중심으로 인지를 조직합니다. 목표는 현재 어떤 정보와 결과가 중요한지를 정의함으로써 주의, 기억 검색, 추론, 계획, 행동 선택(Action Selection)에 영향을 줍니다. 복잡한 시스템은 여러 목표를 동시에 유지하고 우선순위(Priorities)와 제약 조건(Constraints)에 따라 이들 사이의 충돌을 해결할 수 있습니다. 따라서 목표 관리는 서로 분리되어 있을 수 있는 인지 기능 전반에 방향성을 제공합니다.

계획(Planning)은 목표와 미래의 행동 시퀀스(Action Sequences)를 연결합니다. 인지 시스템은 다음의 즉각적인 반응만을 선택하는 대신 중간 목표(Intermediate Objectives)를 구성하고, 의존 관계(Dependencies)를 검토하고, 결과를 예측하며, 시간에 따라 행동을 조직할 수 있습니다. 계층적 계획(Hierarchical Planning)은 추상적인 전략 목표와 세부적인 운영 행동(Operational Actions)을 분리하여 인지가 여러 시간적 및 개념적 척도에 걸쳐 추론할 수 있도록 합니다.

행동(Action)은 내부 표상과 의사결정이 환경에 영향을 미칠 수 있도록 함으로써 인지 루프(Cognitive Loop)를 완성합니다. 행동에는 물리적 움직임(Physical Movement), 의사소통(Communication), 도구 사용(Tool Use), 정보 검색(Information Search), 내부 계산 상태의 변경 등이 포함될 수 있습니다. 행동이 발생하면 그 결과는 새로운 관찰이 됩니다. 따라서 인지는 입력에서 출력으로 진행하는 단방향 과정이 아니라 지속적인 지각--추론--행동(Perception--Reasoning--Action) 주기로 작동합니다.

피드백(Feedback)은 아키텍처가 예상된 결과와 실제 결과를 비교할 수 있도록 합니다. 성공적인 예측은 모델과 전략을 강화할 수 있지만 예상하지 못한 결과는 불완전한 지식이나 부적절한 가정을 나타내는 예측 오류를 생성합니다. 피드백은 자신감을 수정하고, 주의를 재지정하고, 기억을 업데이트하고, 학습을 시작하고, 재계획(Replanning)을 활성화할 수 있습니다. 따라서 폐루프 피드백(Closed-loop Feedback)은 적응적인 지능 행동(Adaptive Intelligent Behavior)의 기본적인 요소입니다.

감정(Emotion)과 동기 과정(Motivational Processes) 역시 사건, 목표, 가능한 결과에 중요성과 긴급성을 부여함으로써 인지 아키텍처에 영향을 미칩니다. 생물학적 인지(Biological Cognition)에서 이러한 과정은 주의, 기억, 학습, 위험 평가, 행동 선택에 영향을 줍니다. 계산 아키텍처에서는 생물학적 감정 자체를 재현하지 않더라도 보상 신호(Reward Signals), 우선순위, 효용 함수(Utility Functions), 욕구(Drives), 동적으로 변화하는 목표 가치(Goal Values)를 통해 기능적으로 유사한 메커니즘을 구현할 수 있습니다.

인지 아키텍처는 표상(Representation)의 문제도 다루어야 합니다. 정보는 기호(Symbols), 분산 신경 패턴(Distributed Neural Patterns), 공간 구조(Spatial Structures), 확률적 상태(Probabilistic States), 언어(Language), 감각 특징(Sensory Features), 또는 이들의 조합으로 표현될 수 있습니다. 서로 다른 표상은 서로 다른 연산을 지원하므로 통합 지능(Integrated Intelligence)은 기호적, 신경적, 언어적, 지각적, 행동 지향적(Action-oriented) 표상 사이에서 정보를 변환하거나 정렬하는 메커니즘을 필요로 할 수 있습니다.

고전적 인지 아키텍처(Classical Cognitive Architectures)는 명시적인 기호 표상(Symbolic Representations)과 지식을 조작하기 위한 구조화된 규칙(Structured Rules)을 강조하는 경우가 많습니다. 연결주의적 접근(Connectionist Approaches)은 상호작용하는 계산 단위의 네트워크를 통해 학습되는 분산 표상을 강조합니다. 현대 아키텍처는 이러한 전통을 점점 더 결합하여 지각과 예측에는 학습된 신경 표상(Neural Representations)을 사용하고, 상위 수준 제어에는 기억, 계획, 도구, 제약 조건 또는 구조화된 추론(Structured Reasoning)을 활용합니다.

인공지능(Artificial Intelligence)은 인지 아키텍처 원리를 구현할 수 있는 실용적인 환경을 제공합니다. 파운데이션 모델(Foundation Models)은 광범위한 지각, 언어, 추론 능력을 제공할 수 있으며, 외부 기억(External Memory), 검색 시스템(Retrieval Systems), 계획기(Planners), 도구, 평가기(Evaluators), 제어기(Controllers)는 이를 보완하는 기능을 제공합니다. 이러한 구성 요소를 결합한 아키텍처는 강력한 예측 모델을 지속적이고 적응적이며 목표 지향적인 행동이 가능한 더 큰 시스템으로 확장할 수 있습니다.

에이전트형 인공지능(Agentic AI)은 이러한 아키텍처적 통합을 특히 명확하게 보여줍니다. 에이전트는 목표와 상태를 유지하고, 환경을 관찰하고, 관련 지식을 검색하고, 대안을 추론하며, 도구나 행동을 선택하고, 결과를 평가하며, 이후의 행동을 업데이트합니다. 따라서 에이전트성(Agency)은 하나의 인지 구성 요소에서 발생하는 것이 아니라 반복적인 폐루프 의사결정 주기(Closed-loop Decision Cycles) 안에서 작동하는 여러 기능의 조정된 상호작용에서 나타납니다.

월드 모델(World Models)은 인지 아키텍처 내부의 예측 구성 요소(Predictive Components)로 기능할 수 있습니다. 월드 모델은 환경의 여러 측면을 표현하고 상태가 시간에 따라 또는 서로 다른 행동에 의해 어떻게 변화할지를 추정합니다. 가능한 미래를 시뮬레이션함으로써 인지 시스템은 실행 전에 후보 계획(Candidate Plans)을 평가할 수 있습니다. 이후 예측 상태와 실제 관찰 상태의 차이는 믿음, 모델, 전략, 자신감을 업데이트하기 위한 신호를 제공합니다.

피지컬 인공지능(Physical AI)에서 인지 아키텍처는 상위 수준 지능(High-level Intelligence)과 실시간 체화 제어(Real-time Embodied Control)를 연결해야 합니다. 지각, 위치 추정(Localization), 월드 모델링(World Modeling), 기억, 과제 추론(Task Reasoning), 모션 계획(Motion Planning), 조작(Manipulation), 안전 모니터링(Safety Monitoring), 저수준 제어(Low-level Control)는 서로 다른 주기와 계산 규모에서 작동합니다. 아키텍처는 즉각적인 위험에 대한 빠른 대응과 복잡한 목표에 대한 깊은 추론을 모두 유지하면서 이러한 과정을 조정해야 합니다.

체화된 인지 아키텍처(Embodied Cognitive Architecture)는 물리적 세계와의 지속적인 상호작용에 기반을 두어야 합니다. 객체가 이동하거나, 사람이 행동하거나, 센서에 드리프트(Drift)가 발생하거나, 환경 조건이 변화하면서 내부 믿음(Internal Beliefs)은 오래된 정보가 될 수 있습니다. 따라서 지각은 내부 표상을 반복적으로 수정해야 하고, 행동은 피드백을 통해 평가되어야 하며, 계획은 지속적으로 수정 가능해야 합니다. 지능은 내부 모델과 외부 현실(External Reality) 사이의 유용한 정렬(Alignment)을 지속적으로 유지하는 과정이 됩니다.

궁극적으로 인지 아키텍처(Cognitive Architecture)는 서로 분리된 인지 능력을 하나의 통합된 지능형 시스템(Integrated Intelligent System)으로 만드는 조직적 기반을 제공합니다. 지각은 증거를 제공하고, 주의는 이를 우선순위화하며, 기억은 경험을 보존하고, 추론은 가능성을 해석하며, 예측은 미래를 예상하고, 계획은 행동을 조직하며, 메타인지는 처리 과정을 감독하고, 피드백은 학습을 지원합니다. 이러한 기능의 조정된 상호작용을 통해 변화하는 환경에서 목표를 추구할 수 있는 적응적 인지(Adaptive Cognition)가 형성됩니다.

##  

## 06.01 SOAR [w/Code]

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

SOAR is a cognitive architecture designed to model general intelligent behavior through a unified computational framework for problem solving, reasoning, learning, memory, and action. Rather than constructing separate systems for every cognitive task, SOAR organizes cognition around common mechanisms that can operate across different domains. Its central objective is to explain how an intelligent agent can select actions, solve problems, acquire knowledge, and improve through experience.

The architecture originated from research on human cognition and artificial intelligence and was developed as an attempt to formulate a general theory of cognition. SOAR treats intelligence as the coordinated operation of persistent architectural mechanisms rather than as a collection of unrelated algorithms. Knowledge can vary between tasks, while the underlying mechanisms for decision making, learning, memory access, and problem solving remain relatively stable.

SOAR represents an agent\'s current situation through a working memory containing symbolic structures that describe states, goals, objects, relationships, and other task-relevant information. Working memory changes continuously as perception introduces new information and internal reasoning generates additional structures. It therefore provides the active context within which the architecture evaluates possible actions and determines what should happen next.

Long-term knowledge is primarily represented through production rules that specify relationships between conditions and actions. When conditions represented in working memory match the conditions of a production, that knowledge becomes applicable to the current situation. Multiple productions can match simultaneously, allowing different pieces of knowledge to contribute in parallel before the architecture selects among possible operators.

Operators are central to SOAR because they represent possible transformations of the current state. An operator may correspond to an external action, an internal reasoning step, a change in problem representation, or progress toward a goal. Cognition repeatedly proposes operators, evaluates them, selects an appropriate operator, and applies it, creating a structured decision cycle through which behavior unfolds over time.

The decision cycle provides the basic rhythm of processing within SOAR. Knowledge in long-term memory matches the current working-memory state, productions generate preferences concerning possible operators, and the architecture evaluates those preferences to select an operator. The selected operator is then applied, potentially changing working memory or producing an external action, after which the cycle begins again with the updated state.

Preferences allow knowledge to influence operator selection without requiring every decision to be encoded as a rigid sequence. Productions can indicate that an operator is acceptable, preferable, worse than another, or otherwise related to competing alternatives. The decision procedure integrates these preferences to determine whether sufficient information exists to make a choice, separating domain knowledge from the architectural mechanism responsible for selection.

A distinctive feature of SOAR is its treatment of situations in which normal knowledge is insufficient to make progress. If the architecture cannot select an operator, cannot determine how an operator should be applied, or encounters another unresolved decision, an impasse occurs. Instead of treating the impasse merely as failure, SOAR automatically creates a substate in which additional reasoning can be performed to resolve the difficulty.

Substates provide a mechanism for deliberate problem solving. The architecture can reason about why the higher-level decision cannot proceed, search for missing information, compare alternatives, or determine how an operator should be implemented. Because substates can themselves encounter impasses, SOAR can create nested reasoning structures. Complex problem solving can therefore emerge recursively from the same basic architectural mechanisms used for ordinary decisions.

Once reasoning within a substate resolves an impasse, the resulting knowledge can influence the higher-level state and allow processing to continue. This organization provides a natural relationship between routine behavior and deliberation. Familiar situations can proceed through rapid operator selection, whereas difficult situations automatically generate additional reasoning when existing knowledge is insufficient to determine the next step.

Chunking is SOAR\'s characteristic learning mechanism for converting problem-solving experience into reusable knowledge. When reasoning in a substate produces a useful result, SOAR can construct a new production rule that captures the conditions responsible for that result. If a similar situation occurs later, the learned production can generate the result directly, reducing or eliminating the need to repeat the original deliberative reasoning process.

This learning process illustrates an important relationship between deliberate and automatic cognition. A problem may initially require several reasoning steps and nested substates, but after successful experience, chunking can compile the relevant result into production knowledge. Repeated problems can therefore become faster and more direct over time, providing an architectural explanation for how deliberate problem solving can develop into efficient skilled behavior.

SOAR also includes mechanisms beyond procedural production knowledge. Semantic memory can preserve general declarative knowledge about concepts, facts, and relationships, while episodic memory can store information associated with previous experiences. These memory systems allow an agent to retrieve knowledge that is not necessarily available through immediate production matching and to use previous states or events during current reasoning.

Semantic memory supports access to relatively context-independent knowledge. An agent may retrieve properties of objects, conceptual relationships, or previously learned facts when such information becomes relevant to a task. This extends cognition beyond the knowledge currently active in working memory and allows reasoning to incorporate persistent declarative information without requiring every fact to be encoded directly into procedural rules.

Episodic memory provides access to previous experiences represented as sequences or snapshots of earlier states. When an agent encounters a new problem, retrieval of related episodes can provide information about what occurred in similar situations. Episodic memory can therefore support reasoning from experience, reconstruction of previous contexts, and decisions that depend on knowledge of earlier interactions rather than only generalized facts.

Perception and action connect SOAR with an external environment. Perceptual systems introduce representations of environmental conditions into working memory, while selected operators can generate commands that affect the environment. The consequences of those actions produce new perceptual information, creating a continuous closed loop between cognition and the world rather than limiting the architecture to abstract symbolic problem solving.

SOAR can be interpreted through a dual-process perspective even though its original organization is not simply identical to System 1 and System 2. Production-based processing can support rapid responses when appropriate knowledge already exists, while impasses and substates introduce additional reasoning when direct processing cannot resolve a decision. Chunking then allows solutions discovered through slower reasoning to become available as faster procedural knowledge in future situations.

Goals are represented within the evolving cognitive state and influence which operators are relevant to current behavior. Complex objectives can produce sequences of intermediate decisions, while impasses can generate subordinate reasoning processes needed to continue toward the objective. SOAR therefore supports goal-directed cognition without requiring every complete action sequence to be predetermined before execution.

SOAR\'s symbolic organization provides interpretability because states, operators, preferences, production rules, and goals can often be examined explicitly. Researchers can investigate why particular operators were proposed, what knowledge influenced a decision, and how learned productions changed later behavior. This transparency distinguishes traditional cognitive architectures from many large neural models whose internal representations are distributed across learned parameters.

At the same time, symbolic cognitive architectures face challenges when processing high-dimensional sensory information such as images, speech, and complex continuous environments. Modern intelligent systems can therefore combine neural perception with symbolic cognitive mechanisms. Neural models may transform raw sensory data into structured representations, while SOAR-like mechanisms can manage goals, reasoning, memory, decisions, and learned procedural knowledge at a higher level.

This possibility makes SOAR conceptually relevant to contemporary hybrid AI architectures. Deep learning can provide powerful representation learning and pattern recognition, while cognitive architecture provides persistent state, explicit goals, structured memory, decision cycles, and mechanisms for deliberate problem solving. The two approaches address different aspects of intelligence and can potentially be integrated rather than treated as mutually exclusive alternatives.

For agentic AI, SOAR offers an important historical and conceptual example of intelligence organized around repeated perception--decision--action cycles. An agent does not merely generate a response to a single prompt but maintains state, evaluates alternatives, encounters difficulties, performs additional reasoning, learns from solutions, and continues acting. These principles closely resemble many requirements now associated with persistent autonomous AI agents.

SOAR is also relevant to Physical AI because embodied robots require coordination among perception, internal state, goals, decision making, memory, learning, and action. Fast learned behaviors can handle familiar situations, while unresolved conditions can trigger additional reasoning or planning. A hybrid robotic architecture could therefore combine neural perception and control with cognitive mechanisms inspired by SOAR for task-level reasoning and adaptive behavior.

The broader importance of SOAR lies in its attempt to explain intelligence through reusable architectural mechanisms rather than isolated task-specific solutions. Working memory represents the current cognitive state, production rules provide procedural knowledge, operators structure possible actions, preferences guide selection, impasses trigger deeper reasoning, substates support problem solving, and chunking converts successful deliberation into reusable knowledge.

SOAR ultimately demonstrates how cognition can be organized as a continuous interaction among representation, decision, reasoning, memory, learning, and action. Its architecture shows how an intelligent system can respond efficiently when knowledge is sufficient, deliberate when knowledge is insufficient, and learn from that deliberation so future behavior becomes more effective. These ideas remain relevant when designing hybrid, agentic, and embodied AI systems that must operate adaptively over extended periods.

SOAR는 문제 해결(Problem Solving), 추론(Reasoning), 학습(Learning), 기억(Memory), 행동(Action)을 위한 통합된 계산 프레임워크(Unified Computational Framework)를 통해 일반적인 지능 행동(General Intelligent Behavior)을 모델링하도록 설계된 인지 아키텍처(Cognitive Architecture)입니다. 각각의 인지 과제를 위해 별도의 시스템을 구성하는 대신, SOAR는 다양한 도메인에서 공통적으로 작동할 수 있는 메커니즘을 중심으로 인지를 조직합니다. 핵심 목표는 지능형 에이전트(Intelligent Agent)가 행동을 선택하고, 문제를 해결하며, 지식을 습득하고, 경험을 통해 향상되는 방식을 설명하는 것입니다.

이 아키텍처는 인간 인지(Human Cognition)와 인공지능(Artificial Intelligence)에 관한 연구에서 시작되었으며, 일반적인 인지 이론(General Theory of Cognition)을 정립하려는 시도로 개발되었습니다. SOAR는 지능을 서로 관련되지 않은 알고리즘의 집합이 아니라 지속적으로 유지되는 아키텍처 메커니즘(Architectural Mechanisms)의 조정된 작동으로 봅니다. 과제에 따라 지식은 달라질 수 있지만 의사결정, 학습, 기억 접근, 문제 해결을 위한 기본 메커니즘은 비교적 안정적으로 유지됩니다.

SOAR는 상태(State), 목표(Goals), 객체(Objects), 관계(Relationships), 기타 과제 관련 정보를 설명하는 기호 구조(Symbolic Structures)를 포함하는 작업 기억(Working Memory)을 통해 에이전트의 현재 상황을 표현합니다. 지각(Perception)을 통해 새로운 정보가 들어오고 내부 추론을 통해 추가적인 구조가 생성되면서 작업 기억은 지속적으로 변화합니다. 따라서 작업 기억은 아키텍처가 가능한 행동을 평가하고 다음에 무엇을 수행해야 하는지를 결정하는 능동적인 문맥(Active Context)을 제공합니다.

장기 지식(Long-term Knowledge)은 주로 조건(Conditions)과 행동(Actions) 사이의 관계를 지정하는 생성 규칙(Production Rules)을 통해 표현됩니다. 작업 기억에 표현된 조건이 생성 규칙의 조건과 일치하면 해당 지식은 현재 상황에 적용 가능한 상태가 됩니다. 여러 생성 규칙이 동시에 일치할 수 있으므로 아키텍처가 가능한 연산자(Operators) 가운데 하나를 선택하기 전에 서로 다른 지식들이 병렬적으로 의사결정에 기여할 수 있습니다.

연산자(Operators)는 현재 상태에 적용할 수 있는 가능한 변환(Transformations)을 나타내기 때문에 SOAR에서 핵심적인 역할을 합니다. 연산자는 외부 행동(External Action), 내부 추론 단계(Internal Reasoning Step), 문제 표상의 변화(Change in Problem Representation), 또는 목표를 향한 진행을 나타낼 수 있습니다. 인지는 연산자를 반복적으로 제안하고, 평가하고, 적절한 연산자를 선택하고, 이를 적용하며, 이러한 구조화된 의사결정 주기(Decision Cycle)를 통해 시간에 따라 행동을 전개합니다.

의사결정 주기(Decision Cycle)는 SOAR 내부 처리의 기본적인 리듬을 제공합니다. 장기 기억의 지식이 현재 작업 기억 상태와 일치하고, 생성 규칙은 가능한 연산자에 관한 선호도(Preferences)를 생성하며, 아키텍처는 이러한 선호도를 평가하여 하나의 연산자를 선택합니다. 선택된 연산자가 적용되면 작업 기억이 변경되거나 외부 행동이 발생할 수 있으며, 이후 업데이트된 상태를 기반으로 새로운 주기가 다시 시작됩니다.

선호도(Preferences)는 모든 의사결정을 엄격한 순서로 인코딩하지 않고도 지식이 연산자 선택에 영향을 줄 수 있도록 합니다. 생성 규칙은 특정 연산자가 허용 가능하거나, 다른 연산자보다 선호되거나, 더 나쁘거나, 경쟁하는 대안들과 특정한 관계를 가진다는 것을 나타낼 수 있습니다. 의사결정 절차(Decision Procedure)는 이러한 선호도를 통합하여 선택을 내리기에 충분한 정보가 존재하는지를 판단하며, 도메인 지식(Domain Knowledge)과 선택을 담당하는 아키텍처 메커니즘을 분리합니다.

SOAR의 특징적인 요소는 일반적인 지식만으로 진행하기 어려운 상황을 처리하는 방식입니다. 아키텍처가 연산자를 선택할 수 없거나, 연산자를 어떻게 적용해야 하는지 결정할 수 없거나, 해결되지 않은 다른 의사결정에 직면하면 교착 상태(Impasse)가 발생합니다. SOAR는 이러한 교착 상태를 단순한 실패로 취급하지 않고 추가적인 추론을 통해 문제를 해결할 수 있는 하위 상태(Substate)를 자동으로 생성합니다.

하위 상태(Substates)는 숙고적 문제 해결(Deliberative Problem Solving)을 위한 메커니즘을 제공합니다. 아키텍처는 상위 수준의 의사결정이 진행되지 못하는 이유를 추론하고, 누락된 정보를 탐색하며, 대안을 비교하거나, 연산자를 어떻게 구현해야 하는지를 결정할 수 있습니다. 하위 상태 자체에서도 교착 상태가 발생할 수 있기 때문에 SOAR는 중첩된 추론 구조(Nested Reasoning Structures)를 생성할 수 있습니다. 따라서 복잡한 문제 해결은 일반적인 의사결정에 사용되는 동일한 기본 아키텍처 메커니즘에서 재귀적으로 나타날 수 있습니다.

하위 상태 내부의 추론이 교착 상태를 해결하면 그 결과로 얻은 지식은 상위 수준 상태에 영향을 주어 처리가 계속될 수 있도록 합니다. 이러한 조직 방식은 일상적인 행동(Routine Behavior)과 숙고(Deliberation) 사이에 자연스러운 관계를 제공합니다. 익숙한 상황에서는 빠른 연산자 선택을 통해 처리가 진행될 수 있지만, 어려운 상황에서는 기존 지식만으로 다음 단계를 결정할 수 없을 때 자동적으로 추가적인 추론이 생성됩니다.

청킹(Chunking)은 문제 해결 경험을 재사용 가능한 지식(Reusable Knowledge)으로 변환하는 SOAR의 대표적인 학습 메커니즘입니다. 하위 상태에서의 추론이 유용한 결과를 생성하면 SOAR는 해당 결과를 만들어낸 조건들을 포착하는 새로운 생성 규칙을 구성할 수 있습니다. 이후 유사한 상황이 발생하면 학습된 생성 규칙이 해당 결과를 직접 생성하여 원래의 숙고적 추론 과정을 반복해야 할 필요성을 감소시키거나 제거할 수 있습니다.

이러한 학습 과정은 숙고적 인지(Deliberate Cognition)와 자동적 인지(Automatic Cognition) 사이의 중요한 관계를 보여줍니다. 처음에는 하나의 문제를 해결하기 위해 여러 추론 단계와 중첩된 하위 상태가 필요할 수 있지만, 성공적인 경험 이후에는 청킹을 통해 관련 결과를 생성 지식(Production Knowledge)으로 컴파일할 수 있습니다. 따라서 반복되는 문제는 시간이 지날수록 더욱 빠르고 직접적으로 처리될 수 있으며, 숙고적 문제 해결이 효율적인 숙련 행동(Skilled Behavior)으로 발전하는 방식을 아키텍처 수준에서 설명할 수 있습니다.

SOAR는 절차적 생성 지식(Procedural Production Knowledge) 이외의 메커니즘도 포함합니다. 의미 기억(Semantic Memory)은 개념, 사실, 관계에 관한 일반적인 선언적 지식(Declarative Knowledge)을 보존할 수 있으며, 일화 기억(Episodic Memory)은 이전 경험과 관련된 정보를 저장할 수 있습니다. 이러한 기억 시스템을 통해 에이전트는 즉각적인 생성 규칙 매칭만으로 사용할 수 없는 지식을 검색하고, 현재의 추론 과정에서 이전 상태나 사건을 활용할 수 있습니다.

의미 기억(Semantic Memory)은 비교적 문맥에 독립적인 지식(Context-independent Knowledge)에 대한 접근을 지원합니다. 에이전트는 과제에 필요한 경우 객체의 속성, 개념적 관계(Conceptual Relationships), 이전에 학습한 사실을 검색할 수 있습니다. 이를 통해 인지는 현재 작업 기억에서 활성화된 지식을 넘어 확장될 수 있으며, 모든 사실을 절차적 규칙으로 직접 인코딩하지 않고도 지속적인 선언적 정보를 추론 과정에 통합할 수 있습니다.

일화 기억(Episodic Memory)은 이전 상태의 시퀀스 또는 스냅샷(Snapshots)으로 표현된 과거 경험에 접근할 수 있도록 합니다. 에이전트가 새로운 문제에 직면하면 관련된 일화를 검색하여 유사한 상황에서 어떤 일이 발생했는지에 대한 정보를 얻을 수 있습니다. 따라서 일화 기억은 경험에 기반한 추론(Reasoning from Experience), 이전 문맥의 재구성, 일반화된 사실뿐 아니라 과거 상호작용에 관한 지식을 필요로 하는 의사결정을 지원할 수 있습니다.

지각(Perception)과 행동(Action)은 SOAR를 외부 환경과 연결합니다. 지각 시스템은 환경 상태에 대한 표상을 작업 기억에 입력하고, 선택된 연산자는 환경에 영향을 주는 명령을 생성할 수 있습니다. 이러한 행동의 결과는 다시 새로운 지각 정보를 발생시키며, 인지와 세계 사이에 지속적인 폐루프(Closed Loop)를 형성합니다. 따라서 SOAR는 추상적인 기호 문제 해결에만 제한되지 않고 환경과의 지속적인 상호작용을 표현할 수 있습니다.

SOAR의 원래 구조가 시스템 1(System 1)과 시스템 2(System 2)에 단순히 동일한 것은 아니지만 이중 처리 관점(Dual-process Perspective)을 통해 해석할 수 있습니다. 적절한 지식이 이미 존재하면 생성 규칙 기반 처리(Production-based Processing)가 빠른 반응을 지원할 수 있으며, 직접적인 처리만으로 의사결정을 해결할 수 없으면 교착 상태와 하위 상태를 통해 추가적인 추론이 수행됩니다. 이후 청킹은 느린 추론으로 발견한 해결책을 미래의 빠른 절차적 지식으로 사용할 수 있도록 합니다.

목표(Goals)는 변화하는 인지 상태 내부에 표현되며 현재 행동에 어떤 연산자가 관련되는지에 영향을 줍니다. 복잡한 목표는 일련의 중간 의사결정(Intermediate Decisions)을 발생시킬 수 있으며, 교착 상태는 목표를 향해 계속 진행하는 데 필요한 하위 추론 과정(Subordinate Reasoning Processes)을 생성할 수 있습니다. 따라서 SOAR는 실행 전에 전체 행동 시퀀스를 모두 미리 결정하지 않고도 목표 지향적 인지(Goal-directed Cognition)를 지원할 수 있습니다.

SOAR의 기호적 조직(Symbolic Organization)은 상태, 연산자, 선호도, 생성 규칙, 목표를 명시적으로 검사할 수 있기 때문에 해석 가능성(Interpretability)을 제공합니다. 연구자는 특정 연산자가 왜 제안되었는지, 어떤 지식이 의사결정에 영향을 미쳤는지, 학습된 생성 규칙이 이후의 행동을 어떻게 변화시켰는지를 조사할 수 있습니다. 이러한 투명성(Transparency)은 내부 표상이 학습된 파라미터 전체에 분산되어 있는 많은 대규모 신경 모델(Large Neural Models)과 전통적인 인지 아키텍처를 구분하는 특징입니다.

동시에 기호적 인지 아키텍처(Symbolic Cognitive Architectures)는 이미지, 음성, 복잡한 연속 환경(Continuous Environments)과 같은 고차원 감각 정보(High-dimensional Sensory Information)를 처리할 때 어려움에 직면할 수 있습니다. 따라서 현대의 지능형 시스템은 신경망 기반 지각(Neural Perception)과 기호적 인지 메커니즘을 결합할 수 있습니다. 신경 모델은 원시 감각 데이터를 구조화된 표상으로 변환하고, SOAR와 유사한 메커니즘은 상위 수준에서 목표, 추론, 기억, 의사결정, 학습된 절차적 지식을 관리할 수 있습니다.

이러한 가능성은 SOAR를 현대적인 하이브리드 인공지능 아키텍처(Hybrid AI Architectures)와 개념적으로 연결합니다. 딥러닝(Deep Learning)은 강력한 표상 학습(Representation Learning)과 패턴 인식(Pattern Recognition)을 제공할 수 있으며, 인지 아키텍처는 지속적인 상태(Persistent State), 명시적인 목표, 구조화된 기억(Structured Memory), 의사결정 주기, 숙고적 문제 해결 메커니즘을 제공합니다. 두 접근법은 지능의 서로 다른 측면을 다루기 때문에 상호 배타적인 대안이 아니라 잠재적으로 통합 가능한 접근법으로 볼 수 있습니다.

에이전트형 인공지능(Agentic AI)의 관점에서 SOAR는 반복적인 지각--의사결정--행동(Perception--Decision--Action) 주기를 중심으로 지능을 조직한 중요한 역사적·개념적 사례를 제공합니다. 에이전트는 단일 프롬프트에 대한 응답만 생성하는 것이 아니라 상태를 유지하고, 대안을 평가하고, 어려움에 직면하면 추가적인 추론을 수행하고, 해결책으로부터 학습하며, 이후에도 계속 행동합니다. 이러한 원리는 현재 지속적으로 작동하는 자율 인공지능 에이전트(Autonomous AI Agents)에 요구되는 여러 특성과 밀접하게 연결됩니다.

SOAR는 체화된 로봇(Embodied Robots)이 지각, 내부 상태, 목표, 의사결정, 기억, 학습, 행동을 조정해야 한다는 점에서 피지컬 인공지능(Physical AI)과도 관련이 있습니다. 빠르게 학습된 행동은 익숙한 상황을 처리할 수 있고, 해결되지 않은 조건은 추가적인 추론이나 계획(Planning)을 활성화할 수 있습니다. 따라서 하이브리드 로봇 아키텍처(Hybrid Robotic Architecture)는 신경망 기반 지각 및 제어와 SOAR에서 영감을 얻은 과제 수준 추론(Task-level Reasoning) 및 적응 행동 메커니즘을 결합할 수 있습니다.

SOAR의 보다 광범위한 중요성은 지능을 서로 분리된 과제별 해결책(Task-specific Solutions)이 아니라 재사용 가능한 아키텍처 메커니즘을 통해 설명하려는 시도에 있습니다. 작업 기억은 현재의 인지 상태를 표현하고, 생성 규칙은 절차적 지식(Procedural Knowledge)을 제공하며, 연산자는 가능한 행동을 구조화하고, 선호도는 선택을 안내하며, 교착 상태는 더 깊은 추론을 활성화하고, 하위 상태는 문제 해결을 지원하며, 청킹은 성공적인 숙고를 재사용 가능한 지식으로 변환합니다.

궁극적으로 SOAR는 인지가 표상(Representation), 의사결정, 추론, 기억, 학습, 행동 사이의 지속적인 상호작용으로 조직될 수 있음을 보여줍니다. SOAR의 아키텍처는 지식이 충분할 때 지능형 시스템이 효율적으로 반응하고, 지식이 부족할 때 숙고하며, 그 숙고 과정으로부터 학습하여 이후의 행동을 더욱 효과적으로 만들 수 있는 방식을 보여줍니다. 이러한 개념은 장기간에 걸쳐 적응적으로 작동해야 하는 하이브리드(Hybrid), 에이전트형(Agentic), 체화형 인공지능(Embodied AI) 시스템을 설계하는 데 여전히 중요한 의미를 가집니다.

##  

## 06.02 ACT R [w/Code]

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

ACT-R, or Adaptive Control of Thought---Rational, is a cognitive architecture developed to explain how human cognition emerges from interactions among perception, memory, learning, reasoning, and action. It proposes that diverse cognitive activities can be understood through a relatively stable set of computational mechanisms. Rather than modeling each task independently, ACT-R provides a unified architecture in which task-specific knowledge operates through common cognitive processes.

The architecture is strongly connected to experimental cognitive psychology and attempts to describe cognition at a level that can generate measurable behavioral predictions. ACT-R models can predict quantities such as response time, memory retrieval latency, error patterns, and learning effects. This emphasis distinguishes cognitive architecture from purely functional AI because the objective is not only successful task performance but also an explanation of how human-like cognitive processing unfolds over time.

ACT-R organizes cognition into specialized modules that perform different functions while communicating through a central production system. Modules can represent perceptual processing, motor activity, goals, declarative memory, and other cognitive capabilities. Each module maintains a limited interface called a buffer, allowing information to become available to the rest of the architecture without requiring unrestricted access to all internal module states.

Buffers are therefore critical communication structures within ACT-R. A buffer normally contains a small amount of currently active information represented as a chunk. The visual system may place information about a perceived object into a visual buffer, declarative memory may return retrieved knowledge through a retrieval buffer, and a goal buffer can maintain information relevant to the current objective. This limited availability reflects constraints on human cognitive processing.

Chunks are structured units used to represent declarative information. A chunk may encode an object, fact, event, relationship, goal state, or other meaningful knowledge through attributes and values. Declarative memory contains many chunks accumulated through experience, but only a small subset becomes active during a particular cognitive operation. Cognition therefore depends not merely on storing information but on efficiently retrieving relevant chunks when they are needed.

Declarative memory represents knowledge that can be explicitly retrieved, including facts and previous experiences. When the production system requests information, the memory system attempts to retrieve a chunk that satisfies the specified conditions. Retrieval is not treated as an instantaneous database lookup. Instead, ACT-R models memory accessibility quantitatively, allowing retrieval speed and probability to depend on previous use, recency, frequency, and contextual relevance.

Activation is a central concept governing declarative memory retrieval. Chunks with greater activation are generally easier and faster to retrieve, while chunks with low activation may require more time or fail to be recalled. Activation can reflect a history of previous encounters and current contextual influences. This provides a computational explanation for familiar psychological effects in which frequently or recently used information becomes more accessible.

Base-level activation captures how the history of using a memory influences its current accessibility. Knowledge that has been encountered repeatedly or used recently tends to maintain greater activation than rarely used or old information. However, activation gradually decreases over time. ACT-R therefore provides mechanisms for modeling both practice effects and forgetting as consequences of the changing accessibility of stored declarative knowledge.

Procedural knowledge is represented differently from declarative knowledge. Instead of chunks, ACT-R uses production rules that specify what cognitive operation should occur when particular conditions are satisfied. A production can inspect information currently available in buffers and initiate operations such as requesting a memory, shifting attention, updating a goal, or performing an action. Procedural cognition therefore controls how information is transformed and used.

The production system repeatedly evaluates which rules match the current buffer contents. When several productions are applicable, a conflict-resolution mechanism determines which production should execute. The selected production then changes buffers or requests operations from modules, producing a new cognitive state. Cognition unfolds as repeated cycles of matching conditions, selecting productions, executing operations, and responding to their consequences.

Production selection can incorporate utility, allowing the architecture to prefer actions that have historically produced valuable outcomes. A production associated with greater expected benefit can become more likely to be selected when several alternatives compete. Utility learning therefore provides a mechanism through which experience modifies procedural decision making, enabling the architecture to gradually favor strategies that have performed successfully.

Goals provide task-level direction within ACT-R. The goal buffer can maintain information describing the current objective or intermediate state of problem solving. Production rules inspect this information together with perceptual and memory contents to determine appropriate operations. As tasks progress, productions can modify the goal representation, effectively moving cognition through a sequence of intermediate states toward completion.

Perceptual modules connect cognition with incoming environmental information. Visual and auditory mechanisms can represent aspects of external stimuli and make selected information available through corresponding buffers. Attention determines which environmental information becomes available for further processing. This architecture allows perception to interact dynamically with goals and memory rather than functioning as an isolated preprocessing stage.

Motor modules allow cognitive decisions to produce observable behavior. Once procedural processing determines that an external response should occur, motor mechanisms execute the required action. Because perceptual, cognitive, and motor processes have temporal characteristics, ACT-R can model the total time required for tasks involving observation, memory retrieval, decision making, and physical response rather than treating cognition as instantaneous computation.

ACT-R places considerable emphasis on cognitive timing. Memory retrieval requires time, perceptual shifts require time, production execution requires time, and motor responses require time. These constraints allow models to generate detailed predictions about human performance. Differences of hundreds of milliseconds can become theoretically meaningful because they reveal how different cognitive operations contribute to the overall structure of behavior.

Learning occurs in both declarative and procedural components. Declarative learning changes the availability and activation of chunks as experience accumulates, while procedural learning can modify production utilities and develop more efficient strategies. Repeated performance can therefore transform slow and effortful task execution into faster behavior as relevant knowledge becomes more accessible and effective procedural choices become better established.

This transition can be interpreted in relation to automaticity. A novice may need several memory retrievals and intermediate cognitive steps to solve a problem, whereas an experienced individual may reach the appropriate response through a shorter sequence of well-practiced operations. ACT-R provides computational mechanisms for describing how repeated experience changes the timing, accessibility, and selection of cognitive processes without requiring an entirely different architecture.

ACT-R also provides an important model of bounded cognition. Memory retrieval can fail, attention is selective, buffers contain limited information, and cognitive operations require time. Intelligence is therefore modeled under resource constraints rather than assuming unlimited memory access and instantaneous reasoning. These limitations are essential for explaining errors, delays, interference, and other characteristics of actual human cognitive performance.

The architecture differs from conventional deep learning because much of its structure and knowledge organization is explicit. Chunks, buffers, production rules, activation values, utilities, and module interactions can be inspected and related to theoretical cognitive mechanisms. Deep neural networks instead learn distributed representations from large datasets. The approaches therefore emphasize different levels and mechanisms of intelligence.

Modern hybrid systems can potentially combine these strengths. Neural networks can provide perception, representation learning, language understanding, and prediction from high-dimensional data, while ACT-R-inspired mechanisms can provide structured working interfaces, explicit goals, memory retrieval, procedural control, and cognitive resource management. Such integration could connect learned representations with more interpretable task-level cognitive organization.

ACT-R is also relevant to contemporary memory-augmented and agentic AI. An artificial agent must maintain goals, retrieve relevant information, decide which operation to perform, observe results, and update subsequent behavior. These requirements resemble the interaction among goal buffers, declarative memory, productions, and perceptual or motor modules. ACT-R therefore provides useful historical principles for designing persistent goal-directed agents.

From a dual-process perspective, well-practiced production sequences and highly accessible memories can support relatively rapid processing, whereas unfamiliar tasks may require repeated retrieval, intermediate goals, and longer sequences of cognitive operations. ACT-R is not simply a System 1/System 2 architecture, but its mechanisms demonstrate how differences in practice, memory accessibility, and procedural organization can generate different levels of cognitive effort and processing speed.

For Physical AI, ACT-R offers conceptual lessons about coordinating perception, memory, goals, decision mechanisms, and action under limited resources. A robot similarly receives sensory information, maintains task state, retrieves relevant knowledge, selects operations, and executes physical responses. Modern robotic systems operate through different computational technologies, but the architectural problem of coordinating these functions remains closely related.

An embodied architecture inspired by ACT-R could combine neural perception with explicit task memory and procedural control. Sensor models could produce structured representations, memory systems could retrieve task-relevant knowledge, goal structures could maintain mission context, and learned policies or rules could select actions. Feedback from execution would then update the system, forming a continuous perception--cognition--action loop grounded in the physical environment.

The broader importance of ACT-R lies in its attempt to connect cognitive theory with executable computational models. Declarative chunks represent knowledge, activation controls accessibility, production rules represent procedural knowledge, utilities influence selection, buffers constrain communication, modules provide specialized functions, and learning modifies performance through experience. These mechanisms together create a detailed account of how multiple cognitive functions can cooperate.

ACT-R ultimately demonstrates that intelligent behavior can be understood as coordinated processing among specialized components operating under constraints of memory, attention, time, and experience. Its value extends beyond modeling individual psychological experiments because it provides a systematic framework for studying integrated cognition. The architecture remains relevant to discussions of hybrid AI, agentic systems, cognitive robotics, and artificial systems designed to combine memory, goals, reasoning, learning, and action.

ACT-R, 즉 사고의 적응적 통제--합리성(Adaptive Control of Thought---Rational)은 인간의 인지(Human Cognition)가 지각(Perception), 기억(Memory), 학습(Learning), 추론(Reasoning), 행동(Action) 사이의 상호작용을 통해 어떻게 나타나는지를 설명하기 위해 개발된 인지 아키텍처(Cognitive Architecture)입니다. ACT-R은 다양한 인지 활동이 비교적 안정적인 계산 메커니즘(Computational Mechanisms)의 집합을 통해 이해될 수 있다고 제안합니다. 각각의 과제를 독립적으로 모델링하는 대신, ACT-R은 과제별 지식(Task-specific Knowledge)이 공통된 인지 과정(Common Cognitive Processes)을 통해 작동하는 통합 아키텍처를 제공합니다.

이 아키텍처는 실험 인지심리학(Experimental Cognitive Psychology)과 밀접하게 연결되어 있으며, 측정 가능한 행동 예측(Measurable Behavioral Predictions)을 생성할 수 있는 수준에서 인지를 설명하려고 합니다. ACT-R 모델은 반응 시간(Response Time), 기억 검색 지연시간(Memory Retrieval Latency), 오류 패턴(Error Patterns), 학습 효과(Learning Effects)와 같은 값을 예측할 수 있습니다. 이러한 강조점은 인지 아키텍처를 순수하게 기능적인 인공지능과 구별합니다. 목표가 단순히 과제를 성공적으로 수행하는 것뿐 아니라 인간과 유사한 인지 처리(Human-like Cognitive Processing)가 시간에 따라 어떻게 전개되는지를 설명하는 것이기 때문입니다.

ACT-R은 서로 다른 기능을 수행하면서 중앙 생성 시스템(Central Production System)을 통해 통신하는 전문화된 모듈(Specialized Modules)들로 인지를 구성합니다. 모듈은 지각 처리(Perceptual Processing), 운동 활동(Motor Activity), 목표(Goals), 선언적 기억(Declarative Memory), 기타 인지 능력을 표현할 수 있습니다. 각각의 모듈은 버퍼(Buffer)라고 하는 제한된 인터페이스를 유지하며, 이를 통해 모든 내부 모듈 상태에 무제한으로 접근하지 않고도 정보를 아키텍처의 다른 부분에서 사용할 수 있도록 합니다.

따라서 버퍼(Buffers)는 ACT-R 내부에서 핵심적인 통신 구조(Communication Structures)입니다. 하나의 버퍼는 일반적으로 청크(Chunk)로 표현되는 소량의 현재 활성 정보를 포함합니다. 시각 시스템(Visual System)은 지각된 객체에 관한 정보를 시각 버퍼(Visual Buffer)에 배치할 수 있고, 선언적 기억은 검색된 지식을 검색 버퍼(Retrieval Buffer)를 통해 반환할 수 있으며, 목표 버퍼(Goal Buffer)는 현재 목표와 관련된 정보를 유지할 수 있습니다. 이러한 제한된 정보 이용 가능성은 인간의 인지 처리에 존재하는 제약을 반영합니다.

청크(Chunks)는 선언적 정보(Declarative Information)를 표현하기 위해 사용되는 구조화된 단위(Structured Units)입니다. 하나의 청크는 속성(Attributes)과 값(Values)을 통해 객체, 사실, 사건, 관계, 목표 상태 또는 기타 의미 있는 지식을 인코딩할 수 있습니다. 선언적 기억에는 경험을 통해 축적된 많은 청크가 존재하지만 특정 인지 연산 과정에서는 그중 일부만 활성화됩니다. 따라서 인지는 단순히 정보를 저장하는 것뿐 아니라 필요할 때 관련 청크를 효율적으로 검색하는 능력에도 의존합니다.

선언적 기억(Declarative Memory)은 사실과 이전 경험을 포함하여 명시적으로 검색할 수 있는 지식을 표현합니다. 생성 시스템이 정보를 요청하면 기억 시스템은 지정된 조건을 만족하는 청크를 검색하려고 시도합니다. 이러한 검색은 즉각적인 데이터베이스 조회(Database Lookup)로 처리되지 않습니다. 대신 ACT-R은 기억 접근성(Memory Accessibility)을 정량적으로 모델링하여 이전 사용, 최근성(Recency), 빈도(Frequency), 문맥적 관련성(Contextual Relevance)에 따라 검색 속도와 검색 가능성이 달라질 수 있도록 합니다.

활성화(Activation)는 선언적 기억 검색을 지배하는 핵심 개념입니다. 활성화 수준이 높은 청크는 일반적으로 더 쉽고 빠르게 검색되지만, 활성화 수준이 낮은 청크는 더 많은 시간이 필요하거나 회상에 실패할 수 있습니다. 활성화는 과거에 해당 정보를 접했던 이력과 현재의 문맥적 영향(Contextual Influences)을 반영할 수 있습니다. 이를 통해 자주 사용되거나 최근에 사용된 정보가 더 쉽게 접근되는 친숙한 심리학적 현상을 계산적으로 설명할 수 있습니다.

기저 수준 활성화(Base-level Activation)는 기억을 사용해 온 이력이 현재의 접근성에 어떤 영향을 주는지를 나타냅니다. 반복적으로 접했거나 최근에 사용한 지식은 드물게 사용되거나 오래된 정보보다 높은 활성화 수준을 유지하는 경향이 있습니다. 그러나 활성화는 시간이 지나면서 점차 감소합니다. 따라서 ACT-R은 저장된 선언적 지식의 접근성이 변화하는 결과로 연습 효과(Practice Effects)와 망각(Forgetting)을 모두 모델링할 수 있는 메커니즘을 제공합니다.

절차적 지식(Procedural Knowledge)은 선언적 지식과 다른 방식으로 표현됩니다. ACT-R은 청크 대신 특정 조건이 충족되었을 때 어떤 인지 연산(Cognitive Operation)을 수행해야 하는지를 지정하는 생성 규칙(Production Rules)을 사용합니다. 생성 규칙은 현재 버퍼에서 이용할 수 있는 정보를 검사하고 기억 요청, 주의 전환(Shifting Attention), 목표 업데이트, 행동 수행과 같은 연산을 시작할 수 있습니다. 따라서 절차적 인지(Procedural Cognition)는 정보가 어떻게 변환되고 활용되는지를 제어합니다.

생성 시스템(Production System)은 어떤 규칙이 현재 버퍼의 내용과 일치하는지를 반복적으로 평가합니다. 여러 생성 규칙이 동시에 적용 가능한 경우 충돌 해결 메커니즘(Conflict-resolution Mechanism)이 어떤 생성 규칙을 실행할지를 결정합니다. 선택된 생성 규칙은 이후 버퍼를 변경하거나 모듈에 연산을 요청하여 새로운 인지 상태(Cognitive State)를 생성합니다. 따라서 인지는 조건 매칭, 생성 규칙 선택, 연산 실행, 그 결과에 대한 반응이 반복되는 주기를 통해 전개됩니다.

생성 규칙 선택(Production Selection)에는 효용(Utility)이 포함될 수 있으며, 이를 통해 아키텍처는 과거에 가치 있는 결과를 생성했던 행동을 선호할 수 있습니다. 여러 대안이 경쟁할 때 더 높은 기대 이익(Expected Benefit)과 연관된 생성 규칙이 선택될 가능성이 높아질 수 있습니다. 따라서 효용 학습(Utility Learning)은 경험이 절차적 의사결정(Procedural Decision Making)을 수정하는 메커니즘을 제공하며, 아키텍처가 성공적으로 수행되었던 전략을 점진적으로 선호할 수 있도록 합니다.

목표(Goals)는 ACT-R 내부에서 과제 수준의 방향성(Task-level Direction)을 제공합니다. 목표 버퍼(Goal Buffer)는 현재의 목표 또는 문제 해결 과정의 중간 상태(Intermediate State)를 설명하는 정보를 유지할 수 있습니다. 생성 규칙은 지각 및 기억의 내용과 함께 이러한 정보를 검사하여 적절한 연산을 결정합니다. 과제가 진행됨에 따라 생성 규칙은 목표 표상(Goal Representation)을 수정할 수 있으며, 이를 통해 인지는 일련의 중간 상태를 거쳐 과제 완료 방향으로 이동합니다.

지각 모듈(Perceptual Modules)은 인지를 환경으로부터 들어오는 정보와 연결합니다. 시각 및 청각 메커니즘(Visual and Auditory Mechanisms)은 외부 자극의 여러 측면을 표현하고 선택된 정보를 해당 버퍼를 통해 이용할 수 있도록 합니다. 주의(Attention)는 어떤 환경 정보가 추가적인 처리에 사용될지를 결정합니다. 이러한 아키텍처를 통해 지각은 독립적인 전처리 단계로 작동하는 것이 아니라 목표 및 기억과 동적으로 상호작용할 수 있습니다.

운동 모듈(Motor Modules)은 인지적 의사결정이 관찰 가능한 행동으로 이어질 수 있도록 합니다. 절차적 처리가 외부 반응이 필요하다고 결정하면 운동 메커니즘이 필요한 행동을 실행합니다. 지각, 인지, 운동 과정은 각각 시간적 특성(Temporal Characteristics)을 가지므로 ACT-R은 인지를 순간적인 계산으로 처리하는 대신 관찰, 기억 검색, 의사결정, 물리적 반응이 포함된 과제를 완료하는 데 필요한 전체 시간을 모델링할 수 있습니다.

ACT-R은 인지 시간(Cognitive Timing)을 상당히 중요하게 다룹니다. 기억 검색에는 시간이 필요하고, 지각적 주의 전환에도 시간이 필요하며, 생성 규칙 실행과 운동 반응에도 시간이 필요합니다. 이러한 제약을 통해 모델은 인간 수행에 관한 상세한 예측을 생성할 수 있습니다. 수백 밀리초(Hundreds of Milliseconds) 수준의 차이도 서로 다른 인지 연산이 전체 행동 구조에 어떻게 기여하는지를 보여줄 수 있기 때문에 이론적으로 중요한 의미를 가질 수 있습니다.

학습(Learning)은 선언적 구성 요소와 절차적 구성 요소 모두에서 발생합니다. 선언적 학습(Declarative Learning)은 경험이 축적됨에 따라 청크의 이용 가능성과 활성화를 변화시키며, 절차적 학습(Procedural Learning)은 생성 규칙의 효용을 수정하고 더 효율적인 전략을 발전시킬 수 있습니다. 따라서 반복적인 수행은 관련 지식에 대한 접근성이 증가하고 효과적인 절차적 선택이 더욱 확립되면서 느리고 많은 노력이 필요한 과제 수행을 더 빠른 행동으로 변화시킬 수 있습니다.

이러한 변화는 자동화(Automaticity)와 관련하여 해석할 수 있습니다. 초보자(Novice)는 문제를 해결하기 위해 여러 차례의 기억 검색과 중간 인지 단계를 필요로 할 수 있지만, 경험이 많은 사람은 잘 연습된 더 짧은 연산 시퀀스를 통해 적절한 반응에 도달할 수 있습니다. ACT-R은 완전히 다른 아키텍처를 필요로 하지 않고도 반복적인 경험이 인지 과정의 시간, 접근성, 선택 방식을 어떻게 변화시키는지를 설명할 수 있는 계산 메커니즘을 제공합니다.

ACT-R은 제한된 인지(Bounded Cognition)에 관한 중요한 모델도 제공합니다. 기억 검색은 실패할 수 있고, 주의는 선택적이며, 버퍼는 제한된 정보만 포함하고, 인지 연산에는 시간이 필요합니다. 따라서 지능은 무제한적인 기억 접근과 순간적인 추론을 가정하는 대신 자원 제약(Resource Constraints) 아래에서 모델링됩니다. 이러한 제한은 실제 인간의 인지 수행에서 나타나는 오류, 지연(Delays), 간섭(Interference), 기타 특성을 설명하는 데 필수적입니다.

이 아키텍처는 구조와 지식 조직의 상당 부분이 명시적이라는 점에서 일반적인 딥러닝(Deep Learning)과 다릅니다. 청크, 버퍼, 생성 규칙, 활성화 값(Activation Values), 효용, 모듈 사이의 상호작용을 검사하고 이론적인 인지 메커니즘과 연결할 수 있습니다. 반면 심층 신경망(Deep Neural Networks)은 대규모 데이터셋으로부터 분산 표상(Distributed Representations)을 학습합니다. 따라서 두 접근법은 지능의 서로 다른 수준과 메커니즘을 강조합니다.

현대적인 하이브리드 시스템(Hybrid Systems)은 이러한 장점들을 잠재적으로 결합할 수 있습니다. 신경망은 고차원 데이터(High-dimensional Data)로부터 지각, 표상 학습(Representation Learning), 언어 이해(Language Understanding), 예측을 제공하고, ACT-R에서 영감을 받은 메커니즘은 구조화된 작업 인터페이스, 명시적인 목표, 기억 검색, 절차적 제어(Procedural Control), 인지 자원 관리(Cognitive Resource Management)를 제공할 수 있습니다. 이러한 통합은 학습된 표상과 보다 해석 가능한 과제 수준의 인지 조직을 연결할 수 있습니다.

ACT-R은 현대의 기억 증강 인공지능(Memory-augmented AI)과 에이전트형 인공지능(Agentic AI)에도 관련이 있습니다. 인공지능 에이전트(Artificial Agent)는 목표를 유지하고, 관련 정보를 검색하고, 어떤 연산을 수행할지 결정하고, 결과를 관찰하며, 이후의 행동을 업데이트해야 합니다. 이러한 요구사항은 목표 버퍼, 선언적 기억, 생성 규칙, 지각 또는 운동 모듈 사이의 상호작용과 유사합니다. 따라서 ACT-R은 지속적인 목표 지향적 에이전트(Persistent Goal-directed Agents)를 설계하는 데 유용한 역사적 원리를 제공합니다.

이중 처리 관점(Dual-process Perspective)에서 충분히 연습된 생성 규칙 시퀀스와 접근성이 높은 기억은 비교적 빠른 처리를 지원할 수 있는 반면, 익숙하지 않은 과제는 반복적인 검색, 중간 목표, 더 긴 인지 연산 시퀀스를 요구할 수 있습니다. ACT-R이 단순히 시스템 1(System 1)과 시스템 2(System 2) 아키텍처인 것은 아니지만, 연습, 기억 접근성, 절차적 조직의 차이가 서로 다른 수준의 인지 노력(Cognitive Effort)과 처리 속도를 만들어낼 수 있음을 보여줍니다.

피지컬 인공지능(Physical AI)의 관점에서 ACT-R은 제한된 자원 아래에서 지각, 기억, 목표, 의사결정 메커니즘, 행동을 조정하는 방법에 관한 개념적 교훈을 제공합니다. 로봇 역시 감각 정보를 받아들이고, 과제 상태(Task State)를 유지하고, 관련 지식을 검색하고, 연산을 선택하고, 물리적인 반응을 실행합니다. 현대 로봇 시스템은 서로 다른 계산 기술을 사용하지만 이러한 기능들을 조정해야 하는 아키텍처적 문제는 밀접하게 관련되어 있습니다.

ACT-R에서 영감을 받은 체화 아키텍처(Embodied Architecture)는 신경망 기반 지각(Neural Perception)과 명시적인 과제 기억(Task Memory) 및 절차적 제어를 결합할 수 있습니다. 센서 모델은 구조화된 표상을 생성하고, 기억 시스템은 과제와 관련된 지식을 검색하며, 목표 구조는 임무 문맥(Mission Context)을 유지하고, 학습된 정책(Learned Policies)이나 규칙은 행동을 선택할 수 있습니다. 이후 실행에서 발생하는 피드백은 시스템을 업데이트하여 물리적 환경에 기반을 둔 지속적인 지각--인지--행동(Perception--Cognition--Action) 루프를 형성합니다.

ACT-R의 보다 광범위한 중요성은 인지 이론(Cognitive Theory)을 실행 가능한 계산 모델(Executable Computational Models)과 연결하려는 시도에 있습니다. 선언적 청크(Declarative Chunks)는 지식을 표현하고, 활성화는 접근성을 제어하며, 생성 규칙은 절차적 지식을 표현하고, 효용은 선택에 영향을 주며, 버퍼는 통신을 제한하고, 모듈은 전문화된 기능을 제공하며, 학습은 경험을 통해 수행을 변화시킵니다. 이러한 메커니즘은 여러 인지 기능이 어떻게 협력할 수 있는지를 상세하게 설명합니다.

궁극적으로 ACT-R은 지능적 행동(Intelligent Behavior)이 기억, 주의, 시간, 경험의 제약 아래에서 작동하는 전문화된 구성 요소(Specialized Components) 사이의 조정된 처리로 이해될 수 있음을 보여줍니다. ACT-R의 가치는 개별 심리학 실험을 모델링하는 데만 국한되지 않으며, 통합 인지(Integrated Cognition)를 연구하기 위한 체계적인 프레임워크를 제공한다는 데 있습니다. 이 아키텍처는 기억, 목표, 추론, 학습, 행동을 결합하도록 설계된 하이브리드 인공지능(Hybrid AI), 에이전트형 시스템(Agentic Systems), 인지 로보틱스(Cognitive Robotics), 인공 지능형 시스템에 관한 논의에서도 여전히 중요한 의미를 가집니다.

##  

## 06.03 CLARION [w/Code]

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

CLARION, or the Connectionist Learning with Adaptive Rule Induction ON-line architecture, is a cognitive architecture designed to explain intelligent behavior through the interaction of implicit and explicit cognitive processes. Its central idea is that cognition cannot be adequately represented by either symbolic rules or distributed neural processing alone. Instead, intelligence emerges from coordinated learning and processing across multiple representational levels.

A defining characteristic of CLARION is its distinction between implicit knowledge and explicit knowledge. Implicit knowledge is represented primarily through distributed subsymbolic structures that can support intuitive, automatic, and experience-driven behavior. Explicit knowledge is represented through symbolic rules and structures that can be consciously accessible, verbally expressible, or deliberately manipulated during reasoning and decision making.

These two forms of knowledge are organized into different representational levels rather than isolated systems. The bottom level generally represents implicit knowledge through connectionist mechanisms, while the top level represents explicit knowledge through symbolic structures. Information can influence behavior from both levels simultaneously, allowing learned patterns and explicit rules to cooperate or compete when the system selects an action.

The bottom level is especially important for learning from experience. Instead of requiring knowledge to be specified in advance as symbolic rules, subsymbolic networks can gradually acquire associations between states, actions, and outcomes. Through repeated interaction with an environment, the system develops patterns that support increasingly effective behavior even when it cannot explicitly describe the knowledge responsible for its performance.

The top level provides explicit representations that can support structured reasoning and more interpretable knowledge. Rules may specify relationships between conditions and actions or describe concepts and relationships that can be directly manipulated. Because these representations are explicit, they can support deliberate cognition, communication, explanation, and the transfer of knowledge across situations where purely implicit pattern matching may be insufficient.

CLARION emphasizes interaction between the two levels rather than treating them as independent cognitive pathways. Explicit rules can guide behavior while implicit knowledge supplies additional preferences based on accumulated experience. Their outputs can be integrated when selecting actions. This allows cognition to combine the efficiency and flexibility of learned intuition with the structure and interpretability of symbolic reasoning.

Bottom-up learning is one of CLARION\'s characteristic mechanisms. Knowledge may first be acquired implicitly through experience at the bottom level and later become represented explicitly through rule extraction or rule induction. A person or artificial agent may therefore learn how to perform a task before being able to articulate why a particular strategy works. Explicit knowledge can emerge gradually from successful implicit behavior.

Top-down learning operates in the opposite direction. Explicit knowledge supplied as instructions, rules, or prior knowledge can influence subsymbolic processing and guide learning at the bottom level. Repeated application of an explicit rule may gradually strengthen corresponding implicit representations. Behavior that initially requires deliberate rule following can therefore become increasingly automatic as experience accumulates.

The interaction between bottom-up and top-down learning provides a computational account of skill development. A learner may discover successful behavior through trial and error, extract an explicit rule from repeated experience, deliberately refine that rule, and eventually internalize the improved strategy as implicit knowledge. Learning therefore becomes a continuous exchange between experience-driven adaptation and explicit cognitive structure.

CLARION organizes cognition into several major subsystems that address different functional requirements. The Action-Centered Subsystem is concerned with selecting and executing actions, the Non-Action-Centered Subsystem handles general knowledge, the Motivational Subsystem provides drives and motivational influences, and the Meta-Cognitive Subsystem regulates cognitive processing. Their interaction creates a broader architecture for adaptive goal-directed behavior.

The Action-Centered Subsystem focuses on procedural knowledge and behavior selection. It maps information about the current state onto possible actions and evaluates alternatives using both implicit and explicit knowledge. The bottom level can learn action tendencies from experience, while the top level can contain explicit action rules. Their combined influence determines which behavior is selected under particular environmental conditions.

Reinforcement learning can play an important role within this action-centered processing. Actions produce outcomes, and feedback from those outcomes changes the values associated with future choices. Through repeated state--action--reward interactions, implicit representations can learn effective policies. Explicit rules can complement this process by incorporating prior knowledge, constraints, or strategies that would otherwise require extensive experience to discover.

The Non-Action-Centered Subsystem represents knowledge that is not primarily concerned with immediate action selection. It can support concepts, facts, relationships, and other forms of general knowledge required for reasoning and interpretation. As with procedural processing, implicit and explicit representations can coexist, allowing conceptual knowledge to include both distributed learned patterns and more structured symbolic descriptions.

The Motivational Subsystem provides internal drives that influence which goals and actions receive priority. Cognition does not operate independently of motivation because different environmental states may have different significance depending on current needs. Drives can therefore influence action selection, learning, and goal formation, providing internal value signals that help organize behavior rather than relying only on external stimuli.

The Meta-Cognitive Subsystem provides higher-level regulation of cognitive activity. It can influence processing strategies, allocate resources, modify parameters, regulate goals, and respond to changing task demands. This introduces a supervisory dimension in which the architecture not only processes information but can also alter how processing is performed according to internal states, environmental conditions, or performance requirements.

Goal structures connect motivational and cognitive processes. Motivational signals can encourage the formation or prioritization of goals, while cognitive mechanisms determine how those goals can be pursued. Goals then influence action selection and information processing. This creates a continuous relationship among motivation, cognition, decision making, and behavior rather than treating goals as externally supplied commands disconnected from the architecture.

CLARION\'s implicit--explicit distinction has a natural relationship with dual-process theories of cognition. Implicit subsymbolic processing resembles important characteristics associated with fast, intuitive processing, while explicit symbolic processing resembles deliberate and rule-based cognition. The correspondence is not exact, but CLARION provides a concrete computational framework for studying interactions between automatic and controlled forms of processing.

Automaticity can emerge as explicit processing becomes supported by increasingly strong implicit knowledge. A novice may initially rely heavily on instructions and explicit rules, requiring attention and deliberate processing. With practice, subsymbolic representations become better adapted to recurring situations, allowing behavior to be produced more rapidly and with less dependence on explicit reasoning. Expertise can therefore develop through changes in the balance between levels.

The reverse process is also important when automatic behavior becomes inadequate. Novel situations, conflicts, errors, or changing environmental conditions may require greater reliance on explicit knowledge and deliberate reasoning. Explicit processing can modify strategies or introduce new rules, after which continued experience can again reshape implicit knowledge. Adaptive cognition therefore depends on movement in both directions between automatic and deliberate processing.

CLARION differs from purely symbolic cognitive architectures because it gives subsymbolic learning a fundamental role rather than treating all important knowledge as explicitly encoded rules. It also differs from purely connectionist approaches because symbolic representations remain an important component of cognition. The architecture consequently represents an early and influential form of hybrid cognitive modeling that attempts to integrate symbolic and neural principles.

This hybrid organization is particularly relevant to modern artificial intelligence. Deep neural networks provide powerful mechanisms for perception, pattern recognition, representation learning, and policy acquisition, while symbolic or structured mechanisms can provide explicit constraints, rules, goals, reasoning, and interpretable knowledge. CLARION demonstrates conceptually how these capabilities can interact rather than requiring one representational paradigm to replace the other.

The architecture is also relevant to agentic AI because autonomous agents require both learned behavior and explicit control. An agent may develop policies from experience while simultaneously following instructions, constraints, plans, and goals. Meta-cognitive mechanisms can regulate these processes, motivational structures can determine priorities, and environmental feedback can continuously modify learned behavior. This produces a persistent adaptive decision loop.

For Physical AI, the implicit level can be related conceptually to learned perception and control policies that operate rapidly from sensor information, while explicit mechanisms can support task rules, constraints, planning, and higher-level reasoning. A robot may execute familiar behavior through learned policies but invoke structured reasoning when facing unusual situations, conflicts, safety constraints, or new task requirements.

Embodied interaction is particularly important because CLARION emphasizes learning through experience. An intelligent robot can observe environmental states, select actions, receive consequences, update implicit knowledge, and gradually construct more effective behavior. Explicit knowledge can accelerate this process by supplying task instructions or safety constraints, while experience can reveal patterns that were never completely specified by designers.

CLARION also highlights that cognition involves more than prediction or reasoning alone. Motivation determines what matters, meta-cognition regulates how processing occurs, knowledge systems represent what is known, and action mechanisms determine what is done. Intelligence therefore emerges from coordination among multiple subsystems operating across implicit and explicit levels rather than from a single general-purpose computational mechanism.

The broader significance of CLARION lies in its attempt to explain how learned intuition, explicit knowledge, motivation, meta-cognition, and action can coexist within one cognitive system. Bottom-up learning can transform implicit experience into explicit knowledge, while top-down learning can transform explicit instruction into increasingly automatic behavior. These reciprocal processes provide a framework for understanding adaptation, skill acquisition, and cognitive flexibility.

Ultimately, CLARION presents cognition as a hybrid, multi-level, continuously learning architecture. Implicit connectionist representations provide adaptive pattern-based competence, explicit symbolic structures provide deliberate and interpretable knowledge, motivational processes establish priorities, and meta-cognitive processes regulate cognition. Their coordinated interaction offers an important architectural model for understanding human cognition and designing adaptive, agentic, and embodied artificial intelligence.

CLARION, 즉 온라인 적응형 규칙 유도를 포함한 연결주의 학습(Connectionist Learning with Adaptive Rule Induction ON-line)은 암묵적 인지 과정(Implicit Cognitive Processes)과 명시적 인지 과정(Explicit Cognitive Processes)의 상호작용을 통해 지능적 행동(Intelligent Behavior)을 설명하도록 설계된 인지 아키텍처(Cognitive Architecture)입니다. 핵심 개념은 인지를 기호적 규칙(Symbolic Rules)이나 분산 신경 처리(Distributed Neural Processing) 가운데 하나만으로 충분히 표현할 수 없다는 것입니다. 대신 지능은 여러 표상 수준(Representational Levels)에 걸친 조정된 학습과 처리 과정에서 나타납니다.

CLARION의 핵심적인 특징은 암묵적 지식(Implicit Knowledge)과 명시적 지식(Explicit Knowledge)을 구분한다는 것입니다. 암묵적 지식은 주로 직관적(Intuitive), 자동적(Automatic), 경험 기반(Experience-driven) 행동을 지원할 수 있는 분산된 하위기호적 구조(Distributed Subsymbolic Structures)를 통해 표현됩니다. 명시적 지식은 의식적으로 접근하거나, 언어로 표현하거나, 추론과 의사결정 과정에서 숙고적으로 조작할 수 있는 기호적 규칙과 구조를 통해 표현됩니다.

이 두 가지 형태의 지식은 서로 독립된 시스템이 아니라 서로 다른 표상 수준으로 조직됩니다. 하위 수준(Bottom Level)은 일반적으로 연결주의적 메커니즘(Connectionist Mechanisms)을 통해 암묵적 지식을 표현하고, 상위 수준(Top Level)은 기호적 구조(Symbolic Structures)를 통해 명시적 지식을 표현합니다. 두 수준의 정보는 동시에 행동에 영향을 줄 수 있으므로 시스템이 행동을 선택할 때 학습된 패턴과 명시적 규칙이 서로 협력하거나 경쟁할 수 있습니다.

하위 수준(Bottom Level)은 경험을 통한 학습(Learning from Experience)에서 특히 중요합니다. 지식을 미리 기호적 규칙으로 지정할 필요 없이 하위기호적 네트워크(Subsymbolic Networks)는 상태(State), 행동(Action), 결과(Outcome) 사이의 연관성을 점진적으로 학습할 수 있습니다. 환경과 반복적으로 상호작용하면서 시스템은 자신의 수행을 가능하게 하는 지식을 명시적으로 설명하지 못하더라도 점점 더 효과적인 행동을 지원하는 패턴을 발달시킵니다.

상위 수준(Top Level)은 구조화된 추론(Structured Reasoning)과 보다 해석 가능한 지식(Interpretable Knowledge)을 지원할 수 있는 명시적 표상(Explicit Representations)을 제공합니다. 규칙은 조건과 행동 사이의 관계를 지정하거나 직접 조작할 수 있는 개념 및 관계를 설명할 수 있습니다. 이러한 표상은 명시적이기 때문에 숙고적 인지(Deliberate Cognition), 의사소통(Communication), 설명(Explanation), 순수한 암묵적 패턴 매칭만으로 충분하지 않은 상황에서의 지식 전이(Knowledge Transfer)를 지원할 수 있습니다.

CLARION은 두 수준을 독립적인 인지 경로로 취급하는 대신 이들 사이의 상호작용을 강조합니다. 명시적 규칙은 행동을 안내할 수 있고, 암묵적 지식은 축적된 경험을 기반으로 추가적인 선호도(Preferences)를 제공할 수 있습니다. 행동을 선택할 때 두 수준의 출력을 통합할 수 있습니다. 이를 통해 인지는 학습된 직관(Learned Intuition)의 효율성과 유연성을 기호적 추론(Symbolic Reasoning)의 구조 및 해석 가능성과 결합할 수 있습니다.

상향식 학습(Bottom-up Learning)은 CLARION의 특징적인 메커니즘 가운데 하나입니다. 지식은 처음에 하위 수준에서 경험을 통해 암묵적으로 습득된 후 규칙 추출(Rule Extraction)이나 규칙 유도(Rule Induction)를 통해 명시적인 형태로 표현될 수 있습니다. 따라서 사람이나 인공지능 에이전트(Artificial Agent)는 특정 전략이 왜 효과적인지를 설명할 수 있게 되기 전에 먼저 과제를 수행하는 방법을 학습할 수 있습니다. 성공적인 암묵적 행동에서 명시적 지식이 점진적으로 나타날 수 있습니다.

하향식 학습(Top-down Learning)은 반대 방향으로 작동합니다. 명령(Instructions), 규칙 또는 사전 지식(Prior Knowledge)의 형태로 제공된 명시적 지식은 하위기호적 처리에 영향을 주고 하위 수준의 학습을 안내할 수 있습니다. 명시적 규칙을 반복적으로 적용하면 이에 대응하는 암묵적 표상이 점차 강화될 수 있습니다. 따라서 처음에는 숙고적인 규칙 준수(Deliberate Rule Following)가 필요했던 행동도 경험이 축적되면서 점점 자동화될 수 있습니다.

상향식 학습과 하향식 학습 사이의 상호작용은 기술 발달(Skill Development)을 계산적으로 설명합니다. 학습자는 시행착오(Trial and Error)를 통해 성공적인 행동을 발견하고, 반복된 경험에서 명시적인 규칙을 추출하고, 해당 규칙을 숙고적으로 개선한 다음, 개선된 전략을 다시 암묵적 지식으로 내재화(Internalize)할 수 있습니다. 따라서 학습은 경험 기반 적응(Experience-driven Adaptation)과 명시적 인지 구조 사이의 지속적인 교환 과정이 됩니다.

CLARION은 서로 다른 기능적 요구사항을 처리하기 위해 인지를 여러 주요 하위 시스템(Subsystems)으로 구성합니다. 행동 중심 하위 시스템(Action-Centered Subsystem)은 행동의 선택과 실행을 담당하고, 비행동 중심 하위 시스템(Non-Action-Centered Subsystem)은 일반적인 지식을 처리하며, 동기 하위 시스템(Motivational Subsystem)은 욕구(Drives)와 동기적 영향을 제공하고, 메타인지 하위 시스템(Meta-Cognitive Subsystem)은 인지 처리를 조절합니다. 이들의 상호작용은 적응적인 목표 지향 행동(Adaptive Goal-directed Behavior)을 위한 더 넓은 아키텍처를 형성합니다.

행동 중심 하위 시스템(Action-Centered Subsystem)은 절차적 지식(Procedural Knowledge)과 행동 선택(Behavior Selection)에 초점을 둡니다. 현재 상태에 관한 정보를 가능한 행동에 매핑하고, 암묵적 지식과 명시적 지식을 모두 사용하여 대안을 평가합니다. 하위 수준은 경험으로부터 행동 경향(Action Tendencies)을 학습할 수 있고, 상위 수준은 명시적인 행동 규칙을 포함할 수 있습니다. 특정 환경 조건에서 어떤 행동을 선택할지는 이 두 수준의 결합된 영향에 의해 결정됩니다.

강화학습(Reinforcement Learning)은 이러한 행동 중심 처리에서 중요한 역할을 수행할 수 있습니다. 행동은 결과를 발생시키고, 이러한 결과에서 얻은 피드백(Feedback)은 미래의 선택과 연관된 가치를 변화시킵니다. 반복적인 상태--행동--보상(State--Action--Reward) 상호작용을 통해 암묵적 표상은 효과적인 정책(Policies)을 학습할 수 있습니다. 명시적 규칙은 사전 지식, 제약 조건(Constraints), 전략을 통합하여 이를 보완하고, 경험만으로 발견하려면 많은 시간이 필요한 지식을 보다 빠르게 활용할 수 있도록 합니다.

비행동 중심 하위 시스템(Non-Action-Centered Subsystem)은 즉각적인 행동 선택을 주된 목적으로 하지 않는 지식을 표현합니다. 이 시스템은 추론과 해석에 필요한 개념, 사실, 관계, 기타 형태의 일반적인 지식을 지원할 수 있습니다. 절차적 처리와 마찬가지로 암묵적 표상과 명시적 표상이 공존할 수 있으며, 개념적 지식(Conceptual Knowledge)은 분산된 학습 패턴과 보다 구조화된 기호적 설명을 모두 포함할 수 있습니다.

동기 하위 시스템(Motivational Subsystem)은 어떤 목표와 행동에 우선순위를 부여할지를 결정하는 내부 욕구(Internal Drives)를 제공합니다. 서로 다른 환경 상태는 현재의 필요에 따라 서로 다른 중요성을 가질 수 있기 때문에 인지는 동기와 독립적으로 작동하지 않습니다. 따라서 욕구는 행동 선택, 학습, 목표 형성(Goal Formation)에 영향을 주며, 외부 자극에만 의존하지 않고 행동을 조직할 수 있는 내부 가치 신호(Internal Value Signals)를 제공합니다.

메타인지 하위 시스템(Meta-Cognitive Subsystem)은 인지 활동을 상위 수준에서 조절합니다. 처리 전략(Processing Strategies)에 영향을 주고, 자원을 할당하고, 파라미터를 수정하고, 목표를 조절하며, 변화하는 과제 요구사항에 대응할 수 있습니다. 이를 통해 아키텍처는 단순히 정보를 처리하는 데 그치지 않고 내부 상태, 환경 조건 또는 수행 요구사항에 따라 처리 방법 자체를 변경할 수 있는 감독적 차원(Supervisory Dimension)을 갖게 됩니다.

목표 구조(Goal Structures)는 동기 과정과 인지 과정을 연결합니다. 동기 신호(Motivational Signals)는 목표의 형성이나 우선순위 설정을 촉진할 수 있으며, 인지 메커니즘은 이러한 목표를 어떻게 추구할 것인지를 결정합니다. 이후 목표는 행동 선택과 정보 처리에 영향을 줍니다. 이를 통해 목표를 아키텍처와 분리된 외부 명령으로 취급하는 대신 동기, 인지, 의사결정, 행동 사이에 지속적인 관계가 형성됩니다.

CLARION의 암묵적--명시적 구분(Implicit--Explicit Distinction)은 인지의 이중 처리 이론(Dual-process Theories)과 자연스럽게 연결됩니다. 암묵적인 하위기호적 처리(Subsymbolic Processing)는 빠르고 직관적인 처리와 관련된 중요한 특성과 유사하며, 명시적인 기호적 처리(Symbolic Processing)는 숙고적이고 규칙 기반인 인지와 유사합니다. 두 개념이 정확하게 일치하는 것은 아니지만, CLARION은 자동적 처리와 통제된 처리(Controlled Processing) 사이의 상호작용을 연구하기 위한 구체적인 계산 프레임워크를 제공합니다.

자동화(Automaticity)는 명시적 처리가 점점 더 강력해지는 암묵적 지식에 의해 지원되면서 나타날 수 있습니다. 초보자(Novice)는 처음에는 명령과 명시적인 규칙에 크게 의존하여 주의와 숙고적 처리를 필요로 할 수 있습니다. 연습이 반복되면서 하위기호적 표상은 반복되는 상황에 더욱 잘 적응하고, 행동은 명시적인 추론에 덜 의존하면서 더 빠르게 생성될 수 있습니다. 따라서 전문성(Expertise)은 두 수준 사이의 균형 변화에 따라 발달할 수 있습니다.

자동적 행동이 충분하지 않을 때 발생하는 반대 방향의 과정도 중요합니다. 새로운 상황(Novel Situations), 충돌(Conflicts), 오류(Errors), 변화하는 환경 조건은 명시적 지식과 숙고적 추론에 대한 의존도를 증가시킬 수 있습니다. 명시적 처리는 전략을 수정하거나 새로운 규칙을 도입할 수 있으며, 이후 지속적인 경험은 다시 암묵적 지식을 변화시킬 수 있습니다. 따라서 적응적 인지(Adaptive Cognition)는 자동적 처리와 숙고적 처리 사이의 양방향 이동에 의존합니다.

CLARION은 모든 중요한 지식을 명시적으로 인코딩된 규칙으로 취급하지 않고 하위기호적 학습(Subsymbolic Learning)에 기본적인 역할을 부여한다는 점에서 순수한 기호적 인지 아키텍처(Purely Symbolic Cognitive Architectures)와 다릅니다. 또한 기호적 표상을 인지의 중요한 구성 요소로 유지한다는 점에서 순수한 연결주의적 접근(Purely Connectionist Approaches)과도 다릅니다. 따라서 CLARION은 기호적 원리와 신경망적 원리를 통합하려는 초기의 영향력 있는 하이브리드 인지 모델링(Hybrid Cognitive Modeling) 형태라고 할 수 있습니다.

이러한 하이브리드 조직(Hybrid Organization)은 현대 인공지능과 특히 관련성이 높습니다. 심층 신경망(Deep Neural Networks)은 지각, 패턴 인식(Pattern Recognition), 표상 학습(Representation Learning), 정책 획득(Policy Acquisition)을 위한 강력한 메커니즘을 제공하고, 기호적 또는 구조화된 메커니즘은 명시적인 제약 조건, 규칙, 목표, 추론, 해석 가능한 지식을 제공할 수 있습니다. CLARION은 하나의 표상 패러다임이 다른 패러다임을 대체해야 한다고 가정하지 않고 이러한 능력들이 어떻게 상호작용할 수 있는지를 개념적으로 보여줍니다.

이 아키텍처는 자율 에이전트가 학습된 행동과 명시적인 제어를 모두 필요로 한다는 점에서 에이전트형 인공지능(Agentic AI)과도 관련됩니다. 에이전트는 경험으로부터 정책을 발전시키면서 동시에 명령, 제약 조건, 계획(Plans), 목표를 따를 수 있습니다. 메타인지 메커니즘은 이러한 과정을 조절하고, 동기 구조는 우선순위를 결정하며, 환경 피드백은 학습된 행동을 지속적으로 수정할 수 있습니다. 이를 통해 지속적으로 적응하는 의사결정 루프(Adaptive Decision Loop)가 형성됩니다.

피지컬 인공지능(Physical AI)에서 암묵적 수준은 센서 정보로부터 빠르게 작동하는 학습된 지각(Perception) 및 제어 정책(Control Policies)과 개념적으로 연결할 수 있으며, 명시적 메커니즘은 과제 규칙(Task Rules), 제약 조건, 계획, 상위 수준 추론(Higher-level Reasoning)을 지원할 수 있습니다. 로봇은 익숙한 행동을 학습된 정책을 통해 실행하면서 비정상적인 상황, 충돌, 안전 제약(Safety Constraints), 새로운 과제 요구사항에 직면하면 구조화된 추론을 활성화할 수 있습니다.

CLARION은 경험을 통한 학습을 강조하기 때문에 체화된 상호작용(Embodied Interaction)이 특히 중요합니다. 지능형 로봇은 환경 상태를 관찰하고, 행동을 선택하고, 그 결과를 받아들이고, 암묵적 지식을 업데이트하면서 점차 더 효과적인 행동을 구성할 수 있습니다. 명시적 지식은 과제 명령이나 안전 제약을 제공하여 이러한 과정을 가속할 수 있고, 경험은 설계자가 완전히 지정하지 못했던 패턴을 발견할 수 있도록 합니다.

CLARION은 또한 인지가 예측(Prediction)이나 추론만으로 구성되는 것이 아니라는 점을 강조합니다. 동기(Motivation)는 무엇이 중요한지를 결정하고, 메타인지(Meta-cognition)는 처리가 어떻게 수행되는지를 조절하며, 지식 시스템(Knowledge Systems)은 무엇을 알고 있는지를 표현하고, 행동 메커니즘(Action Mechanisms)은 무엇을 수행할지를 결정합니다. 따라서 지능은 하나의 범용 계산 메커니즘에서 발생하는 것이 아니라 암묵적 및 명시적 수준에 걸쳐 작동하는 여러 하위 시스템의 조정을 통해 나타납니다.

CLARION의 보다 광범위한 중요성은 학습된 직관, 명시적 지식, 동기, 메타인지, 행동이 하나의 인지 시스템 내부에서 어떻게 공존할 수 있는지를 설명하려는 시도에 있습니다. 상향식 학습은 암묵적인 경험을 명시적 지식으로 변환할 수 있고, 하향식 학습은 명시적인 지시를 점차 자동화된 행동으로 변환할 수 있습니다. 이러한 상호적인 과정은 적응(Adaptation), 기술 습득(Skill Acquisition), 인지적 유연성(Cognitive Flexibility)을 이해하기 위한 프레임워크를 제공합니다.

궁극적으로 CLARION은 인지를 하이브리드(Hybrid), 다수준(Multi-level), 지속 학습(Continuously Learning) 아키텍처로 제시합니다. 암묵적인 연결주의적 표상(Connectionist Representations)은 적응적인 패턴 기반 능력(Pattern-based Competence)을 제공하고, 명시적인 기호적 구조(Symbolic Structures)는 숙고적이고 해석 가능한 지식을 제공하며, 동기 과정은 우선순위를 설정하고, 메타인지 과정은 인지를 조절합니다. 이러한 요소들의 조정된 상호작용은 인간의 인지를 이해하고 적응형(Adaptive), 에이전트형(Agentic), 체화형 인공지능(Embodied Artificial Intelligence)을 설계하기 위한 중요한 아키텍처 모델을 제공합니다.

##  

## 06.04 LIDA [w/Code]

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

LIDA, or the Learning Intelligent Distribution Agent architecture, is a cognitive architecture designed to model integrated cognition through recurring cycles of perception, attention, memory, learning, decision making, and action. Rather than treating cognition as a single sequential computation, LIDA describes intelligent behavior as the coordinated activity of multiple specialized processes operating continuously and partly in parallel within an embodied agent.

A central principle of LIDA is the cognitive cycle, a recurring sequence through which an agent perceives its environment, constructs an interpretation of the current situation, selects information for conscious processing, chooses an appropriate action, and learns from the resulting experience. Each cycle is relatively short, while complex cognition emerges from many interacting cycles unfolding continuously over longer periods of time.

The cognitive cycle provides a bridge between moment-to-moment processing and extended intelligent behavior. Individual cycles can respond to immediate environmental changes, while sequences of cycles support activities such as reasoning, planning, problem solving, communication, and goal pursuit. Cognition is therefore understood as an ongoing stream of coordinated processing rather than as isolated responses to individual inputs.

Perception begins when sensory information enters the architecture from the environment or the agent\'s internal state. Specialized perceptual processes analyze incoming signals and identify features, objects, events, and relationships that may be relevant. Perception is not simply passive recording because previously learned knowledge influences how sensory information is interpreted and which structures become meaningful within the current context.

The Perceptual Associative Memory contains learned representations that help recognize meaningful patterns in incoming information. Current sensory data can activate related perceptual structures, allowing the architecture to categorize objects and situations according to previous experience. This interaction between sensory input and learned representations transforms raw information into cognitively useful content that can participate in subsequent processing.

The Current Situational Model represents the architecture\'s evolving interpretation of what is happening now. It integrates perceptual information with relevant knowledge retrieved from memory, creating a structured representation of objects, events, relationships, and contextual conditions. Because environments continually change, this model must also change from cycle to cycle as new information becomes available.

Workspace mechanisms allow information from perception and memory to interact during construction of the current situation. Relevant episodes, concepts, expectations, and relationships can contribute to interpretation. The resulting representation is therefore not determined solely by present sensory input. It reflects an interaction among current evidence, previous experience, contextual knowledge, and the agent\'s ongoing cognitive state.

Attention is essential because only a portion of the information represented within the architecture can receive prioritized processing. Attention codelets detect information that may be important because of novelty, relevance, urgency, goals, or other factors. These processes form coalitions of related content that compete for access to the architecture\'s global broadcasting mechanism.

Competition among attentional coalitions determines which content becomes globally available. Different perceptual events, memories, goals, or internal concerns may simultaneously demand processing resources. LIDA therefore models attention as a competitive selection process rather than an unrestricted flow of all available information. The winning coalition gains a privileged role in coordinating subsequent cognitive activity.

LIDA is strongly influenced by Global Workspace Theory, which proposes that consciousness involves the widespread broadcasting of selected information across otherwise specialized cognitive processes. In LIDA, the content that wins the attentional competition enters the Global Workspace and is broadcast throughout the architecture. This broadcast makes selected information available to multiple memory, learning, evaluation, and action-related mechanisms.

Conscious broadcast does not imply that every cognitive process is conscious. Much of LIDA\'s processing occurs outside global awareness through specialized mechanisms operating automatically. Conscious content represents information that has temporarily achieved broad accessibility because it is sufficiently important to influence multiple systems. The architecture therefore combines extensive unconscious processing with limited but globally influential conscious processing.

The global broadcast can activate several forms of learning simultaneously. Perceptual learning can modify how environmental patterns are recognized, episodic learning can preserve aspects of current experience, and procedural learning can change the likelihood of selecting particular behaviors. Conscious processing therefore acts not merely as an informational endpoint but as an important coordination mechanism for adaptation across the architecture.

Episodic memory allows information about previous experiences to influence current cognition. When the current situation resembles earlier events, relevant episodes can be retrieved and incorporated into the situational model. Past experience can consequently affect interpretation, expectations, decisions, and behavior. New experiences can also be encoded, creating a continuing relationship between present processing and accumulated personal history.

Declarative and semantic forms of knowledge provide more generalized information beyond individual episodes. Concepts, relationships, categories, and learned regularities can influence interpretation of current events. Together with episodic information, this knowledge allows cognition to move beyond immediate sensory evidence and use accumulated experience to construct richer models of situations and possible outcomes.

Procedural memory contains schemes for possible actions. When information is globally broadcast, relevant behavior schemes can become activated according to the current situation, goals, expectations, and learned associations. Multiple schemes may become candidates for execution. The architecture must therefore move from conscious information availability toward action selection rather than assuming that awareness automatically determines behavior.

Action selection evaluates competing behavior schemes and determines which action should be executed. Selection can depend on activation levels, contextual relevance, motivational influences, expected consequences, and previously learned values. The chosen scheme is then instantiated into an executable action. This creates a transition from perception and conscious evaluation to concrete interaction with the environment.

Sensory-motor memory supports the execution of selected actions by connecting higher-level behavior choices with appropriate motor patterns. Once an action has been chosen, lower-level mechanisms translate the selected behavior into operations capable of affecting the environment. The resulting environmental change generates new sensory input, beginning another cognitive cycle and closing the perception--cognition--action loop.

Learning occurs continuously throughout repeated cognitive cycles. Experiences alter perceptual associations, episodic memories, procedural structures, and other internal representations. Consequently, the architecture that processes a situation today may respond differently to a similar situation later. LIDA therefore treats learning as an integral property of cognition rather than as a separate training phase performed before intelligent behavior begins.

Motivation influences which information becomes important and which behaviors become attractive. Internal drives, needs, goals, and affective values can modify attention and action selection. The same environmental event may therefore produce different cognitive consequences depending on the agent\'s current state. Intelligent behavior emerges from the interaction between external conditions and internally generated priorities.

LIDA\'s organization illustrates how fast automatic processing and more globally coordinated cognition can coexist. Many specialized processes operate rapidly and unconsciously, while attentional competition occasionally selects content for global broadcast. This resembles some aspects of dual-process cognition, although LIDA is not simply divided into System 1 and System 2. Complex cognition instead emerges from repeated coordination across many cycles.

Extended reasoning can arise through sequences of cognitive cycles rather than requiring one exceptionally long processing operation. A conclusion reached during one cycle can modify the situational model and become input to subsequent cycles. Step-by-step reasoning, planning, and problem solving can therefore emerge as intermediate representations are repeatedly constructed, attended to, broadcast, evaluated, and transformed.

This cyclic organization is particularly relevant to agentic AI. Persistent agents must repeatedly observe changing conditions, update internal state, identify important information, retrieve relevant memories, choose actions, evaluate consequences, and learn. LIDA provides a conceptual architecture in which these capabilities are coordinated through recurring cycles instead of being treated as independent modules invoked only when explicitly requested.

Modern neural models could potentially provide several capabilities required within a LIDA-inspired system. Deep networks can support perception and representation learning, language models can contribute semantic interpretation and reasoning, and learned policies can assist action selection. Memory systems, attentional control, global information sharing, and explicit agent state can then organize these learned components within a persistent cognitive loop.

LIDA is especially relevant to Physical AI because embodied intelligence must operate continuously in environments that change while actions are being executed. A robot cannot complete perception once and then reason indefinitely from a frozen world representation. It must repeatedly perceive, update its situational model, allocate attention, select behavior, execute actions, observe consequences, and revise its knowledge as the physical world evolves.

For robotic systems, the Current Situational Model can be conceptually related to an evolving world state assembled from cameras, LiDAR, proprioception, localization, language, and other sensory information. Attention can prioritize hazards, goals, people, objects, or unexpected events. Action-selection mechanisms can then coordinate navigation, manipulation, communication, or other behaviors according to the currently broadcast information.

The architecture also highlights the importance of different temporal scales. Low-level sensor and motor control may operate much faster than complete cognitive cycles, while planning and complex problem solving may extend across many cycles. An effective embodied architecture therefore requires coordination among rapid reactive control, intermediate cognitive processing, and longer-term goals without forcing every function to operate at the same frequency.

LIDA\'s broader significance lies in its attempt to explain cognition through continuous interaction among specialized processes rather than through a single reasoning engine. Perception constructs meaningful representations, memory contributes previous knowledge, attention selects important content, global broadcasting coordinates processing, procedural memory proposes behaviors, action selection chooses responses, and learning modifies future cognition.

Ultimately, LIDA presents intelligence as an ongoing sequence of perception--attention--broadcast--action--learning cycles embedded within continuous interaction with an environment. Individual mechanisms perform specialized functions, but adaptive cognition emerges from their repeated coordination. This perspective provides a useful conceptual bridge among cognitive science, consciousness research, agentic AI, and Physical AI systems that must perceive, remember, decide, learn, and act continuously.

LIDA, 즉 학습 지능 분산 에이전트(Learning Intelligent Distribution Agent) 아키텍처는 반복적으로 수행되는 지각(Perception), 주의(Attention), 기억(Memory), 학습(Learning), 의사결정(Decision Making), 행동(Action)의 주기를 통해 통합 인지(Integrated Cognition)를 모델링하도록 설계된 인지 아키텍처(Cognitive Architecture)입니다. LIDA는 인지를 하나의 순차적 계산 과정으로 보는 대신, 체화된 에이전트(Embodied Agent) 내부에서 지속적이고 부분적으로 병렬 작동하는 여러 전문화된 과정의 조정된 활동으로 지능적 행동을 설명합니다.

LIDA의 핵심 원리는 인지 주기(Cognitive Cycle)입니다. 이는 에이전트가 환경을 지각하고, 현재 상황에 대한 해석을 구성하고, 의식적 처리를 위한 정보를 선택하고, 적절한 행동을 결정하며, 그 결과로 얻은 경험으로부터 학습하는 반복적인 과정입니다. 각각의 주기는 비교적 짧지만, 복잡한 인지(Complex Cognition)는 장기간에 걸쳐 지속적으로 전개되는 수많은 상호작용하는 인지 주기로부터 나타납니다.

인지 주기(Cognitive Cycle)는 순간순간 이루어지는 처리와 장기간에 걸쳐 지속되는 지능적 행동 사이를 연결합니다. 개별 주기는 즉각적인 환경 변화에 대응할 수 있으며, 연속적인 여러 주기는 추론(Reasoning), 계획(Planning), 문제 해결(Problem Solving), 의사소통(Communication), 목표 추구(Goal Pursuit)와 같은 활동을 지원합니다. 따라서 인지는 개별 입력에 대한 고립된 반응이 아니라 지속적으로 이어지는 조정된 처리의 흐름으로 이해됩니다.

지각(Perception)은 환경이나 에이전트의 내부 상태에서 발생한 감각 정보(Sensory Information)가 아키텍처로 들어오면서 시작됩니다. 전문화된 지각 과정은 들어오는 신호를 분석하고 관련성이 있을 수 있는 특징(Features), 객체(Objects), 사건(Events), 관계(Relationships)를 식별합니다. 이전에 학습된 지식이 감각 정보가 해석되는 방식과 현재 문맥에서 어떤 구조가 의미를 갖게 되는지에 영향을 주기 때문에 지각은 단순한 수동적 기록 과정이 아닙니다.

지각 연상 기억(Perceptual Associative Memory)은 입력 정보에서 의미 있는 패턴을 인식하도록 돕는 학습된 표상(Learned Representations)을 포함합니다. 현재의 감각 데이터는 관련된 지각 구조를 활성화할 수 있으며, 이를 통해 아키텍처는 이전 경험에 따라 객체와 상황을 범주화할 수 있습니다. 감각 입력과 학습된 표상 사이의 이러한 상호작용은 원시 정보(Raw Information)를 이후의 인지 처리에 활용할 수 있는 인지적으로 유용한 내용으로 변환합니다.

현재 상황 모델(Current Situational Model)은 현재 어떤 일이 발생하고 있는지에 대한 아키텍처의 지속적으로 변화하는 해석을 표현합니다. 이 모델은 지각 정보와 기억에서 검색된 관련 지식을 통합하여 객체, 사건, 관계, 문맥 조건(Contextual Conditions)에 대한 구조화된 표상을 구성합니다. 환경은 지속적으로 변화하기 때문에 새로운 정보가 이용 가능해짐에 따라 이 모델 역시 각 인지 주기마다 변화해야 합니다.

작업공간 메커니즘(Workspace Mechanisms)은 현재 상황을 구성하는 동안 지각과 기억의 정보가 서로 상호작용할 수 있도록 합니다. 관련된 일화(Episodes), 개념(Concepts), 기대(Expectations), 관계가 상황 해석에 기여할 수 있습니다. 따라서 결과적으로 생성되는 표상은 현재의 감각 입력만으로 결정되지 않으며, 현재의 증거(Current Evidence), 이전 경험, 문맥적 지식(Contextual Knowledge), 에이전트의 지속적인 인지 상태 사이의 상호작용을 반영합니다.

아키텍처 내부에 표현된 모든 정보가 동일한 우선순위로 처리될 수 없기 때문에 주의(Attention)는 필수적입니다. 주의 코드렛(Attention Codelets)은 새로움(Novelty), 관련성(Relevance), 긴급성(Urgency), 목표(Goals), 기타 요인으로 인해 중요할 수 있는 정보를 탐지합니다. 이러한 과정은 서로 관련된 내용의 연합(Coalitions)을 형성하며, 이 연합들은 아키텍처의 전역 방송 메커니즘(Global Broadcasting Mechanism)에 접근하기 위해 서로 경쟁합니다.

주의 연합(Attentional Coalitions) 사이의 경쟁은 어떤 내용이 전역적으로 이용 가능하게 되는지를 결정합니다. 서로 다른 지각 사건, 기억, 목표 또는 내부적인 관심 사항이 동시에 처리 자원을 요구할 수 있습니다. 따라서 LIDA는 주의를 이용 가능한 모든 정보가 제한 없이 흐르는 과정이 아니라 경쟁적인 선택 과정(Competitive Selection Process)으로 모델링합니다. 경쟁에서 승리한 연합은 이후의 인지 활동을 조정하는 데 우선적인 역할을 갖습니다.

LIDA는 의식(Consciousness)이 서로 전문화된 인지 과정 전체에 선택된 정보를 광범위하게 방송하는 것과 관련된다고 설명하는 전역 작업공간 이론(Global Workspace Theory)의 강한 영향을 받았습니다. LIDA에서는 주의 경쟁에서 승리한 내용이 전역 작업공간(Global Workspace)에 진입하여 아키텍처 전체로 방송됩니다. 이러한 방송은 선택된 정보를 여러 기억, 학습, 평가(Evaluation), 행동 관련 메커니즘에서 이용할 수 있도록 합니다.

의식적 방송(Conscious Broadcast)이 모든 인지 과정이 의식적이라는 것을 의미하지는 않습니다. LIDA의 처리 과정 가운데 상당 부분은 자동적으로 작동하는 전문화된 메커니즘을 통해 전역적 인식(Global Awareness) 외부에서 수행됩니다. 의식적 내용은 여러 시스템에 영향을 줄 만큼 충분히 중요하기 때문에 일시적으로 광범위한 접근성을 획득한 정보를 의미합니다. 따라서 이 아키텍처는 광범위한 무의식적 처리(Unconscious Processing)와 제한적이지만 전역적으로 영향력이 있는 의식적 처리를 결합합니다.

전역 방송(Global Broadcast)은 여러 형태의 학습을 동시에 활성화할 수 있습니다. 지각 학습(Perceptual Learning)은 환경 패턴을 인식하는 방식을 수정할 수 있고, 일화 학습(Episodic Learning)은 현재 경험의 여러 측면을 보존할 수 있으며, 절차적 학습(Procedural Learning)은 특정 행동이 선택될 가능성을 변화시킬 수 있습니다. 따라서 의식적 처리는 단순한 정보 처리의 종착점이 아니라 아키텍처 전체의 적응을 위한 중요한 조정 메커니즘으로 기능합니다.

일화 기억(Episodic Memory)은 이전 경험에 관한 정보가 현재 인지에 영향을 줄 수 있도록 합니다. 현재 상황이 과거의 사건과 유사한 경우 관련된 일화를 검색하여 현재 상황 모델에 통합할 수 있습니다. 따라서 과거 경험은 해석, 기대, 의사결정, 행동에 영향을 줄 수 있습니다. 새로운 경험 역시 인코딩될 수 있으므로 현재의 처리 과정과 축적된 개인적 경험의 역사 사이에 지속적인 관계가 형성됩니다.

선언적 및 의미적 형태의 지식(Declarative and Semantic Knowledge)은 개별적인 일화를 넘어 더욱 일반화된 정보를 제공합니다. 개념, 관계, 범주(Categories), 학습된 규칙성(Learned Regularities)은 현재 사건을 해석하는 데 영향을 줄 수 있습니다. 이러한 지식은 일화 정보와 함께 인지가 즉각적인 감각 증거를 넘어설 수 있도록 하며, 축적된 경험을 활용하여 상황과 가능한 결과에 대한 더욱 풍부한 모델을 구성하도록 합니다.

절차 기억(Procedural Memory)은 가능한 행동을 위한 행동 스킴(Behavior Schemes)을 포함합니다. 정보가 전역적으로 방송되면 현재 상황, 목표, 기대, 학습된 연관성에 따라 관련 행동 스킴이 활성화될 수 있습니다. 여러 스킴이 동시에 실행 후보가 될 수 있습니다. 따라서 아키텍처는 의식적 정보의 이용 가능성에서 행동 선택(Action Selection)으로 이동해야 하며, 의식이 자동적으로 행동을 결정한다고 가정하지 않습니다.

행동 선택(Action Selection)은 서로 경쟁하는 행동 스킴을 평가하여 어떤 행동을 실행할지를 결정합니다. 선택은 활성화 수준(Activation Levels), 문맥적 관련성, 동기적 영향(Motivational Influences), 예상 결과(Expected Consequences), 이전에 학습된 가치에 따라 달라질 수 있습니다. 선택된 스킴은 이후 실제로 실행할 수 있는 행동으로 구체화됩니다. 이를 통해 지각과 의식적 평가에서 환경과의 구체적인 상호작용으로 전환됩니다.

감각운동 기억(Sensory-motor Memory)은 상위 수준의 행동 선택을 적절한 운동 패턴(Motor Patterns)과 연결함으로써 선택된 행동의 실행을 지원합니다. 행동이 선택되면 하위 수준 메커니즘이 선택된 행동을 환경에 영향을 줄 수 있는 연산으로 변환합니다. 그 결과로 발생하는 환경 변화는 새로운 감각 입력을 생성하여 또 다른 인지 주기를 시작하며, 지각--인지--행동(Perception--Cognition--Action) 루프를 완성합니다.

학습(Learning)은 반복되는 인지 주기 전체에서 지속적으로 발생합니다. 경험은 지각적 연관성(Perceptual Associations), 일화 기억, 절차적 구조, 기타 내부 표상을 변화시킵니다. 따라서 오늘 특정 상황을 처리하는 아키텍처는 미래에 유사한 상황을 접했을 때 서로 다른 방식으로 반응할 수 있습니다. LIDA는 학습을 지능적 행동이 시작되기 전에 수행되는 별도의 훈련 단계가 아니라 인지 자체의 본질적인 특성으로 다룹니다.

동기(Motivation)는 어떤 정보가 중요해지고 어떤 행동이 매력적인 선택지가 되는지에 영향을 줍니다. 내부 욕구(Internal Drives), 필요(Needs), 목표, 정서적 가치(Affective Values)는 주의와 행동 선택을 변화시킬 수 있습니다. 따라서 동일한 환경 사건이라도 에이전트의 현재 상태에 따라 서로 다른 인지적 결과를 생성할 수 있습니다. 지능적 행동은 외부 조건과 내부적으로 생성된 우선순위 사이의 상호작용에서 나타납니다.

LIDA의 조직 방식은 빠른 자동적 처리(Fast Automatic Processing)와 보다 전역적으로 조정되는 인지(Global Coordinated Cognition)가 어떻게 공존할 수 있는지를 보여줍니다. 많은 전문화된 과정은 빠르고 무의식적으로 작동하지만, 주의 경쟁은 특정 내용을 선택하여 전역 방송으로 전달합니다. 이는 이중 처리 인지(Dual-process Cognition)의 일부 특성과 유사하지만 LIDA가 단순히 시스템 1(System 1)과 시스템 2(System 2)로 구분되는 것은 아닙니다. 복잡한 인지는 여러 주기에 걸친 반복적인 조정에서 나타납니다.

확장된 추론(Extended Reasoning)은 하나의 매우 긴 처리 연산을 필요로 하는 대신 여러 인지 주기의 연속을 통해 나타날 수 있습니다. 한 주기에서 도출된 결론은 현재 상황 모델을 변경하고 이후 주기의 입력이 될 수 있습니다. 따라서 단계별 추론(Step-by-step Reasoning), 계획, 문제 해결은 중간 표상이 반복적으로 구성되고, 주의를 받고, 방송되고, 평가되고, 변환되면서 나타날 수 있습니다.

이러한 순환적 조직(Cyclic Organization)은 에이전트형 인공지능(Agentic AI)과 특히 관련성이 높습니다. 지속적으로 작동하는 에이전트(Persistent Agents)는 변화하는 조건을 반복적으로 관찰하고, 내부 상태를 업데이트하고, 중요한 정보를 식별하고, 관련 기억을 검색하고, 행동을 선택하고, 결과를 평가하며, 학습해야 합니다. LIDA는 이러한 능력을 명시적으로 요청될 때만 호출되는 독립적인 모듈로 취급하는 대신 반복적인 주기를 통해 조정하는 개념적 아키텍처를 제공합니다.

현대의 신경망 모델(Neural Models)은 LIDA에서 영감을 받은 시스템에 필요한 여러 기능을 잠재적으로 제공할 수 있습니다. 심층 신경망(Deep Networks)은 지각과 표상 학습을 지원하고, 언어 모델(Language Models)은 의미적 해석(Semantic Interpretation)과 추론에 기여하며, 학습된 정책(Learned Policies)은 행동 선택을 지원할 수 있습니다. 이후 기억 시스템, 주의 제어(Attentional Control), 전역 정보 공유(Global Information Sharing), 명시적인 에이전트 상태(Explicit Agent State)가 이러한 학습 구성 요소를 지속적인 인지 루프 안에서 조직할 수 있습니다.

LIDA는 체화된 지능(Embodied Intelligence)이 행동이 실행되는 동안에도 계속 변화하는 환경에서 지속적으로 작동해야 한다는 점에서 피지컬 인공지능(Physical AI)과 특히 관련성이 높습니다. 로봇은 한 번 지각을 완료한 후 고정된 세계 표상(Frozen World Representation)을 기반으로 무한정 추론할 수 없습니다. 물리적 세계가 변화함에 따라 지속적으로 지각하고, 현재 상황 모델을 업데이트하고, 주의를 할당하고, 행동을 선택하고, 행동을 실행하고, 결과를 관찰하며, 지식을 수정해야 합니다.

로봇 시스템에서 현재 상황 모델(Current Situational Model)은 카메라(Cameras), 라이다(LiDAR), 고유수용감각(Proprioception), 위치 추정(Localization), 언어(Language), 기타 감각 정보로부터 구성되는 지속적으로 변화하는 세계 상태(World State)와 개념적으로 연결할 수 있습니다. 주의는 위험 요소(Hazards), 목표, 사람, 객체, 예상하지 못한 사건의 우선순위를 높일 수 있습니다. 이후 행동 선택 메커니즘은 현재 방송된 정보에 따라 내비게이션(Navigation), 조작(Manipulation), 의사소통 또는 기타 행동을 조정할 수 있습니다.

이 아키텍처는 서로 다른 시간 척도(Temporal Scales)의 중요성도 강조합니다. 저수준 센서 및 운동 제어(Low-level Sensor and Motor Control)는 전체 인지 주기보다 훨씬 빠르게 작동할 수 있는 반면, 계획과 복잡한 문제 해결은 여러 인지 주기에 걸쳐 지속될 수 있습니다. 따라서 효과적인 체화 아키텍처는 모든 기능이 동일한 주기로 작동하도록 강제하지 않으면서 빠른 반응 제어(Rapid Reactive Control), 중간 수준의 인지 처리, 장기 목표(Long-term Goals)를 조정해야 합니다.

LIDA의 보다 광범위한 중요성은 하나의 추론 엔진(Single Reasoning Engine)이 아니라 전문화된 과정 사이의 지속적인 상호작용을 통해 인지를 설명하려는 시도에 있습니다. 지각은 의미 있는 표상을 구성하고, 기억은 이전 지식을 제공하며, 주의는 중요한 내용을 선택하고, 전역 방송은 처리를 조정하며, 절차 기억은 행동을 제안하고, 행동 선택은 반응을 결정하며, 학습은 미래의 인지를 변화시킵니다.

궁극적으로 LIDA는 환경과의 지속적인 상호작용 속에 포함된 지각--주의--방송--행동--학습(Perception--Attention--Broadcast--Action--Learning) 주기의 연속으로 지능을 설명합니다. 개별 메커니즘은 전문화된 기능을 수행하지만 적응적 인지(Adaptive Cognition)는 이들의 반복적인 조정에서 나타납니다. 이러한 관점은 인지과학(Cognitive Science), 의식 연구(Consciousness Research), 에이전트형 인공지능(Agentic AI), 그리고 지속적으로 지각하고, 기억하고, 결정하고, 학습하고, 행동해야 하는 피지컬 인공지능(Physical AI) 시스템을 연결하는 유용한 개념적 가교를 제공합니다.

##  

## 06.05 Global Workspace Theory [w/Code]

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

Global Workspace Theory proposes that conscious cognition emerges when selected information becomes globally available to many otherwise specialized cognitive processes. Instead of assuming that consciousness is produced by a single central processor, the theory describes the mind as a distributed collection of specialized systems. Most processes operate locally and unconsciously, while a limited amount of selected information gains widespread access across the cognitive system.

The theory is closely associated with Bernard Baars, who introduced the global workspace as a functional framework for understanding consciousness and cognitive integration. The central problem addressed by the theory is how numerous specialized processes involved in perception, memory, language, attention, evaluation, and action can coordinate their activities. A shared workspace provides a mechanism through which selected information can influence many systems simultaneously.

A common metaphor compares the global workspace to a theater. Conscious information resembles the content illuminated on a stage, while numerous unconscious processes operate behind the scenes. Attention determines which information reaches the illuminated stage, and the selected content is then made available to a large audience of specialized cognitive systems. The metaphor emphasizes limited conscious capacity combined with extensive unconscious processing.

Most cognitive processing occurs outside the global workspace. Visual analysis, auditory processing, memory activation, emotional evaluation, motor preparation, and other specialized operations can proceed without becoming conscious. These processes continuously generate interpretations and candidate contents. Only a small fraction becomes sufficiently important or relevant to compete successfully for access to the global workspace.

Competition is therefore a fundamental mechanism within Global Workspace Theory. Different representations may simultaneously compete for global availability because cognitive capacity is limited. A sudden sound, a relevant memory, an unresolved goal, an unexpected visual event, or an internally generated thought may each become candidates. Attention and contextual relevance help determine which coalition of information becomes dominant.

Coalitions are groups of related cognitive contents that cooperate during competition for access to the workspace. Rather than individual signals competing independently, perceptual representations, memories, goals, emotions, and contextual information can combine into coherent structures. A sufficiently strong coalition may win the competition and enter the global workspace, allowing its integrated content to become widely accessible.

Once information gains access to the global workspace, it is globally broadcast to many specialized processes. Memory systems may encode or retrieve related information, language mechanisms may construct verbal descriptions, evaluative systems may estimate significance, planning processes may consider future consequences, and motor systems may prepare responses. Broadcasting therefore enables coordinated cognition without requiring direct connections among every specialized subsystem.

The global broadcast provides a solution to the problem of cognitive integration. Specialized processors may possess different forms of information, but globally available content creates a shared context that can influence them simultaneously. This allows perception to affect memory, memory to affect decision making, goals to influence attention, and conscious evaluation to modify action. Complex cognition emerges from this coordinated exchange.

Conscious access is limited compared with the enormous amount of unconscious processing occurring at any moment. This bottleneck is not necessarily a weakness. By allowing only selected information to become globally available, the architecture can prioritize information requiring broad coordination while leaving routine operations to specialized unconscious mechanisms. Consciousness can therefore function as a scarce coordination resource.

Attention and consciousness are closely related within the framework but should not be treated as identical. Attention helps amplify, select, and organize information that may gain access to the global workspace. Consciousness refers more specifically to the broad availability produced when selected content is globally broadcast. Attentional mechanisms can therefore be viewed as important contributors to determining what becomes globally accessible.

Working memory is also closely connected with global workspace processing. Information that becomes globally available can remain active long enough to influence reasoning, planning, comparison, and decision making. Recurrent processing may maintain or refresh selected representations across successive cognitive moments. The workspace consequently supports temporary integration of information required for complex cognitive operations.

Long-term memory interacts bidirectionally with globally available information. A conscious representation can trigger retrieval of related concepts, facts, or previous experiences, while retrieved memories can themselves become candidates for global access. Conscious processing can also promote memory encoding. The global workspace therefore creates a dynamic bridge between immediate cognitive activity and accumulated knowledge.

Perception can be understood as a progression from extensive unconscious processing toward selective global access. Sensory systems initially analyze many features and patterns in parallel. Some representations become sufficiently salient or task-relevant to attract attention and participate in competition. When selected and broadcast, perceptual content becomes available for explicit recognition, reporting, reasoning, and deliberate action.

Goals strongly influence workspace competition because information relevant to current objectives can receive greater priority. The same sensory event may become globally significant in one context and remain largely ignored in another. Goal-directed attention therefore modifies the competition among candidate contents, allowing cognition to allocate its limited global processing capacity according to current behavioral requirements.

Novelty and unexpected events can also capture global access. When environmental information violates expectations, specialized systems may generate strong signals indicating that existing models are insufficient. Such information can interrupt ongoing processing and become globally broadcast. This enables the cognitive system to reorient attention, retrieve relevant knowledge, revise expectations, and select a more appropriate response.

Global Workspace Theory provides an important account of flexible behavior. Routine actions can often be controlled by specialized automatic processes without requiring global access. Difficult, novel, ambiguous, or conflicting situations require broader coordination among memory, evaluation, reasoning, and action systems. Global broadcasting becomes especially valuable under these conditions because information must influence several cognitive functions at once.

This distinction has similarities with dual-process theories. Fast and familiar behavior can often proceed through specialized automatic mechanisms, while difficult problems may require globally coordinated processing. However, Global Workspace Theory is not simply a System 1 and System 2 model. Its emphasis is on information availability and cognitive integration rather than dividing cognition into exactly two independent processing systems.

Reasoning can unfold through repeated episodes of global broadcasting. A representation becomes globally available, activates relevant memories and processes, and generates new candidate information. Some of this new information then competes for the next broadcast. Multi-step reasoning can therefore emerge as a sequence of globally accessible states in which intermediate conclusions repeatedly modify the context for subsequent processing.

Planning can operate in a similar manner. A goal becomes globally available and activates possible actions, memories, constraints, and predictions. Candidate consequences can then enter the workspace and influence subsequent evaluation. Through repeated broadcasts, the system can construct and compare possible future trajectories. Deliberation consequently emerges from successive cycles of selection, broadcasting, evaluation, and updating.

Global Workspace Theory also provides a useful perspective on meta-cognition. Information about uncertainty, errors, conflicts, or performance can itself become globally available. Once broadcast, these signals can influence reasoning strategies, attention allocation, memory retrieval, and action selection. The system can therefore regulate aspects of its own processing by making internally generated information accessible to multiple cognitive mechanisms.

The theory has influenced computational cognitive architectures, particularly systems that model cognition as recurring cycles of competition and broadcast. LIDA is a prominent example in which attention coalitions compete for access to a global workspace and winning information is distributed throughout the architecture. Such computational interpretations demonstrate how abstract principles of global availability can be translated into mechanisms for integrated cognitive processing.

Global Workspace Theory is also conceptually relevant to modern artificial intelligence. Contemporary AI systems often contain specialized components for perception, language, memory, planning, reasoning, and action. A workspace-like mechanism could provide a shared representational context through which selected information becomes available to multiple components, helping coordinate otherwise separate capabilities within a persistent intelligent agent.

In agentic AI, global broadcasting can be interpreted as a mechanism for coordinating goals, observations, memories, plans, tool results, and internal evaluations. Not every piece of information needs to influence every process continuously. Instead, important information can be selected and placed into a shared context, allowing planning, reasoning, memory, and action systems to respond coherently to changing circumstances.

The concept is particularly relevant to Physical AI because embodied agents continuously receive far more sensory information than can be processed through high-level reasoning. Cameras, LiDAR, audio, proprioception, tactile sensors, and internal system states may generate enormous streams of data. Attention mechanisms must identify important events, while workspace-like processing can distribute selected information to planning, memory, reasoning, and control systems.

A robot encountering an unexpected obstacle illustrates this principle. Low-level perception may detect the object automatically, but information about the obstacle can become globally significant when it threatens the current goal. Broadcasting this information can activate localization, world modeling, risk assessment, path planning, memory retrieval, and action-selection processes, enabling coordinated adaptation rather than an isolated perceptual response.

Modern neural architectures provide possible mechanisms for implementing portions of these ideas, although they should not automatically be equated with Global Workspace Theory. Attention mechanisms, multimodal representations, recurrent state, memory systems, and shared latent spaces can facilitate information integration. A complete workspace-inspired architecture additionally requires mechanisms for competition, selective access, broadcasting, persistent context, and coordinated downstream influence.

The broader importance of Global Workspace Theory lies in explaining how a system composed of many specialized processes can nevertheless behave as an integrated cognitive agent. Extensive unconscious processing generates candidate information, attention organizes competition, selected content enters a limited workspace, global broadcasting distributes that content, and specialized systems use the shared information to guide memory, reasoning, learning, and action.

Ultimately, Global Workspace Theory presents consciousness as a mechanism of global information availability and cognitive coordination. Intelligence does not require every process to access every piece of information continuously. Instead, selective broadcasting allows important information to temporarily organize distributed cognitive activity. This principle provides a powerful conceptual bridge among consciousness research, cognitive architecture, agentic AI, and embodied Physical AI.

전역 작업공간 이론(Global Workspace Theory)은 선택된 정보가 서로 전문화되어 있는 여러 인지 과정(Cognitive Processes)에서 전역적으로 이용 가능하게 될 때 의식적 인지(Conscious Cognition)가 나타난다고 제안합니다. 의식이 하나의 중앙 처리기(Central Processor)에 의해 생성된다고 가정하는 대신, 이 이론은 마음을 전문화된 여러 시스템으로 구성된 분산 구조(Distributed Architecture)로 설명합니다. 대부분의 과정은 국소적이고 무의식적으로 작동하며, 제한적으로 선택된 정보만 인지 시스템 전체에 광범위하게 접근할 수 있게 됩니다.

이 이론은 의식(Consciousness)과 인지 통합(Cognitive Integration)을 이해하기 위한 기능적 프레임워크로 전역 작업공간(Global Workspace)을 제안한 버나드 바스(Bernard Baars)와 밀접하게 관련되어 있습니다. 이 이론이 다루는 핵심 문제는 지각(Perception), 기억(Memory), 언어(Language), 주의(Attention), 평가(Evaluation), 행동(Action)에 관여하는 수많은 전문화된 과정들이 어떻게 서로의 활동을 조정할 수 있는가입니다. 공유 작업공간(Shared Workspace)은 선택된 정보가 여러 시스템에 동시에 영향을 미칠 수 있도록 하는 메커니즘을 제공합니다.

전역 작업공간을 설명하기 위해 흔히 사용되는 비유는 극장(Theater)입니다. 의식적 정보는 무대(Stage)에서 조명을 받는 내용과 유사하며, 수많은 무의식적 과정은 무대 뒤에서 작동합니다. 주의는 어떤 정보가 조명된 무대에 도달할지를 결정하며, 선택된 내용은 이후 전문화된 수많은 인지 시스템이라는 관객에게 전달됩니다. 이러한 비유는 광범위한 무의식적 처리와 대비되는 제한적인 의식 용량(Limited Conscious Capacity)을 강조합니다.

대부분의 인지 처리는 전역 작업공간 외부에서 발생합니다. 시각 분석(Visual Analysis), 청각 처리(Auditory Processing), 기억 활성화(Memory Activation), 정서적 평가(Emotional Evaluation), 운동 준비(Motor Preparation), 기타 전문화된 연산은 의식적 상태가 되지 않고도 진행될 수 있습니다. 이러한 과정은 지속적으로 해석과 후보 내용(Candidate Contents)을 생성하며, 그중 중요하거나 관련성이 충분히 높은 일부 정보만 전역 작업공간에 접근하기 위한 경쟁에서 성공합니다.

따라서 경쟁(Competition)은 전역 작업공간 이론의 기본적인 메커니즘입니다. 인지 용량이 제한되어 있기 때문에 서로 다른 표상(Representations)이 동시에 전역적 이용 가능성(Global Availability)을 얻기 위해 경쟁할 수 있습니다. 갑작스러운 소리, 관련된 기억, 해결되지 않은 목표, 예상하지 못한 시각적 사건, 내부적으로 생성된 사고(Thought)는 모두 후보가 될 수 있습니다. 주의와 문맥적 관련성(Contextual Relevance)은 어떤 정보 연합이 우세해질지를 결정하는 데 기여합니다.

연합(Coalitions)은 작업공간에 접근하기 위한 경쟁 과정에서 서로 협력하는 관련 인지 내용의 집합입니다. 개별 신호가 독립적으로 경쟁하는 대신 지각 표상, 기억, 목표, 감정(Emotions), 문맥 정보(Contextual Information)가 결합되어 일관된 구조를 형성할 수 있습니다. 충분히 강력한 연합은 경쟁에서 승리하여 전역 작업공간에 진입하고, 통합된 내용을 광범위하게 이용할 수 있도록 합니다.

정보가 전역 작업공간에 접근하면 여러 전문화된 과정으로 전역 방송(Global Broadcast)됩니다. 기억 시스템은 관련 정보를 인코딩하거나 검색할 수 있고, 언어 메커니즘은 언어적 설명을 구성하며, 평가 시스템은 중요성을 추정하고, 계획 과정은 미래 결과를 검토하며, 운동 시스템은 반응을 준비할 수 있습니다. 따라서 방송(Broadcasting)은 모든 전문화된 하위 시스템이 서로 직접 연결될 필요 없이 조정된 인지를 가능하게 합니다.

전역 방송은 인지 통합 문제(Cognitive Integration Problem)에 대한 하나의 해결책을 제공합니다. 전문화된 처리기는 서로 다른 형태의 정보를 가지고 있을 수 있지만, 전역적으로 이용 가능한 내용은 여러 처리기에 동시에 영향을 미치는 공유 문맥(Shared Context)을 형성합니다. 이를 통해 지각은 기억에 영향을 주고, 기억은 의사결정에 영향을 주며, 목표는 주의에 영향을 주고, 의식적 평가는 행동을 수정할 수 있습니다. 복잡한 인지는 이러한 조정된 정보 교환을 통해 나타납니다.

의식적 접근(Conscious Access)은 특정 순간에 발생하는 막대한 양의 무의식적 처리와 비교하면 매우 제한적입니다. 이러한 병목 현상(Bottleneck)이 반드시 약점인 것은 아닙니다. 선택된 정보만 전역적으로 이용할 수 있도록 함으로써 아키텍처는 광범위한 조정이 필요한 정보에 우선순위를 부여하고 일상적인 연산은 전문화된 무의식적 메커니즘에 맡길 수 있습니다. 따라서 의식은 희소한 조정 자원(Scarce Coordination Resource)으로 기능할 수 있습니다.

주의와 의식은 이 프레임워크에서 밀접하게 관련되어 있지만 동일한 개념으로 취급해서는 안 됩니다. 주의는 전역 작업공간에 접근할 가능성이 있는 정보를 증폭(Amplify), 선택(Select), 조직화(Organize)하는 데 도움을 줍니다. 의식은 선택된 내용이 전역적으로 방송될 때 발생하는 광범위한 이용 가능성을 보다 구체적으로 의미합니다. 따라서 주의 메커니즘은 무엇이 전역적으로 접근 가능해지는지를 결정하는 중요한 요소로 볼 수 있습니다.

작업 기억(Working Memory) 역시 전역 작업공간 처리와 밀접하게 연결됩니다. 전역적으로 이용 가능하게 된 정보는 추론(Reasoning), 계획(Planning), 비교(Comparison), 의사결정에 영향을 줄 수 있을 정도로 충분한 시간 동안 활성 상태를 유지할 수 있습니다. 반복 처리(Recurrent Processing)는 연속적인 인지 순간에 걸쳐 선택된 표상을 유지하거나 갱신할 수 있습니다. 따라서 작업공간은 복잡한 인지 연산에 필요한 정보의 일시적인 통합(Temporary Integration)을 지원합니다.

장기 기억(Long-term Memory)은 전역적으로 이용 가능한 정보와 양방향으로 상호작용합니다. 의식적인 표상은 관련된 개념, 사실, 이전 경험의 검색을 활성화할 수 있으며, 검색된 기억 자체가 다시 전역적 접근의 후보가 될 수 있습니다. 의식적 처리는 기억 인코딩(Memory Encoding)을 촉진할 수도 있습니다. 따라서 전역 작업공간은 현재의 인지 활동과 축적된 지식 사이를 연결하는 동적인 가교 역할을 합니다.

지각은 광범위한 무의식적 처리에서 선택적인 전역 접근으로 진행되는 과정으로 이해할 수 있습니다. 감각 시스템(Sensory Systems)은 처음에 수많은 특징과 패턴을 병렬적으로 분석합니다. 그중 일부 표상은 충분한 현저성(Salience)이나 과제 관련성(Task Relevance)을 가지게 되어 주의를 끌고 경쟁에 참여합니다. 선택되어 방송되면 이러한 지각 내용은 명시적인 인식(Explicit Recognition), 보고(Reporting), 추론, 숙고적 행동(Deliberate Action)에 이용될 수 있습니다.

목표(Goals)는 현재의 목적과 관련된 정보에 더 높은 우선순위를 부여할 수 있기 때문에 작업공간 경쟁에 강한 영향을 줍니다. 동일한 감각 사건도 한 문맥에서는 전역적으로 중요해질 수 있지만 다른 문맥에서는 대부분 무시될 수 있습니다. 따라서 목표 지향적 주의(Goal-directed Attention)는 후보 내용 사이의 경쟁을 변화시키고, 현재의 행동 요구사항에 따라 제한된 전역 처리 용량을 할당하도록 합니다.

새로움(Novelty)과 예상하지 못한 사건 역시 전역 접근을 확보할 수 있습니다. 환경 정보가 기대(Expectations)를 위반하면 전문화된 시스템은 기존 모델이 충분하지 않다는 것을 나타내는 강력한 신호를 생성할 수 있습니다. 이러한 정보는 진행 중인 처리를 중단시키고 전역적으로 방송될 수 있습니다. 이를 통해 인지 시스템은 주의를 재조정하고, 관련 지식을 검색하고, 기대를 수정하며, 보다 적절한 반응을 선택할 수 있습니다.

전역 작업공간 이론은 유연한 행동(Flexible Behavior)을 설명하는 중요한 관점을 제공합니다. 일상적인 행동은 전역 접근 없이도 전문화된 자동적 과정(Automatic Processes)에 의해 제어될 수 있습니다. 그러나 어렵거나, 새롭거나, 모호하거나, 충돌이 발생하는 상황에서는 기억, 평가, 추론, 행동 시스템 사이의 더 광범위한 조정이 필요합니다. 이러한 상황에서는 정보가 여러 인지 기능에 동시에 영향을 주어야 하므로 전역 방송이 특히 중요해집니다.

이러한 구분은 이중 처리 이론(Dual-process Theories)과 유사한 측면을 가지고 있습니다. 빠르고 익숙한 행동은 전문화된 자동적 메커니즘을 통해 진행될 수 있지만, 어려운 문제는 전역적으로 조정된 처리를 필요로 할 수 있습니다. 그러나 전역 작업공간 이론은 단순한 시스템 1(System 1)과 시스템 2(System 2) 모델은 아닙니다. 이 이론의 핵심은 인지를 정확히 두 개의 독립적인 처리 시스템으로 구분하는 것이 아니라 정보의 이용 가능성과 인지 통합에 있습니다.

추론은 반복적인 전역 방송을 통해 전개될 수 있습니다. 하나의 표상이 전역적으로 이용 가능해지면 관련 기억과 인지 과정을 활성화하고 새로운 후보 정보를 생성합니다. 새롭게 생성된 정보 가운데 일부는 다시 다음 전역 방송을 위한 경쟁에 참여합니다. 따라서 다단계 추론(Multi-step Reasoning)은 중간 결론이 이후 처리의 문맥을 반복적으로 변화시키는 일련의 전역 접근 상태를 통해 나타날 수 있습니다.

계획 역시 유사한 방식으로 작동할 수 있습니다. 하나의 목표가 전역적으로 이용 가능해지면 가능한 행동, 기억, 제약 조건(Constraints), 예측(Predictions)을 활성화합니다. 이후 후보 결과가 작업공간에 진입하여 다음 평가에 영향을 줄 수 있습니다. 반복적인 방송을 통해 시스템은 가능한 미래 경로(Future Trajectories)를 구성하고 비교할 수 있습니다. 따라서 숙고(Deliberation)는 연속적인 선택, 방송, 평가, 업데이트 주기를 통해 나타날 수 있습니다.

전역 작업공간 이론은 메타인지(Meta-cognition)에 대해서도 유용한 관점을 제공합니다. 불확실성(Uncertainty), 오류(Errors), 충돌(Conflicts), 수행 상태(Performance)에 관한 정보 자체가 전역적으로 이용 가능해질 수 있습니다. 이러한 신호가 방송되면 추론 전략, 주의 할당, 기억 검색, 행동 선택에 영향을 줄 수 있습니다. 따라서 시스템은 내부적으로 생성된 정보를 여러 인지 메커니즘에서 이용 가능하게 함으로써 자신의 처리 과정 일부를 조절할 수 있습니다.

이 이론은 인지를 반복적인 경쟁과 방송 주기로 모델링하는 계산 인지 아키텍처(Computational Cognitive Architectures)에 영향을 주었습니다. 대표적인 사례가 LIDA이며, LIDA에서는 주의 연합(Attention Coalitions)이 전역 작업공간에 접근하기 위해 경쟁하고, 경쟁에서 승리한 정보가 아키텍처 전체에 분산됩니다. 이러한 계산적 해석은 전역적 정보 이용 가능성이라는 추상적인 원리가 통합 인지 처리를 위한 구체적인 메커니즘으로 어떻게 변환될 수 있는지를 보여줍니다.

전역 작업공간 이론은 현대 인공지능(Artificial Intelligence)과도 개념적으로 관련이 있습니다. 현대의 인공지능 시스템은 지각, 언어, 기억, 계획, 추론, 행동을 위한 전문화된 구성 요소를 포함하는 경우가 많습니다. 작업공간과 유사한 메커니즘은 선택된 정보가 여러 구성 요소에서 이용될 수 있는 공유 표상 문맥(Shared Representational Context)을 제공하여 지속적으로 작동하는 지능형 에이전트(Persistent Intelligent Agent) 내부에서 서로 분리된 능력을 조정하는 데 도움을 줄 수 있습니다.

에이전트형 인공지능(Agentic AI)에서 전역 방송은 목표, 관찰, 기억, 계획, 도구 실행 결과(Tool Results), 내부 평가를 조정하는 메커니즘으로 해석할 수 있습니다. 모든 정보가 항상 모든 처리 과정에 영향을 줄 필요는 없습니다. 대신 중요한 정보를 선택하여 공유 문맥에 배치함으로써 계획, 추론, 기억, 행동 시스템이 변화하는 상황에 일관되게 대응하도록 할 수 있습니다.

이 개념은 체화된 에이전트(Embodied Agents)가 상위 수준 추론으로 처리할 수 있는 양보다 훨씬 많은 감각 정보를 지속적으로 받아들인다는 점에서 피지컬 인공지능(Physical AI)과 특히 관련성이 높습니다. 카메라(Cameras), 라이다(LiDAR), 오디오(Audio), 고유수용감각(Proprioception), 촉각 센서(Tactile Sensors), 내부 시스템 상태는 막대한 데이터 스트림을 생성할 수 있습니다. 주의 메커니즘은 중요한 사건을 식별하고, 작업공간과 유사한 처리는 선택된 정보를 계획, 기억, 추론, 제어 시스템으로 전달할 수 있습니다.

예상하지 못한 장애물을 마주친 로봇은 이러한 원리를 보여주는 사례입니다. 저수준 지각(Low-level Perception)은 객체를 자동으로 탐지할 수 있지만, 해당 장애물이 현재 목표를 위협하면 장애물에 관한 정보가 전역적으로 중요해질 수 있습니다. 이 정보를 방송하면 위치 추정(Localization), 월드 모델링(World Modeling), 위험 평가(Risk Assessment), 경로 계획(Path Planning), 기억 검색, 행동 선택 과정이 활성화되어 고립된 지각 반응이 아니라 조정된 적응 행동(Coordinated Adaptive Behavior)을 가능하게 합니다.

현대의 신경 아키텍처(Neural Architectures)는 이러한 아이디어의 일부를 구현할 수 있는 잠재적 메커니즘을 제공하지만, 이를 자동적으로 전역 작업공간 이론과 동일시해서는 안 됩니다. 어텐션 메커니즘(Attention Mechanisms), 멀티모달 표상(Multimodal Representations), 순환 상태(Recurrent State), 기억 시스템, 공유 잠재 공간(Shared Latent Spaces)은 정보 통합을 촉진할 수 있습니다. 완전한 작업공간 기반 아키텍처에는 경쟁, 선택적 접근, 방송, 지속적 문맥(Persistent Context), 조정된 하위 시스템 영향 메커니즘이 추가로 필요합니다.

전역 작업공간 이론의 보다 광범위한 중요성은 여러 전문화된 과정으로 구성된 시스템이 어떻게 하나의 통합된 인지 에이전트(Integrated Cognitive Agent)처럼 행동할 수 있는지를 설명하는 데 있습니다. 광범위한 무의식적 처리는 후보 정보를 생성하고, 주의는 경쟁을 조직하며, 선택된 내용은 제한된 작업공간에 진입하고, 전역 방송은 해당 내용을 분산시키며, 전문화된 시스템은 공유된 정보를 사용하여 기억, 추론, 학습, 행동을 안내합니다.

궁극적으로 전역 작업공간 이론(Global Workspace Theory)은 의식(Consciousness)을 전역적인 정보 이용 가능성(Global Information Availability)과 인지 조정(Cognitive Coordination)을 위한 메커니즘으로 설명합니다. 지능은 모든 처리 과정이 모든 정보에 지속적으로 접근할 것을 요구하지 않습니다. 대신 선택적 방송(Selective Broadcasting)을 통해 중요한 정보가 일시적으로 분산된 인지 활동을 조직할 수 있습니다. 이러한 원리는 의식 연구(Consciousness Research), 인지 아키텍처(Cognitive Architecture), 에이전트형 인공지능(Agentic AI), 체화된 피지컬 인공지능(Embodied Physical AI)을 연결하는 강력한 개념적 가교를 제공합니다.

##  

## 06.06 Predictive Processing [w/Code]

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

Predictive processing is a theoretical framework in cognitive science that describes the brain as an active prediction system rather than a passive receiver of sensory information. According to this view, perception emerges from continuous interaction between internally generated predictions and incoming sensory signals. The brain attempts to anticipate the causes of sensory input and updates its internal models whenever observations differ from what was expected.

A central idea of predictive processing is that the nervous system maintains generative models of the world. These models represent hypotheses about objects, events, relationships, bodily states, and environmental dynamics that could produce particular sensory patterns. Instead of reconstructing reality entirely from incoming data, the brain uses these models to predict likely sensory input and compares those predictions with actual observations.

The difference between predicted sensory information and observed sensory information is called prediction error. Prediction errors indicate that the current internal model does not completely explain the available evidence. These error signals can propagate through the processing hierarchy and encourage changes in beliefs, representations, attention, or behavior. Cognition therefore becomes a continuous process of predicting, comparing, correcting, and predicting again.

Predictive processing is commonly described through hierarchical organization. Higher levels represent relatively abstract and temporally extended causes, while lower levels represent increasingly detailed sensory properties. Predictions flow downward through this hierarchy, whereas prediction errors generally provide information upward. Repeated interaction between these directions allows abstract expectations and detailed sensory evidence to constrain each other.

Hierarchical prediction helps explain how perception can remain stable despite noisy, incomplete, or ambiguous sensory signals. Higher-level expectations provide contextual information that helps interpret uncertain lower-level input. At the same time, sufficiently strong prediction errors can challenge existing expectations. Perception therefore depends neither entirely on sensory evidence nor entirely on prior beliefs, but on their continuously changing interaction.

This relationship is closely connected to Bayesian interpretations of cognition. Prior beliefs represent expectations about possible causes of observations, while sensory evidence provides likelihood information. Their combination produces updated beliefs about what is most likely occurring. Predictive processing does not require every neural computation to explicitly perform Bayesian equations, but Bayesian inference provides an important mathematical framework for understanding the underlying logic.

Not every prediction error should have equal influence. Sensory signals differ in reliability, and predictions differ in confidence. Predictive processing therefore introduces the concept of precision, which represents the estimated reliability or importance of a signal. Highly precise prediction errors can strongly modify beliefs, whereas uncertain or noisy errors may receive less influence. Precision weighting consequently becomes essential for adaptive inference.

Attention can be interpreted partly as the selective regulation of precision. When a stimulus, location, feature, or task becomes important, the cognitive system can increase the effective weight assigned to relevant sensory evidence or prediction errors. This allows selected information to exert greater influence over inference. Attention therefore helps determine not only what information is processed, but how strongly particular evidence modifies internal models.

Predictive processing provides a different interpretation of perception from classical bottom-up models. Sensory information does not simply travel upward until an object is recognized. Higher-level hypotheses continuously generate expectations about lower-level representations. Incoming signals mainly provide evidence about mismatches. Perception can therefore be understood as inference about the hidden causes most capable of explaining sensory observations.

Visual perception illustrates this interaction clearly. The brain may predict shapes, boundaries, motion, depth, objects, and scene structure before all sensory details have been fully resolved. Context can help interpret ambiguous visual information, while unexpected features generate errors requiring model revision. Recognition consequently emerges from recurrent interaction between expectations and evidence rather than from a purely feedforward sequence.

Prediction also extends beyond immediate perception into time. Internal models can estimate what is likely to happen next based on current state, previous experience, and learned environmental dynamics. Temporal prediction enables anticipation of moving objects, other agents, future sensory consequences, and possible outcomes of actions. This capability connects predictive processing directly with planning, control, and adaptive behavior.

The body itself is an important target of prediction. The nervous system receives continuous information about posture, movement, internal physiological conditions, and bodily sensations. Predictive mechanisms can estimate expected proprioceptive and interoceptive states and compare them with actual signals. This makes predictive processing relevant not only to external perception but also to bodily regulation, emotion, movement, and sense of self.

Action introduces an important extension known as active inference. Prediction errors can sometimes be reduced by changing internal beliefs, but they can also be reduced by acting on the environment so that observations become more consistent with predicted or desired states. An agent therefore does not merely update its internal model to fit the world; it can also change the world through action.

Active inference creates a tight relationship among perception, prediction, and control. Suppose an agent predicts that its body should occupy a particular state. Motor actions can change the physical state until proprioceptive observations become consistent with that prediction. More broadly, goal-directed behavior can be interpreted as selecting actions that move the agent toward expected or preferred future states.

Learning improves the generative models responsible for prediction. Repeated prediction errors reveal systematic weaknesses in existing representations and environmental dynamics. Over time, model parameters and structures can be adjusted so that future observations become more accurately predicted. Learning therefore changes the expectations used in subsequent perception, producing a continuous feedback relationship among prediction, error, adaptation, and experience.

Prediction errors can arise at multiple levels of abstraction. A low-level error might involve unexpected color, motion, sound, or position, while a higher-level error might indicate that an object, event, intention, or causal relationship differs from expectation. Hierarchical processing allows these different errors to influence appropriate levels of representation rather than forcing every mismatch to modify the entire cognitive model.

Novelty and surprise are naturally important within predictive processing. An event is surprising when it is poorly predicted by the current model. Unexpected observations generate larger prediction errors and may attract additional processing resources. Persistent surprise can indicate that the existing model is inadequate, encouraging learning or behavioral exploration. Prediction therefore provides a computational basis for detecting meaningful changes in the environment.

Uncertainty is equally important because an intelligent system rarely knows the world with complete confidence. Predictions can represent multiple possible interpretations or future states rather than one deterministic answer. As evidence accumulates, confidence can change. Effective cognition therefore requires not only predicting what may happen but estimating uncertainty about those predictions and deciding when additional information is necessary.

Predictive processing can also contribute to an understanding of cognitive biases and perceptual illusions. Strong prior expectations may dominate when sensory evidence is weak or ambiguous, causing perception to favor an expected interpretation. Conversely, highly weighted sensory errors can override prior knowledge. Many cognitive phenomena can therefore be analyzed as consequences of how priors, evidence, uncertainty, and precision are balanced.

Memory plays an important role because predictions depend on previously learned regularities. Semantic knowledge provides expectations about objects and relationships, episodic memory supplies information from previous experiences, and procedural knowledge contributes expectations about actions and outcomes. Memory is therefore not merely a historical record but an important source for constructing predictions about present and future situations.

Predictive processing has significant connections with world models in artificial intelligence. A world model attempts to represent environmental state and dynamics so that an agent can estimate how situations may evolve. Predictions can include future observations, latent states, rewards, risks, or consequences of candidate actions. Prediction errors generated during learning can then improve the model\'s ability to represent environmental dynamics.

Modern generative models provide computational mechanisms that resemble portions of this framework. Learned latent representations can encode hidden causes of observations, while generative components can reconstruct or predict sensory information. Sequence models can estimate future states from previous states and actions. However, predictive processing is broader than any single neural architecture because it proposes an integrated theory of perception, learning, attention, and action.

For agentic AI, predictive processing suggests that an intelligent agent should continuously maintain expectations about its environment, its own actions, and future outcomes. The agent can compare predicted states with observations, detect deviations, update its internal representation, and reconsider plans when necessary. This creates a closed cognitive loop in which prediction becomes a mechanism for monitoring both the external world and the agent\'s own behavior.

Predictive processing is particularly relevant to Physical AI because robots operate in dynamic environments where sensory information is incomplete, noisy, delayed, and uncertain. A robot can combine cameras, LiDAR, radar, proprioception, localization, and other sensors with predictions generated from an internal world model. Expected observations provide context, while mismatches reveal environmental changes or failures in the current model.

A mobile robot, for example, can predict the future positions of pedestrians, vehicles, obstacles, and itself. As new sensor measurements arrive, observed states can be compared with predicted trajectories. Small errors may be absorbed through normal state estimation, whereas significant errors can trigger model updates, replanning, or emergency responses. Prediction thus connects perception directly with safe navigation and adaptive control.

Different prediction horizons can operate simultaneously within an embodied system. Millisecond-scale predictions may support motor control, short-term predictions may estimate object motion, intermediate predictions may support navigation and manipulation, and longer-term predictions may contribute to task planning. Hierarchical temporal models can coordinate these horizons so that immediate control remains connected with broader goals and expected future states.

The broader significance of predictive processing lies in treating intelligence as continuous model-based interaction with an uncertain world. Perception estimates hidden causes, prediction anticipates future sensory states, prediction errors reveal mismatches, precision determines their influence, learning improves the model, and action changes the environment. These processes form a recurring loop rather than isolated cognitive functions.

Ultimately, predictive processing presents cognition as prediction-driven adaptation. An intelligent system continuously asks, implicitly, what state of the world would explain its observations, what is likely to happen next, how confident those expectations are, and what should change when reality differs from prediction. This framework provides an important conceptual bridge among neuroscience, cognitive science, world models, agentic AI, and embodied Physical AI.

예측 처리(Predictive Processing)는 뇌를 감각 정보(Sensory Information)를 수동적으로 받아들이는 시스템이 아니라 능동적인 예측 시스템(Active Prediction System)으로 설명하는 인지과학(Cognitive Science)의 이론적 프레임워크입니다. 이 관점에 따르면 지각(Perception)은 내부적으로 생성된 예측(Internally Generated Predictions)과 외부에서 들어오는 감각 신호 사이의 지속적인 상호작용을 통해 나타납니다. 뇌는 감각 입력의 원인을 미리 예측하려고 하며, 실제 관찰이 예상과 다를 때마다 내부 모델(Internal Models)을 업데이트합니다.

예측 처리의 핵심 개념은 신경계(Nervous System)가 세계에 대한 생성 모델(Generative Models)을 유지한다는 것입니다. 이러한 모델은 특정 감각 패턴을 생성할 수 있는 객체, 사건, 관계, 신체 상태(Bodily States), 환경 동역학(Environmental Dynamics)에 관한 가설을 표현합니다. 뇌는 입력 데이터만으로 현실을 완전히 재구성하는 대신 이러한 모델을 사용하여 발생할 가능성이 높은 감각 입력을 예측하고 실제 관찰 결과와 비교합니다.

예측된 감각 정보와 실제로 관찰된 감각 정보 사이의 차이를 예측 오류(Prediction Error)라고 합니다. 예측 오류는 현재의 내부 모델이 이용 가능한 증거를 완전하게 설명하지 못한다는 것을 나타냅니다. 이러한 오류 신호(Error Signals)는 처리 계층을 따라 전달되면서 믿음(Beliefs), 표상(Representations), 주의(Attention), 행동(Behavior)의 변화를 유도할 수 있습니다. 따라서 인지는 예측하고, 비교하고, 수정한 다음 다시 예측하는 지속적인 과정이 됩니다.

예측 처리는 일반적으로 계층적 조직(Hierarchical Organization)을 통해 설명됩니다. 상위 수준은 비교적 추상적이고 시간적으로 확장된 원인을 표현하는 반면, 하위 수준은 점점 더 세부적인 감각 특성을 표현합니다. 예측은 이러한 계층을 따라 하향식(Top-down)으로 전달되며, 예측 오류는 일반적으로 상향식(Bottom-up)으로 정보를 제공합니다. 두 방향의 반복적인 상호작용을 통해 추상적인 기대와 세부적인 감각 증거가 서로를 제약할 수 있습니다.

계층적 예측(Hierarchical Prediction)은 잡음이 많거나 불완전하고 모호한 감각 신호에도 불구하고 지각이 어떻게 안정적으로 유지될 수 있는지를 설명하는 데 도움을 줍니다. 상위 수준의 기대는 불확실한 하위 수준 입력을 해석하는 데 필요한 문맥 정보를 제공합니다. 동시에 충분히 강한 예측 오류는 기존의 기대에 이의를 제기할 수 있습니다. 따라서 지각은 감각 증거나 사전 믿음 중 어느 하나에만 의존하지 않고 이들 사이의 지속적으로 변화하는 상호작용에 의존합니다.

이러한 관계는 인지에 대한 베이지안 해석(Bayesian Interpretations)과 밀접하게 연결됩니다. 사전 믿음(Prior Beliefs)은 관찰의 가능한 원인에 대한 기대를 나타내고, 감각 증거는 우도 정보(Likelihood Information)를 제공합니다. 이 두 요소의 결합을 통해 현재 어떤 일이 발생하고 있을 가능성이 가장 높은지에 대한 믿음이 업데이트됩니다. 예측 처리가 모든 신경 계산에서 명시적으로 베이지안 방정식을 수행해야 한다는 의미는 아니지만, 베이지안 추론(Bayesian Inference)은 그 기본 논리를 이해하기 위한 중요한 수학적 프레임워크를 제공합니다.

모든 예측 오류가 동일한 영향력을 가져야 하는 것은 아닙니다. 감각 신호는 신뢰성(Reliability)이 서로 다르며, 예측 역시 서로 다른 신뢰도(Confidence)를 가집니다. 따라서 예측 처리에서는 신호의 추정된 신뢰성이나 중요성을 나타내는 정밀도(Precision)라는 개념을 도입합니다. 정밀도가 높은 예측 오류는 믿음을 크게 수정할 수 있지만 불확실하거나 잡음이 많은 오류는 상대적으로 작은 영향을 미칠 수 있습니다. 따라서 정밀도 가중(Precision Weighting)은 적응적 추론(Adaptive Inference)에 필수적입니다.

주의(Attention)는 부분적으로 정밀도를 선택적으로 조절하는 과정으로 해석할 수 있습니다. 특정 자극, 위치, 특징 또는 과제가 중요해지면 인지 시스템은 관련된 감각 증거나 예측 오류에 부여되는 실질적인 가중치를 증가시킬 수 있습니다. 이를 통해 선택된 정보가 추론 과정에 더 큰 영향을 미치게 됩니다. 따라서 주의는 어떤 정보가 처리되는지만 결정하는 것이 아니라 특정 증거가 내부 모델을 얼마나 강하게 수정하는지도 결정하는 데 도움을 줍니다.

예측 처리는 고전적인 상향식 모델(Bottom-up Models)과 다른 방식으로 지각을 해석합니다. 감각 정보가 단순히 상위 계층으로 전달되어 최종적으로 객체가 인식되는 것이 아닙니다. 상위 수준의 가설은 하위 수준의 표상에 관한 기대를 지속적으로 생성합니다. 입력 신호는 주로 이러한 기대와의 불일치에 관한 증거를 제공합니다. 따라서 지각은 감각 관찰을 가장 잘 설명할 수 있는 숨겨진 원인(Hidden Causes)을 추론하는 과정으로 이해할 수 있습니다.

시각 지각(Visual Perception)은 이러한 상호작용을 명확하게 보여줍니다. 뇌는 모든 감각적 세부 사항이 완전히 해결되기 전에 형태(Shapes), 경계(Boundaries), 움직임(Motion), 깊이(Depth), 객체(Objects), 장면 구조(Scene Structure)를 예측할 수 있습니다. 문맥은 모호한 시각 정보를 해석하는 데 도움을 주며, 예상하지 못한 특징은 모델 수정을 요구하는 오류를 생성합니다. 따라서 인식(Recognition)은 순수한 순방향 처리(Feedforward Sequence)가 아니라 기대와 증거 사이의 반복적인 상호작용에서 나타납니다.

예측은 즉각적인 지각을 넘어 시간적 차원으로 확장됩니다. 내부 모델은 현재 상태, 이전 경험, 학습된 환경 동역학을 기반으로 다음에 어떤 일이 발생할 가능성이 높은지를 추정할 수 있습니다. 시간적 예측(Temporal Prediction)을 통해 움직이는 객체, 다른 에이전트, 미래의 감각 결과, 행동으로 인해 발생할 수 있는 결과를 예상할 수 있습니다. 이러한 능력은 예측 처리를 계획(Planning), 제어(Control), 적응적 행동(Adaptive Behavior)과 직접 연결합니다.

신체 자체 역시 중요한 예측 대상입니다. 신경계는 자세(Posture), 움직임, 내부 생리적 상태(Physiological Conditions), 신체 감각에 관한 정보를 지속적으로 받아들입니다. 예측 메커니즘은 예상되는 고유수용감각(Proprioceptive) 및 내수용감각(Interoceptive) 상태를 추정하고 이를 실제 신호와 비교할 수 있습니다. 따라서 예측 처리는 외부 지각뿐만 아니라 신체 조절(Bodily Regulation), 감정(Emotion), 움직임, 자아 감각(Sense of Self)과도 관련됩니다.

행동(Action)은 능동 추론(Active Inference)이라는 중요한 확장을 도입합니다. 예측 오류는 내부 믿음을 변화시켜 감소시킬 수도 있지만, 환경에 행동을 가하여 관찰 결과가 예측되거나 원하는 상태와 더 일치하도록 만들어 감소시킬 수도 있습니다. 따라서 에이전트(Agent)는 단순히 세계에 맞추어 자신의 내부 모델을 업데이트하는 것이 아니라 행동을 통해 세계 자체를 변화시킬 수도 있습니다.

능동 추론은 지각, 예측, 제어 사이에 긴밀한 관계를 형성합니다. 예를 들어 에이전트가 자신의 신체가 특정 상태에 있어야 한다고 예측한다고 가정할 수 있습니다. 운동 행동(Motor Actions)은 고유수용감각 관찰이 해당 예측과 일치할 때까지 물리적 상태를 변화시킬 수 있습니다. 보다 광범위하게는 목표 지향적 행동(Goal-directed Behavior)을 에이전트를 예상되거나 선호되는 미래 상태(Preferred Future States)로 이동시키는 행동을 선택하는 과정으로 해석할 수 있습니다.

학습(Learning)은 예측을 담당하는 생성 모델을 개선합니다. 반복적으로 발생하는 예측 오류는 기존 표상과 환경 동역학에 존재하는 체계적인 약점을 드러냅니다. 시간이 지나면서 모델의 파라미터와 구조를 조정하여 미래의 관찰을 더욱 정확하게 예측할 수 있습니다. 따라서 학습은 이후의 지각에서 사용되는 기대를 변화시키며, 예측, 오류, 적응(Adaptation), 경험(Experience) 사이에 지속적인 피드백 관계를 형성합니다.

예측 오류는 여러 추상화 수준(Abstraction Levels)에서 발생할 수 있습니다. 저수준 오류는 예상하지 못한 색상, 움직임, 소리, 위치와 관련될 수 있으며, 상위 수준 오류는 객체, 사건, 의도(Intention), 인과 관계(Causal Relationship)가 예상과 다르다는 것을 나타낼 수 있습니다. 계층적 처리를 통해 이러한 서로 다른 오류가 전체 인지 모델을 모두 수정하도록 하는 대신 적절한 표상 수준에 영향을 줄 수 있습니다.

새로움(Novelty)과 놀라움(Surprise)은 예측 처리에서 자연스럽게 중요한 역할을 합니다. 어떤 사건이 현재 모델에 의해 제대로 예측되지 않을 때 그 사건은 놀라운 것으로 간주됩니다. 예상하지 못한 관찰은 더 큰 예측 오류를 생성하며 추가적인 처리 자원(Processing Resources)을 끌어들일 수 있습니다. 지속적인 놀라움은 기존 모델이 충분하지 않다는 것을 나타내며 학습이나 행동적 탐색(Behavioral Exploration)을 촉진할 수 있습니다. 따라서 예측은 환경의 의미 있는 변화를 탐지하기 위한 계산적 기반을 제공합니다.

불확실성(Uncertainty) 역시 중요합니다. 지능형 시스템은 세계를 완전한 확신을 가지고 이해하는 경우가 거의 없기 때문입니다. 예측은 하나의 결정론적인 답변만을 표현하는 대신 여러 가능한 해석이나 미래 상태를 나타낼 수 있습니다. 증거가 축적되면서 신뢰도는 변화할 수 있습니다. 따라서 효과적인 인지는 무엇이 발생할지를 예측하는 것뿐만 아니라 그러한 예측에 대한 불확실성을 추정하고 언제 추가 정보가 필요한지를 결정하는 능력을 요구합니다.

예측 처리는 인지 편향(Cognitive Biases)과 지각적 착시(Perceptual Illusions)를 이해하는 데에도 기여할 수 있습니다. 감각 증거가 약하거나 모호한 경우 강력한 사전 기대가 지배적인 영향을 미쳐 예상된 해석을 선호하는 지각을 생성할 수 있습니다. 반대로 높은 가중치가 부여된 감각 오류는 사전 지식을 압도할 수 있습니다. 따라서 많은 인지 현상을 사전 믿음, 증거, 불확실성, 정밀도 사이의 균형이 어떻게 설정되는가의 결과로 분석할 수 있습니다.

기억(Memory)은 예측이 이전에 학습된 규칙성(Regularities)에 의존하기 때문에 중요한 역할을 수행합니다. 의미 기억(Semantic Memory)은 객체와 관계에 대한 기대를 제공하고, 일화 기억(Episodic Memory)은 이전 경험에서 얻은 정보를 제공하며, 절차 기억(Procedural Memory)은 행동과 결과에 대한 기대를 제공합니다. 따라서 기억은 단순히 과거의 기록이 아니라 현재와 미래 상황에 관한 예측을 구성하는 중요한 정보원입니다.

예측 처리는 인공지능의 월드 모델(World Models)과 중요한 연관성을 가집니다. 월드 모델은 환경 상태(Environmental State)와 동역학(Dynamics)을 표현하여 에이전트가 상황이 어떻게 변화할지를 추정하도록 합니다. 예측에는 미래의 관찰(Future Observations), 잠재 상태(Latent States), 보상(Rewards), 위험(Risks), 후보 행동의 결과가 포함될 수 있습니다. 학습 과정에서 생성되는 예측 오류는 환경 동역학을 표현하는 모델의 능력을 향상시킬 수 있습니다.

현대의 생성 모델(Generative Models)은 이러한 프레임워크의 일부와 유사한 계산 메커니즘을 제공합니다. 학습된 잠재 표상(Latent Representations)은 관찰의 숨겨진 원인을 인코딩할 수 있으며, 생성 구성 요소는 감각 정보를 재구성하거나 예측할 수 있습니다. 시퀀스 모델(Sequence Models)은 이전 상태와 행동으로부터 미래 상태를 추정할 수 있습니다. 그러나 예측 처리는 지각, 학습, 주의, 행동을 통합하는 이론을 제안하기 때문에 하나의 특정 신경망 아키텍처보다 훨씬 광범위한 개념입니다.

에이전트형 인공지능(Agentic AI)의 관점에서 예측 처리는 지능형 에이전트가 자신의 환경, 자신의 행동, 미래 결과에 대한 기대를 지속적으로 유지해야 한다는 점을 제안합니다. 에이전트는 예측 상태와 관찰 결과를 비교하고, 편차(Deviations)를 탐지하고, 내부 표상을 업데이트하며, 필요한 경우 계획을 다시 검토할 수 있습니다. 이를 통해 예측이 외부 세계와 에이전트 자신의 행동을 모두 감시하는 메커니즘으로 작동하는 폐쇄형 인지 루프(Closed Cognitive Loop)가 형성됩니다.

예측 처리는 로봇이 감각 정보가 불완전하고, 잡음이 많으며, 지연되고, 불확실한 동적 환경에서 작동한다는 점에서 피지컬 인공지능(Physical AI)과 특히 관련성이 높습니다. 로봇은 카메라(Cameras), 라이다(LiDAR), 레이더(Radar), 고유수용감각, 위치 추정(Localization), 기타 센서 정보를 내부 월드 모델에서 생성된 예측과 결합할 수 있습니다. 예상된 관찰은 문맥을 제공하고, 불일치는 환경 변화나 현재 모델의 실패를 드러냅니다.

예를 들어 이동 로봇(Mobile Robot)은 보행자, 차량, 장애물, 그리고 자신의 미래 위치를 예측할 수 있습니다. 새로운 센서 측정값이 들어오면 관찰된 상태를 예측된 궤적(Predicted Trajectories)과 비교할 수 있습니다. 작은 오류는 일반적인 상태 추정(State Estimation)을 통해 흡수할 수 있지만, 큰 오류는 모델 업데이트, 재계획(Replanning), 비상 대응(Emergency Responses)을 유발할 수 있습니다. 따라서 예측은 지각을 안전한 내비게이션(Safe Navigation) 및 적응적 제어와 직접 연결합니다.

체화된 시스템(Embodied System) 내부에서는 서로 다른 예측 시간 범위(Prediction Horizons)가 동시에 작동할 수 있습니다. 밀리초 수준의 예측은 운동 제어를 지원하고, 단기 예측은 객체 움직임을 추정하며, 중기 예측은 내비게이션과 조작(Manipulation)을 지원하고, 장기 예측은 과제 계획(Task Planning)에 기여할 수 있습니다. 계층적 시간 모델(Hierarchical Temporal Models)은 이러한 시간 범위를 조정하여 즉각적인 제어가 더 광범위한 목표 및 예상 미래 상태와 연결되도록 할 수 있습니다.

예측 처리의 보다 광범위한 중요성은 지능을 불확실한 세계와 지속적으로 상호작용하는 모델 기반 과정(Model-based Process)으로 다룬다는 데 있습니다. 지각은 숨겨진 원인을 추정하고, 예측은 미래의 감각 상태를 예상하며, 예측 오류는 불일치를 드러내고, 정밀도는 오류의 영향력을 결정하며, 학습은 모델을 개선하고, 행동은 환경을 변화시킵니다. 이러한 과정은 서로 고립된 인지 기능이 아니라 반복적으로 연결되는 하나의 루프를 형성합니다.

궁극적으로 예측 처리(Predictive Processing)는 인지를 예측 주도 적응(Prediction-driven Adaptation)으로 설명합니다. 지능형 시스템은 암묵적으로 어떤 세계 상태가 현재의 관찰을 설명할 수 있는지, 다음에 어떤 일이 발생할 가능성이 높은지, 이러한 기대에 대해 얼마나 확신할 수 있는지, 현실이 예측과 다를 때 무엇을 변화시켜야 하는지를 지속적으로 판단합니다. 이러한 프레임워크는 신경과학(Neuroscience), 인지과학(Cognitive Science), 월드 모델(World Models), 에이전트형 인공지능(Agentic AI), 체화된 피지컬 인공지능(Embodied Physical AI)을 연결하는 중요한 개념적 가교를 제공합니다.

##  

## 06.07 Symbolic Cognitive Models [w/Code]

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

Symbolic cognitive models represent intelligence through explicit symbols, structured knowledge, and operations that manipulate those representations according to defined rules. A symbol may represent an object, concept, event, relationship, goal, or state of the world. Cognition is modeled as transformations among symbolic structures, allowing reasoning processes to be described in an explicit and interpretable computational form.

The symbolic approach is closely associated with the physical symbol system hypothesis, which argues that intelligent behavior can emerge from systems capable of creating, modifying, combining, and interpreting symbolic expressions. Under this view, cognition depends not simply on numerical computation but on structured representations whose components have functional relationships. Reasoning becomes a process of operating systematically on these representations.

Knowledge representation is therefore fundamental to symbolic cognitive modeling. Facts may be encoded as propositions, concepts may be organized into categories, relationships may connect entities, and rules may describe how one state implies another. Structured representations allow a cognitive system to distinguish objects, properties, actions, causes, goals, and constraints while preserving relationships that can be directly inspected and manipulated.

Production rules are a common mechanism for representing procedural knowledge. A production typically contains conditions describing when the rule is applicable and actions specifying what should happen when those conditions are satisfied. Cognitive processing can proceed by matching current symbolic states against available rules, selecting an appropriate production, executing it, and updating the internal state before another processing cycle begins.

Rule-based processing provides a natural mechanism for representing skills, strategies, and decision procedures. A system can encode knowledge such as selecting an action when particular conditions occur or applying a transformation when a problem reaches a specific state. Complex behavior can emerge from sequences of relatively simple rules whose execution progressively transforms the current representation toward a desired goal.

Symbolic models often distinguish declarative knowledge from procedural knowledge. Declarative knowledge describes what the system knows, including facts, concepts, relationships, and events. Procedural knowledge describes how operations should be performed. Maintaining this distinction allows cognitive architectures to model the interaction between retrieving information and applying procedures, an organization visible in architectures such as ACT-R and SOAR.

Working memory provides a temporary symbolic representation of the current cognitive situation. It may contain active goals, perceived objects, intermediate conclusions, task constraints, and retrieved knowledge. Rules inspect this information to determine which operations are currently relevant. As processing continues, working memory changes, providing an evolving context that guides subsequent reasoning and action.

Long-term memory stores more persistent symbolic knowledge that can be retrieved when required. A reasoning process may recognize that information is missing, retrieve relevant facts or rules, and incorporate them into the active problem representation. Memory retrieval therefore supports reasoning by connecting the immediate cognitive state with previously acquired knowledge rather than requiring all information to remain continuously active.

Search is another important principle in symbolic cognition. Many cognitive tasks can be represented as movement through a problem space containing possible states and operations. A system begins with an initial state, applies available operators, evaluates resulting states, and searches for a path toward a goal. Problem solving consequently becomes structured exploration over explicitly represented possibilities.

The problem-space perspective became especially important in classical artificial intelligence and cognitive psychology. Chess, puzzles, theorem proving, planning, and logical problems can all be described in terms of states, operators, goals, and constraints. Different search strategies determine which possibilities are examined first, allowing symbolic models to explain how knowledge and heuristics reduce otherwise enormous spaces of possible solutions.

Heuristics provide practical guidance when exhaustive search is computationally impossible. Rather than exploring every possible state, symbolic systems can apply rules that estimate which alternatives are more promising. Human problem solving similarly appears to rely on structured strategies and domain knowledge. Symbolic cognitive models can represent these heuristics explicitly, making their influence on reasoning comparatively easy to analyze.

Logic provides another foundation for symbolic reasoning. Propositions can express facts, predicates can represent relationships, and inference rules can derive conclusions from existing knowledge. Deductive reasoning can preserve logical validity, while other symbolic frameworks can support uncertain, defeasible, or abductive reasoning. Explicit representations make it possible to trace which premises and operations produced a particular conclusion.

Planning extends symbolic reasoning into future action. Goals can be represented explicitly, possible actions can be described through preconditions and effects, and a planner can search for sequences of operations that transform an initial state into a desired state. This framework provides a powerful connection between abstract reasoning and goal-directed behavior because the same symbolic structures can represent both knowledge and possible actions.

Symbolic models are particularly strong when tasks require compositionality. Complex representations can be constructed from simpler components while preserving relationships among them. A system that understands symbols for objects, actions, locations, and properties can combine them into new configurations without learning every combination independently. This supports systematic reasoning and generalization across structurally related problems.

Compositional representation also supports variable binding, which allows abstract relationships to be applied to different entities. A rule may describe a relationship between variables rather than specific objects, enabling the same reasoning structure to operate across many situations. This capacity is important for language, mathematics, planning, analogy, and other domains in which relational structure matters more than particular surface features.

Interpretability is one of the major strengths of symbolic cognitive models. Because knowledge and reasoning steps are represented explicitly, researchers can often inspect which facts were retrieved, which rules were selected, and how intermediate conclusions were produced. This makes symbolic systems useful for studying cognitive mechanisms and for applications where explanations, verification, traceability, or explicit constraints are important.

However, symbolic systems face important limitations. Constructing explicit knowledge bases and rules can require substantial human effort, and manually specified representations may become difficult to maintain as environments grow complex. Real-world perception also produces noisy, continuous, high-dimensional information that does not naturally arrive as clean symbols. Transforming raw sensory data into reliable symbolic structures therefore presents a major challenge.

The symbol grounding problem highlights this limitation. Symbols manipulated internally by a cognitive system must ultimately acquire meaning through relationships with perception, action, experience, or other grounded processes. Merely defining one symbol through additional symbols can create an endless network of formal relationships without explaining how those representations connect to the external world.

Learning presents another challenge for traditional symbolic approaches. Human cognition can acquire categories, patterns, motor skills, and perceptual representations from large amounts of experience without receiving explicit rules for every situation. Classical symbolic models are less naturally suited to this form of statistical learning than modern connectionist systems, which can automatically learn distributed representations from examples.

Connectionist models take a substantially different approach by representing knowledge through patterns of activation and learned parameters distributed across neural networks. They are particularly effective for perception, pattern recognition, language modeling, and learning from high-dimensional data. However, their internal representations can be less directly interpretable, and explicit multi-step symbolic manipulation may be difficult to guarantee.

These complementary strengths have motivated hybrid cognitive models that combine symbolic and subsymbolic processing. Neural components can transform sensory observations into learned representations, while symbolic components can manipulate structured concepts, goals, rules, and constraints. The objective is not necessarily to replace one paradigm with another but to allow each representation type to operate where its computational characteristics are most useful.

CLARION illustrates this principle through explicit and implicit representational levels, while ACT-R combines explicit symbolic structures with quantitative activation and learning mechanisms. Other cognitive architectures similarly attempt to integrate structured reasoning with adaptive processing. Such systems demonstrate that the boundary between symbolic and subsymbolic cognition can be treated as an architectural interface rather than an absolute division.

Modern language models have renewed interest in the relationship between distributed representations and symbolic reasoning. Neural models can produce behavior resembling rule application, planning, abstraction, and compositional reasoning without relying exclusively on traditional symbolic representations. Nevertheless, reliable reasoning, constraint satisfaction, verification, and persistent structured knowledge remain areas where explicit symbolic mechanisms can provide important advantages.

Agentic AI provides a natural setting for combining these approaches. An autonomous agent may use neural models to interpret language and perception while maintaining explicit representations of goals, plans, constraints, tool states, and task progress. Symbolic structures can organize long-horizon activity, while learned models provide flexible interpretation and prediction. Their interaction can support more coherent and controllable behavior.

Symbolic cognition is also relevant to world models. A purely continuous latent world model can efficiently encode complex sensory states, but an agent may additionally benefit from explicit representations of objects, agents, relationships, causal rules, goals, and constraints. Combining latent dynamics with structured symbolic state can support both prediction and higher-level reasoning about how the environment may change.

For Physical AI, this hybrid organization is particularly useful because robots must connect continuous sensor information with discrete tasks and decisions. Neural perception can identify objects, terrain, people, motion, and environmental conditions, while symbolic representations can encode mission goals, safety rules, spatial relationships, task sequences, and operational constraints. Planning can then operate over structures grounded in physical observations.

A robot performing a manipulation task, for example, may perceive objects through neural vision while representing relationships such as object identity, location, graspability, destination, and task order symbolically. A planner can reason over these relationships to determine an action sequence, while learned control policies execute physical movements. Sensor feedback then updates both continuous state estimates and symbolic task representations.

Symbolic cognitive models therefore remain important even as artificial intelligence becomes increasingly neural and data-driven. Their greatest contribution is the explicit representation of structure: concepts can be named, relationships can be preserved, rules can be applied, goals can be maintained, and reasoning paths can be inspected. These properties complement rather than necessarily compete with the strengths of learned distributed representations.

Ultimately, symbolic cognitive models describe cognition as structured manipulation of meaningful representations. Symbols provide explicit knowledge, rules transform cognitive states, memory supplies relevant information, search explores possibilities, heuristics guide problem solving, and planning connects reasoning with action. Combined with modern neural learning and grounded world models, these principles remain highly relevant to cognitive architectures, agentic AI, and embodied Physical AI.

기호적 인지 모델(Symbolic Cognitive Models)은 명시적 기호(Explicit Symbols), 구조화된 지식(Structured Knowledge), 그리고 정의된 규칙에 따라 이러한 표상을 조작하는 연산을 통해 지능(Intelligence)을 표현합니다. 하나의 기호(Symbol)는 객체, 개념, 사건, 관계, 목표 또는 세계의 상태를 나타낼 수 있습니다. 인지는 기호적 구조(Symbolic Structures) 사이의 변환 과정으로 모델링되며, 이를 통해 추론 과정(Reasoning Processes)을 명시적이고 해석 가능한 계산 형태로 설명할 수 있습니다.

기호적 접근(Symbolic Approach)은 지능적 행동(Intelligent Behavior)이 기호 표현(Symbolic Expressions)을 생성하고, 수정하고, 결합하고, 해석할 수 있는 시스템에서 나타날 수 있다고 주장하는 물리적 기호 시스템 가설(Physical Symbol System Hypothesis)과 밀접하게 관련되어 있습니다. 이 관점에서 인지는 단순한 수치 계산에만 의존하는 것이 아니라 구성 요소 사이에 기능적 관계를 가진 구조화된 표상에 의존합니다. 따라서 추론은 이러한 표상을 체계적으로 조작하는 과정이 됩니다.

따라서 지식 표현(Knowledge Representation)은 기호적 인지 모델링의 핵심적인 요소입니다. 사실은 명제(Propositions)로 인코딩될 수 있고, 개념은 범주(Categories)로 조직될 수 있으며, 관계는 개체(Entities)를 서로 연결하고, 규칙은 하나의 상태가 다른 상태를 어떻게 함의하는지를 설명할 수 있습니다. 구조화된 표상을 통해 인지 시스템은 객체, 속성, 행동, 원인, 목표, 제약 조건을 구분하면서 직접 검사하고 조작할 수 있는 관계를 유지할 수 있습니다.

생성 규칙(Production Rules)은 절차적 지식(Procedural Knowledge)을 표현하는 일반적인 메커니즘입니다. 하나의 생성 규칙은 일반적으로 해당 규칙을 언제 적용할 수 있는지를 설명하는 조건(Conditions)과 이러한 조건이 충족되었을 때 무엇을 수행해야 하는지를 지정하는 행동(Actions)을 포함합니다. 인지 처리는 현재의 기호적 상태를 이용 가능한 규칙과 비교하고, 적절한 생성 규칙을 선택하고 실행한 다음, 또 다른 처리 주기가 시작되기 전에 내부 상태를 업데이트하는 방식으로 진행될 수 있습니다.

규칙 기반 처리(Rule-based Processing)는 기술(Skills), 전략(Strategies), 의사결정 절차(Decision Procedures)를 표현하기 위한 자연스러운 메커니즘을 제공합니다. 시스템은 특정 조건이 발생했을 때 특정 행동을 선택하거나 문제가 특정 상태에 도달했을 때 변환을 적용하는 것과 같은 지식을 인코딩할 수 있습니다. 비교적 단순한 여러 규칙이 연속적으로 실행되면서 현재의 표상을 원하는 목표 방향으로 점진적으로 변화시키고, 이를 통해 복잡한 행동이 나타날 수 있습니다.

기호적 모델은 흔히 선언적 지식(Declarative Knowledge)과 절차적 지식(Procedural Knowledge)을 구분합니다. 선언적 지식은 사실, 개념, 관계, 사건을 포함하여 시스템이 무엇을 알고 있는지를 설명합니다. 절차적 지식은 연산을 어떻게 수행해야 하는지를 설명합니다. 이러한 구분을 유지하면 인지 아키텍처(Cognitive Architectures)는 정보 검색과 절차 적용 사이의 상호작용을 모델링할 수 있으며, 이러한 조직은 ACT-R과 SOAR 같은 아키텍처에서도 확인할 수 있습니다.

작업 기억(Working Memory)은 현재의 인지 상황을 일시적으로 나타내는 기호적 표상을 제공합니다. 여기에는 활성화된 목표(Active Goals), 지각된 객체(Perceived Objects), 중간 결론(Intermediate Conclusions), 과제 제약 조건(Task Constraints), 검색된 지식이 포함될 수 있습니다. 규칙은 이러한 정보를 검사하여 현재 어떤 연산이 관련되어 있는지를 결정합니다. 처리가 계속됨에 따라 작업 기억이 변화하고, 이러한 변화는 이후의 추론과 행동을 안내하는 지속적으로 변화하는 문맥을 제공합니다.

장기 기억(Long-term Memory)은 필요할 때 검색할 수 있는 보다 지속적인 기호적 지식을 저장합니다. 추론 과정은 정보가 부족하다는 것을 인식하고 관련된 사실이나 규칙을 검색하여 현재 활성화된 문제 표상에 통합할 수 있습니다. 따라서 기억 검색(Memory Retrieval)은 모든 정보를 지속적으로 활성 상태로 유지할 필요 없이 현재의 인지 상태와 이전에 습득한 지식을 연결함으로써 추론을 지원합니다.

탐색(Search)은 기호적 인지의 또 다른 중요한 원리입니다. 많은 인지 과제는 가능한 상태와 연산으로 구성된 문제 공간(Problem Space)을 이동하는 과정으로 표현할 수 있습니다. 시스템은 초기 상태(Initial State)에서 시작하여 이용 가능한 연산자(Operators)를 적용하고, 그 결과로 생성된 상태를 평가하며, 목표를 향하는 경로를 탐색합니다. 따라서 문제 해결(Problem Solving)은 명시적으로 표현된 가능성에 대한 구조화된 탐색 과정이 됩니다.

문제 공간 관점(Problem-space Perspective)은 고전적 인공지능(Classical Artificial Intelligence)과 인지심리학(Cognitive Psychology)에서 특히 중요하게 다루어졌습니다. 체스, 퍼즐, 정리 증명(Theorem Proving), 계획, 논리 문제는 모두 상태, 연산자, 목표, 제약 조건의 관점에서 설명할 수 있습니다. 서로 다른 탐색 전략(Search Strategies)은 어떤 가능성을 먼저 검토할지를 결정하며, 이를 통해 기호적 모델은 지식과 휴리스틱(Heuristics)이 방대한 잠재적 해결 공간을 어떻게 축소하는지를 설명할 수 있습니다.

휴리스틱(Heuristics)은 완전 탐색(Exhaustive Search)이 계산적으로 불가능할 때 실용적인 지침을 제공합니다. 모든 가능한 상태를 탐색하는 대신 기호적 시스템은 어떤 대안이 더 유망한지를 추정하는 규칙을 적용할 수 있습니다. 인간의 문제 해결 역시 구조화된 전략과 도메인 지식(Domain Knowledge)에 의존하는 것으로 보입니다. 기호적 인지 모델은 이러한 휴리스틱을 명시적으로 표현할 수 있으므로 추론에 미치는 영향을 비교적 쉽게 분석할 수 있습니다.

논리(Logic)는 기호적 추론(Symbolic Reasoning)의 또 다른 기반을 제공합니다. 명제는 사실을 표현할 수 있고, 술어(Predicates)는 관계를 나타낼 수 있으며, 추론 규칙(Inference Rules)은 기존 지식에서 새로운 결론을 도출할 수 있습니다. 연역적 추론(Deductive Reasoning)은 논리적 타당성(Logical Validity)을 유지할 수 있으며, 다른 기호적 프레임워크는 불확실 추론(Uncertain Reasoning), 취소 가능 추론(Defeasible Reasoning), 귀추 추론(Abductive Reasoning)을 지원할 수 있습니다. 명시적 표상을 사용하면 어떤 전제와 연산이 특정 결론을 생성했는지 추적할 수 있습니다.

계획(Planning)은 기호적 추론을 미래의 행동으로 확장합니다. 목표를 명시적으로 표현할 수 있고, 가능한 행동은 전제 조건(Preconditions)과 효과(Effects)를 통해 설명할 수 있으며, 계획기는 초기 상태를 원하는 상태로 변환하는 연산의 시퀀스를 탐색할 수 있습니다. 동일한 기호적 구조를 사용하여 지식과 가능한 행동을 모두 표현할 수 있기 때문에 이러한 프레임워크는 추상적 추론과 목표 지향적 행동(Goal-directed Behavior)을 강력하게 연결합니다.

기호적 모델은 과제가 구성성(Compositionality)을 요구할 때 특히 강점을 가집니다. 복잡한 표상은 구성 요소 사이의 관계를 유지하면서 더 단순한 구성 요소를 조합하여 생성할 수 있습니다. 객체, 행동, 위치, 속성에 대한 기호를 이해하는 시스템은 모든 조합을 독립적으로 학습하지 않고도 새로운 구성으로 이들을 결합할 수 있습니다. 이는 구조적으로 관련된 문제 전반에 걸친 체계적 추론(Systematic Reasoning)과 일반화(Generalization)를 지원합니다.

구성적 표상(Compositional Representation)은 추상적인 관계를 서로 다른 개체에 적용할 수 있도록 하는 변수 바인딩(Variable Binding)도 지원합니다. 하나의 규칙은 특정 객체가 아니라 변수 사이의 관계를 설명할 수 있으므로 동일한 추론 구조를 다양한 상황에 적용할 수 있습니다. 이러한 능력은 표면적인 개별 특징보다 관계적 구조(Relational Structure)가 중요한 언어, 수학, 계획, 유추(Analogy), 기타 여러 영역에서 중요합니다.

해석 가능성(Interpretability)은 기호적 인지 모델의 주요 강점 가운데 하나입니다. 지식과 추론 단계가 명시적으로 표현되기 때문에 연구자는 어떤 사실이 검색되었는지, 어떤 규칙이 선택되었는지, 중간 결론이 어떻게 생성되었는지를 확인할 수 있습니다. 따라서 기호적 시스템은 인지 메커니즘을 연구하거나 설명(Explanation), 검증(Verification), 추적 가능성(Traceability), 명시적인 제약 조건이 중요한 응용 분야에서 유용합니다.

그러나 기호적 시스템에는 중요한 한계도 존재합니다. 명시적인 지식 베이스(Knowledge Bases)와 규칙을 구축하려면 상당한 인간의 노력이 필요할 수 있으며, 환경이 복잡해지면 수작업으로 지정된 표상을 유지하기 어려워질 수 있습니다. 실제 세계의 지각은 또한 깔끔한 기호의 형태가 아니라 잡음이 많고 연속적이며 고차원적인 정보(High-dimensional Information)를 생성합니다. 따라서 원시 감각 데이터를 신뢰할 수 있는 기호적 구조로 변환하는 것은 중요한 문제입니다.

기호 접지 문제(Symbol Grounding Problem)는 이러한 한계를 강조합니다. 인지 시스템 내부에서 조작되는 기호는 궁극적으로 지각, 행동, 경험 또는 다른 접지된 과정(Grounded Processes)과의 관계를 통해 의미를 획득해야 합니다. 하나의 기호를 단순히 또 다른 기호를 통해 정의하는 방식은 이러한 표상이 외부 세계와 어떻게 연결되는지를 설명하지 못한 채 형식적인 관계만 끝없이 이어지는 네트워크를 생성할 수 있습니다.

학습(Learning)은 전통적인 기호적 접근에서 또 다른 어려움을 제기합니다. 인간의 인지는 모든 상황에 대한 명시적 규칙을 제공받지 않고도 대량의 경험으로부터 범주, 패턴, 운동 기술(Motor Skills), 지각 표상을 습득할 수 있습니다. 고전적인 기호적 모델은 사례로부터 분산 표상(Distributed Representations)을 자동으로 학습할 수 있는 현대의 연결주의 시스템(Connectionist Systems)보다 이러한 형태의 통계적 학습(Statistical Learning)에 자연스럽게 적합하지 않습니다.

연결주의 모델(Connectionist Models)은 신경망 전체에 분산된 활성화 패턴(Patterns of Activation)과 학습된 파라미터를 통해 지식을 표현함으로써 상당히 다른 접근 방식을 사용합니다. 이러한 모델은 지각, 패턴 인식(Pattern Recognition), 언어 모델링(Language Modeling), 고차원 데이터 학습에서 특히 효과적입니다. 그러나 내부 표상을 직접 해석하기 어려울 수 있으며, 명시적인 다단계 기호 조작(Multi-step Symbolic Manipulation)을 보장하기도 어려울 수 있습니다.

이러한 상호보완적인 강점은 기호적 처리(Symbolic Processing)와 하위기호적 처리(Subsymbolic Processing)를 결합하는 하이브리드 인지 모델(Hybrid Cognitive Models)의 발전을 촉진했습니다. 신경망 구성 요소는 감각 관찰을 학습된 표상으로 변환하고, 기호적 구성 요소는 구조화된 개념, 목표, 규칙, 제약 조건을 조작할 수 있습니다. 목표는 반드시 하나의 패러다임을 다른 패러다임으로 대체하는 것이 아니라 각각의 표상 유형을 해당 계산 특성이 가장 유용한 영역에서 활용하는 것입니다.

CLARION은 명시적 표상 수준과 암묵적 표상 수준(Implicit Representational Levels)을 통해 이러한 원리를 보여주며, ACT-R은 명시적인 기호 구조와 정량적인 활성화(Quantitative Activation) 및 학습 메커니즘을 결합합니다. 다른 인지 아키텍처 역시 구조화된 추론과 적응적 처리(Adaptive Processing)를 통합하려고 시도합니다. 이러한 시스템은 기호적 인지와 하위기호적 인지 사이의 경계를 절대적인 구분이 아니라 아키텍처적 인터페이스(Architectural Interface)로 다룰 수 있음을 보여줍니다.

현대의 언어 모델(Language Models)은 분산 표상과 기호적 추론 사이의 관계에 대한 관심을 다시 높였습니다. 신경망 모델은 전통적인 기호 표상에만 의존하지 않고도 규칙 적용, 계획, 추상화(Abstraction), 구성적 추론(Compositional Reasoning)과 유사한 행동을 생성할 수 있습니다. 그러나 신뢰할 수 있는 추론(Reliable Reasoning), 제약 조건 만족(Constraint Satisfaction), 검증, 지속적인 구조화된 지식(Persistent Structured Knowledge)은 여전히 명시적인 기호 메커니즘이 중요한 장점을 제공할 수 있는 영역입니다.

에이전트형 인공지능(Agentic AI)은 이러한 접근 방식을 결합하기에 자연스러운 환경을 제공합니다. 자율 에이전트(Autonomous Agent)는 신경망 모델을 사용하여 언어와 지각 정보를 해석하면서 목표, 계획, 제약 조건, 도구 상태(Tool States), 과제 진행 상태(Task Progress)를 명시적인 표상으로 유지할 수 있습니다. 기호적 구조는 장기적인 활동(Long-horizon Activity)을 조직하고, 학습된 모델은 유연한 해석과 예측을 제공할 수 있습니다. 이들의 상호작용은 보다 일관되고 제어 가능한 행동을 지원할 수 있습니다.

기호적 인지는 월드 모델(World Models)과도 관련이 있습니다. 순수하게 연속적인 잠재 월드 모델(Latent World Model)은 복잡한 감각 상태를 효율적으로 인코딩할 수 있지만, 에이전트는 객체, 다른 에이전트, 관계, 인과 규칙(Causal Rules), 목표, 제약 조건에 대한 명시적인 표상을 추가로 활용할 수 있습니다. 잠재 동역학(Latent Dynamics)과 구조화된 기호 상태(Symbolic State)를 결합하면 환경이 어떻게 변화할지에 대한 예측과 상위 수준 추론을 모두 지원할 수 있습니다.

피지컬 인공지능(Physical AI)에서는 로봇이 연속적인 센서 정보를 이산적인 과제 및 의사결정과 연결해야 하기 때문에 이러한 하이브리드 조직이 특히 유용합니다. 신경망 기반 지각(Neural Perception)은 객체, 지형(Terrain), 사람, 움직임, 환경 조건을 식별할 수 있으며, 기호적 표상은 임무 목표(Mission Goals), 안전 규칙(Safety Rules), 공간 관계(Spatial Relationships), 과제 시퀀스(Task Sequences), 운영 제약 조건(Operational Constraints)을 인코딩할 수 있습니다. 이후 계획 과정은 물리적 관찰에 접지된 구조를 기반으로 작동할 수 있습니다.

예를 들어 조작 과제(Manipulation Task)를 수행하는 로봇은 신경망 기반 비전(Neural Vision)을 통해 객체를 지각하면서 객체 정체성(Object Identity), 위치(Location), 파지 가능성(Graspability), 목적지(Destination), 작업 순서(Task Order)와 같은 관계를 기호적으로 표현할 수 있습니다. 계획기는 이러한 관계를 기반으로 행동 시퀀스를 결정하고, 학습된 제어 정책(Learned Control Policies)은 실제 물리적 움직임을 실행할 수 있습니다. 이후 센서 피드백은 연속적인 상태 추정과 기호적 과제 표상을 모두 업데이트합니다.

따라서 인공지능이 점점 더 신경망 기반이고 데이터 주도적(Data-driven)으로 발전하고 있음에도 기호적 인지 모델은 여전히 중요합니다. 가장 중요한 기여는 구조(Structure)를 명시적으로 표현할 수 있다는 점입니다. 개념에는 이름을 부여할 수 있고, 관계를 유지할 수 있으며, 규칙을 적용하고, 목표를 유지하며, 추론 경로(Reasoning Paths)를 검사할 수 있습니다. 이러한 특성은 학습된 분산 표상의 강점과 경쟁하기보다는 서로 보완할 수 있습니다.

궁극적으로 기호적 인지 모델(Symbolic Cognitive Models)은 인지를 의미 있는 표상(Meaningful Representations)의 구조화된 조작으로 설명합니다. 기호는 명시적인 지식을 제공하고, 규칙은 인지 상태를 변환하며, 기억은 관련 정보를 제공하고, 탐색은 가능성을 조사하며, 휴리스틱은 문제 해결을 안내하고, 계획은 추론을 행동과 연결합니다. 이러한 원리를 현대의 신경망 학습(Neural Learning) 및 접지된 월드 모델(Grounded World Models)과 결합하면 인지 아키텍처(Cognitive Architectures), 에이전트형 인공지능(Agentic AI), 체화된 피지컬 인공지능(Embodied Physical AI)에 여전히 높은 관련성을 가질 수 있습니다.

##  

## 06.08 Neural Cognitive Models [w/Code]

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

Neural cognitive models explain cognition through networks of interconnected processing units whose behavior emerges from patterns of activation and learned connection strengths. Instead of representing knowledge primarily through explicit symbols and hand-designed rules, these models encode information in distributed numerical representations. Cognitive functions emerge from interactions among many simple computational elements operating collectively.

The approach is strongly influenced by biological neural systems, where cognition results from coordinated activity across populations of neurons rather than from a single central processor. Artificial neural models simplify biological mechanisms substantially, but they preserve the principle of distributed computation. Perception, memory, learning, categorization, prediction, and decision making can therefore emerge from patterns distributed across interconnected processing structures.

A fundamental concept is the artificial neuron or processing unit. Each unit receives signals from other units, combines them according to connection weights, applies a transformation, and produces an output. Individually these operations are simple, but large networks can implement highly complex mappings. Intelligence emerges from the collective organization of many units rather than from explicit instructions stored within any individual component.

Connection weights determine how strongly activity in one unit influences another. Learning modifies these weights so that the network gradually develops useful internal representations. Rather than manually specifying every relationship, a neural model discovers statistical regularities from experience. Knowledge is consequently embedded within the distributed configuration of parameters and activation patterns that develops during training.

Distributed representation is one of the defining characteristics of neural cognitive models. A concept is usually not represented by one dedicated unit but by a pattern of activity across many dimensions. Individual units can participate in representing many different concepts. This organization allows neural systems to encode similarity, context, uncertainty, and overlapping properties within continuous representational spaces.

Learning allows these representations to adapt through experience. A model receives examples, produces outputs or predictions, measures discrepancies using an objective function, and adjusts its parameters to reduce future errors. Repeated optimization gradually reorganizes internal representations. Cognitive capabilities can therefore emerge from exposure to data instead of requiring researchers to explicitly encode every rule or category beforehand.

Error-driven learning provides an important mechanism for this adaptation. When a model\'s prediction differs from the desired or observed outcome, an error signal indicates how its behavior should change. Algorithms such as backpropagation distribute information about this error through the network and modify relevant parameters. Repeated corrections allow complex behaviors to emerge from large numbers of relatively small numerical adjustments.

Neural cognitive models are particularly effective for perception because sensory information is continuous, noisy, high-dimensional, and often ambiguous. Networks can learn useful features directly from images, sound, language, tactile signals, or multimodal observations. Hierarchical representations can progressively transform raw input into increasingly abstract structures, allowing recognition to emerge without requiring manually constructed symbolic descriptions of every sensory pattern.

Hierarchical representation is therefore another important principle. Lower layers may encode local or relatively simple patterns, while higher layers combine them into increasingly abstract representations. In visual processing, for example, early representations may capture edges and textures while later representations encode shapes, objects, relationships, or scene-level information. Similar hierarchical organization can occur in language, audio, and sensor fusion.

Recurrent neural models extend processing across time by allowing previous internal states to influence current computation. This enables a system to represent temporal context and sequential dependencies. Recurrent neural networks, gated architectures, and related mechanisms have been used to model language, memory, motor sequences, prediction, and decision making where current cognition depends on information accumulated from previous moments.

Attention mechanisms provide another way to dynamically control information processing. Rather than treating every representation as equally relevant, a model can assign different weights to different inputs or internal states according to the current context. Attention allows information from distant positions or modalities to interact selectively and has become a central mechanism in modern neural architectures, particularly Transformer-based models.

Transformers significantly expanded the capabilities of neural cognitive modeling by enabling large-scale learning of relationships across sequences. Self-attention allows each representation to incorporate information from other relevant representations. When trained on sufficiently large datasets, Transformer models can acquire rich statistical structures supporting language understanding, generation, abstraction, contextual interpretation, and forms of multi-step reasoning.

Memory in neural cognitive models can take several forms. Information may be stored implicitly in learned parameters, temporarily represented through activation states, or maintained through explicit external memory mechanisms. Parameter memory provides accumulated statistical knowledge, while contextual or working representations support immediate tasks. More sophisticated architectures can add episodic retrieval systems that preserve and recover information from specific previous experiences.

Associative memory is particularly compatible with neural computation. Partial or noisy input can activate representations corresponding to previously learned patterns. Instead of requiring exact symbolic keys, retrieval can occur according to similarity within representational space. This property helps explain pattern completion, recognition under uncertainty, and context-sensitive recall, all of which are important characteristics of biological cognition.

Neural models also provide a natural framework for probabilistic and uncertain cognition. Continuous activation values and learned probability distributions can represent multiple possible interpretations rather than requiring one fixed symbolic state. A system can estimate confidence, compare alternatives, and update predictions as new evidence arrives. This makes neural representations useful in environments where information is incomplete or ambiguous.

Representation learning reduces the need for manually engineered features. Earlier artificial intelligence systems often depended heavily on human-designed representations describing which properties of data were important. Deep neural networks can instead learn useful features jointly with the task itself. The resulting representations may capture structures that are difficult to specify explicitly but highly effective for prediction, recognition, or control.

A major strength of neural cognitive models is graceful generalization. Because related experiences can occupy nearby regions of a learned representational space, knowledge acquired from one example may transfer to similar examples. Neural systems can therefore respond meaningfully to inputs that were never encountered exactly during training. The quality of this generalization, however, depends strongly on training data, architecture, objectives, and distributional similarity.

Neural systems can also integrate multiple modalities within shared or aligned representational spaces. Vision, language, audio, proprioception, and other sensory streams can be encoded into representations that interact during inference. Multimodal learning allows a system to associate words with objects, actions with observations, and sensory events with semantic descriptions, providing an important foundation for grounded and embodied cognition.

Despite these strengths, neural cognitive models have important limitations. Knowledge is distributed across many parameters, making individual reasoning steps difficult to inspect. A network may produce an effective answer without providing a reliable account of how the conclusion was derived. Interpretability, causal understanding, systematic reasoning, verification, and predictable behavior therefore remain significant research challenges.

Another limitation concerns systematic compositionality. Humans can often combine familiar concepts and rules in novel ways, even when a particular combination has never been observed. Neural systems can demonstrate substantial compositional behavior, but performance may degrade when tasks require combinations far outside the training distribution. Explicit symbolic representations can sometimes provide stronger guarantees for such systematic manipulation.

Neural models can also learn unintended correlations. If training data contains biases, shortcuts, or spurious relationships, optimization may exploit them because they help reduce training error. Successful performance therefore does not necessarily imply that the system learned the intended causal structure. Robust cognitive modeling requires careful evaluation of what representations actually encode and how they behave under changing conditions.

These limitations motivate neural-symbolic cognitive architectures. Neural systems can provide perception, representation learning, pattern recognition, prediction, and flexible language processing, while symbolic systems provide explicit concepts, rules, constraints, planning structures, and verifiable reasoning. Combining these capabilities can create systems that learn efficiently from complex data while preserving structured mechanisms for higher-level cognition.

Neural cognitive models are strongly related to predictive processing because networks can learn internal models that anticipate sensory states or future events. A model can predict upcoming observations, compare them with actual input, and use discrepancies for learning or state correction. Hierarchical neural representations can support prediction across different levels of abstraction and different temporal horizons.

They are similarly important for world models. Neural world models encode observations into latent states and learn how those states change through time and action. Instead of predicting every sensory detail directly, the system can model compact representations capturing task-relevant environmental dynamics. Such models allow an agent to predict possible futures and evaluate actions before physically executing them.

Agentic AI extends neural cognition from passive inference toward persistent interaction. Neural models can interpret observations, retrieve relevant information, generate candidate plans, predict outcomes, and evaluate possible actions. When combined with memory, goals, tools, feedback, and repeated reasoning cycles, they can participate in agents that continually update their internal state rather than responding independently to isolated prompts.

Neural cognitive models are particularly important to Physical AI because embodied systems must process enormous quantities of continuous sensor information in real time. Cameras, LiDAR, radar, microphones, tactile sensors, proprioception, and localization systems produce complex data that is difficult to represent manually. Neural networks can transform these signals into learned representations suitable for perception, prediction, planning, and control.

A robot can use neural perception to identify objects and terrain, multimodal fusion to construct an environmental representation, a world model to predict future states, and learned policies to generate candidate actions. Feedback from sensors can then update the internal state and modify subsequent decisions. Cognition becomes a continuous perception--representation--prediction--action loop grounded in physical interaction.

Different neural components can operate at different temporal scales. Fast networks may support motor control and obstacle avoidance, intermediate models may track objects and predict local motion, while larger models may contribute semantic interpretation and long-horizon planning. Coordinating these components enables embodied intelligence to connect millisecond-level control with goals extending over seconds, minutes, or longer periods.

Modern cognitive architectures may therefore benefit from treating neural processing not as a replacement for all previous cognitive models but as a powerful computational substrate. Neural representations provide learning, generalization, perception, prediction, and flexible association, while explicit memory, symbolic reasoning, global coordination, and structured planning can provide complementary capabilities needed for persistent intelligent behavior.

Ultimately, neural cognitive models describe cognition as adaptive computation emerging from distributed learned representations. Networks transform sensory information, learning changes connection strengths, hierarchical representations construct abstractions, attention selects relevant relationships, memory preserves experience, and prediction anticipates future states. Combined with symbolic reasoning and embodied interaction, these principles provide a major foundation for cognitive architectures, world models, agentic AI, and Physical AI.

신경 인지 모델(Neural Cognitive Models)은 상호 연결된 처리 단위(Processing Units)의 네트워크를 통해 인지를 설명하며, 이들의 행동은 활성화 패턴(Patterns of Activation)과 학습된 연결 강도(Learned Connection Strengths)로부터 나타납니다. 이러한 모델은 지식을 주로 명시적인 기호(Explicit Symbols)와 사람이 설계한 규칙으로 표현하는 대신 분산된 수치적 표상(Distributed Numerical Representations)에 정보를 인코딩합니다. 인지 기능은 다수의 단순한 계산 요소가 집단적으로 작동하면서 서로 상호작용하는 과정에서 나타납니다.

이 접근 방식은 인지가 하나의 중앙 처리기(Central Processor)가 아니라 여러 뉴런 집단(Populations of Neurons)에 걸친 조정된 활동에서 발생하는 생물학적 신경계(Biological Neural Systems)의 영향을 크게 받았습니다. 인공 신경 모델(Artificial Neural Models)은 생물학적 메커니즘을 상당히 단순화하지만 분산 계산(Distributed Computation)의 원리는 유지합니다. 따라서 지각(Perception), 기억(Memory), 학습(Learning), 범주화(Categorization), 예측(Prediction), 의사결정(Decision Making)은 상호 연결된 처리 구조 전체에 분산된 패턴으로부터 나타날 수 있습니다.

기본적인 개념 가운데 하나는 인공 뉴런(Artificial Neuron) 또는 처리 단위(Processing Unit)입니다. 각 단위는 다른 단위로부터 신호를 받아 연결 가중치(Connection Weights)에 따라 결합하고 변환을 적용한 후 출력을 생성합니다. 개별적으로 보면 이러한 연산은 단순하지만, 대규모 네트워크는 매우 복잡한 매핑(Mappings)을 구현할 수 있습니다. 지능은 특정 개별 구성 요소에 저장된 명시적인 명령이 아니라 수많은 단위의 집단적 조직으로부터 나타납니다.

연결 가중치(Connection Weights)는 한 단위의 활동이 다른 단위에 얼마나 강하게 영향을 주는지를 결정합니다. 학습은 이러한 가중치를 수정하여 네트워크가 점진적으로 유용한 내부 표상(Internal Representations)을 발달시키도록 합니다. 모든 관계를 수동으로 지정하는 대신 신경 모델은 경험으로부터 통계적 규칙성(Statistical Regularities)을 발견합니다. 따라서 지식은 훈련 과정에서 형성되는 분산된 파라미터 구성과 활성화 패턴 내부에 내재됩니다.

분산 표상(Distributed Representation)은 신경 인지 모델을 정의하는 핵심적인 특징 가운데 하나입니다. 하나의 개념은 일반적으로 특정한 하나의 전용 단위로 표현되는 것이 아니라 여러 차원에 걸친 활동 패턴으로 표현됩니다. 개별 단위는 서로 다른 여러 개념을 표현하는 데 동시에 참여할 수 있습니다. 이러한 조직을 통해 신경 시스템은 연속적인 표상 공간(Continuous Representational Spaces)에서 유사성, 문맥(Context), 불확실성(Uncertainty), 중첩되는 속성(Overlapping Properties)을 인코딩할 수 있습니다.

학습(Learning)은 이러한 표상이 경험을 통해 적응할 수 있도록 합니다. 모델은 사례를 입력받고, 출력이나 예측을 생성하며, 목적 함수(Objective Function)를 사용하여 차이를 측정하고, 미래의 오류를 줄이도록 파라미터를 조정합니다. 반복적인 최적화(Optimization)는 내부 표상을 점진적으로 재구성합니다. 따라서 연구자가 모든 규칙이나 범주를 사전에 명시적으로 인코딩하지 않아도 데이터에 노출되는 과정에서 인지 능력이 나타날 수 있습니다.

오류 주도 학습(Error-driven Learning)은 이러한 적응을 위한 중요한 메커니즘을 제공합니다. 모델의 예측이 원하는 결과나 관찰된 결과와 다를 경우 오류 신호(Error Signal)는 모델의 행동이 어떻게 변화해야 하는지를 나타냅니다. 역전파(Backpropagation)와 같은 알고리즘은 이러한 오류에 관한 정보를 네트워크 전체에 전달하고 관련 파라미터를 수정합니다. 반복적인 수정 과정을 통해 비교적 작은 수치적 조정이 대량으로 누적되면서 복잡한 행동이 나타날 수 있습니다.

신경 인지 모델은 감각 정보가 연속적이고, 잡음이 많고, 고차원적이며, 흔히 모호하기 때문에 지각(Perception)에 특히 효과적입니다. 네트워크는 이미지, 소리, 언어, 촉각 신호(Tactile Signals), 멀티모달 관찰(Multimodal Observations)로부터 유용한 특징을 직접 학습할 수 있습니다. 계층적 표상(Hierarchical Representations)은 원시 입력을 점차 추상적인 구조로 변환하여 모든 감각 패턴에 대해 사람이 직접 기호적 설명을 구성하지 않아도 인식(Recognition)이 나타날 수 있도록 합니다.

따라서 계층적 표상(Hierarchical Representation)은 또 하나의 중요한 원리입니다. 하위 계층은 국소적이거나 비교적 단순한 패턴을 인코딩할 수 있고, 상위 계층은 이러한 패턴을 결합하여 점점 더 추상적인 표상을 형성합니다. 예를 들어 시각 처리에서 초기 표상은 경계(Edges)와 질감(Textures)을 포착하고 이후의 표상은 형태, 객체, 관계 또는 장면 수준 정보(Scene-level Information)를 인코딩할 수 있습니다. 이와 유사한 계층적 조직은 언어, 오디오, 센서 융합(Sensor Fusion)에서도 나타날 수 있습니다.

순환 신경 모델(Recurrent Neural Models)은 이전의 내부 상태가 현재 계산에 영향을 주도록 하여 처리 과정을 시간적으로 확장합니다. 이를 통해 시스템은 시간적 문맥(Temporal Context)과 순차적 의존성(Sequential Dependencies)을 표현할 수 있습니다. 순환 신경망(Recurrent Neural Networks), 게이트 아키텍처(Gated Architectures), 관련 메커니즘은 현재의 인지가 이전 순간부터 축적된 정보에 의존하는 언어, 기억, 운동 시퀀스(Motor Sequences), 예측, 의사결정을 모델링하는 데 사용되어 왔습니다.

어텐션 메커니즘(Attention Mechanisms)은 정보 처리를 동적으로 제어하는 또 다른 방법을 제공합니다. 모든 표상을 동일하게 관련 있는 것으로 처리하는 대신 모델은 현재 문맥에 따라 서로 다른 입력이나 내부 상태에 서로 다른 가중치를 부여할 수 있습니다. 어텐션은 멀리 떨어진 위치 또는 서로 다른 모달리티(Modality)의 정보가 선택적으로 상호작용하도록 하며, 현대 신경 아키텍처, 특히 트랜스포머 기반 모델(Transformer-based Models)의 핵심적인 메커니즘이 되었습니다.

트랜스포머(Transformers)는 시퀀스 전체에 걸친 관계를 대규모로 학습할 수 있도록 함으로써 신경 인지 모델링의 능력을 크게 확장했습니다. 자기 어텐션(Self-attention)은 각각의 표상이 다른 관련 표상으로부터 정보를 통합할 수 있도록 합니다. 충분히 큰 데이터셋으로 학습할 경우 트랜스포머 모델은 언어 이해(Language Understanding), 생성(Generation), 추상화(Abstraction), 문맥적 해석(Contextual Interpretation), 다단계 추론(Multi-step Reasoning)의 일부 형태를 지원하는 풍부한 통계적 구조를 습득할 수 있습니다.

신경 인지 모델에서 기억(Memory)은 여러 형태로 존재할 수 있습니다. 정보는 학습된 파라미터에 암묵적으로 저장되거나, 활성화 상태를 통해 일시적으로 표현되거나, 명시적인 외부 기억 메커니즘(External Memory Mechanisms)을 통해 유지될 수 있습니다. 파라미터 기억(Parameter Memory)은 축적된 통계적 지식을 제공하고, 문맥적 또는 작업 표상(Contextual or Working Representations)은 즉각적인 과제를 지원합니다. 보다 정교한 아키텍처는 특정한 과거 경험의 정보를 보존하고 검색하는 일화 검색 시스템(Episodic Retrieval Systems)을 추가할 수 있습니다.

연상 기억(Associative Memory)은 신경 계산과 특히 잘 호환됩니다. 부분적이거나 잡음이 포함된 입력도 이전에 학습된 패턴에 해당하는 표상을 활성화할 수 있습니다. 정확한 기호적 키(Symbolic Keys)를 요구하는 대신 표상 공간에서의 유사성에 따라 검색이 이루어질 수 있습니다. 이러한 특성은 생물학적 인지의 중요한 특징인 패턴 완성(Pattern Completion), 불확실한 상황에서의 인식, 문맥 의존적 회상(Context-sensitive Recall)을 설명하는 데 도움을 줍니다.

신경 모델은 확률적이고 불확실한 인지(Probabilistic and Uncertain Cognition)를 표현하기 위한 자연스러운 프레임워크도 제공합니다. 연속적인 활성화 값과 학습된 확률 분포(Probability Distributions)는 하나의 고정된 기호 상태만을 요구하는 대신 여러 가능한 해석을 표현할 수 있습니다. 시스템은 신뢰도(Confidence)를 추정하고, 대안을 비교하며, 새로운 증거가 입력됨에 따라 예측을 업데이트할 수 있습니다. 따라서 신경 표상은 정보가 불완전하거나 모호한 환경에서 유용합니다.

표상 학습(Representation Learning)은 사람이 직접 특징을 설계해야 하는 필요성을 줄여 줍니다. 초기의 인공지능 시스템은 데이터의 어떤 속성이 중요한지를 설명하는 인간 설계 표상(Human-designed Representations)에 크게 의존하는 경우가 많았습니다. 반면 심층 신경망(Deep Neural Networks)은 과제 자체와 함께 유용한 특징을 학습할 수 있습니다. 그 결과 생성되는 표상은 명시적으로 정의하기 어려운 구조를 포착하면서도 예측, 인식 또는 제어에 매우 효과적일 수 있습니다.

신경 인지 모델의 주요 강점 가운데 하나는 유연한 일반화(Graceful Generalization)입니다. 서로 관련된 경험이 학습된 표상 공간에서 가까운 영역을 차지할 수 있기 때문에 하나의 사례에서 습득한 지식이 유사한 사례로 전이될 수 있습니다. 따라서 신경 시스템은 훈련 과정에서 정확히 경험하지 못한 입력에도 의미 있게 대응할 수 있습니다. 그러나 이러한 일반화의 품질은 훈련 데이터, 아키텍처, 목적 함수, 분포적 유사성(Distributional Similarity)에 크게 의존합니다.

신경 시스템은 여러 모달리티를 공유되거나 정렬된 표상 공간(Aligned Representational Spaces)으로 통합할 수도 있습니다. 시각(Vision), 언어(Language), 오디오(Audio), 고유수용감각(Proprioception), 기타 감각 스트림을 추론 과정에서 상호작용하는 표상으로 인코딩할 수 있습니다. 멀티모달 학습(Multimodal Learning)은 단어와 객체, 행동과 관찰, 감각 사건과 의미적 설명을 연결하여 접지된 인지(Grounded Cognition)와 체화된 인지(Embodied Cognition)를 위한 중요한 기반을 제공합니다.

이러한 강점에도 불구하고 신경 인지 모델에는 중요한 한계가 존재합니다. 지식이 많은 파라미터에 분산되어 있기 때문에 개별적인 추론 단계를 검사하기 어렵습니다. 네트워크는 효과적인 답을 생성하면서도 해당 결론이 어떻게 도출되었는지에 대한 신뢰할 수 있는 설명을 제공하지 못할 수 있습니다. 따라서 해석 가능성(Interpretability), 인과적 이해(Causal Understanding), 체계적 추론(Systematic Reasoning), 검증(Verification), 예측 가능한 행동(Predictable Behavior)은 여전히 중요한 연구 과제로 남아 있습니다.

또 다른 한계는 체계적 구성성(Systematic Compositionality)과 관련됩니다. 인간은 특정한 조합을 이전에 경험하지 않았더라도 익숙한 개념과 규칙을 새로운 방식으로 결합할 수 있습니다. 신경 시스템 역시 상당한 구성적 행동(Compositional Behavior)을 보여줄 수 있지만, 과제가 훈련 분포(Training Distribution)에서 크게 벗어난 조합을 요구하면 성능이 저하될 수 있습니다. 명시적인 기호적 표상(Symbolic Representations)은 이러한 체계적인 조작에 대해 더 강한 보장을 제공할 수 있습니다.

신경 모델은 의도하지 않은 상관관계(Unintended Correlations)를 학습할 수도 있습니다. 훈련 데이터에 편향(Biases), 지름길(Shortcuts), 허위 상관관계(Spurious Relationships)가 포함되어 있다면 최적화 과정은 훈련 오류를 줄이는 데 도움이 된다는 이유로 이를 활용할 수 있습니다. 따라서 높은 성능이 반드시 시스템이 의도된 인과 구조(Causal Structure)를 학습했다는 것을 의미하지는 않습니다. 견고한 인지 모델링을 위해서는 표상이 실제로 무엇을 인코딩하고 환경 조건 변화에 어떻게 행동하는지를 신중하게 평가해야 합니다.

이러한 한계는 신경-기호 인지 아키텍처(Neural-symbolic Cognitive Architectures)의 필요성을 촉진합니다. 신경 시스템은 지각, 표상 학습, 패턴 인식, 예측, 유연한 언어 처리를 제공하고, 기호적 시스템은 명시적인 개념, 규칙, 제약 조건, 계획 구조(Planning Structures), 검증 가능한 추론(Verifiable Reasoning)을 제공할 수 있습니다. 이러한 능력을 결합하면 복잡한 데이터로부터 효율적으로 학습하면서 상위 수준 인지를 위한 구조화된 메커니즘을 유지하는 시스템을 구축할 수 있습니다.

신경 인지 모델은 네트워크가 감각 상태나 미래 사건을 예상하는 내부 모델을 학습할 수 있다는 점에서 예측 처리(Predictive Processing)와 밀접하게 관련됩니다. 모델은 앞으로 나타날 관찰을 예측하고 이를 실제 입력과 비교하며, 그 차이를 학습이나 상태 수정에 사용할 수 있습니다. 계층적 신경 표상은 서로 다른 추상화 수준과 서로 다른 시간 범위(Temporal Horizons)에 걸친 예측을 지원할 수 있습니다.

신경 인지 모델은 월드 모델(World Models)에서도 중요합니다. 신경 월드 모델(Neural World Models)은 관찰을 잠재 상태(Latent States)로 인코딩하고 이러한 상태가 시간과 행동에 따라 어떻게 변화하는지를 학습합니다. 모든 감각적 세부 정보를 직접 예측하는 대신 시스템은 과제와 관련된 환경 동역학(Environmental Dynamics)을 포착하는 압축된 표상을 모델링할 수 있습니다. 이러한 모델을 통해 에이전트는 실제 행동을 수행하기 전에 가능한 미래를 예측하고 행동을 평가할 수 있습니다.

에이전트형 인공지능(Agentic AI)은 신경 인지를 수동적인 추론에서 지속적인 상호작용(Persistent Interaction)으로 확장합니다. 신경 모델은 관찰을 해석하고, 관련 정보를 검색하고, 후보 계획(Candidate Plans)을 생성하고, 결과를 예측하며, 가능한 행동을 평가할 수 있습니다. 기억, 목표, 도구(Tools), 피드백, 반복적인 추론 주기와 결합되면 개별 프롬프트에 독립적으로 반응하는 대신 내부 상태를 지속적으로 업데이트하는 에이전트에 참여할 수 있습니다.

신경 인지 모델은 체화된 시스템이 방대한 양의 연속적인 센서 정보를 실시간으로 처리해야 하기 때문에 피지컬 인공지능(Physical AI)에 특히 중요합니다. 카메라(Cameras), 라이다(LiDAR), 레이더(Radar), 마이크(Microphones), 촉각 센서(Tactile Sensors), 고유수용감각, 위치 추정 시스템(Localization Systems)은 수동으로 표현하기 어려운 복잡한 데이터를 생성합니다. 신경망은 이러한 신호를 지각, 예측, 계획, 제어에 적합한 학습된 표상으로 변환할 수 있습니다.

로봇은 신경 지각(Neural Perception)을 사용하여 객체와 지형을 식별하고, 멀티모달 융합(Multimodal Fusion)을 통해 환경 표상을 구성하고, 월드 모델을 통해 미래 상태를 예측하며, 학습된 정책(Learned Policies)을 사용하여 후보 행동을 생성할 수 있습니다. 이후 센서 피드백은 내부 상태를 업데이트하고 다음 의사결정을 수정할 수 있습니다. 따라서 인지는 물리적 상호작용에 접지된 지속적인 지각--표상--예측--행동(Perception--Representation--Prediction--Action) 루프가 됩니다.

서로 다른 신경 구성 요소는 서로 다른 시간 척도(Temporal Scales)에서 작동할 수 있습니다. 빠른 네트워크는 운동 제어(Motor Control)와 장애물 회피(Obstacle Avoidance)를 지원하고, 중간 수준 모델은 객체를 추적하고 국소적인 움직임을 예측하며, 더 큰 모델은 의미적 해석(Semantic Interpretation)과 장기 계획(Long-horizon Planning)에 기여할 수 있습니다. 이러한 구성 요소를 조정하면 체화된 지능은 밀리초 수준의 제어를 수초, 수분 또는 그 이상 지속되는 목표와 연결할 수 있습니다.

따라서 현대 인지 아키텍처(Modern Cognitive Architectures)는 신경 처리를 이전의 모든 인지 모델을 대체하는 것으로 보기보다 강력한 계산 기반(Computational Substrate)으로 활용함으로써 이점을 얻을 수 있습니다. 신경 표상은 학습, 일반화, 지각, 예측, 유연한 연상(Flexible Association)을 제공하며, 명시적 기억(Explicit Memory), 기호적 추론(Symbolic Reasoning), 전역적 조정(Global Coordination), 구조화된 계획(Structured Planning)은 지속적인 지능적 행동에 필요한 상호보완적인 능력을 제공할 수 있습니다.

궁극적으로 신경 인지 모델(Neural Cognitive Models)은 인지를 분산되고 학습된 표상(Distributed Learned Representations)으로부터 나타나는 적응적 계산(Adaptive Computation)로 설명합니다. 네트워크는 감각 정보를 변환하고, 학습은 연결 강도를 변화시키며, 계층적 표상은 추상화를 구성하고, 어텐션은 관련 관계를 선택하며, 기억은 경험을 보존하고, 예측은 미래 상태를 예상합니다. 이러한 원리를 기호적 추론(Symbolic Reasoning) 및 체화된 상호작용(Embodied Interaction)과 결합하면 인지 아키텍처, 월드 모델, 에이전트형 인공지능, 피지컬 인공지능을 위한 중요한 기반을 제공할 수 있습니다.

##  

## 06.09 Hybrid Cognitive Architectures [w/Code]

![](images/image10.png){width="7.268055555555556in" height="7.268055555555556in"}

Hybrid cognitive architectures combine multiple computational paradigms within a unified system so that different forms of cognition can be handled by mechanisms suited to their characteristics. Instead of assuming that intelligence should be explained entirely through symbolic reasoning or entirely through neural computation, hybrid architectures integrate complementary approaches for perception, memory, learning, reasoning, planning, decision making, and action.

The motivation for hybrid cognition arises from the diversity of cognitive functions required by intelligent agents. Perception must interpret noisy and high-dimensional sensory information, while reasoning often requires explicit relationships, constraints, and compositional structures. Learning must adapt from experience, whereas planning must maintain goals and evaluate future alternatives. A single representational mechanism may not efficiently support all these requirements.

Symbolic processing provides one major component of hybrid architectures. Symbols can explicitly represent objects, concepts, relationships, goals, rules, and task states. Structured representations make logical inference, constraint satisfaction, planning, and explanation comparatively transparent. Symbolic mechanisms are therefore particularly useful when cognition requires precise manipulation of relationships or explicit control over reasoning procedures.

Neural or subsymbolic processing provides a complementary capability. Neural networks learn distributed representations from data and are highly effective for perception, pattern recognition, prediction, language processing, and continuous control. Rather than requiring every rule to be manually specified, neural systems can discover statistical regularities through experience. This makes them suitable for complex environments where explicit symbolic modeling would be difficult.

A hybrid architecture attempts to connect these capabilities rather than simply placing them beside each other. Neural representations must influence symbolic reasoning, and symbolic goals or constraints must influence neural processing. The interface between representational levels is therefore a central architectural problem. Effective integration requires mechanisms for translating, aligning, grounding, or jointly maintaining information across different computational forms.

One common organization separates cognition into subsymbolic and symbolic levels. The subsymbolic level processes continuous signals, learned features, probabilities, activation strengths, and latent representations. The symbolic level represents discrete concepts, relationships, rules, and goals. Information can move between these levels so that perceptual evidence becomes structured knowledge and symbolic intentions influence lower-level processing and action.

Bottom-up information flow typically begins with sensory or learned representations. Neural perception may identify objects, events, locations, actions, or environmental properties from raw data. These representations can then be transformed into symbolic structures describing the current situation. Higher-level reasoning can operate on this structured state without processing every pixel, waveform, or sensor measurement directly.

Top-down information flow operates in the opposite direction. Goals, expectations, rules, and plans represented at a symbolic level can guide neural attention, perception, prediction, or control. A task requiring a particular object can increase processing priority for relevant visual features, while a planned action can constrain which predictions are important. Hybrid cognition therefore creates recurrent interaction between abstract intention and detailed sensory processing.

Memory can also be organized across multiple representational forms. Neural parameter memory may encode statistical regularities learned from large datasets, while episodic memory preserves particular experiences and symbolic memory stores explicit facts, rules, and relationships. Working memory can maintain currently relevant information from several sources. Coordinating these memory systems allows both flexible retrieval and structured reasoning over accumulated knowledge.

Learning within hybrid architectures can occur at several levels. Neural components can improve through gradient-based optimization, reinforcement learning, self-supervised learning, or predictive objectives. Symbolic components can acquire new rules, concepts, or problem-solving strategies. Information discovered by one level may eventually be transferred to another, enabling learned patterns to become explicit knowledge or symbolic guidance to shape subsequent learning.

CLARION provides an important example of hybrid cognitive organization by distinguishing explicit and implicit knowledge representations. Its architecture models interactions between processes that operate through accessible symbolic structures and processes represented through distributed subsymbolic mechanisms. This organization reflects the idea that human cognition often combines conscious rule-based reasoning with implicit skills and associations acquired through experience.

ACT-R also demonstrates hybrid characteristics despite its strong symbolic foundation. Declarative chunks and production rules provide explicit cognitive structures, while activation equations, retrieval probabilities, timing mechanisms, and learning processes introduce quantitative subsymbolic dynamics. Cognitive behavior emerges from interaction between structured symbolic representations and numerical mechanisms that influence which knowledge becomes available and when.

SOAR similarly combines symbolic problem solving with learning mechanisms that modify future behavior. Working memory represents the current situation, production rules propose and select operators, and learning can create new knowledge from previous problem-solving episodes. Modern extensions can connect such architectures with perceptual, probabilistic, and neural components, illustrating how classical cognitive systems can participate in broader hybrid designs.

Hybrid architectures are especially valuable for reasoning under uncertainty. Neural systems can estimate probabilities, confidence, similarities, or possible future states from incomplete evidence, while symbolic systems can enforce logical constraints and explicit rules. A decision process can therefore combine uncertain predictions with structured requirements, allowing an agent to reason flexibly without abandoning safety conditions or task constraints.

Planning provides another natural integration point. Symbolic planners can represent goals, preconditions, effects, and action sequences explicitly, while neural models can estimate costs, success probabilities, environmental dynamics, or likely consequences. Neural predictions can guide search toward promising plans, and symbolic constraints can prevent invalid actions. Planning becomes a cooperative process between learned prediction and structured search.

World models can serve as an important bridge between neural and symbolic cognition. A neural world model can encode complex sensory observations into compact latent states and predict how those states evolve. A symbolic layer can represent objects, agents, causal relationships, goals, and constraints derived from those states. Together they support both detailed prediction and abstract reasoning about possible futures.

Predictive processing also fits naturally within hybrid architectures. Neural components can continuously predict sensory or latent states and generate prediction errors, while higher-level symbolic models represent hypotheses, goals, or causal interpretations. Unexpected observations can trigger updates at several levels. This creates a hierarchical loop connecting perception, prediction, interpretation, reasoning, and adaptive action.

Attention and global workspace mechanisms can provide coordination across heterogeneous components. Specialized neural and symbolic processes may generate competing information, while an attention mechanism selects content that is currently important. A shared workspace can then distribute selected information to memory, reasoning, planning, language, and action systems. Hybrid cognition therefore requires not only multiple components but mechanisms for coordinating them.

Meta-cognition becomes particularly important when several reasoning mechanisms are available. An intelligent system must determine whether a problem should be handled through fast learned responses, explicit symbolic reasoning, additional information retrieval, simulation, or extended planning. Monitoring confidence, uncertainty, conflicts, and task difficulty can help select the appropriate cognitive strategy and allocate computational resources accordingly.

This organization has a strong relationship with dual-process theories. Fast processing can be supported by neural policies, learned associations, and automatic perception, while slower processing can involve symbolic reasoning, search, verification, and planning. However, hybrid architectures need not divide cognition into exactly two systems. Instead, they can contain multiple interacting mechanisms operating at different levels of abstraction and temporal scale.

Modern large language models provide powerful neural components for hybrid cognitive systems. They can interpret instructions, generate hypotheses, summarize information, produce candidate plans, and interact through natural language. However, persistent memory, exact constraint enforcement, reliable calculation, formal verification, and long-term task management may benefit from external structured components rather than relying entirely on neural parameter representations.

Agentic AI therefore provides a major application area for hybrid architectures. An agent can use neural models for perception and language, symbolic structures for goals and task states, databases or retrieval systems for memory, world models for prediction, planners for action sequencing, and external tools for specialized operations. A coordination mechanism can combine these capabilities into a persistent perception--reasoning--action loop.

Tool use further demonstrates the advantages of hybrid organization. A neural model may recognize that additional information or computation is required, while an explicit controller determines which tool can satisfy the requirement. Tool outputs can be converted into structured state and incorporated into subsequent reasoning. This separates flexible interpretation from deterministic operations that may require higher precision or external verification.

Hybrid architectures are particularly relevant to Physical AI because embodied agents operate simultaneously in continuous physical environments and discrete task structures. Sensor measurements, motor commands, trajectories, and dynamics are naturally continuous, while mission goals, safety rules, object relationships, task sequences, and operational constraints often benefit from explicit representations. A robot must connect these domains continuously.

A Physical AI system may use neural perception to interpret cameras, LiDAR, radar, audio, and proprioception. Sensor fusion can create a latent environmental representation, while symbolic structures identify objects, semantic relationships, goals, and constraints. A world model predicts possible future states, a planner evaluates alternatives, and learned control policies convert selected actions into continuous physical motion.

Safety provides a particularly important reason for hybrid design. Learned policies can adapt effectively to complex environments but may behave unpredictably outside familiar conditions. Explicit safety rules, constraint monitors, verification layers, and fallback controllers can supervise neural decisions. Hybrid systems can therefore combine adaptive intelligence with mechanisms designed to prevent actions that violate defined operational boundaries.

Temporal hierarchy is also important in embodied hybrid cognition. Low-level neural controllers may operate at millisecond timescales, perception and tracking at tens or hundreds of milliseconds, local planning over seconds, and symbolic task reasoning over minutes or longer. Coordinating these timescales allows immediate physical reactions to remain consistent with long-term goals and mission-level constraints.

The major challenge is architectural complexity. Combining multiple representations, memories, learning methods, reasoning systems, and control loops creates difficult interface problems. Information can become inconsistent across components, translation between representations can lose meaning, and different modules may produce conflicting recommendations. Effective hybrid systems therefore require carefully designed coordination, synchronization, arbitration, and state-management mechanisms.

Another challenge concerns learning across boundaries. A neural component may discover useful patterns that are difficult to express symbolically, while symbolic rules may be difficult to translate into differentiable learning objectives. Research in neural-symbolic learning, differentiable reasoning, program induction, structured latent representations, and grounded language attempts to reduce this gap and enable more integrated learning.

Despite these challenges, hybrid cognitive architectures offer a compelling direction for advanced artificial intelligence. Purely symbolic systems provide structure but struggle with complex perception and large-scale learning, while purely neural systems provide adaptability but may lack explicit reasoning guarantees and transparent control. Combining them allows an architecture to exploit different computational strengths according to the demands of each cognitive function.

Ultimately, hybrid cognitive architectures describe intelligence as coordinated interaction among multiple representational and computational systems. Neural processing supplies learning, perception, prediction, and flexible generalization; symbolic processing supplies structure, rules, goals, and explicit reasoning; memory preserves experience; world models anticipate futures; and coordination mechanisms connect these capabilities to planning and action. This integration provides a powerful foundation for cognitive architectures, agentic AI, world-model-based intelligence, and embodied Physical AI.

하이브리드 인지 아키텍처(Hybrid Cognitive Architectures)는 서로 다른 형태의 인지를 각각의 특성에 적합한 메커니즘으로 처리할 수 있도록 여러 계산 패러다임(Computational Paradigms)을 하나의 통합된 시스템 안에서 결합합니다. 지능(Intelligence)을 전적으로 기호적 추론(Symbolic Reasoning)이나 신경망 계산(Neural Computation)만으로 설명해야 한다고 가정하는 대신, 하이브리드 아키텍처는 지각(Perception), 기억(Memory), 학습(Learning), 추론(Reasoning), 계획(Planning), 의사결정(Decision Making), 행동(Action)을 위해 상호보완적인 접근 방식을 통합합니다.

하이브리드 인지(Hybrid Cognition)의 필요성은 지능형 에이전트(Intelligent Agents)에 요구되는 인지 기능의 다양성에서 비롯됩니다. 지각은 잡음이 많고 고차원적인 감각 정보를 해석해야 하는 반면, 추론은 명시적인 관계, 제약 조건(Constraints), 구성적 구조(Compositional Structures)를 요구하는 경우가 많습니다. 학습은 경험으로부터 적응해야 하고, 계획은 목표를 유지하면서 미래의 대안을 평가해야 합니다. 하나의 표상 메커니즘만으로 이러한 모든 요구사항을 효율적으로 지원하기는 어려울 수 있습니다.

기호적 처리(Symbolic Processing)는 하이브리드 아키텍처의 주요 구성 요소 가운데 하나입니다. 기호(Symbols)는 객체, 개념, 관계, 목표, 규칙, 과제 상태(Task States)를 명시적으로 표현할 수 있습니다. 구조화된 표상(Structured Representations)은 논리적 추론(Logical Inference), 제약 조건 만족(Constraint Satisfaction), 계획, 설명(Explanation)을 비교적 투명하게 만듭니다. 따라서 기호적 메커니즘은 인지가 관계를 정밀하게 조작하거나 추론 절차를 명시적으로 제어해야 하는 경우에 특히 유용합니다.

신경망 또는 하위기호적 처리(Neural or Subsymbolic Processing)는 상호보완적인 능력을 제공합니다. 신경망(Neural Networks)은 데이터로부터 분산 표상(Distributed Representations)을 학습하며 지각, 패턴 인식(Pattern Recognition), 예측(Prediction), 언어 처리(Language Processing), 연속 제어(Continuous Control)에 매우 효과적입니다. 모든 규칙을 사람이 직접 지정할 필요 없이 신경 시스템은 경험을 통해 통계적 규칙성(Statistical Regularities)을 발견할 수 있습니다. 따라서 명시적인 기호 모델링이 어려운 복잡한 환경에 적합합니다.

하이브리드 아키텍처는 이러한 능력을 단순히 나란히 배치하는 것이 아니라 서로 연결하려고 합니다. 신경 표상(Neural Representations)은 기호적 추론에 영향을 주어야 하며, 기호적 목표나 제약 조건은 신경 처리에 영향을 주어야 합니다. 따라서 표상 수준 사이의 인터페이스(Interface)는 핵심적인 아키텍처 문제입니다. 효과적인 통합을 위해서는 서로 다른 계산 형태 사이에서 정보를 변환하고, 정렬하고, 접지(Grounding)하거나 공동으로 유지하는 메커니즘이 필요합니다.

일반적인 구성 방식 가운데 하나는 인지를 하위기호 수준(Subsymbolic Level)과 기호 수준(Symbolic Level)으로 구분하는 것입니다. 하위기호 수준은 연속 신호, 학습된 특징, 확률, 활성화 강도(Activation Strengths), 잠재 표상(Latent Representations)을 처리합니다. 기호 수준은 이산적인 개념, 관계, 규칙, 목표를 표현합니다. 정보는 이러한 수준 사이를 이동하면서 지각적 증거가 구조화된 지식으로 변환되고, 기호적 의도(Symbolic Intentions)는 저수준 처리와 행동에 영향을 줄 수 있습니다.

상향식 정보 흐름(Bottom-up Information Flow)은 일반적으로 감각 또는 학습된 표상에서 시작됩니다. 신경 지각(Neural Perception)은 원시 데이터에서 객체, 사건, 위치, 행동, 환경 속성을 식별할 수 있습니다. 이후 이러한 표상은 현재 상황을 설명하는 기호적 구조로 변환될 수 있습니다. 상위 수준 추론은 모든 픽셀, 파형(Waveform), 센서 측정값을 직접 처리하지 않고 이러한 구조화된 상태를 기반으로 작동할 수 있습니다.

하향식 정보 흐름(Top-down Information Flow)은 반대 방향으로 작동합니다. 기호 수준에서 표현된 목표, 기대, 규칙, 계획은 신경 어텐션(Neural Attention), 지각, 예측, 제어를 안내할 수 있습니다. 특정 객체가 필요한 과제는 관련 시각적 특징의 처리 우선순위를 높일 수 있으며, 계획된 행동은 어떤 예측이 중요한지를 제한할 수 있습니다. 따라서 하이브리드 인지는 추상적인 의도와 세부적인 감각 처리 사이에 반복적인 상호작용을 형성합니다.

기억(Memory) 역시 여러 형태의 표상으로 구성될 수 있습니다. 신경 파라미터 기억(Neural Parameter Memory)은 대규모 데이터셋에서 학습된 통계적 규칙성을 인코딩할 수 있고, 일화 기억(Episodic Memory)은 특정 경험을 보존하며, 기호 기억(Symbolic Memory)은 명시적인 사실, 규칙, 관계를 저장합니다. 작업 기억(Working Memory)은 여러 정보원에서 현재 관련성이 높은 정보를 유지할 수 있습니다. 이러한 기억 시스템을 조정하면 축적된 지식을 유연하게 검색하면서 구조화된 추론을 수행할 수 있습니다.

하이브리드 아키텍처의 학습은 여러 수준에서 발생할 수 있습니다. 신경 구성 요소는 경사 기반 최적화(Gradient-based Optimization), 강화학습(Reinforcement Learning), 자기지도학습(Self-supervised Learning), 예측 목적 함수(Predictive Objectives)를 통해 향상될 수 있습니다. 기호 구성 요소는 새로운 규칙, 개념, 문제 해결 전략을 습득할 수 있습니다. 한 수준에서 발견된 정보가 다른 수준으로 전달되면 학습된 패턴이 명시적인 지식으로 변환되거나 기호적 지침이 이후의 학습 방향에 영향을 줄 수 있습니다.

CLARION은 명시적 지식 표상(Explicit Knowledge Representations)과 암묵적 지식 표상(Implicit Knowledge Representations)을 구분함으로써 하이브리드 인지 조직의 중요한 사례를 제공합니다. 이 아키텍처는 접근 가능한 기호 구조를 통해 작동하는 과정과 분산된 하위기호 메커니즘으로 표현되는 과정 사이의 상호작용을 모델링합니다. 이러한 구성은 인간의 인지가 의식적인 규칙 기반 추론과 경험을 통해 습득된 암묵적인 기술 및 연상을 결합하는 경우가 많다는 생각을 반영합니다.

ACT-R 역시 강력한 기호적 기반을 가지고 있지만 하이브리드 특성을 보여줍니다. 선언적 청크(Declarative Chunks)와 생성 규칙(Production Rules)은 명시적인 인지 구조를 제공하고, 활성화 방정식(Activation Equations), 검색 확률(Retrieval Probabilities), 타이밍 메커니즘(Timing Mechanisms), 학습 과정은 정량적인 하위기호 동역학(Subsymbolic Dynamics)을 도입합니다. 인지 행동은 구조화된 기호 표상과 어떤 지식이 언제 이용 가능해지는지에 영향을 미치는 수치적 메커니즘 사이의 상호작용에서 나타납니다.

SOAR 역시 기호적 문제 해결(Symbolic Problem Solving)과 미래 행동을 변화시키는 학습 메커니즘을 결합합니다. 작업 기억은 현재 상황을 표현하고, 생성 규칙은 연산자(Operators)를 제안하고 선택하며, 학습은 이전의 문제 해결 경험으로부터 새로운 지식을 생성할 수 있습니다. 현대적인 확장에서는 이러한 아키텍처를 지각, 확률적 처리(Probabilistic Processing), 신경망 구성 요소와 연결할 수 있으며, 이는 고전적 인지 시스템이 더 광범위한 하이브리드 설계에 참여할 수 있음을 보여줍니다.

하이브리드 아키텍처는 불확실성하의 추론(Reasoning under Uncertainty)에 특히 유용합니다. 신경 시스템은 불완전한 증거로부터 확률, 신뢰도(Confidence), 유사성, 가능한 미래 상태를 추정할 수 있으며, 기호 시스템은 논리적 제약 조건과 명시적인 규칙을 강제할 수 있습니다. 따라서 의사결정 과정은 불확실한 예측과 구조화된 요구사항을 결합하여 안전 조건이나 과제 제약을 포기하지 않으면서 유연하게 추론할 수 있습니다.

계획(Planning)은 또 하나의 자연스러운 통합 지점을 제공합니다. 기호적 계획기(Symbolic Planners)는 목표, 전제 조건(Preconditions), 효과(Effects), 행동 시퀀스(Action Sequences)를 명시적으로 표현할 수 있으며, 신경 모델은 비용, 성공 확률, 환경 동역학(Environmental Dynamics), 예상 결과를 추정할 수 있습니다. 신경망 예측은 탐색(Search)을 유망한 계획 방향으로 안내하고, 기호적 제약은 유효하지 않은 행동을 방지할 수 있습니다. 따라서 계획은 학습된 예측과 구조화된 탐색 사이의 협력 과정이 됩니다.

월드 모델(World Models)은 신경 인지와 기호 인지를 연결하는 중요한 가교 역할을 할 수 있습니다. 신경 월드 모델(Neural World Model)은 복잡한 감각 관찰을 압축된 잠재 상태(Latent States)로 인코딩하고 이러한 상태가 어떻게 변화하는지를 예측할 수 있습니다. 기호 계층(Symbolic Layer)은 이러한 상태에서 도출된 객체, 에이전트, 인과 관계(Causal Relationships), 목표, 제약 조건을 표현할 수 있습니다. 이들을 결합하면 세부적인 예측과 가능한 미래에 관한 추상적인 추론을 모두 지원할 수 있습니다.

예측 처리(Predictive Processing) 역시 하이브리드 아키텍처에 자연스럽게 적용될 수 있습니다. 신경 구성 요소는 감각 상태나 잠재 상태를 지속적으로 예측하고 예측 오류(Prediction Errors)를 생성할 수 있으며, 상위 수준의 기호 모델은 가설, 목표, 인과적 해석(Causal Interpretations)을 표현합니다. 예상하지 못한 관찰은 여러 수준에서 업데이트를 유발할 수 있습니다. 이를 통해 지각, 예측, 해석, 추론, 적응적 행동(Adaptive Action)을 연결하는 계층적 루프(Hierarchical Loop)가 형성됩니다.

어텐션(Attention)과 전역 작업공간 메커니즘(Global Workspace Mechanisms)은 서로 이질적인 구성 요소들을 조정하는 역할을 할 수 있습니다. 전문화된 신경 및 기호 처리 과정은 서로 경쟁하는 정보를 생성할 수 있으며, 어텐션 메커니즘은 현재 중요한 내용을 선택합니다. 이후 공유 작업공간(Shared Workspace)은 선택된 정보를 기억, 추론, 계획, 언어, 행동 시스템으로 전달할 수 있습니다. 따라서 하이브리드 인지는 여러 구성 요소뿐만 아니라 이들을 조정하기 위한 메커니즘도 필요로 합니다.

여러 추론 메커니즘을 사용할 수 있는 경우 메타인지(Meta-cognition)는 특히 중요해집니다. 지능형 시스템은 문제가 빠르게 학습된 반응(Fast Learned Responses), 명시적인 기호적 추론, 추가 정보 검색, 시뮬레이션(Simulation), 확장된 계획 가운데 어떤 방식으로 처리되어야 하는지를 결정해야 합니다. 신뢰도, 불확실성, 충돌(Conflicts), 과제 난이도를 모니터링하면 적절한 인지 전략을 선택하고 계산 자원(Computational Resources)을 할당하는 데 도움을 줄 수 있습니다.

이러한 구성은 이중 처리 이론(Dual-process Theories)과 강한 연관성을 가집니다. 빠른 처리는 신경 정책(Neural Policies), 학습된 연상(Learned Associations), 자동적 지각(Automatic Perception)을 통해 지원할 수 있으며, 느린 처리는 기호적 추론, 탐색, 검증(Verification), 계획을 포함할 수 있습니다. 그러나 하이브리드 아키텍처가 반드시 인지를 정확히 두 개의 시스템으로 구분해야 하는 것은 아닙니다. 서로 다른 추상화 수준과 시간 척도(Temporal Scales)에서 작동하는 여러 상호작용 메커니즘을 포함할 수 있습니다.

현대의 대규모 언어 모델(Large Language Models)은 하이브리드 인지 시스템을 위한 강력한 신경 구성 요소를 제공합니다. 이러한 모델은 명령을 해석하고, 가설을 생성하고, 정보를 요약하고, 후보 계획을 생성하며, 자연어를 통해 상호작용할 수 있습니다. 그러나 지속적 기억(Persistent Memory), 정확한 제약 조건 적용, 신뢰할 수 있는 계산, 형식적 검증(Formal Verification), 장기적인 과제 관리(Long-term Task Management)는 신경 파라미터 표상에 전적으로 의존하기보다 외부의 구조화된 구성 요소를 활용함으로써 이점을 얻을 수 있습니다.

따라서 에이전트형 인공지능(Agentic AI)은 하이브리드 아키텍처의 주요 응용 분야를 제공합니다. 에이전트는 지각과 언어에 신경 모델을 사용하고, 목표와 과제 상태에 기호적 구조를 사용하며, 기억에는 데이터베이스나 검색 시스템(Retrieval Systems)을 활용하고, 예측에는 월드 모델을 사용하며, 행동 시퀀스에는 계획기를 사용할 수 있습니다. 조정 메커니즘(Coordination Mechanism)은 이러한 능력을 하나의 지속적인 지각--추론--행동(Perception--Reasoning--Action) 루프로 결합할 수 있습니다.

도구 사용(Tool Use)은 하이브리드 조직의 장점을 더욱 명확하게 보여줍니다. 신경 모델은 추가적인 정보나 계산이 필요하다는 것을 인식할 수 있으며, 명시적인 제어기(Explicit Controller)는 어떤 도구가 해당 요구사항을 충족할 수 있는지를 결정할 수 있습니다. 도구의 출력은 구조화된 상태로 변환되어 이후의 추론에 통합될 수 있습니다. 이를 통해 유연한 해석과 더 높은 정밀도 또는 외부 검증을 요구하는 결정론적 연산(Deterministic Operations)을 분리할 수 있습니다.

하이브리드 아키텍처는 체화된 에이전트(Embodied Agents)가 연속적인 물리 환경과 이산적인 과제 구조 안에서 동시에 작동하기 때문에 피지컬 인공지능(Physical AI)과 특히 관련성이 높습니다. 센서 측정값, 모터 명령(Motor Commands), 궤적(Trajectories), 동역학(Dynamics)은 본질적으로 연속적인 반면, 임무 목표(Mission Goals), 안전 규칙(Safety Rules), 객체 관계, 과제 시퀀스, 운영 제약 조건(Operational Constraints)은 명시적 표상으로 표현하는 것이 유리한 경우가 많습니다. 로봇은 이러한 영역을 지속적으로 연결해야 합니다.

피지컬 인공지능 시스템(Physical AI System)은 신경 지각(Neural Perception)을 사용하여 카메라, 라이다(LiDAR), 레이더(Radar), 오디오(Audio), 고유수용감각(Proprioception)을 해석할 수 있습니다. 센서 융합(Sensor Fusion)은 잠재 환경 표상(Latent Environmental Representation)을 생성하고, 기호 구조는 객체, 의미적 관계(Semantic Relationships), 목표, 제약 조건을 식별합니다. 월드 모델은 가능한 미래 상태를 예측하고, 계획기는 대안을 평가하며, 학습된 제어 정책(Learned Control Policies)은 선택된 행동을 연속적인 물리적 움직임으로 변환합니다.

안전(Safety)은 하이브리드 설계가 중요한 또 하나의 이유입니다. 학습된 정책은 복잡한 환경에 효과적으로 적응할 수 있지만 익숙하지 않은 조건에서는 예측하기 어려운 행동을 보일 수 있습니다. 명시적인 안전 규칙, 제약 조건 모니터(Constraint Monitors), 검증 계층(Verification Layers), 폴백 제어기(Fallback Controllers)는 신경망의 의사결정을 감독할 수 있습니다. 따라서 하이브리드 시스템은 적응적 지능과 정의된 운영 경계를 위반하는 행동을 방지하기 위한 메커니즘을 결합할 수 있습니다.

시간적 계층(Temporal Hierarchy) 역시 체화된 하이브리드 인지에서 중요합니다. 저수준 신경 제어기(Low-level Neural Controllers)는 밀리초 단위로 작동할 수 있고, 지각과 추적은 수십 또는 수백 밀리초 단위로 작동하며, 지역 계획(Local Planning)은 수초 단위로, 기호적 과제 추론(Symbolic Task Reasoning)은 수분 또는 그 이상의 시간 범위에서 작동할 수 있습니다. 이러한 시간 척도를 조정하면 즉각적인 물리적 반응을 장기 목표 및 임무 수준의 제약 조건과 일관되게 유지할 수 있습니다.

주요 과제는 아키텍처 복잡성(Architectural Complexity)입니다. 여러 표상, 기억, 학습 방법, 추론 시스템, 제어 루프(Control Loops)를 결합하면 어려운 인터페이스 문제가 발생합니다. 구성 요소 사이에서 정보가 불일치할 수 있고, 표상 사이의 변환 과정에서 의미가 손실될 수 있으며, 서로 다른 모듈이 충돌하는 권고를 생성할 수도 있습니다. 따라서 효과적인 하이브리드 시스템에는 신중하게 설계된 조정, 동기화(Synchronization), 중재(Arbitration), 상태 관리(State Management) 메커니즘이 필요합니다.

또 다른 과제는 서로 다른 경계 사이의 학습(Learning Across Boundaries)과 관련됩니다. 신경 구성 요소는 기호적으로 표현하기 어려운 유용한 패턴을 발견할 수 있으며, 반대로 기호 규칙은 미분 가능한 학습 목적 함수(Differentiable Learning Objectives)로 변환하기 어려울 수 있습니다. 신경-기호 학습(Neural-symbolic Learning), 미분 가능한 추론(Differentiable Reasoning), 프로그램 귀납(Program Induction), 구조화된 잠재 표상(Structured Latent Representations), 접지된 언어(Grounded Language)에 관한 연구는 이러한 격차를 줄이고 보다 통합적인 학습을 가능하게 하는 것을 목표로 합니다.

이러한 어려움에도 불구하고 하이브리드 인지 아키텍처는 고급 인공지능(Advanced Artificial Intelligence)을 위한 매우 중요한 발전 방향을 제공합니다. 순수한 기호 시스템은 구조를 제공하지만 복잡한 지각과 대규모 학습에 어려움을 겪으며, 순수한 신경 시스템은 적응성을 제공하지만 명시적인 추론 보장(Reasoning Guarantees)과 투명한 제어가 부족할 수 있습니다. 이들을 결합하면 각 인지 기능의 요구사항에 따라 서로 다른 계산적 강점을 활용할 수 있습니다.

궁극적으로 하이브리드 인지 아키텍처(Hybrid Cognitive Architectures)는 지능을 여러 표상 및 계산 시스템 사이의 조정된 상호작용(Coordinated Interaction)으로 설명합니다. 신경 처리(Neural Processing)는 학습, 지각, 예측, 유연한 일반화를 제공하고, 기호 처리(Symbolic Processing)는 구조, 규칙, 목표, 명시적 추론을 제공하며, 기억은 경험을 보존하고, 월드 모델은 미래를 예상하며, 조정 메커니즘은 이러한 능력을 계획과 행동으로 연결합니다. 이러한 통합은 인지 아키텍처(Cognitive Architectures), 에이전트형 인공지능(Agentic AI), 월드 모델 기반 지능(World-model-based Intelligence), 체화된 피지컬 인공지능(Embodied Physical AI)을 위한 강력한 기반을 제공합니다.

##  

## 06.10 Cognitive Agents [w/Code]

![](images/image11.png){width="7.268055555555556in" height="7.268055555555556in"}

Cognitive agents are autonomous systems designed to perceive environments, maintain internal representations, reason about situations, pursue goals, and select actions over time. Unlike simple reactive systems that map observations directly to responses, cognitive agents maintain information about previous events, current conditions, and possible futures. Their behavior emerges from continuous interaction among perception, memory, reasoning, learning, planning, and action.

The concept of a cognitive agent originates from attempts to model intelligence as an integrated process rather than as isolated algorithms. Human cognition does not perform perception, memory retrieval, reasoning, and action independently. These functions continually influence one another. Cognitive agents adopt the same principle by organizing specialized cognitive mechanisms into an architecture capable of maintaining coherent behavior across changing situations.

An agent can be described through the perception--cognition--action cycle. Sensors or information channels provide observations about the environment, cognitive mechanisms interpret those observations, and the agent selects actions that modify either the environment or its own information state. New observations then reflect the consequences of previous actions, creating a recurrent closed loop through which intelligent behavior develops over time.

Perception provides the interface between an agent and its environment. Raw sensory signals or digital observations must be transformed into representations useful for cognition. Neural perception systems may recognize objects, people, events, language, spatial relationships, or environmental conditions. The resulting information becomes part of the agent\'s internal state and provides evidence for subsequent reasoning, prediction, and decision making.

Internal state distinguishes cognitive agents from purely reactive mechanisms. The agent maintains information that is not directly available from the current observation, including previous events, inferred conditions, active goals, unresolved tasks, and expectations about the future. This state provides temporal continuity, allowing behavior to depend on accumulated experience rather than only on the immediately available input.

Working memory maintains information that is currently relevant to ongoing cognition. It may contain perceived entities, active goals, intermediate reasoning results, retrieved knowledge, candidate actions, and task constraints. Because computational resources are limited, not every available piece of information can remain equally active. Attention and control mechanisms therefore determine which information receives priority during each cognitive cycle.

Long-term memory provides persistent knowledge accumulated across experiences. Semantic memory can preserve concepts, facts, and relationships, while episodic memory can retain information about particular events and interactions. Procedural memory can encode learned skills and action patterns. Cognitive agents can retrieve information from these different memory systems according to the requirements of the current situation.

Memory retrieval allows previous experience to influence present reasoning. When an agent encounters a new problem, it may search for similar situations, relevant facts, successful strategies, or previous failures. Retrieved information can modify the current internal state and reduce the need to solve every problem from the beginning. Memory therefore provides an important foundation for adaptive and persistent intelligence.

Goals organize cognition around desired outcomes. A cognitive agent may maintain one or several goals describing states it attempts to achieve or preserve. Goals influence attention, information retrieval, reasoning, planning, and action selection. Higher-level goals can also be decomposed into subgoals, allowing complex activities to be organized into manageable structures that can be executed and monitored progressively.

Reasoning transforms available information into conclusions that are useful for action. Symbolic mechanisms may apply rules and logical relationships, while neural mechanisms may generate hypotheses, estimate similarities, or infer likely interpretations. Hybrid agents can combine these processes so that flexible learned representations support structured reasoning when tasks require explicit relationships, constraints, or verification.

Planning extends reasoning into the future. Instead of selecting only the immediately attractive action, an agent can construct candidate sequences and evaluate how they may affect future states. Plans may represent goals, subgoals, preconditions, actions, expected effects, costs, risks, and dependencies. This enables behavior to remain coherent across multiple steps and supports long-horizon goal-directed activity.

World models provide cognitive agents with mechanisms for predicting environmental change. A world model represents relevant aspects of the environment and estimates how states may evolve through time or in response to actions. By simulating possible futures internally, an agent can compare alternatives before acting. Prediction therefore connects perception of the present with planning for future consequences.

Decision making selects among competing alternatives. An agent may evaluate expected rewards, costs, uncertainty, risk, safety constraints, and compatibility with current goals. Some decisions can be generated rapidly through learned policies or heuristics, while difficult situations may require extended reasoning and simulation. Cognitive agents can therefore employ multiple decision mechanisms according to task complexity.

Uncertainty is unavoidable because observations are incomplete and predictions are imperfect. Cognitive agents must distinguish between what is known, inferred, predicted, or uncertain. Confidence estimates can influence whether an agent acts immediately, gathers additional information, retrieves more knowledge, performs deeper reasoning, or requests external assistance. Managing uncertainty is therefore central to reliable autonomous behavior.

Meta-cognition allows an agent to reason about its own cognitive processes. The system can monitor confidence, detect contradictions, recognize failed plans, evaluate progress, and determine whether additional computation is necessary. Rather than merely reasoning about the external environment, a meta-cognitive agent also evaluates how well its own reasoning process is functioning and adapts its strategy accordingly.

Attention determines which information should receive computational priority. Environments may contain far more information than an agent can process simultaneously, making selective processing necessary. Attention can be influenced by perceptual salience, current goals, uncertainty, expected value, or detected anomalies. Effective attention connects bottom-up environmental signals with top-down task requirements.

Learning allows cognitive agents to improve through interaction. Neural components can learn representations, predictions, and policies from data, while symbolic mechanisms can acquire rules, concepts, or task procedures. Reinforcement learning can modify behavior according to outcomes, and self-supervised learning can exploit unlabeled experience. Continual learning enables adaptation as environments, tasks, and available knowledge change.

Cognitive control coordinates competing processes and determines which operations should occur next. Perception may reveal urgent information while planning is underway, memory retrieval may introduce contradictory evidence, or several goals may compete for resources. Control mechanisms resolve these conflicts, allocate computational effort, interrupt obsolete processes, and maintain coherent progression toward important objectives.

Global workspace concepts provide one possible mechanism for cognitive coordination. Specialized modules can process information independently, while selected content becomes globally available to other systems. A representation identified as important may therefore influence memory, reasoning, language, planning, and action simultaneously. Such broadcasting can help otherwise specialized cognitive processes contribute to unified behavior.

Dual-process organization provides another useful perspective. Fast processing can rely on learned associations, heuristics, pattern recognition, and automatic policies, while slower processing can perform explicit reasoning, search, verification, and planning. Cognitive agents can dynamically move between these modes, using inexpensive automatic responses for familiar situations and allocating additional computation when uncertainty or complexity increases.

Language provides a powerful interface for cognitive agents because it can represent instructions, goals, explanations, plans, observations, and knowledge. Large language models can interpret natural-language tasks and generate candidate reasoning or actions. However, persistent agency requires additional mechanisms for memory, state management, verification, tool use, planning, and environmental interaction beyond isolated language generation.

Tool use extends an agent\'s cognitive capabilities beyond its internal models. An agent may recognize that a task requires external information, precise calculation, database access, simulation, communication, or specialized software. It can select an appropriate tool, formulate an operation, interpret the returned result, and incorporate that information into its internal state before continuing the cognitive process.

Agentic AI can therefore be understood as a modern implementation direction for cognitive agents. A language or multimodal foundation model may provide flexible interpretation and reasoning, while external memory preserves persistent information, planners organize tasks, tools perform specialized operations, and control mechanisms maintain execution state. Together these components create a persistent loop rather than a single input--output response.

Multiple cognitive agents can also cooperate. Each agent may maintain its own observations, goals, knowledge, and capabilities while exchanging information with other agents. Cooperation requires communication, task allocation, shared representations, negotiation, and coordination. Multi-agent cognition can distribute complex problems across specialized agents but also introduces challenges involving conflicting beliefs, goals, and decisions.

Embodiment adds another dimension by connecting cognition directly to physical interaction. An embodied cognitive agent receives continuous sensory information, generates motor actions, and experiences physical consequences. Concepts such as distance, force, object permanence, affordance, and causality can therefore be grounded through interaction rather than represented only abstractly. This connection is fundamental to Physical AI.

A robotic cognitive agent may combine cameras, LiDAR, radar, audio, tactile sensing, proprioception, and localization information to estimate its current environment. Neural perception transforms these signals into useful representations, while memory preserves context and symbolic structures maintain goals and constraints. World models predict possible changes, planners select actions, and controllers execute physical motion.

Physical environments impose strict timing requirements. Low-level control may operate at millisecond scales, perception and tracking at tens or hundreds of milliseconds, local planning across seconds, and task-level reasoning over minutes or longer periods. A cognitive agent must coordinate these temporal layers so that immediate reactions remain compatible with long-term goals and safety constraints.

Safety is particularly important for cognitive agents operating in the physical world. Learned predictions and policies may fail under unfamiliar conditions, making independent monitoring mechanisms necessary. Explicit safety constraints, collision avoidance, uncertainty thresholds, verification processes, fallback behaviors, and emergency control can supervise higher-level cognition and prevent unacceptable actions from reaching physical actuators.

Cognitive agents must also maintain persistent task state during long-running activities. Real environments change while plans are being executed, actions may fail, and new information may invalidate previous assumptions. The agent must therefore repeatedly compare expected and observed states, identify discrepancies, update its beliefs, revise plans, and continue from the new situation rather than blindly following a fixed sequence.

This produces a continual cognitive loop of perceive, interpret, remember, predict, reason, plan, act, observe, and learn. The loop is not strictly linear because information can move between components in multiple directions. Predictions can guide perception, goals can guide memory retrieval, unexpected observations can interrupt plans, and learning can modify future decisions. Intelligence emerges from coordination across the entire loop.

Ultimately, cognitive agents represent intelligence as persistent goal-directed interaction between an autonomous system and its environment. Perception constructs the current state, memory preserves experience, reasoning interprets relationships, world models predict possible futures, planning organizes actions, meta-cognition monitors reliability, and learning improves behavior. Their integration provides a foundation for agentic AI, autonomous robots, and advanced Physical AI systems.

인지 에이전트(Cognitive Agents)는 환경을 지각하고, 내부 표상(Internal Representations)을 유지하며, 상황을 추론하고, 목표를 추구하며, 시간의 흐름에 따라 행동을 선택하도록 설계된 자율 시스템(Autonomous Systems)입니다. 관찰을 행동에 직접 연결하는 단순한 반응형 시스템(Reactive Systems)과 달리 인지 에이전트는 과거 사건, 현재 조건, 가능한 미래에 관한 정보를 유지합니다. 이들의 행동은 지각(Perception), 기억(Memory), 추론(Reasoning), 학습(Learning), 계획(Planning), 행동(Action)의 지속적인 상호작용에서 나타납니다.

인지 에이전트라는 개념은 지능(Intelligence)을 서로 분리된 알고리즘의 집합이 아니라 하나의 통합된 과정(Integrated Process)으로 모델링하려는 시도에서 비롯되었습니다. 인간의 인지는 지각, 기억 검색(Memory Retrieval), 추론, 행동을 서로 독립적으로 수행하지 않습니다. 이러한 기능들은 지속적으로 서로에게 영향을 줍니다. 인지 에이전트는 전문화된 인지 메커니즘을 변화하는 상황에서도 일관된 행동을 유지할 수 있는 하나의 아키텍처로 구성함으로써 동일한 원리를 적용합니다.

에이전트는 지각--인지--행동 순환(Perception--Cognition--Action Cycle)을 통해 설명할 수 있습니다. 센서 또는 정보 채널은 환경에 대한 관찰을 제공하고, 인지 메커니즘은 이러한 관찰을 해석하며, 에이전트는 환경 또는 자신의 정보 상태를 변화시키는 행동을 선택합니다. 이후 새로운 관찰에는 이전 행동의 결과가 반영되며, 이를 통해 시간에 따라 지능적 행동이 발달하는 반복적인 폐쇄 루프(Closed Loop)가 형성됩니다.

지각(Perception)은 에이전트와 환경 사이의 인터페이스를 제공합니다. 원시 감각 신호(Raw Sensory Signals) 또는 디지털 관찰은 인지에 유용한 표상으로 변환되어야 합니다. 신경 지각 시스템(Neural Perception Systems)은 객체, 사람, 사건, 언어, 공간적 관계(Spatial Relationships), 환경 조건을 인식할 수 있습니다. 그 결과 생성된 정보는 에이전트의 내부 상태(Internal State)의 일부가 되고 이후의 추론, 예측, 의사결정을 위한 증거를 제공합니다.

내부 상태(Internal State)는 인지 에이전트를 순수한 반응형 메커니즘과 구별하는 중요한 특징입니다. 에이전트는 이전 사건, 추론된 조건, 활성 목표(Active Goals), 해결되지 않은 과제, 미래에 대한 기대처럼 현재 관찰만으로 직접 얻을 수 없는 정보를 유지합니다. 이러한 상태는 시간적 연속성(Temporal Continuity)을 제공하여 행동이 현재 입력에만 의존하지 않고 축적된 경험에 의존할 수 있도록 합니다.

작업 기억(Working Memory)은 현재 진행 중인 인지 과정과 관련된 정보를 유지합니다. 여기에는 지각된 개체, 활성 목표, 중간 추론 결과, 검색된 지식, 후보 행동(Candidate Actions), 과제 제약 조건(Task Constraints)이 포함될 수 있습니다. 계산 자원(Computational Resources)은 제한되어 있기 때문에 이용 가능한 모든 정보를 동일한 수준으로 활성화할 수 없습니다. 따라서 어텐션(Attention)과 제어 메커니즘(Control Mechanisms)은 각 인지 주기에서 어떤 정보에 우선순위를 부여할지를 결정합니다.

장기 기억(Long-term Memory)은 경험을 통해 축적된 지속적인 지식을 제공합니다. 의미 기억(Semantic Memory)은 개념, 사실, 관계를 보존하고, 일화 기억(Episodic Memory)은 특정 사건과 상호작용에 관한 정보를 유지할 수 있습니다. 절차 기억(Procedural Memory)은 학습된 기술과 행동 패턴을 인코딩할 수 있습니다. 인지 에이전트는 현재 상황의 요구사항에 따라 이러한 서로 다른 기억 시스템으로부터 정보를 검색할 수 있습니다.

기억 검색(Memory Retrieval)은 이전 경험이 현재의 추론에 영향을 미치도록 합니다. 에이전트가 새로운 문제를 만났을 때 유사한 상황, 관련 사실, 성공적인 전략 또는 이전의 실패 사례를 검색할 수 있습니다. 검색된 정보는 현재 내부 상태를 수정하고 모든 문제를 처음부터 다시 해결해야 하는 필요성을 줄여 줍니다. 따라서 기억은 적응적이고 지속적인 지능(Adaptive and Persistent Intelligence)을 위한 중요한 기반을 제공합니다.

목표(Goals)는 원하는 결과를 중심으로 인지 과정을 조직합니다. 인지 에이전트는 달성하거나 유지하려는 상태를 설명하는 하나 이상의 목표를 유지할 수 있습니다. 목표는 어텐션, 정보 검색, 추론, 계획, 행동 선택(Action Selection)에 영향을 줍니다. 상위 수준의 목표는 하위 목표(Subgoals)로 분해될 수도 있으며, 이를 통해 복잡한 활동을 점진적으로 실행하고 모니터링할 수 있는 관리 가능한 구조로 구성할 수 있습니다.

추론(Reasoning)은 이용 가능한 정보를 행동에 유용한 결론으로 변환합니다. 기호적 메커니즘(Symbolic Mechanisms)은 규칙과 논리적 관계를 적용할 수 있으며, 신경 메커니즘(Neural Mechanisms)은 가설을 생성하고, 유사성을 추정하거나, 가능성이 높은 해석을 추론할 수 있습니다. 하이브리드 에이전트(Hybrid Agents)는 이러한 과정을 결합하여 유연하게 학습된 표상이 명시적인 관계, 제약 조건 또는 검증(Verification)이 필요한 상황에서 구조화된 추론을 지원하도록 할 수 있습니다.

계획(Planning)은 추론을 미래로 확장합니다. 에이전트는 즉각적으로 가장 매력적인 행동만을 선택하는 대신 후보 행동 시퀀스(Candidate Action Sequences)를 구성하고 이러한 행동이 미래 상태에 어떤 영향을 줄 수 있는지를 평가할 수 있습니다. 계획은 목표, 하위 목표, 전제 조건(Preconditions), 행동, 예상 효과(Expected Effects), 비용, 위험, 의존 관계를 표현할 수 있습니다. 이를 통해 여러 단계에 걸쳐 행동의 일관성을 유지하고 장기적인 목표 지향적 활동(Long-horizon Goal-directed Activity)을 지원할 수 있습니다.

월드 모델(World Models)은 인지 에이전트가 환경 변화를 예측할 수 있는 메커니즘을 제공합니다. 월드 모델은 환경의 관련 측면을 표현하고 상태가 시간에 따라 또는 행동에 대응하여 어떻게 변화할지를 추정합니다. 에이전트는 가능한 미래를 내부적으로 시뮬레이션함으로써 실제로 행동하기 전에 여러 대안을 비교할 수 있습니다. 따라서 예측(Prediction)은 현재에 대한 지각과 미래 결과를 고려하는 계획을 연결합니다.

의사결정(Decision Making)은 서로 경쟁하는 여러 대안 가운데 하나를 선택합니다. 에이전트는 예상 보상(Expected Rewards), 비용, 불확실성(Uncertainty), 위험(Risk), 안전 제약 조건(Safety Constraints), 현재 목표와의 적합성을 평가할 수 있습니다. 일부 의사결정은 학습된 정책(Learned Policies)이나 휴리스틱(Heuristics)을 통해 빠르게 생성될 수 있지만 어려운 상황에서는 확장된 추론과 시뮬레이션이 필요할 수 있습니다. 따라서 인지 에이전트는 과제의 복잡성에 따라 여러 의사결정 메커니즘을 활용할 수 있습니다.

관찰은 불완전하고 예측은 완벽하지 않기 때문에 불확실성(Uncertainty)은 피할 수 없습니다. 인지 에이전트는 무엇이 알려진 사실인지, 추론된 것인지, 예측된 것인지, 또는 불확실한 것인지를 구별해야 합니다. 신뢰도 추정(Confidence Estimates)은 에이전트가 즉시 행동할지, 추가 정보를 수집할지, 더 많은 지식을 검색할지, 심층적인 추론을 수행할지 또는 외부의 도움을 요청할지를 결정하는 데 영향을 줄 수 있습니다. 따라서 불확실성 관리는 신뢰할 수 있는 자율 행동(Reliable Autonomous Behavior)의 핵심입니다.

메타인지(Meta-cognition)는 에이전트가 자신의 인지 과정 자체에 대해 추론할 수 있도록 합니다. 시스템은 신뢰도를 모니터링하고, 모순(Contradictions)을 탐지하고, 실패한 계획을 인식하고, 진행 상황을 평가하며, 추가적인 계산이 필요한지를 결정할 수 있습니다. 메타인지 에이전트는 외부 환경만을 추론하는 것이 아니라 자신의 추론 과정이 얼마나 효과적으로 작동하고 있는지도 평가하고 그에 따라 전략을 조정합니다.

어텐션(Attention)은 어떤 정보에 계산적 우선순위(Computational Priority)를 부여할지를 결정합니다. 환경에는 에이전트가 동시에 처리할 수 있는 것보다 훨씬 많은 정보가 존재할 수 있으므로 선택적 처리가 필요합니다. 어텐션은 지각적 현저성(Perceptual Salience), 현재 목표, 불확실성, 기대 가치(Expected Value), 탐지된 이상(Detected Anomalies)의 영향을 받을 수 있습니다. 효과적인 어텐션은 상향식 환경 신호(Bottom-up Environmental Signals)와 하향식 과제 요구사항(Top-down Task Requirements)을 연결합니다.

학습(Learning)은 인지 에이전트가 상호작용을 통해 능력을 향상시킬 수 있도록 합니다. 신경 구성 요소는 데이터에서 표상, 예측, 정책을 학습할 수 있고, 기호적 메커니즘은 규칙, 개념, 과제 절차(Task Procedures)를 습득할 수 있습니다. 강화학습(Reinforcement Learning)은 결과에 따라 행동을 수정할 수 있으며, 자기지도학습(Self-supervised Learning)은 라벨이 없는 경험을 활용할 수 있습니다. 지속 학습(Continual Learning)은 환경, 과제, 이용 가능한 지식이 변화함에 따라 지속적인 적응을 가능하게 합니다.

인지 제어(Cognitive Control)는 서로 경쟁하는 처리 과정을 조정하고 다음에 어떤 연산을 수행해야 하는지를 결정합니다. 계획이 진행되는 동안 지각 시스템이 긴급한 정보를 발견하거나, 기억 검색에서 모순되는 증거가 나타나거나, 여러 목표가 자원을 두고 경쟁할 수 있습니다. 제어 메커니즘은 이러한 충돌을 해결하고, 계산 자원을 할당하고, 더 이상 유효하지 않은 과정을 중단하며, 중요한 목표를 향한 일관된 진행을 유지합니다.

전역 작업공간 개념(Global Workspace Concepts)은 인지 조정을 위한 하나의 가능한 메커니즘을 제공합니다. 전문화된 모듈(Specialized Modules)은 정보를 독립적으로 처리할 수 있으며, 그 가운데 선택된 내용은 다른 시스템에서 전역적으로 이용할 수 있게 됩니다. 중요하다고 판단된 표상은 기억, 추론, 언어, 계획, 행동에 동시에 영향을 줄 수 있습니다. 이러한 정보의 전역적 방송(Global Broadcasting)은 서로 전문화된 인지 과정들이 통합된 행동에 기여하도록 도울 수 있습니다.

이중 처리 조직(Dual-process Organization)은 또 다른 유용한 관점을 제공합니다. 빠른 처리(Fast Processing)는 학습된 연상, 휴리스틱, 패턴 인식, 자동화된 정책에 의존할 수 있으며, 느린 처리(Slow Processing)는 명시적인 추론, 탐색(Search), 검증, 계획을 수행할 수 있습니다. 인지 에이전트는 익숙한 상황에서는 계산 비용이 낮은 자동 반응을 사용하고 불확실성이나 복잡성이 증가하면 추가적인 계산을 할당하면서 이러한 모드 사이를 동적으로 전환할 수 있습니다.

언어(Language)는 명령, 목표, 설명, 계획, 관찰, 지식을 표현할 수 있기 때문에 인지 에이전트를 위한 강력한 인터페이스를 제공합니다. 대규모 언어 모델(Large Language Models)은 자연어 과제를 해석하고 후보 추론이나 행동을 생성할 수 있습니다. 그러나 지속적인 에이전시(Persistent Agency)를 구현하려면 단일 언어 생성만으로는 부족하며 기억, 상태 관리(State Management), 검증, 도구 사용(Tool Use), 계획, 환경과의 상호작용을 위한 추가적인 메커니즘이 필요합니다.

도구 사용(Tool Use)은 에이전트의 인지 능력을 내부 모델의 범위를 넘어 확장합니다. 에이전트는 과제 수행에 외부 정보, 정확한 계산, 데이터베이스 접근(Database Access), 시뮬레이션(Simulation), 통신 또는 전문 소프트웨어가 필요하다는 것을 인식할 수 있습니다. 적절한 도구를 선택하고, 연산을 구성하고, 반환된 결과를 해석하며, 해당 정보를 내부 상태에 통합한 다음 인지 과정을 계속할 수 있습니다.

따라서 에이전트형 인공지능(Agentic AI)은 인지 에이전트의 현대적인 구현 방향으로 이해할 수 있습니다. 언어 또는 멀티모달 파운데이션 모델(Multimodal Foundation Model)은 유연한 해석과 추론을 제공하고, 외부 기억(External Memory)은 지속적인 정보를 보존하며, 계획기는 과제를 조직하고, 도구는 전문화된 연산을 수행하며, 제어 메커니즘은 실행 상태(Execution State)를 유지할 수 있습니다. 이러한 구성 요소를 결합하면 단일 입력--출력 반응이 아니라 지속적으로 작동하는 루프를 구성할 수 있습니다.

여러 인지 에이전트는 서로 협력할 수도 있습니다. 각각의 에이전트는 자신의 관찰, 목표, 지식, 능력을 유지하면서 다른 에이전트와 정보를 교환할 수 있습니다. 협력을 위해서는 통신(Communication), 과제 할당(Task Allocation), 공유 표상(Shared Representations), 협상(Negotiation), 조정(Coordination)이 필요합니다. 다중 에이전트 인지(Multi-agent Cognition)는 복잡한 문제를 전문화된 에이전트에 분산할 수 있지만 서로 충돌하는 믿음, 목표, 의사결정을 처리해야 하는 새로운 문제도 발생시킵니다.

체화(Embodiment)는 인지를 물리적 상호작용과 직접 연결함으로써 또 다른 차원을 추가합니다. 체화된 인지 에이전트(Embodied Cognitive Agent)는 지속적인 감각 정보를 받아들이고, 운동 행동(Motor Actions)을 생성하며, 그에 따른 물리적 결과를 경험합니다. 거리, 힘, 객체 영속성(Object Permanence), 행동유도성(Affordance), 인과성(Causality)과 같은 개념은 추상적으로만 표현되는 것이 아니라 상호작용을 통해 접지(Grounding)될 수 있습니다. 이러한 연결은 피지컬 인공지능(Physical AI)의 핵심적인 기반입니다.

로봇 인지 에이전트(Robotic Cognitive Agent)는 카메라, 라이다(LiDAR), 레이더(Radar), 오디오(Audio), 촉각 감지(Tactile Sensing), 고유수용감각(Proprioception), 위치 추정(Localization) 정보를 결합하여 현재 환경을 추정할 수 있습니다. 신경 지각은 이러한 신호를 유용한 표상으로 변환하고, 기억은 문맥을 보존하며, 기호 구조(Symbolic Structures)는 목표와 제약 조건을 유지합니다. 월드 모델은 가능한 변화를 예측하고, 계획기는 행동을 선택하며, 제어기는 실제 물리적 움직임을 실행합니다.

물리적 환경은 엄격한 시간 요구사항(Timing Requirements)을 부과합니다. 저수준 제어(Low-level Control)는 밀리초 단위로 작동할 수 있고, 지각과 추적은 수십 또는 수백 밀리초 단위로, 지역 계획(Local Planning)은 수초 단위로, 과제 수준의 추론(Task-level Reasoning)은 수분 또는 그 이상의 시간 범위에서 작동할 수 있습니다. 인지 에이전트는 즉각적인 반응이 장기 목표와 안전 제약 조건에 일치하도록 이러한 시간 계층(Temporal Layers)을 조정해야 합니다.

물리 세계에서 작동하는 인지 에이전트에서는 안전(Safety)이 특히 중요합니다. 학습된 예측과 정책은 익숙하지 않은 조건에서 실패할 수 있으므로 독립적인 모니터링 메커니즘이 필요합니다. 명시적인 안전 제약 조건, 충돌 회피(Collision Avoidance), 불확실성 임계값(Uncertainty Thresholds), 검증 과정, 폴백 행동(Fallback Behaviors), 비상 제어(Emergency Control)는 상위 수준 인지를 감독하고 허용할 수 없는 행동이 실제 액추에이터(Physical Actuators)에 전달되는 것을 방지할 수 있습니다.

인지 에이전트는 장시간 실행되는 활동에서도 지속적인 과제 상태(Persistent Task State)를 유지해야 합니다. 계획이 실행되는 동안 실제 환경은 변화할 수 있고, 행동은 실패할 수 있으며, 새로운 정보가 이전의 가정을 무효화할 수도 있습니다. 따라서 에이전트는 예상 상태와 관찰 상태를 반복적으로 비교하고, 불일치(Discrepancies)를 식별하고, 자신의 믿음을 업데이트하고, 계획을 수정하며, 고정된 시퀀스를 맹목적으로 따르는 대신 변화된 상황에서 다시 행동을 이어가야 합니다.

이를 통해 지각하고, 해석하고, 기억하고, 예측하고, 추론하고, 계획하고, 행동하고, 관찰하고, 학습하는 지속적인 인지 루프(Continual Cognitive Loop)가 형성됩니다. 이 루프는 정보가 구성 요소 사이에서 여러 방향으로 이동할 수 있기 때문에 엄격한 선형 과정이 아닙니다. 예측은 지각을 안내하고, 목표는 기억 검색을 안내하며, 예상하지 못한 관찰은 계획을 중단시킬 수 있고, 학습은 미래의 의사결정을 변화시킬 수 있습니다. 지능은 이러한 전체 루프에 걸친 조정에서 나타납니다.

궁극적으로 인지 에이전트(Cognitive Agents)는 지능을 자율 시스템과 환경 사이에서 지속되는 목표 지향적 상호작용(Persistent Goal-directed Interaction)으로 표현합니다. 지각은 현재 상태를 구성하고, 기억은 경험을 보존하며, 추론은 관계를 해석하고, 월드 모델은 가능한 미래를 예측하며, 계획은 행동을 조직하고, 메타인지는 신뢰성을 모니터링하며, 학습은 행동을 향상시킵니다. 이러한 요소들의 통합은 에이전트형 인공지능(Agentic AI), 자율 로봇(Autonomous Robots), 고급 피지컬 인공지능(Advanced Physical AI Systems)을 위한 중요한 기반을 제공합니다.

##  

## 06.11 Internal Models and World Models [w/Code]

![](images/image12.png){width="7.268055555555556in" height="7.268055555555556in"}

Internal models are cognitive representations that allow an intelligent system to maintain information about itself, its environment, and the relationships connecting actions to consequences. Rather than responding only to immediate sensory input, a system equipped with internal models can represent conditions that are temporarily unobservable, interpret ongoing events, anticipate changes, and use predicted outcomes to guide future behavior.

An internal model does not need to reproduce every physical detail of reality. Its purpose is to preserve information that is useful for cognition and action. Depending on the task, it may represent objects, spatial relationships, agents, motion, causal dependencies, goals, uncertainty, or action possibilities. Effective internal models therefore emphasize task-relevant structure while compressing or ignoring unnecessary environmental detail.

The idea is closely related to the distinction between reactive and model-based behavior. A purely reactive agent maps current observations directly to actions, whereas a model-based agent maintains an internal state that summarizes relevant information accumulated over time. This state allows the agent to reason about situations in which the current observation alone does not contain enough information for an appropriate decision.

Internal state estimation is necessary because observations rarely provide a complete description of the environment. Sensors may be noisy, objects may become occluded, and important variables may not be directly measurable. An intelligent system must therefore combine current observations with previous states and learned expectations. The resulting internal representation becomes the system\'s best estimate of what is currently happening.

World models extend this principle by representing how an environment behaves and changes. A world model describes relationships among states, observations, actions, and future outcomes. Given a representation of the current situation and a possible action, the model attempts to estimate what may happen next. This predictive capability allows cognition to extend beyond interpretation of the present toward simulation of possible futures.

A simple world model can be expressed as a transition relationship from a current state and action to a predicted next state. More sophisticated models can predict sequences of future states over multiple time steps. Instead of asking only what will happen immediately, an agent can estimate trajectories of possible futures and compare how different actions may influence the evolution of the environment.

State representation is therefore central to world-model design. Raw sensory observations such as images, audio, LiDAR measurements, or tactile signals are often too large and redundant for efficient prediction. Neural encoders can transform these observations into compact latent states that preserve important information. Prediction can then operate within this latent space rather than reconstructing every detail of the original sensory input.

Latent representations allow world models to capture environmental structure at useful levels of abstraction. A latent state may encode object identity, location, velocity, interaction, scene context, or other task-relevant properties without explicitly assigning a human-readable symbol to every dimension. Learning determines which structures become useful for predicting future observations, rewards, events, or consequences of actions.

World models may also contain explicit structured representations. Objects, agents, relationships, maps, semantic categories, causal dependencies, and physical constraints can be represented symbolically or geometrically. Such structures make some forms of reasoning easier because an agent can manipulate meaningful entities directly. Modern systems can therefore combine learned latent representations with explicit structured knowledge.

Prediction is the fundamental operation connecting an internal model to future-oriented cognition. The system uses its current state and candidate actions to estimate possible future states. Prediction can occur over short horizons for immediate control or over longer horizons for planning. Different predictive components may operate simultaneously at several temporal and representational scales.

Prediction error provides an important learning signal. When the observed future differs from the predicted future, the discrepancy indicates that the internal model is incomplete or inaccurate. The system can use this error to update representations, transition dynamics, or uncertainty estimates. Repeated prediction and correction allow the model to become increasingly aligned with regularities encountered through experience.

This process connects world models directly with predictive processing. Perception can be interpreted not only as extracting information from sensory input but also as comparing incoming observations with internally generated expectations. Predictions flow toward expected observations, while prediction errors provide corrective information. Cognition consequently becomes an ongoing interaction between expectation and sensory evidence.

Dynamics models represent how states evolve through time. In embodied systems, dynamics can include the effects of motion, forces, object interactions, environmental changes, and actions performed by the agent. Learned dynamics models can approximate these relationships from experience. Accurate dynamics are particularly important when an agent must anticipate the consequences of physical actions before executing them.

World models can be deterministic when similar states and actions are expected to produce approximately predictable outcomes. Real environments, however, frequently contain uncertainty, hidden variables, other agents, and stochastic events. Probabilistic world models can represent multiple possible futures and assign different likelihoods to them. This allows planning to consider uncertainty rather than relying on a single predicted trajectory.

Uncertainty can arise from several sources. The environment itself may be stochastic, observations may be incomplete, or the model may encounter situations outside its previous experience. A capable world model should distinguish confident predictions from uncertain ones. This information can influence whether an agent proceeds with an action, gathers additional observations, reduces speed, selects a safer alternative, or requests assistance.

Memory and world models are deeply connected. Episodic memory preserves specific previous experiences, while semantic memory stores more generalized knowledge about the world. A world model can use both forms of information when estimating future states. Conversely, prediction errors and surprising events can determine which experiences are important enough to preserve for later retrieval and learning.

Causal representation provides a deeper level of internal modeling than statistical association alone. Predicting that two events commonly occur together is different from understanding how an intervention changes an outcome. Agents that interact with environments can learn from actions as interventions. This creates opportunities to discover relationships between causes, effects, controllable variables, and external events.

Counterfactual reasoning extends internal simulation beyond straightforward prediction. An agent can ask what might have happened if a different action had been selected or if some condition had changed. Counterfactual models support learning from alternatives that were not actually executed and can improve planning, explanation, diagnosis, and decision making by comparing observed outcomes with hypothetical possibilities.

Planning uses world models to search through possible futures. Candidate actions can be applied within the internal model rather than immediately in the physical environment. Predicted states are evaluated according to goals, costs, rewards, risks, and constraints. The agent can then select actions whose simulated consequences appear most favorable, converting prediction into purposeful decision making.

Model-based reinforcement learning applies this idea to learned behavior. Instead of learning only a direct mapping from observations to actions, an agent learns a model of environmental dynamics and uses that model to evaluate behavior. Simulated experience can supplement real interaction, potentially reducing the number of costly or dangerous physical trials required to discover effective policies.

Imagination can be understood computationally as the generation of internally simulated states that are not currently being observed. A world model allows an agent to construct hypothetical situations, roll forward possible trajectories, and evaluate outcomes without physically experiencing every alternative. This capability creates an important connection between prediction, planning, creativity, and goal-directed cognition.

Hierarchical world models represent environments at several levels of abstraction. Low-level models may predict immediate sensor or motion changes, intermediate models may represent objects and local interactions, and higher-level models may describe events, tasks, intentions, or long-term consequences. Hierarchical organization allows detailed physical prediction to coexist with efficient reasoning over extended time horizons.

Temporal abstraction is particularly important because predicting every small physical change far into the future is computationally expensive and increasingly uncertain. Higher-level models can instead reason about meaningful events or subgoals. An agent might predict precise motion for the next few seconds while representing later stages through semantic states such as reaching a location, completing a task, or interacting with an object.

Internal models can also include models of the agent itself. A self-model may represent the agent\'s body, capabilities, available resources, knowledge, uncertainty, goals, and limitations. For robots, this can include kinematics, dynamics, sensor configurations, battery state, payload, reachability, or damage conditions. Effective planning requires understanding not only the external world but also what the agent can actually do within it.

Models of other agents become important in social and multi-agent environments. An intelligent system may estimate another agent\'s goals, beliefs, intentions, capabilities, or likely future actions. These models enable cooperation, negotiation, collision avoidance, prediction of human behavior, and coordinated planning. Multi-agent world models therefore extend environmental prediction to include interacting decision-making entities.

Language can contribute semantic structure to internal models. Linguistic descriptions provide compact representations of objects, relationships, events, goals, and causal explanations that may be difficult to derive from sensory signals alone. Multimodal models can connect language with visual and physical observations, allowing internal representations to combine perceptual grounding with abstract conceptual knowledge.

Large neural models provide powerful mechanisms for learning world representations from extensive datasets, but prediction alone does not guarantee an accurate understanding of physical reality. Models may reproduce statistical patterns while failing under unfamiliar interventions or long prediction horizons. Grounding through observation, interaction, feedback, and physical constraints remains important for developing reliable internal models.

World models are especially important for cognitive agents because they provide a shared predictive substrate for several cognitive functions. Perception updates the current state, memory supplies relevant experience, reasoning interprets relationships, planning generates alternatives, and decision making evaluates predicted outcomes. The world model connects these processes by providing a representation of what exists and how it may change.

For Physical AI, world models must connect multimodal perception with physical dynamics and action. Cameras, LiDAR, radar, tactile sensors, proprioception, and localization systems provide observations of the environment and robot state. These observations can be fused into a world representation from which the system predicts object motion, terrain changes, interactions, collisions, and consequences of robot actions.

A robotic world model can support navigation by predicting free space and moving obstacles, manipulation by predicting object responses to contact, and task planning by estimating how actions change semantic states. Instead of treating perception, planning, and control as completely separate pipelines, the model can provide a common predictive representation linking what the robot observes with what it expects to happen.

Real-time operation requires world models to balance accuracy with computational efficiency. Short-horizon predictions may need rapid updates for control and safety, while long-horizon planning can use slower and more abstract simulations. Hierarchical architectures can distribute computation across these timescales, allowing immediate responses to remain synchronized with broader task objectives and future expectations.

The reliability of an internal model must be continuously evaluated because environments change and learned assumptions can become invalid. Agents should compare predictions with observations, monitor uncertainty, detect distribution shifts, and recognize when simulation is unreliable. Meta-cognitive mechanisms can then determine whether to replan, gather more information, switch models, or adopt conservative behavior.

Ultimately, internal models and world models transform intelligent behavior from immediate reaction into predictive interaction. Internal states preserve information beyond current observations, learned representations organize environmental structure, dynamics models predict change, uncertainty represents alternative futures, and simulation allows actions to be evaluated before execution. These capabilities provide a central foundation for cognitive agents, planning, model-based learning, robotics, and advanced Physical AI.

내부 모델(Internal Models)은 지능형 시스템(Intelligent System)이 자기 자신, 환경, 그리고 행동과 결과를 연결하는 관계에 대한 정보를 유지할 수 있도록 하는 인지적 표상(Cognitive Representations)입니다. 즉각적인 감각 입력(Sensory Input)에만 반응하는 대신 내부 모델을 갖춘 시스템은 일시적으로 관찰할 수 없는 조건을 표현하고, 진행 중인 사건을 해석하며, 변화를 예상하고, 예측된 결과를 활용하여 미래의 행동을 안내할 수 있습니다.

내부 모델(Internal Model)은 현실의 모든 물리적 세부 사항을 그대로 재현할 필요는 없습니다. 그 목적은 인지와 행동에 유용한 정보를 보존하는 것입니다. 과제에 따라 객체, 공간적 관계(Spatial Relationships), 에이전트, 움직임, 인과적 의존 관계(Causal Dependencies), 목표, 불확실성(Uncertainty), 행동 가능성(Action Possibilities)을 표현할 수 있습니다. 따라서 효과적인 내부 모델은 불필요한 환경적 세부 사항을 압축하거나 무시하면서 과제와 관련된 구조를 강조합니다.

이 개념은 반응형 행동(Reactive Behavior)과 모델 기반 행동(Model-based Behavior)의 구분과 밀접하게 관련됩니다. 순수한 반응형 에이전트(Reactive Agent)는 현재 관찰을 행동에 직접 매핑하지만, 모델 기반 에이전트(Model-based Agent)는 시간에 따라 축적된 관련 정보를 요약하는 내부 상태(Internal State)를 유지합니다. 이러한 상태를 통해 현재 관찰만으로는 적절한 의사결정을 내리기에 충분한 정보가 없는 상황에서도 추론할 수 있습니다.

관찰만으로 환경에 대한 완전한 설명을 얻는 경우는 드물기 때문에 내부 상태 추정(Internal State Estimation)이 필요합니다. 센서에는 잡음이 존재할 수 있고, 객체는 가려질 수 있으며, 중요한 변수를 직접 측정하지 못할 수도 있습니다. 따라서 지능형 시스템은 현재 관찰을 이전 상태 및 학습된 기대(Learned Expectations)와 결합해야 합니다. 이렇게 생성된 내부 표상(Internal Representation)은 현재 어떤 일이 발생하고 있는지에 대한 시스템의 최선의 추정치가 됩니다.

월드 모델(World Models)은 환경이 어떻게 행동하고 변화하는지를 표현함으로써 이러한 원리를 확장합니다. 월드 모델은 상태(State), 관찰(Observations), 행동(Actions), 미래 결과(Future Outcomes) 사이의 관계를 설명합니다. 현재 상황에 대한 표상과 가능한 행동이 주어지면 모델은 다음에 어떤 일이 발생할지를 추정하려고 합니다. 이러한 예측 능력(Predictive Capability)은 인지를 현재의 해석에서 가능한 미래의 시뮬레이션으로 확장합니다.

단순한 월드 모델(World Model)은 현재 상태와 행동에서 예측된 다음 상태(Predicted Next State)로 이어지는 전이 관계(Transition Relationship)로 표현할 수 있습니다. 더욱 정교한 모델은 여러 시간 단계에 걸친 미래 상태의 시퀀스를 예측할 수 있습니다. 에이전트는 바로 다음 순간에 어떤 일이 발생하는지만 질문하는 대신 가능한 미래의 궤적(Trajectories)을 추정하고 서로 다른 행동이 환경의 변화 과정에 어떤 영향을 미치는지를 비교할 수 있습니다.

따라서 상태 표상(State Representation)은 월드 모델 설계(World-model Design)의 핵심입니다. 이미지, 오디오, 라이다(LiDAR) 측정값, 촉각 신호(Tactile Signals)와 같은 원시 감각 관찰(Raw Sensory Observations)은 효율적인 예측에 사용하기에는 지나치게 크고 중복성이 높은 경우가 많습니다. 신경 인코더(Neural Encoders)는 이러한 관찰을 중요한 정보를 보존하는 압축된 잠재 상태(Latent States)로 변환할 수 있습니다. 이후 예측은 원래 감각 입력의 모든 세부 사항을 재구성하는 대신 이러한 잠재 공간(Latent Space)에서 수행될 수 있습니다.

잠재 표상(Latent Representations)을 통해 월드 모델은 유용한 추상화 수준에서 환경의 구조를 포착할 수 있습니다. 잠재 상태는 각 차원에 사람이 읽을 수 있는 명시적 기호를 할당하지 않고도 객체 정체성(Object Identity), 위치, 속도, 상호작용, 장면 문맥(Scene Context), 기타 과제 관련 속성을 인코딩할 수 있습니다. 학습은 미래 관찰, 보상, 사건 또는 행동의 결과를 예측하는 데 어떤 구조가 유용한지를 결정합니다.

월드 모델은 명시적인 구조화된 표상(Structured Representations)을 포함할 수도 있습니다. 객체, 에이전트, 관계, 지도(Maps), 의미적 범주(Semantic Categories), 인과적 의존 관계, 물리적 제약 조건(Physical Constraints)을 기호적 또는 기하학적으로 표현할 수 있습니다. 이러한 구조는 에이전트가 의미 있는 개체를 직접 조작할 수 있게 하므로 일부 형태의 추론을 쉽게 만듭니다. 따라서 현대 시스템은 학습된 잠재 표상과 명시적인 구조화된 지식을 결합할 수 있습니다.

예측(Prediction)은 내부 모델을 미래 지향적 인지(Future-oriented Cognition)와 연결하는 핵심 연산입니다. 시스템은 현재 상태와 후보 행동(Candidate Actions)을 사용하여 가능한 미래 상태를 추정합니다. 예측은 즉각적인 제어를 위한 단기 범위(Short Horizons)에서 수행될 수도 있고 계획을 위한 장기 범위(Longer Horizons)에서 수행될 수도 있습니다. 여러 예측 구성 요소가 서로 다른 시간 및 표상 척도에서 동시에 작동할 수도 있습니다.

예측 오류(Prediction Error)는 중요한 학습 신호(Learning Signal)를 제공합니다. 실제로 관찰된 미래가 예측된 미래와 다르면 이러한 차이는 내부 모델이 불완전하거나 부정확하다는 것을 나타냅니다. 시스템은 이러한 오류를 사용하여 표상, 전이 동역학(Transition Dynamics), 불확실성 추정(Uncertainty Estimates)을 업데이트할 수 있습니다. 반복적인 예측과 수정 과정을 통해 모델은 경험에서 발견되는 규칙성에 점차 더 잘 정렬될 수 있습니다.

이 과정은 월드 모델을 예측 처리(Predictive Processing)와 직접 연결합니다. 지각(Perception)은 단순히 감각 입력에서 정보를 추출하는 과정뿐만 아니라 들어오는 관찰과 내부적으로 생성된 기대를 비교하는 과정으로도 해석할 수 있습니다. 예측은 예상되는 관찰을 향해 전달되고, 예측 오류는 수정 정보를 제공합니다. 따라서 인지는 기대(Expectation)와 감각적 증거(Sensory Evidence) 사이의 지속적인 상호작용이 됩니다.

동역학 모델(Dynamics Models)은 상태가 시간에 따라 어떻게 변화하는지를 표현합니다. 체화된 시스템(Embodied Systems)에서는 움직임, 힘, 객체 상호작용(Object Interactions), 환경 변화, 에이전트가 수행한 행동의 효과 등이 동역학에 포함될 수 있습니다. 학습된 동역학 모델(Learned Dynamics Models)은 경험을 통해 이러한 관계를 근사할 수 있습니다. 정확한 동역학은 에이전트가 물리적 행동을 실행하기 전에 그 결과를 예상해야 할 때 특히 중요합니다.

유사한 상태와 행동이 대략 예측 가능한 결과를 생성한다고 기대되는 경우 월드 모델은 결정론적(Deterministic)일 수 있습니다. 그러나 실제 환경에는 불확실성, 숨겨진 변수(Hidden Variables), 다른 에이전트, 확률적 사건(Stochastic Events)이 존재하는 경우가 많습니다. 확률적 월드 모델(Probabilistic World Models)은 여러 가능한 미래를 표현하고 각각에 서로 다른 가능성을 할당할 수 있습니다. 이를 통해 계획은 하나의 예측된 궤적에만 의존하지 않고 불확실성을 고려할 수 있습니다.

불확실성(Uncertainty)은 여러 원인에서 발생할 수 있습니다. 환경 자체가 확률적일 수도 있고, 관찰이 불완전할 수도 있으며, 모델이 이전 경험에서 벗어난 상황을 만날 수도 있습니다. 능력 있는 월드 모델은 신뢰도가 높은 예측과 불확실한 예측을 구분해야 합니다. 이러한 정보는 에이전트가 행동을 계속할지, 추가 관찰을 수집할지, 속도를 줄일지, 더 안전한 대안을 선택할지 또는 도움을 요청할지를 결정하는 데 영향을 줄 수 있습니다.

기억(Memory)과 월드 모델은 깊게 연결되어 있습니다. 일화 기억(Episodic Memory)은 특정한 과거 경험을 보존하고, 의미 기억(Semantic Memory)은 세계에 대한 보다 일반화된 지식을 저장합니다. 월드 모델은 미래 상태를 추정할 때 두 형태의 정보를 모두 활용할 수 있습니다. 반대로 예측 오류와 예상 밖의 사건(Surprising Events)은 어떤 경험이 이후의 검색과 학습을 위해 보존할 만큼 중요한지를 결정할 수 있습니다.

인과적 표상(Causal Representation)은 단순한 통계적 연관성(Statistical Association)보다 더 깊은 수준의 내부 모델링을 제공합니다. 두 사건이 자주 함께 발생한다고 예측하는 것과 개입(Intervention)이 결과를 어떻게 변화시키는지를 이해하는 것은 서로 다릅니다. 환경과 상호작용하는 에이전트는 행동을 일종의 개입으로 활용하여 학습할 수 있습니다. 이를 통해 원인, 결과, 제어 가능한 변수(Controllable Variables), 외부 사건 사이의 관계를 발견할 가능성이 생깁니다.

반사실적 추론(Counterfactual Reasoning)은 내부 시뮬레이션을 단순한 예측 이상으로 확장합니다. 에이전트는 다른 행동을 선택했다면 어떤 일이 발생했을지 또는 특정 조건이 달라졌다면 결과가 어떻게 변화했을지를 질문할 수 있습니다. 반사실적 모델(Counterfactual Models)은 실제로 실행하지 않은 대안에서도 학습할 수 있도록 하며, 관찰된 결과와 가상의 가능성을 비교함으로써 계획, 설명, 진단(Diagnosis), 의사결정을 향상시킬 수 있습니다.

계획(Planning)은 월드 모델을 사용하여 가능한 미래를 탐색합니다. 후보 행동은 물리 환경에서 즉시 실행되는 대신 내부 모델 안에서 적용될 수 있습니다. 예측된 상태는 목표, 비용, 보상, 위험, 제약 조건에 따라 평가됩니다. 이후 에이전트는 시뮬레이션된 결과가 가장 유리한 것으로 판단되는 행동을 선택할 수 있으며, 이를 통해 예측이 목적 지향적 의사결정(Purposeful Decision Making)으로 전환됩니다.

모델 기반 강화학습(Model-based Reinforcement Learning)은 이러한 개념을 학습된 행동에 적용합니다. 관찰에서 행동으로 이어지는 직접적인 매핑만 학습하는 대신 에이전트는 환경 동역학 모델(Environmental Dynamics Model)을 학습하고 이를 사용하여 행동을 평가합니다. 시뮬레이션 경험(Simulated Experience)은 실제 상호작용을 보완할 수 있으며, 효과적인 정책을 발견하기 위해 필요한 비용이 크거나 위험한 물리적 시행 횟수를 줄일 가능성이 있습니다.

상상(Imagination)은 현재 관찰되고 있지 않은 상태를 내부적으로 시뮬레이션하여 생성하는 과정으로 계산적으로 이해할 수 있습니다. 월드 모델을 통해 에이전트는 가상의 상황을 구성하고, 가능한 궤적을 미래 방향으로 전개(Roll Forward)하며, 모든 대안을 물리적으로 경험하지 않고도 결과를 평가할 수 있습니다. 이러한 능력은 예측, 계획, 창의성(Creativity), 목표 지향적 인지 사이에 중요한 연결을 형성합니다.

계층적 월드 모델(Hierarchical World Models)은 여러 추상화 수준에서 환경을 표현합니다. 저수준 모델은 즉각적인 센서 또는 움직임 변화를 예측하고, 중간 수준 모델은 객체와 국소적 상호작용(Local Interactions)을 표현하며, 상위 수준 모델은 사건, 과제, 의도, 장기적인 결과를 설명할 수 있습니다. 계층적 조직을 통해 세부적인 물리적 예측과 장기간에 걸친 효율적인 추론이 함께 이루어질 수 있습니다.

시간적 추상화(Temporal Abstraction)는 작은 물리적 변화를 하나씩 먼 미래까지 예측하는 것이 계산적으로 매우 비싸고 시간이 길어질수록 불확실성이 증가하기 때문에 특히 중요합니다. 상위 수준 모델은 대신 의미 있는 사건이나 하위 목표(Subgoals)를 중심으로 추론할 수 있습니다. 에이전트는 앞으로 몇 초 동안은 정확한 움직임을 예측하면서 이후 단계는 특정 위치 도달, 과제 완료, 객체와의 상호작용 같은 의미적 상태(Semantic States)로 표현할 수 있습니다.

내부 모델에는 에이전트 자신에 대한 모델도 포함될 수 있습니다. 자기 모델(Self-model)은 에이전트의 신체, 능력, 이용 가능한 자원, 지식, 불확실성, 목표, 한계를 표현할 수 있습니다. 로봇에서는 운동학(Kinematics), 동역학(Dynamics), 센서 구성(Sensor Configurations), 배터리 상태, 페이로드(Payload), 도달 가능성(Reachability), 손상 상태(Damage Conditions)가 포함될 수 있습니다. 효과적인 계획을 위해서는 외부 세계뿐만 아니라 에이전트 자신이 그 세계에서 실제로 무엇을 할 수 있는지도 이해해야 합니다.

다른 에이전트에 대한 모델(Models of Other Agents)은 사회적 환경 및 다중 에이전트 환경(Multi-agent Environments)에서 중요해집니다. 지능형 시스템은 다른 에이전트의 목표, 믿음, 의도, 능력 또는 향후 행동을 추정할 수 있습니다. 이러한 모델은 협력(Cooperation), 협상(Negotiation), 충돌 회피(Collision Avoidance), 인간 행동 예측, 조정된 계획(Coordinated Planning)을 가능하게 합니다. 따라서 다중 에이전트 월드 모델은 환경 예측의 범위를 서로 상호작용하는 의사결정 주체까지 확장합니다.

언어(Language)는 내부 모델에 의미적 구조(Semantic Structure)를 제공할 수 있습니다. 언어적 설명은 객체, 관계, 사건, 목표, 인과적 설명을 압축된 형태로 표현할 수 있으며, 이러한 정보 가운데 일부는 감각 신호만으로 도출하기 어려울 수 있습니다. 멀티모달 모델(Multimodal Models)은 언어를 시각적 및 물리적 관찰과 연결하여 내부 표상이 지각적 접지(Perceptual Grounding)와 추상적인 개념 지식(Abstract Conceptual Knowledge)을 함께 포함하도록 할 수 있습니다.

대규모 신경 모델(Large Neural Models)은 방대한 데이터셋으로부터 세계 표상(World Representations)을 학습하기 위한 강력한 메커니즘을 제공하지만, 예측 능력만으로 물리적 현실을 정확하게 이해한다고 보장할 수는 없습니다. 모델은 익숙하지 않은 개입이나 장기간의 예측 범위에서 실패하면서도 통계적 패턴을 재현할 수 있습니다. 따라서 신뢰할 수 있는 내부 모델을 개발하려면 관찰, 상호작용, 피드백, 물리적 제약 조건을 통한 접지(Grounding)가 여전히 중요합니다.

월드 모델은 여러 인지 기능을 위한 공유 예측 기반(Shared Predictive Substrate)을 제공하기 때문에 인지 에이전트(Cognitive Agents)에서 특히 중요합니다. 지각은 현재 상태를 업데이트하고, 기억은 관련 경험을 제공하며, 추론은 관계를 해석하고, 계획은 대안을 생성하며, 의사결정은 예측된 결과를 평가합니다. 월드 모델은 무엇이 존재하고 어떻게 변화할 수 있는지에 대한 표상을 제공함으로써 이러한 과정을 연결합니다.

피지컬 인공지능(Physical AI)에서 월드 모델은 멀티모달 지각(Multimodal Perception)을 물리 동역학(Physical Dynamics) 및 행동과 연결해야 합니다. 카메라, 라이다(LiDAR), 레이더(Radar), 촉각 센서(Tactile Sensors), 고유수용감각(Proprioception), 위치 추정 시스템(Localization Systems)은 환경과 로봇 상태에 관한 관찰을 제공합니다. 이러한 관찰을 하나의 세계 표상으로 융합하여 객체 움직임, 지형 변화, 상호작용, 충돌, 로봇 행동의 결과를 예측할 수 있습니다.

로봇 월드 모델(Robotic World Model)은 자유 공간(Free Space)과 이동 장애물을 예측하여 내비게이션(Navigation)을 지원하고, 접촉에 대한 객체의 반응을 예측하여 조작(Manipulation)을 지원하며, 행동이 의미적 상태를 어떻게 변화시키는지 추정하여 과제 계획(Task Planning)을 지원할 수 있습니다. 지각, 계획, 제어를 완전히 분리된 파이프라인으로 처리하는 대신 월드 모델은 로봇이 관찰하는 것과 앞으로 발생할 것으로 예상하는 것을 연결하는 공통의 예측 표상을 제공할 수 있습니다.

실시간 동작(Real-time Operation)을 위해서는 월드 모델이 정확성과 계산 효율성(Computational Efficiency) 사이에서 균형을 유지해야 합니다. 단기 예측은 제어와 안전을 위해 빠르게 업데이트되어야 할 수 있으며, 장기 계획은 더 느리고 추상적인 시뮬레이션을 사용할 수 있습니다. 계층적 아키텍처(Hierarchical Architectures)는 이러한 시간 척도에 계산을 분배하여 즉각적인 반응을 더 광범위한 과제 목표 및 미래의 기대와 동기화할 수 있습니다.

환경은 변화하고 학습된 가정이 더 이상 유효하지 않을 수 있기 때문에 내부 모델의 신뢰성(Reliability)은 지속적으로 평가되어야 합니다. 에이전트는 예측과 관찰을 비교하고, 불확실성을 모니터링하며, 분포 변화(Distribution Shifts)를 탐지하고, 시뮬레이션을 신뢰하기 어려운 상황을 인식해야 합니다. 이후 메타인지 메커니즘(Meta-cognitive Mechanisms)은 재계획(Replanning), 추가 정보 수집, 모델 전환 또는 보수적인 행동(Conservative Behavior)이 필요한지를 결정할 수 있습니다.

궁극적으로 내부 모델(Internal Models)과 월드 모델(World Models)은 지능적 행동을 즉각적인 반응에서 예측적 상호작용(Predictive Interaction)으로 전환합니다. 내부 상태는 현재 관찰을 넘어서는 정보를 보존하고, 학습된 표상은 환경 구조를 조직하며, 동역학 모델은 변화를 예측하고, 불확실성은 여러 가능한 미래를 표현하며, 시뮬레이션은 실제 실행 전에 행동을 평가할 수 있도록 합니다. 이러한 능력은 인지 에이전트(Cognitive Agents), 계획(Planning), 모델 기반 학습(Model-based Learning), 로보틱스(Robotics), 고급 피지컬 인공지능(Advanced Physical AI)을 위한 핵심적인 기반을 제공합니다.

##  

## 06.12 State Space and Temporal Representation [w/Code]

![](images/image13.png){width="7.268055555555556in" height="7.268055555555556in"}

![](images/image14.png){width="7.268055555555556in" height="7.268055555555556in"}

State-space representation provides a formal way to describe what an intelligent system believes about itself and its environment at a particular moment. Instead of storing every raw observation independently, cognition organizes relevant variables into a state that summarizes the current situation. This representation becomes the foundation for prediction, reasoning, planning, decision making, and control across time.

A state can contain many kinds of information depending on the task. For a robot, it may include position, orientation, velocity, nearby objects, terrain properties, battery condition, active goals, and uncertainty. For a cognitive agent, it may additionally represent beliefs, intentions, remembered events, task progress, and relationships among entities. State design therefore determines what information is available for subsequent cognition.

The state space is the collection of all states that a system can represent. Each state corresponds to one possible configuration of relevant variables, while transitions describe movement from one state to another. A simple system may have a small discrete state space, whereas realistic environments can produce enormous continuous spaces containing physical, semantic, cognitive, and social variables simultaneously.

Continuous state spaces are common in physical systems because quantities such as position, velocity, force, temperature, and time vary continuously. Discrete state spaces are useful for representing categories, task stages, symbolic conditions, or logical relationships. Cognitive and Physical AI systems often require hybrid state spaces that combine continuous physical variables with discrete semantic and task-level information.

State representations must balance completeness and efficiency. A representation containing too little information may fail to distinguish situations that require different actions, while one containing every observable detail can become computationally impractical. Useful states preserve information required for future prediction and decision making while compressing irrelevant details. Representation learning can discover compact states automatically from high-dimensional observations.

The Markov property provides an important conceptual principle for state representation. Ideally, the current state should contain enough information to predict the relevant future without requiring the entire observation history. If two situations appear identical in the current observation but have different hidden histories that affect future outcomes, the observation itself is not a sufficient state and additional memory must be incorporated.

Real environments are frequently partially observable. A robot may temporarily lose sight of an object, a sensor may provide incomplete measurements, or another agent\'s intention may remain hidden. Under partial observability, the system cannot directly know the true environmental state. It must maintain a belief state that combines current evidence, previous information, uncertainty, and learned dynamics to estimate what is likely to be true.

Belief states provide probability distributions or confidence-weighted representations over possible states rather than committing to a single interpretation. As new observations arrive, the system updates these beliefs. This allows uncertainty to persist explicitly through time and enables decisions to account for several plausible explanations of the current situation rather than assuming that perception is always complete and correct.

Temporal representation extends state representation by describing how information changes across time. A single state provides a snapshot, but intelligent behavior depends on sequences, durations, trends, events, and causal relationships. Temporal cognition therefore requires mechanisms that connect past states to the present and represent possible future states, transforming isolated observations into structured trajectories of change.

A state transition describes how a system moves from one state to another. In a passive environment, transitions may result from natural dynamics, while in an interactive system they also depend on actions. A transition model can therefore be expressed conceptually as a relationship between the current state, an action, and the next state. Learning this relationship is fundamental to predictive world models.

Sequences of state transitions form trajectories. A trajectory describes how a system or environment evolves over an interval rather than at a single instant. Navigation paths, manipulation procedures, conversations, task execution, and human activities can all be represented as trajectories through appropriate state spaces. Comparing trajectories allows an agent to evaluate alternative ways of reaching a desired state.

Time itself can be represented in several ways. Absolute time identifies when an event occurred, relative time describes ordering or separation between events, and duration describes how long a state or activity persists. Many cognitive tasks depend more strongly on relationships such as before, after, during, recently, or soon than on exact clock values, making temporal structure more important than timestamps alone.

Temporal ordering enables an agent to distinguish sequences that contain the same events but occur in different arrangements. Picking up an object before opening a container differs from performing the actions in the opposite order. Correct ordering is essential for procedural reasoning, causal inference, planning, language comprehension, and task execution because many outcomes depend on the sequence in which conditions and actions occur.

Duration also carries important information. Two states that contain similar variables may have different meanings depending on how long they persist. A temporary obstacle may require waiting, while a persistent blockage may require replanning. Temporal representations that encode duration allow agents to distinguish transient conditions from stable changes and to choose behavior according to how environmental conditions evolve.

Event representations provide a higher-level abstraction over continuous state change. Instead of describing every intermediate sensor value, an agent can represent meaningful transitions such as an object appearing, a door opening, a robot reaching a destination, or a task being completed. Events compress long streams of low-level information into structures that are easier to use for reasoning, memory, and planning.

Temporal abstraction allows cognition to operate simultaneously at multiple timescales. Low-level control may reason in milliseconds, perception and tracking across fractions of a second, local planning over seconds, task planning over minutes, and mission reasoning over much longer periods. Representing every cognitive process at the same temporal resolution would be inefficient and often unnecessary.

Hierarchical temporal representation addresses this problem by organizing states and events across multiple levels. Fine-grained states describe immediate physical changes, intermediate representations describe actions and interactions, and higher-level representations describe tasks, goals, or episodes. Information can move between these levels so that detailed control remains coordinated with long-term objectives.

Memory provides access to states that are no longer directly observable. Working memory preserves information relevant to the current task, while episodic memory can store sequences of previous states and events. Retrieved memories can provide historical context when the current state is ambiguous. Temporal representation therefore connects perception with memory by maintaining continuity across observations separated in time.

Recurrent neural networks introduced an important computational mechanism for representing temporal dependencies. Their hidden state summarizes information accumulated from previous inputs and influences processing of the current input. Long short-term memory and gated recurrent architectures improve the ability to preserve information over extended sequences, making them useful for temporal signals, behavior sequences, and dynamic environments.

Transformers provide another approach by using attention to relate information across different positions in a sequence. Instead of compressing the entire past into a single recurrent state, attention mechanisms can selectively access relevant previous representations. Positional and temporal encodings provide information about ordering, allowing the model to distinguish identical observations appearing at different points in a sequence.

Modern temporal models can combine recurrence, attention, memory, and learned latent dynamics. The appropriate architecture depends on the temporal horizon, computational constraints, and structure of the task. Short-horizon control may require compact rapidly updated states, while long-horizon reasoning may benefit from explicit memory and selective retrieval rather than continuously processing the entire historical sequence.

Temporal prediction uses previous and current states to estimate what may happen next. A model may predict a single next state, several future states, or a distribution over possible trajectories. Short-term prediction is often more precise, whereas uncertainty typically increases with prediction horizon. Long-horizon prediction therefore benefits from representing multiple alternatives rather than assuming one deterministic future.

Multi-step prediction introduces the problem of accumulated error. Small inaccuracies in an early predicted state can affect later predictions, causing simulated trajectories to drift away from reality. World models must therefore learn robust representations, estimate uncertainty, periodically incorporate new observations, and replan when predictions diverge significantly from actual environmental evolution.

Hierarchical prediction can reduce some difficulties of long horizons. Instead of predicting every low-level state far into the future, a model can predict detailed dynamics over short intervals and higher-level events over longer periods. For example, a robot may estimate exact trajectories for the next few seconds while predicting later outcomes as semantic events such as reaching a waypoint or completing an operation.

Temporal representation is closely connected with causality. Temporal order alone does not establish causal relationships, but causes must generally precede their effects. By observing transitions and interventions across repeated experiences, an agent can learn which changes reliably influence later states. Actions provide particularly valuable information because they allow the system to test how deliberate interventions alter future outcomes.

Planning can be interpreted as search through a state space over time. The agent begins from an estimated current state, considers available actions, predicts resulting transitions, and evaluates candidate future states according to goals and constraints. A plan is therefore a temporally organized path through possible states, connecting present conditions to desired future configurations.

Goals themselves can be represented as desired regions of state space rather than single exact states. A navigation goal may allow several acceptable positions, while a manipulation goal may require an object to satisfy particular semantic relationships. This flexibility allows planning to search for multiple valid trajectories and select one according to efficiency, safety, uncertainty, or other criteria.

Physical AI requires especially rich state representations because embodied systems must integrate many asynchronous information streams. Cameras, LiDAR, radar, IMU, GNSS, tactile sensors, proprioception, maps, language instructions, and task information may update at different rates. The system must synchronize and fuse these observations into a temporally coherent representation of the robot and its environment.

For mobile robots, state may include pose, velocity, acceleration, free space, obstacles, terrain, nearby agents, planned paths, and localization uncertainty. Temporal information distinguishes stationary structures from moving objects and enables estimation of velocity and future trajectories. Without temporal representation, perception provides only isolated scenes and cannot reliably support prediction of dynamic interactions.

Manipulation introduces additional temporal structure involving contact, force, object motion, grasp state, and sequential task constraints. The same visual scene can require different actions depending on whether an object has already been grasped, moved, released, or inspected. Internal state must therefore preserve task history and interaction status that may not be directly visible in the current sensory observation.

State-space models also provide a bridge between classical control and modern AI. Control theory has long represented dynamical systems using states and transition equations, while machine learning can learn states and transitions directly from complex data. Combining these perspectives allows Physical AI systems to integrate established principles of estimation and control with neural representation learning and predictive world models.

Ultimately, state-space and temporal representation provide the structural foundation for intelligence that operates through time. State summarizes what is currently believed, memory preserves relevant history, transition models describe change, temporal structures organize sequences and events, and prediction extends cognition toward possible futures. Together they enable world models, cognitive agents, planning, autonomous robotics, and Physical AI to transform continuous experience into coherent goal-directed behavior.

상태 공간 표상(State-space Representation)은 지능형 시스템(Intelligent System)이 특정 시점에서 자기 자신과 환경에 대해 무엇을 믿고 있는지를 형식적으로 기술하는 방법을 제공합니다. 모든 원시 관찰(Raw Observations)을 개별적으로 저장하는 대신 인지는 관련 변수들을 현재 상황을 요약하는 하나의 상태(State)로 구성합니다. 이러한 표상은 시간의 흐름에 따른 예측(Prediction), 추론(Reasoning), 계획(Planning), 의사결정(Decision Making), 제어(Control)의 기반이 됩니다.

상태(State)는 과제에 따라 다양한 종류의 정보를 포함할 수 있습니다. 로봇의 경우 위치(Position), 방향(Orientation), 속도(Velocity), 주변 객체, 지형 속성(Terrain Properties), 배터리 상태, 활성 목표(Active Goals), 불확실성(Uncertainty)을 포함할 수 있습니다. 인지 에이전트(Cognitive Agent)의 경우에는 믿음(Beliefs), 의도(Intentions), 기억된 사건, 과제 진행 상태(Task Progress), 개체 사이의 관계도 추가로 표현할 수 있습니다. 따라서 상태 설계(State Design)는 이후의 인지 과정에서 어떤 정보를 사용할 수 있는지를 결정합니다.

상태 공간(State Space)은 시스템이 표현할 수 있는 모든 상태의 집합입니다. 각각의 상태는 관련 변수들이 가질 수 있는 하나의 가능한 구성(Configuration)에 대응하며, 전이(Transitions)는 한 상태에서 다른 상태로 이동하는 과정을 설명합니다. 단순한 시스템은 작은 이산 상태 공간(Discrete State Space)을 가질 수 있지만, 현실적인 환경에서는 물리적, 의미적, 인지적, 사회적 변수를 동시에 포함하는 거대한 연속 상태 공간(Continuous State Space)이 형성될 수 있습니다.

위치, 속도, 힘, 온도, 시간과 같은 물리량은 연속적으로 변화하기 때문에 물리 시스템에서는 연속 상태 공간(Continuous State Spaces)이 일반적입니다. 이산 상태 공간(Discrete State Spaces)은 범주, 과제 단계(Task Stages), 기호적 조건(Symbolic Conditions), 논리적 관계(Logical Relationships)를 표현하는 데 유용합니다. 인지 및 피지컬 인공지능(Physical AI) 시스템은 연속적인 물리 변수와 이산적인 의미 및 과제 수준 정보를 결합하는 하이브리드 상태 공간(Hybrid State Spaces)을 필요로 하는 경우가 많습니다.

상태 표상(State Representations)은 완전성과 효율성 사이에서 균형을 유지해야 합니다. 너무 적은 정보를 포함하는 표상은 서로 다른 행동이 필요한 상황을 구별하지 못할 수 있으며, 관찰 가능한 모든 세부 정보를 포함하는 표상은 계산적으로 비현실적일 수 있습니다. 유용한 상태는 미래 예측과 의사결정에 필요한 정보를 보존하면서 관련성이 낮은 세부 사항을 압축합니다. 표상 학습(Representation Learning)은 고차원 관찰(High-dimensional Observations)에서 이러한 압축된 상태를 자동으로 발견할 수 있습니다.

마르코프 속성(Markov Property)은 상태 표상을 위한 중요한 개념적 원리를 제공합니다. 이상적으로 현재 상태는 전체 관찰 이력(Observation History)을 요구하지 않고도 관련된 미래를 예측할 수 있을 만큼 충분한 정보를 포함해야 합니다. 현재 관찰에서는 동일하게 보이는 두 상황이라도 미래 결과에 영향을 주는 서로 다른 숨겨진 이력(Hidden Histories)을 가지고 있다면 관찰 자체만으로는 충분한 상태가 아니며 추가적인 기억(Memory)을 포함해야 합니다.

실제 환경은 부분 관찰 가능(Partially Observable)한 경우가 많습니다. 로봇이 일시적으로 객체를 시야에서 놓칠 수 있고, 센서가 불완전한 측정값을 제공할 수도 있으며, 다른 에이전트의 의도(Intentions)가 숨겨져 있을 수도 있습니다. 부분 관찰 상황에서는 시스템이 실제 환경 상태(True Environmental State)를 직접 알 수 없습니다. 따라서 현재 증거, 이전 정보, 불확실성, 학습된 동역학(Learned Dynamics)을 결합하는 믿음 상태(Belief State)를 유지하여 무엇이 사실일 가능성이 높은지를 추정해야 합니다.

믿음 상태(Belief States)는 하나의 해석에 확정적으로 의존하는 대신 가능한 여러 상태에 대한 확률 분포(Probability Distributions) 또는 신뢰도 가중 표상(Confidence-weighted Representations)을 제공합니다. 새로운 관찰이 입력되면 시스템은 이러한 믿음을 업데이트합니다. 이를 통해 불확실성이 시간에 따라 명시적으로 유지될 수 있으며, 지각이 항상 완전하고 정확하다고 가정하지 않고 현재 상황에 대한 여러 가능한 설명을 고려하여 의사결정을 수행할 수 있습니다.

시간적 표상(Temporal Representation)은 정보가 시간에 따라 어떻게 변화하는지를 기술함으로써 상태 표상을 확장합니다. 하나의 상태는 특정 순간의 스냅샷(Snapshot)을 제공하지만 지능적인 행동은 시퀀스(Sequences), 지속 시간(Durations), 추세(Trends), 사건(Events), 인과 관계(Causal Relationships)에 의존합니다. 따라서 시간적 인지는 과거 상태를 현재와 연결하고 가능한 미래 상태를 표현하여 서로 분리된 관찰을 구조화된 변화의 궤적(Trajectories)으로 변환하는 메커니즘을 필요로 합니다.

상태 전이(State Transition)는 시스템이 하나의 상태에서 다른 상태로 어떻게 이동하는지를 설명합니다. 수동적인 환경에서는 자연적인 동역학(Natural Dynamics)에 의해 전이가 발생할 수 있으며, 상호작용 시스템에서는 행동(Action)의 영향도 받습니다. 따라서 전이 모델(Transition Model)은 개념적으로 현재 상태, 행동, 다음 상태 사이의 관계로 표현할 수 있습니다. 이러한 관계를 학습하는 것은 예측적 월드 모델(Predictive World Models)의 핵심입니다.

상태 전이의 연속은 궤적(Trajectory)을 형성합니다. 궤적은 시스템이나 환경이 단일 순간이 아니라 일정한 시간 구간에 걸쳐 어떻게 변화하는지를 설명합니다. 내비게이션 경로(Navigation Paths), 조작 절차(Manipulation Procedures), 대화, 과제 실행(Task Execution), 인간 활동은 모두 적절한 상태 공간을 통해 궤적으로 표현될 수 있습니다. 여러 궤적을 비교하면 에이전트가 원하는 상태에 도달하기 위한 다양한 방법을 평가할 수 있습니다.

시간(Time) 자체도 여러 방식으로 표현될 수 있습니다. 절대 시간(Absolute Time)은 사건이 언제 발생했는지를 나타내고, 상대 시간(Relative Time)은 사건 사이의 순서나 시간적 간격을 설명하며, 지속 시간(Duration)은 상태나 활동이 얼마나 오래 유지되는지를 나타냅니다. 많은 인지 과제는 정확한 시계 값보다 이전(Before), 이후(After), 진행 중(During), 최근(Recently), 곧(Soon)과 같은 관계에 더 크게 의존하기 때문에 단순한 타임스탬프(Timestamps)보다 시간적 구조(Temporal Structure)가 중요할 수 있습니다.

시간적 순서(Temporal Ordering)는 동일한 사건을 포함하더라도 서로 다른 순서로 발생하는 시퀀스를 에이전트가 구별할 수 있도록 합니다. 객체를 집어 든 다음 컨테이너를 여는 것과 반대 순서로 행동하는 것은 서로 다른 결과를 만들 수 있습니다. 올바른 순서는 절차적 추론(Procedural Reasoning), 인과 추론(Causal Inference), 계획, 언어 이해(Language Comprehension), 과제 실행에서 필수적이며, 많은 결과가 조건과 행동이 발생하는 순서에 의존합니다.

지속 시간(Duration) 역시 중요한 정보를 전달합니다. 유사한 변수를 포함하는 두 상태도 얼마나 오래 지속되는지에 따라 서로 다른 의미를 가질 수 있습니다. 일시적인 장애물(Temporary Obstacle)은 기다리는 것으로 해결할 수 있지만 지속적인 통행 차단(Persistent Blockage)은 재계획(Replanning)을 요구할 수 있습니다. 지속 시간을 인코딩하는 시간적 표상은 에이전트가 일시적인 조건과 안정적인 변화를 구분하고 환경 조건이 어떻게 변화하는지에 따라 행동을 선택할 수 있도록 합니다.

사건 표상(Event Representations)은 연속적인 상태 변화에 대해 더 높은 수준의 추상화(Higher-level Abstraction)를 제공합니다. 모든 중간 센서 값을 기술하는 대신 에이전트는 객체의 출현, 문이 열리는 상황, 로봇의 목적지 도달, 과제 완료와 같은 의미 있는 전이를 표현할 수 있습니다. 사건은 긴 저수준 정보 스트림(Low-level Information Streams)을 추론, 기억, 계획에서 더욱 쉽게 사용할 수 있는 구조로 압축합니다.

시간적 추상화(Temporal Abstraction)는 인지가 여러 시간 척도(Timescales)에서 동시에 작동할 수 있도록 합니다. 저수준 제어(Low-level Control)는 밀리초 단위로 추론할 수 있고, 지각과 추적(Tracking)은 수십 분의 일초 단위에서, 지역 계획(Local Planning)은 수초 단위에서, 과제 계획(Task Planning)은 수분 단위에서, 임무 추론(Mission Reasoning)은 훨씬 긴 시간 범위에서 작동할 수 있습니다. 모든 인지 과정을 동일한 시간 해상도(Temporal Resolution)로 표현하는 것은 비효율적이며 대부분 불필요합니다.

계층적 시간 표상(Hierarchical Temporal Representation)은 상태와 사건을 여러 수준으로 구성하여 이러한 문제를 해결합니다. 세밀한 상태(Fine-grained States)는 즉각적인 물리 변화를 설명하고, 중간 수준의 표상은 행동과 상호작용을 설명하며, 상위 수준의 표상은 과제, 목표, 에피소드(Episodes)를 설명합니다. 이러한 수준 사이에서 정보가 이동함으로써 세부적인 제어가 장기적인 목표와 지속적으로 조정될 수 있습니다.

기억(Memory)은 더 이상 직접 관찰할 수 없는 상태에 접근할 수 있도록 합니다. 작업 기억(Working Memory)은 현재 과제와 관련된 정보를 보존하며, 일화 기억(Episodic Memory)은 이전 상태와 사건의 시퀀스를 저장할 수 있습니다. 검색된 기억은 현재 상태가 모호할 때 역사적 문맥(Historical Context)을 제공합니다. 따라서 시간적 표상은 시간적으로 분리된 관찰 사이의 연속성을 유지함으로써 지각과 기억을 연결합니다.

순환 신경망(Recurrent Neural Networks)은 시간적 의존성(Temporal Dependencies)을 표현하기 위한 중요한 계산 메커니즘을 도입했습니다. 은닉 상태(Hidden State)는 이전 입력에서 축적된 정보를 요약하고 현재 입력의 처리에 영향을 줍니다. 장단기 기억(Long Short-term Memory)과 게이트 순환 아키텍처(Gated Recurrent Architectures)는 긴 시퀀스에서도 정보를 보존하는 능력을 향상시켜 시간 신호, 행동 시퀀스, 동적 환경(Dynamic Environments)을 처리하는 데 유용합니다.

트랜스포머(Transformers)는 어텐션(Attention)을 사용하여 시퀀스의 서로 다른 위치에 존재하는 정보를 연결하는 또 다른 접근 방식을 제공합니다. 전체 과거를 하나의 순환 상태(Recurrent State)에 압축하는 대신 어텐션 메커니즘은 관련된 이전 표상에 선택적으로 접근할 수 있습니다. 위치 인코딩(Positional Encodings)과 시간 인코딩(Temporal Encodings)은 순서에 관한 정보를 제공하여 동일한 관찰이 시퀀스의 서로 다른 지점에 나타나는 경우를 모델이 구별할 수 있도록 합니다.

현대의 시간 모델(Temporal Models)은 순환(Reccurence), 어텐션, 기억, 학습된 잠재 동역학(Learned Latent Dynamics)을 결합할 수 있습니다. 적절한 아키텍처는 시간 범위(Temporal Horizon), 계산 제약 조건(Computational Constraints), 과제의 구조에 따라 달라집니다. 단기 제어에는 빠르게 업데이트되는 압축된 상태가 필요할 수 있으며, 장기 추론에는 전체 과거 시퀀스를 지속적으로 처리하는 대신 명시적 기억과 선택적 검색(Selective Retrieval)이 더 효과적일 수 있습니다.

시간적 예측(Temporal Prediction)은 이전 상태와 현재 상태를 사용하여 다음에 발생할 수 있는 상황을 추정합니다. 모델은 하나의 다음 상태, 여러 미래 상태 또는 가능한 궤적에 대한 확률 분포를 예측할 수 있습니다. 단기 예측(Short-term Prediction)은 일반적으로 더 정확하지만 예측 범위가 길어질수록 불확실성이 증가합니다. 따라서 장기 예측(Long-horizon Prediction)은 하나의 결정론적 미래를 가정하기보다 여러 대안을 표현함으로써 이점을 얻을 수 있습니다.

다단계 예측(Multi-step Prediction)은 누적 오류(Accumulated Error)의 문제를 발생시킵니다. 초기 예측 상태에서 발생한 작은 부정확성이 이후의 예측에 영향을 주어 시뮬레이션된 궤적이 현실에서 점차 벗어날 수 있습니다. 따라서 월드 모델(World Models)은 견고한 표상을 학습하고, 불확실성을 추정하며, 새로운 관찰을 주기적으로 반영하고, 예측이 실제 환경의 변화와 크게 달라질 경우 재계획해야 합니다.

계층적 예측(Hierarchical Prediction)은 장기 예측의 일부 어려움을 줄일 수 있습니다. 먼 미래까지 모든 저수준 상태를 예측하는 대신 모델은 짧은 구간에서는 세부적인 동역학을 예측하고 긴 시간 범위에서는 상위 수준의 사건을 예측할 수 있습니다. 예를 들어 로봇은 앞으로 몇 초 동안의 정확한 궤적을 추정하면서 그 이후의 결과는 웨이포인트(Waypoint) 도달이나 작업 완료와 같은 의미적 사건(Semantic Events)으로 예측할 수 있습니다.

시간적 표상은 인과성(Causality)과 밀접하게 연결됩니다. 시간적 순서 자체만으로 인과 관계를 증명할 수는 없지만 일반적으로 원인은 결과보다 먼저 발생해야 합니다. 에이전트는 반복적인 경험에서 전이와 개입(Interventions)을 관찰함으로써 어떤 변화가 이후 상태에 안정적으로 영향을 미치는지를 학습할 수 있습니다. 행동은 의도적인 개입이 미래 결과를 어떻게 변화시키는지 시험할 수 있기 때문에 특히 중요한 정보를 제공합니다.

계획(Planning)은 시간에 따른 상태 공간 탐색(Search through a State Space)으로 해석할 수 있습니다. 에이전트는 추정된 현재 상태에서 시작하여 이용 가능한 행동을 고려하고, 그 결과로 발생하는 전이를 예측하며, 목표와 제약 조건에 따라 후보 미래 상태를 평가합니다. 따라서 계획은 현재 조건을 원하는 미래 구성과 연결하는 가능한 상태들을 통과하는 시간적으로 조직된 경로입니다.

목표(Goals) 자체도 하나의 정확한 상태가 아니라 상태 공간의 원하는 영역(Desired Regions of State Space)으로 표현할 수 있습니다. 내비게이션 목표는 여러 허용 가능한 위치를 포함할 수 있으며, 조작 목표(Manipulation Goal)는 객체가 특정한 의미적 관계를 만족하도록 요구할 수 있습니다. 이러한 유연성을 통해 계획은 여러 유효한 궤적을 탐색하고 효율성, 안전성, 불확실성 또는 기타 기준에 따라 하나를 선택할 수 있습니다.

피지컬 인공지능(Physical AI)은 체화된 시스템이 비동기적인 여러 정보 스트림(Asynchronous Information Streams)을 통합해야 하기 때문에 특히 풍부한 상태 표상을 필요로 합니다. 카메라, 라이다(LiDAR), 레이더(Radar), 관성 측정 장치(IMU), 위성항법시스템(GNSS), 촉각 센서, 고유수용감각(Proprioception), 지도, 언어 명령, 과제 정보는 서로 다른 속도로 업데이트될 수 있습니다. 시스템은 이러한 관찰을 동기화하고 융합하여 로봇과 환경에 대한 시간적으로 일관된 표상을 구성해야 합니다.

이동 로봇(Mobile Robots)의 상태에는 자세(Pose), 속도, 가속도, 자유 공간(Free Space), 장애물, 지형, 주변 에이전트, 계획된 경로, 위치 추정 불확실성(Localization Uncertainty)이 포함될 수 있습니다. 시간 정보는 고정된 구조물과 이동 객체를 구별하고 속도 및 미래 궤적을 추정할 수 있도록 합니다. 시간적 표상이 없다면 지각은 서로 분리된 장면만을 제공하며 동적인 상호작용을 신뢰성 있게 예측하기 어렵습니다.

조작(Manipulation)은 접촉(Contact), 힘(Force), 객체 움직임, 파지 상태(Grasp State), 순차적 과제 제약 조건(Sequential Task Constraints)과 관련된 추가적인 시간 구조를 필요로 합니다. 동일한 시각적 장면이라도 객체가 이미 파지되었는지, 이동되었는지, 놓였는지 또는 검사되었는지에 따라 서로 다른 행동이 필요할 수 있습니다. 따라서 내부 상태는 현재 감각 관찰에서 직접 보이지 않을 수 있는 과제 이력(Task History)과 상호작용 상태(Interaction Status)를 보존해야 합니다.

상태 공간 모델(State-space Models)은 고전 제어(Classical Control)와 현대 인공지능(Modern AI)을 연결하는 가교 역할도 합니다. 제어 이론(Control Theory)은 오랫동안 상태와 전이 방정식(Transition Equations)을 사용하여 동적 시스템을 표현해 왔으며, 머신러닝(Machine Learning)은 복잡한 데이터로부터 상태와 전이를 직접 학습할 수 있습니다. 이러한 관점을 결합하면 피지컬 인공지능 시스템은 검증된 상태 추정 및 제어 원리와 신경 표상 학습(Neural Representation Learning), 예측적 월드 모델을 통합할 수 있습니다.

궁극적으로 상태 공간 및 시간적 표상(State-space and Temporal Representation)은 시간의 흐름 속에서 작동하는 지능을 위한 구조적 기반을 제공합니다. 상태는 현재 무엇을 믿고 있는지를 요약하고, 기억은 관련된 과거를 보존하며, 전이 모델은 변화를 설명하고, 시간적 구조는 시퀀스와 사건을 조직하며, 예측은 인지를 가능한 미래로 확장합니다. 이들을 결합하면 월드 모델(World Models), 인지 에이전트(Cognitive Agents), 계획, 자율 로보틱스(Autonomous Robotics), 피지컬 인공지능이 지속적인 경험을 일관된 목표 지향적 행동(Coherent Goal-directed Behavior)으로 변환할 수 있습니다.

##  

## 06.13 Sensorimotor Cognitive Loops [w/Code]

![](images/image15.png){width="7.268055555555556in" height="7.268055555555556in"}

Sensorimotor cognitive loops describe intelligence as a continuous interaction between sensing, internal processing, and physical action. An embodied agent does not simply perceive the environment and then produce an isolated response. Its actions modify the world, body, or viewpoint, producing new sensory information that influences the next decision. Cognition therefore develops within a recurrent perception--action cycle.

The sensorimotor perspective emphasizes that perception and action are deeply interdependent. Visual, auditory, tactile, proprioceptive, vestibular, and other sensory signals provide information about both the environment and the agent\'s body. Motor commands then change physical relationships between the agent and its surroundings. Every movement consequently creates new observations and changes the information available for subsequent cognition.

A basic sensorimotor loop begins when sensors observe the current environment and body state. Perceptual processes transform these signals into useful representations, cognitive mechanisms interpret the situation, and action-selection systems determine an appropriate response. Motor controllers execute the selected action, changing the physical state. Sensors then measure the resulting conditions, closing the loop through continuous feedback.

Feedback distinguishes sensorimotor cognition from open-loop behavior. In an open-loop system, an action sequence may execute without continuously considering its consequences. Closed-loop systems repeatedly compare expected and observed results and modify behavior when necessary. This feedback enables correction of disturbances, adaptation to uncertainty, compensation for modeling errors, and robust interaction with environments that cannot be perfectly predicted.

Proprioception provides information about the agent\'s own physical configuration and motion. In humans it contributes information about joint position, muscle state, and movement, while robots obtain related information from joint encoders, motor currents, inertial sensors, and other internal measurements. Proprioceptive information allows cognition to distinguish changes in the external environment from changes produced by the agent\'s own movement.

Exteroception provides information about the external world through modalities such as vision, hearing, touch, LiDAR, radar, or proximity sensing. Combining exteroceptive and proprioceptive information enables an embodied agent to estimate relationships between itself and surrounding objects. Sensor fusion therefore supports a unified state representation connecting environmental structure with body configuration, motion, and potential interaction.

Internal state estimation becomes necessary because sensor measurements are incomplete and noisy. A cognitive system combines current observations with previous estimates and models of expected change to infer the most likely present state. This estimated state may contain body pose, object locations, velocities, contacts, task conditions, uncertainty, and other variables required for selecting and controlling actions.

Motor commands transform cognitive decisions into physical change. High-level cognition may specify an objective such as reaching an object, while intermediate processes generate trajectories and low-level controllers produce actuator commands. Sensorimotor architectures therefore connect multiple levels of abstraction, translating semantic goals into increasingly concrete actions while feedback continuously reports whether execution is progressing as expected.

Forward models predict the sensory or physical consequences of actions. Given the current state and a motor command, a forward model estimates what the next state or observation should be. The prediction can be compared with actual sensory feedback after the action occurs. Differences between expected and observed outcomes provide information for correction, learning, anomaly detection, and adaptation.

Inverse models address the complementary problem of determining which action can produce a desired change. Given a current state and target state, an inverse model estimates an appropriate motor command or action sequence. Sensorimotor control can combine inverse models for generating actions with forward models for predicting their consequences, creating a powerful mechanism for goal-directed physical interaction.

Prediction error plays a central role in closed-loop cognition. When predicted sensory consequences differ from observations, the system must determine whether the difference results from external disturbance, inaccurate perception, incorrect dynamics, or execution error. The discrepancy can trigger immediate control correction or longer-term model learning. Repeated prediction and correction progressively improve the agent\'s sensorimotor competence.

Sensorimotor contingencies describe systematic relationships between actions and changes in sensory input. Moving the head changes visual perspective, touching an object produces characteristic tactile signals, and moving toward a sound modifies its spatial properties. By learning these regularities, an agent develops knowledge about how its actions transform perception, grounding environmental understanding in interactive experience.

Active perception follows naturally from this principle. An agent does not need to treat sensing as a passive process because actions can be selected specifically to obtain better information. A robot may move its camera to resolve an occluded object, approach a surface for inspection, or reposition itself to improve localization. Action therefore serves both physical goals and information-gathering objectives.

Attention can also participate in sensorimotor loops by allocating sensing and computation according to current goals. Instead of processing every signal with equal priority, the agent can focus resources on task-relevant regions, objects, modalities, or unexpected events. Actions may subsequently change the sensory viewpoint, producing a coordinated cycle between attention, perception, movement, and renewed attention.

Affordances connect perception directly with possible actions. Rather than representing an object only through its appearance or category, an embodied system can represent what interactions the object permits, such as grasping, pushing, traversing, opening, or avoiding. Affordance representations are relational because possible actions depend on both environmental properties and the physical capabilities of the agent.

Embodied cognition extends this relationship by proposing that intelligent representations are strongly influenced by the body\'s ability to interact with the world. Concepts such as distance, reachability, support, collision, force, and containment have direct sensorimotor significance. Physical interaction provides grounding that connects abstract representations with measurable consequences of actions in real environments.

Temporal continuity is essential because sensorimotor interaction unfolds as sequences rather than isolated observations. The agent must connect previous actions with subsequent sensory effects and distinguish delayed consequences from unrelated events. Working memory, recurrent states, attention mechanisms, and temporal models can preserve relevant history so that cognition can interpret ongoing interactions coherently.

Sensorimotor learning emerges through repeated experience with these temporal relationships. The agent observes states, performs actions, measures consequences, and gradually learns mappings among perception, action, and environmental change. Supervised, self-supervised, imitation, and reinforcement learning can contribute different forms of knowledge, while prediction errors provide naturally occurring learning signals during continuous interaction.

Self-supervised learning is particularly compatible with sensorimotor loops because physical interaction continuously generates structured training data. Current observations and actions provide context, while later observations provide targets for prediction. An embodied system can therefore learn motion, object persistence, contact effects, spatial relationships, and action consequences without requiring explicit human labels for every interaction.

Reinforcement learning adds goal-directed evaluation to the loop. Actions produce both environmental transitions and rewards or costs that indicate whether behavior supports an objective. The agent can improve its policy by relating actions and states to long-term outcomes. When combined with a learned world model, reinforcement learning can also evaluate simulated sensorimotor experiences before executing actions physically.

Hierarchical control is necessary because sensorimotor cognition operates across several timescales. Motor stabilization may require millisecond-level feedback, trajectory control may operate over fractions of seconds, local actions may unfold across seconds, and task reasoning may span minutes or longer. Higher levels establish goals and constraints while lower levels continuously adapt execution to rapidly changing sensory feedback.

Reflexive behavior represents the fastest layer of sensorimotor control. Some situations require responses before extensive deliberation is possible, such as maintaining balance, avoiding imminent collision, or limiting excessive force. These fast loops can operate alongside slower cognitive processes. Deliberative mechanisms can establish broader objectives while reflexive mechanisms preserve stability and safety during execution.

Dual-process organization can therefore be observed within embodied control. Fast pathways handle familiar or urgent sensorimotor patterns through learned policies and control laws, whereas slower pathways support planning, uncertainty analysis, simulation, and problem solving. A capable cognitive system can shift computational resources toward deliberation when routine sensorimotor behavior becomes unreliable or encounters unfamiliar conditions.

World models extend sensorimotor loops by allowing consequences to be evaluated internally before physical execution. The model receives a representation of the current state and candidate action and predicts possible future states. Planning can compare these simulated trajectories and select promising actions. Real sensory feedback subsequently determines whether the prediction was accurate and updates the model when necessary.

This produces an interaction between real and imagined sensorimotor loops. Real loops generate observations through physical actions, whereas imagined loops generate predicted observations through internal simulation. Planning can execute many hypothetical actions within a world model before selecting one for reality. Physical experience then provides grounding and correction, preventing internal simulation from becoming disconnected from actual environmental dynamics.

Manipulation provides a clear example of sensorimotor cognition. A robot observes an object, estimates its pose, selects a grasp, approaches it, detects contact, regulates force, lifts the object, and monitors whether the grasp remains stable. Each stage changes both the physical state and available sensory information. Successful manipulation therefore depends on continuous feedback rather than a single perception followed by a fixed motion sequence.

Mobile robotics demonstrates the same principle at larger spatial scales. Cameras, LiDAR, radar, IMU, GNSS, wheel encoders, and other sensors continuously estimate robot motion and environmental structure. Navigation generates actions that change the robot\'s position and viewpoint, producing new observations. Localization, mapping, obstacle prediction, planning, and control consequently operate as interconnected sensorimotor loops.

Unexpected environmental changes reveal why these loops are essential. A planned trajectory may become invalid when a person enters the path, an object moves, terrain changes, or localization confidence decreases. Continuous sensing detects the discrepancy, state estimation updates the internal representation, planning revises the intended behavior, and control executes the new action. Autonomy emerges through repeated correction rather than fixed execution.

Human--robot interaction introduces additional feedback because human behavior responds to robot behavior. A robot\'s motion, speech, or gesture changes the human\'s subsequent actions, which become new observations for the robot. The sensorimotor loop therefore extends across multiple interacting agents. Effective behavior requires prediction not only of physical dynamics but also of socially responsive actions and intentions.

Safety must remain integrated throughout the sensorimotor loop. Independent monitoring can enforce limits on velocity, force, proximity, stability, and uncertainty even when higher-level predictions are incorrect. When observations indicate dangerous divergence from expected behavior, safety mechanisms can interrupt planned actions and initiate fallback responses. Reliable Physical AI therefore requires feedback at both cognitive and safety-control levels.

Meta-cognition can supervise these loops by evaluating whether perception, prediction, and action are functioning reliably. Persistent prediction errors may indicate sensor failure, model mismatch, unfamiliar terrain, or an inappropriate strategy. The system can respond by gathering additional observations, slowing movement, switching control modes, replanning, or requesting assistance rather than continuing with unjustified confidence.

Ultimately, sensorimotor cognitive loops transform intelligence into an ongoing process of perceiving, predicting, acting, observing consequences, and adapting. Sensory signals ground internal representations, forward models predict consequences, inverse models support action generation, feedback corrects behavior, and learning improves future interaction. Their integration forms a fundamental mechanism for embodied cognition, autonomous robotics, cognitive agents, and advanced Physical AI.

감각운동 인지 루프(Sensorimotor Cognitive Loops)는 지능을 감각(Sensing), 내부 처리(Internal Processing), 물리적 행동(Physical Action) 사이의 지속적인 상호작용으로 설명합니다. 체화된 에이전트(Embodied Agent)는 단순히 환경을 지각한 뒤 하나의 독립된 반응을 생성하는 것이 아닙니다. 에이전트의 행동은 세계, 신체 또는 관찰 시점을 변화시키고, 그 결과 새로운 감각 정보가 생성되어 다음 의사결정에 영향을 줍니다. 따라서 인지는 반복적인 지각--행동 순환(Perception--Action Cycle) 안에서 발달합니다.

감각운동 관점(Sensorimotor Perspective)은 지각(Perception)과 행동(Action)이 서로 깊게 의존한다는 점을 강조합니다. 시각(Visual), 청각(Auditory), 촉각(Tactile), 고유수용감각(Proprioceptive), 전정감각(Vestibular) 등의 감각 신호는 환경과 에이전트의 신체 모두에 대한 정보를 제공합니다. 이후 운동 명령(Motor Commands)은 에이전트와 주변 환경 사이의 물리적 관계를 변화시킵니다. 따라서 모든 움직임은 새로운 관찰을 생성하고 이후의 인지 과정에서 사용할 수 있는 정보를 변화시킵니다.

기본적인 감각운동 루프(Sensorimotor Loop)는 센서가 현재 환경과 신체 상태를 관찰하면서 시작됩니다. 지각 과정은 이러한 신호를 유용한 표상(Representations)으로 변환하고, 인지 메커니즘(Cognitive Mechanisms)은 상황을 해석하며, 행동 선택 시스템(Action-selection Systems)은 적절한 반응을 결정합니다. 운동 제어기(Motor Controllers)는 선택된 행동을 실행하여 물리적 상태를 변화시키고, 센서는 다시 그 결과를 측정하면서 지속적인 피드백(Feedback)을 통해 루프를 닫습니다.

피드백(Feedback)은 감각운동 인지를 개방 루프 행동(Open-loop Behavior)과 구별합니다. 개방 루프 시스템에서는 행동 시퀀스가 그 결과를 지속적으로 고려하지 않고 실행될 수 있습니다. 폐쇄 루프 시스템(Closed-loop Systems)은 예상 결과와 관찰 결과를 반복적으로 비교하고 필요하면 행동을 수정합니다. 이러한 피드백은 외란(Disturbances)의 보정, 불확실성에 대한 적응, 모델링 오류의 보상, 완벽하게 예측할 수 없는 환경과의 견고한 상호작용을 가능하게 합니다.

고유수용감각(Proprioception)은 에이전트 자신의 물리적 구성과 움직임에 관한 정보를 제공합니다. 인간에서는 관절 위치, 근육 상태, 움직임 등에 대한 정보를 제공하며, 로봇은 관절 인코더(Joint Encoders), 모터 전류(Motor Currents), 관성 센서(Inertial Sensors) 등의 내부 측정값에서 관련 정보를 얻습니다. 고유수용감각 정보는 인지가 외부 환경의 변화와 에이전트 자신의 움직임으로 발생한 변화를 구별하도록 합니다.

외수용감각(Exteroception)은 시각, 청각, 촉각, 라이다(LiDAR), 레이더(Radar), 근접 감지(Proximity Sensing)와 같은 감각 양식을 통해 외부 세계에 대한 정보를 제공합니다. 외수용감각과 고유수용감각 정보를 결합하면 체화된 에이전트가 자기 자신과 주변 객체 사이의 관계를 추정할 수 있습니다. 따라서 센서 융합(Sensor Fusion)은 환경 구조를 신체 구성, 움직임, 잠재적 상호작용과 연결하는 통합 상태 표상(Unified State Representation)을 지원합니다.

센서 측정값은 불완전하고 잡음을 포함하기 때문에 내부 상태 추정(Internal State Estimation)이 필요합니다. 인지 시스템은 현재 관찰을 이전 추정치 및 예상되는 변화에 대한 모델과 결합하여 가장 가능성이 높은 현재 상태를 추론합니다. 이렇게 추정된 상태에는 신체 자세(Body Pose), 객체 위치, 속도, 접촉(Contact), 과제 조건(Task Conditions), 불확실성(Uncertainty), 행동을 선택하고 제어하는 데 필요한 기타 변수들이 포함될 수 있습니다.

운동 명령(Motor Commands)은 인지적 의사결정을 물리적 변화로 변환합니다. 상위 수준 인지(High-level Cognition)는 객체에 도달하는 것과 같은 목표를 지정할 수 있으며, 중간 수준의 과정은 궤적(Trajectories)을 생성하고, 저수준 제어기(Low-level Controllers)는 액추에이터 명령(Actuator Commands)을 생성합니다. 따라서 감각운동 아키텍처는 여러 추상화 수준을 연결하여 의미적 목표를 점차 구체적인 행동으로 변환하는 동시에 피드백을 통해 실행이 예상대로 진행되고 있는지를 지속적으로 확인합니다.

순방향 모델(Forward Models)은 행동으로 인해 발생할 감각적 또는 물리적 결과를 예측합니다. 현재 상태와 운동 명령이 주어지면 순방향 모델은 다음 상태 또는 관찰이 어떻게 될지를 추정합니다. 행동이 실행된 후 이러한 예측은 실제 감각 피드백과 비교될 수 있습니다. 예상 결과와 관찰 결과의 차이는 보정(Correction), 학습(Learning), 이상 탐지(Anomaly Detection), 적응(Adaptation)을 위한 정보를 제공합니다.

역방향 모델(Inverse Models)은 원하는 변화를 만들어내기 위해 어떤 행동이 필요한지를 결정하는 상호보완적인 문제를 다룹니다. 현재 상태와 목표 상태(Target State)가 주어지면 역방향 모델은 적절한 운동 명령 또는 행동 시퀀스를 추정합니다. 감각운동 제어는 행동을 생성하기 위한 역방향 모델과 그 결과를 예측하기 위한 순방향 모델을 결합함으로써 목표 지향적인 물리적 상호작용(Goal-directed Physical Interaction)을 위한 강력한 메커니즘을 구성할 수 있습니다.

예측 오류(Prediction Error)는 폐쇄 루프 인지(Closed-loop Cognition)에서 핵심적인 역할을 합니다. 예측된 감각 결과와 실제 관찰이 다르면 시스템은 그 차이가 외부 외란, 부정확한 지각, 잘못된 동역학(Dynamics), 실행 오류 중 무엇에서 발생했는지를 판단해야 합니다. 이러한 차이는 즉각적인 제어 보정 또는 장기적인 모델 학습을 유발할 수 있습니다. 반복적인 예측과 보정을 통해 에이전트의 감각운동 능력(Sensorimotor Competence)은 점차 향상됩니다.

감각운동 우발성(Sensorimotor Contingencies)은 행동과 감각 입력 변화 사이의 체계적인 관계를 설명합니다. 머리를 움직이면 시각적 관점이 변하고, 객체를 만지면 특징적인 촉각 신호가 발생하며, 소리를 향해 이동하면 소리의 공간적 특성이 변화합니다. 이러한 규칙성을 학습함으로써 에이전트는 자신의 행동이 지각을 어떻게 변화시키는지에 대한 지식을 발달시키며, 환경에 대한 이해를 상호작용 경험에 접지(Grounding)할 수 있습니다.

능동 지각(Active Perception)은 이러한 원리에서 자연스럽게 도출됩니다. 감각을 수동적인 과정으로만 처리할 필요는 없으며, 더 좋은 정보를 얻기 위한 목적으로 행동을 선택할 수 있습니다. 로봇은 가려진 객체를 더 명확하게 확인하기 위해 카메라를 움직이거나, 검사를 위해 표면에 접근하거나, 위치 추정(Localization)을 개선하기 위해 자신의 위치를 변경할 수 있습니다. 따라서 행동은 물리적 목표뿐만 아니라 정보 수집(Information Gathering)의 목적도 수행합니다.

어텐션(Attention) 역시 현재 목표에 따라 감각 및 계산 자원을 할당함으로써 감각운동 루프에 참여할 수 있습니다. 에이전트는 모든 신호를 동일한 우선순위로 처리하는 대신 과제와 관련된 영역, 객체, 감각 양식 또는 예상하지 못한 사건에 자원을 집중할 수 있습니다. 이후 행동이 감각적 관찰 시점을 변화시키면서 어텐션, 지각, 움직임, 새로운 어텐션 사이의 조정된 순환이 형성될 수 있습니다.

행동유도성(Affordances)은 지각을 가능한 행동과 직접 연결합니다. 체화된 시스템은 객체를 외형이나 범주만으로 표현하는 대신 잡기(Grasping), 밀기(Pushing), 통과하기(Traversing), 열기(Opening), 회피하기(Avoiding)와 같이 객체가 허용하는 상호작용을 표현할 수 있습니다. 행동유도성 표상(Affordance Representations)은 가능한 행동이 환경의 속성과 에이전트의 물리적 능력 모두에 의존하기 때문에 관계적(Relational)입니다.

체화된 인지(Embodied Cognition)는 지능적 표상이 신체가 세계와 상호작용할 수 있는 능력에 크게 영향을 받는다고 봄으로써 이러한 관계를 확장합니다. 거리(Distance), 도달 가능성(Reachability), 지지(Support), 충돌(Collision), 힘(Force), 포함 관계(Containment)와 같은 개념은 직접적인 감각운동적 의미를 갖습니다. 물리적 상호작용은 추상적인 표상을 실제 환경에서 행동이 만들어내는 측정 가능한 결과와 연결하는 접지(Grounding)를 제공합니다.

감각운동 상호작용은 서로 분리된 관찰이 아니라 시퀀스(Sequences)로 진행되기 때문에 시간적 연속성(Temporal Continuity)이 필수적입니다. 에이전트는 이전 행동을 이후의 감각적 효과와 연결하고 지연된 결과를 관련 없는 사건과 구별해야 합니다. 작업 기억(Working Memory), 순환 상태(Recurrent States), 어텐션 메커니즘, 시간 모델(Temporal Models)은 관련 이력을 보존하여 인지가 진행 중인 상호작용을 일관되게 해석하도록 할 수 있습니다.

감각운동 학습(Sensorimotor Learning)은 이러한 시간적 관계를 반복적으로 경험하면서 형성됩니다. 에이전트는 상태를 관찰하고, 행동을 수행하고, 결과를 측정하며, 지각, 행동, 환경 변화 사이의 매핑을 점차 학습합니다. 지도학습(Supervised Learning), 자기지도학습(Self-supervised Learning), 모방학습(Imitation Learning), 강화학습(Reinforcement Learning)은 서로 다른 형태의 지식 습득에 기여할 수 있으며, 예측 오류는 지속적인 상호작용 과정에서 자연스럽게 발생하는 학습 신호를 제공합니다.

자기지도학습(Self-supervised Learning)은 물리적 상호작용이 지속적으로 구조화된 학습 데이터를 생성하기 때문에 감각운동 루프와 특히 잘 결합됩니다. 현재 관찰과 행동은 문맥(Context)을 제공하고 이후의 관찰은 예측을 위한 목표(Target)를 제공합니다. 따라서 체화된 시스템은 모든 상호작용에 대해 사람이 명시적인 라벨을 제공하지 않더라도 움직임, 객체 영속성(Object Persistence), 접촉 효과(Contact Effects), 공간적 관계, 행동 결과를 학습할 수 있습니다.

강화학습(Reinforcement Learning)은 감각운동 루프에 목표 지향적 평가(Goal-directed Evaluation)를 추가합니다. 행동은 환경의 상태 전이와 함께 해당 행동이 목표 달성에 도움이 되는지를 나타내는 보상 또는 비용을 생성합니다. 에이전트는 행동과 상태를 장기적인 결과와 연결하여 정책(Policy)을 향상시킬 수 있습니다. 학습된 월드 모델(World Model)과 결합하면 강화학습은 물리적으로 행동을 실행하기 전에 시뮬레이션된 감각운동 경험을 평가할 수도 있습니다.

감각운동 인지는 여러 시간 척도(Timescales)에서 작동하기 때문에 계층적 제어(Hierarchical Control)가 필요합니다. 운동 안정화(Motor Stabilization)는 밀리초 수준의 피드백을 요구할 수 있고, 궤적 제어(Trajectory Control)는 수십 또는 수백 밀리초 수준에서, 지역 행동은 수초에 걸쳐, 과제 추론(Task Reasoning)은 수분 또는 그 이상의 시간 범위에서 작동할 수 있습니다. 상위 수준은 목표와 제약 조건을 설정하고, 하위 수준은 빠르게 변화하는 감각 피드백에 맞추어 실행을 지속적으로 조정합니다.

반사적 행동(Reflexive Behavior)은 감각운동 제어의 가장 빠른 계층을 나타냅니다. 균형 유지, 임박한 충돌 회피, 과도한 힘 제한과 같은 일부 상황에서는 충분한 숙고(Deliberation)를 수행하기 전에 반응해야 합니다. 이러한 빠른 루프는 느린 인지 과정과 함께 작동할 수 있습니다. 숙고 메커니즘은 더 광범위한 목표를 설정하고, 반사적 메커니즘은 실행 중 안정성과 안전을 유지합니다.

따라서 이중 처리 조직(Dual-process Organization)은 체화된 제어에서도 관찰될 수 있습니다. 빠른 경로(Fast Pathways)는 학습된 정책과 제어 법칙(Control Laws)을 통해 익숙하거나 긴급한 감각운동 패턴을 처리하고, 느린 경로(Slow Pathways)는 계획, 불확실성 분석, 시뮬레이션, 문제 해결을 지원합니다. 능력 있는 인지 시스템은 일상적인 감각운동 행동의 신뢰성이 떨어지거나 익숙하지 않은 조건을 만날 경우 계산 자원을 숙고 과정으로 이동시킬 수 있습니다.

월드 모델(World Models)은 물리적 행동을 실행하기 전에 내부적으로 그 결과를 평가할 수 있도록 하여 감각운동 루프를 확장합니다. 모델은 현재 상태의 표상과 후보 행동(Candidate Action)을 입력받아 가능한 미래 상태를 예측합니다. 계획 과정은 이러한 시뮬레이션 궤적(Simulated Trajectories)을 비교하여 유망한 행동을 선택할 수 있습니다. 이후 실제 감각 피드백은 예측의 정확성을 평가하고 필요할 경우 모델을 업데이트합니다.

이를 통해 실제 감각운동 루프(Real Sensorimotor Loops)와 상상된 감각운동 루프(Imagined Sensorimotor Loops) 사이의 상호작용이 형성됩니다. 실제 루프는 물리적 행동을 통해 관찰을 생성하지만, 상상된 루프는 내부 시뮬레이션을 통해 예측된 관찰을 생성합니다. 계획은 실제 세계에서 하나의 행동을 선택하기 전에 월드 모델 안에서 여러 가상 행동을 실행할 수 있습니다. 이후 물리적 경험은 접지와 보정을 제공하여 내부 시뮬레이션이 실제 환경 동역학에서 분리되는 것을 방지합니다.

조작(Manipulation)은 감각운동 인지의 명확한 사례를 제공합니다. 로봇은 객체를 관찰하고, 자세(Pose)를 추정하고, 파지(Grasp)를 선택하고, 객체에 접근하고, 접촉을 감지하고, 힘을 조절하고, 객체를 들어 올리며, 파지가 안정적으로 유지되는지를 모니터링합니다. 각각의 단계는 물리적 상태와 이용 가능한 감각 정보를 모두 변화시킵니다. 따라서 성공적인 조작은 한 번의 지각 이후 고정된 움직임을 실행하는 것이 아니라 지속적인 피드백에 의존합니다.

이동 로보틱스(Mobile Robotics)는 더 큰 공간적 범위에서 동일한 원리를 보여줍니다. 카메라, 라이다(LiDAR), 레이더(Radar), 관성 측정 장치(IMU), 위성항법시스템(GNSS), 휠 인코더(Wheel Encoders) 등의 센서는 로봇의 움직임과 환경 구조를 지속적으로 추정합니다. 내비게이션(Navigation)은 로봇의 위치와 관찰 시점을 변화시키는 행동을 생성하고, 그 결과 새로운 관찰이 만들어집니다. 따라서 위치 추정, 지도 작성(Mapping), 장애물 예측, 계획, 제어는 서로 연결된 감각운동 루프로 작동합니다.

예상하지 못한 환경 변화는 이러한 루프가 필수적인 이유를 보여줍니다. 사람이 경로에 들어오거나, 객체가 움직이거나, 지형이 변화하거나, 위치 추정의 신뢰도가 감소하면 계획된 궤적이 더 이상 유효하지 않을 수 있습니다. 지속적인 감지는 이러한 불일치를 탐지하고, 상태 추정은 내부 표상을 업데이트하며, 계획은 의도한 행동을 수정하고, 제어기는 새로운 행동을 실행합니다. 자율성(Autonomy)은 고정된 실행이 아니라 이러한 반복적인 보정을 통해 나타납니다.

인간--로봇 상호작용(Human--Robot Interaction)은 인간의 행동이 로봇의 행동에 반응하기 때문에 추가적인 피드백을 발생시킵니다. 로봇의 움직임, 말, 제스처는 인간의 이후 행동을 변화시키며, 이러한 행동은 다시 로봇의 새로운 관찰이 됩니다. 따라서 감각운동 루프는 서로 상호작용하는 여러 에이전트에 걸쳐 확장됩니다. 효과적인 행동을 위해서는 물리적 동역학뿐만 아니라 사회적으로 반응하는 행동과 의도도 예측해야 합니다.

안전(Safety)은 감각운동 루프 전체에 통합되어야 합니다. 독립적인 모니터링(Independent Monitoring)은 상위 수준의 예측이 잘못된 경우에도 속도, 힘, 근접 거리(Proximity), 안정성(Stability), 불확실성에 대한 제한을 강제할 수 있습니다. 관찰 결과가 예상 행동에서 위험하게 벗어나는 것을 나타내면 안전 메커니즘은 계획된 행동을 중단하고 폴백 반응(Fallback Responses)을 시작할 수 있습니다. 따라서 신뢰할 수 있는 피지컬 인공지능(Physical AI)은 인지 수준과 안전 제어 수준 모두에서 피드백을 필요로 합니다.

메타인지(Meta-cognition)는 지각, 예측, 행동이 신뢰할 수 있게 작동하고 있는지를 평가함으로써 이러한 루프를 감독할 수 있습니다. 지속적인 예측 오류는 센서 고장(Sensor Failure), 모델 불일치(Model Mismatch), 익숙하지 않은 지형, 부적절한 전략을 나타낼 수 있습니다. 시스템은 근거 없는 확신을 가지고 계속 행동하는 대신 추가 관찰을 수집하고, 이동 속도를 낮추고, 제어 모드를 전환하고, 재계획하거나 외부의 도움을 요청할 수 있습니다.

궁극적으로 감각운동 인지 루프(Sensorimotor Cognitive Loops)는 지능을 지각하고, 예측하고, 행동하고, 결과를 관찰하며, 적응하는 지속적인 과정으로 전환합니다. 감각 신호는 내부 표상(Internal Representations)을 현실에 접지하고, 순방향 모델(Forward Models)은 행동의 결과를 예측하며, 역방향 모델(Inverse Models)은 행동 생성을 지원하고, 피드백은 행동을 보정하며, 학습은 미래의 상호작용을 향상시킵니다. 이러한 요소들의 통합은 체화된 인지(Embodied Cognition), 자율 로보틱스(Autonomous Robotics), 인지 에이전트(Cognitive Agents), 고급 피지컬 인공지능(Advanced Physical AI)을 위한 핵심적인 메커니즘을 형성합니다.
