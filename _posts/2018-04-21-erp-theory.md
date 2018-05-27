---
layout: post
title:  "ERP 理论的形成"
date:   2018-04-21 10:15:59 +0800
categories: ERP
---

ERP 的形成大致经历了 4 个阶段：基本 MRP 阶段、闭环 MRP 阶段。MRP-II 阶段以及 ERP 的形成阶段。ERP 理论的形成是随着产品复杂性的增加，市场竞争的加剧及信息全球化而产生的。

20 世纪 60 年代的制造业为了打破“发出订单，然后催办”的计划管理方式，设置了安全库存量，为需求与订货提前期提供缓冲。20 世纪 70 年代，企业的管理者们已经清楚地认识到，真正的需要是有效的订单交货日期，因而产生了对物料清单的管理与利用，形成了物料需求计划-MRP。20 世纪 80 年代，企业的管理者们又认识到制造业要有一个集成的计划，以解决阻碍生产的各种问题。要以生产与库存控制的集成方法来解决问题，而不是以库存来弥补或以缓冲时间的方法去补偿，于是 MRP-II，即制造资源计划产生了。20 世纪 90 年代以来，随着科学技术的进步及其不断向生产与库存控制方面的渗透，解决合理库存与生产控制问题所需要处理的大量信息和企业资源管理的复杂化，要求信息处理的效率更高。传统的人工管理方式难以适应以上系统，这时只能依靠计算机系统来实现。而且信息的集成度要求扩大到企业的整个资源的利用和管理，因此产生了新一代的管理理论与计算机系统-一企业资源计划 ERP。

ERP 是由美国 Garter Group Inc. 咨询公司首先提出的。它是当今国际上先进的企业管理模式。其主要宗旨是对企业所拥有的人、财、物、信息、时间和空间等综合资源进行综合平衡和优化管理，面向全球市场，协调企业各管理部门，围绕市场导向开展业务活动，使得企业在激烈的市场竞争中全方位地发挥足够的能力，从而取得最好的经济效益。下面对 ERP 的形成历史及有关理论和思想分别予以介绍。

# 基本 MRP

20 世纪 40 年代初期，西方经济学家通过对库存物料随时间推移而被使用和消耗的规律的研究，提出了订货点的方法和理论，并将其运用于企业的库存计划管理中。20 世纪 60 年代中期，美国 IBM 公司的管理专家约瑟夫。奥利佛博士首先提出了独立需求和相关需求的概念，将企业内的物料分成独立需求物料和相关需求物料两种类型。并在此基础上总结出了-种新的管理理论：物料需求计划（Material Requirements Planning- MRP）理论，也称做基本 MRP。这种理论和方法与传统的库存理论和方法有着明显的不同。其最主要的特点是，在传统的基础上引入了时间分段和反映产品结构的物料清单 BOM  (Bill Of Materials），较好地解决了库存管理和生产控制中的难题，即按时按量得到所需要的物料。为了更好地了解基本 MRP 理论，先来了解一下库存订货点理论。

## 库存订货理论

早在 20 世纪 30 年代初期，企业控制物料的需求通常采用控制库存物品数量的方法，为需求的每种物料设置一个最大库存量和安全库存量。最大库存量是为库存容量、库存占用资金的限制而设置的，安全库存量也叫最小库存量，意思是说物料的消耗不能小于安全库存量。由于物料的供应需要一定的时间（即供应周期，如物料的采购周期、加工周期等），因此不能等到物料的库存量消耗到安全库存量时才补充库存，而必须有一定的时间提前量，即必须在安全库存量的基础上增加一定数量的库存。这个库存量作为物料订货期间的供应量，即应该满足这样的条件：当物料的供应到货时，物料的消耗刚好到了安全库存量。这种控制模型必须确定两个参数；订货点与订货批量。

这种模型在当时的环境下也起到了一定的作用，但是随着市场的变化和品复杂性的增加，它的应用受到一定的限制。下面是订货点应用的条件：

- 物料的消耗相对稳定；

- 物料的供应比较稳定；

- 物料的需求是独立的：

- 物料的价格不是太高。

# 物料需求计划理论

订货点控制法受到众多条件的限制，而且不能反映物料的实际需求，往往为了满足生产需求而不断提高订货点的数量，从而造成库存积压，库存占用的资金大量增加，产品成本也就随之较高，企业缺乏竞争力。20 世纪 60 年代，IBM 公司的约瑟夫。奥利佛博士提出了把对物料的需求分为独立需求与相关需求的概念。在此基础上，人们形成了“在需要的时候提供需要的数量”的重要认识。理论的研究与实践的推动，发展并形成了物料需求计划理论，也即基本的 MRP。这种思想提出物料的订货量是根据需求来确定的，这种需求应考虑产品的结构，即产品结构中物料的需求量是相关的。

企业生产产品可以说是从原材料的购买开始的，也就是说，任何产品最终都由原材料构成。原材料经过一定的生产加工，发生物理和化学变化，然后经过组装和配制形成产品的组件，也即中间件，再通过一定的加工（组装等）形成最终产品。产品的结构与产品的复杂程度有关，有的产品由成千上万个零部件组成，如飞机、火箭、轮船、汽车等；有的比较简单，如镜子、文具盒、圆珠笔等。

顶层的是最终产品（是指生产的最终产品，但不一定是市场销售的最终产品），最下层的是采购件（原材料），笔芯是中间件。这样就形成了一定的结构层次。在由直接构成的上下层关系中，把上层的物料（组件）称为母件（有时称为父件，其道理是-样的），下层的构成件都称为该母件的子件。因此，处于中间层的所有物料（组件、部件），既是其上层的子件，又是其下层的母件。

由于产品构成的层次性，产品在生产时的生产和组装就存在-一定的顺序。完成一个产品，必须提前 l6 个小时采购计划，也就是产品的累计提前期为 16 个小时（但不是产品的工时）。由于产品各层次需求时间不同，这就要求“在需要的时候”，“提供需要的数量”。产品结构是多层次和树状结构的，其最长的一条加工路线就决定了产品的加工周期。这个原理也就是网络计划中的关键线路法原理。在对产品及各层次安排生产时，应按照产品需求的日期和时间往低层次安排，也就是倒排计划，即从确定各层次物料的最迟完工与最迟开工时间开始。因此，在制订物料需求计划时，需要考虑产品的结构，得出需求后，才考虑物料的库存（含在制品）数量，再得出各层次物料的实际需求量。其中最终原材料就是采购的需求量，中间件就形成了生产的加工计划。

在上节讨论 MRP 的形成、制订过程中，考虑了产品结构相关信息和库存相关信息。但实际生产中的条件是变化的，如企业的制造工艺、生产设备及生产规模都是发展变化的；甚至要受社会环境的影响，如能源的供应、社会福利待遇等的影响。基本 MRP 制订的采购计划可能受供货能力或运输能力的限制而无法保障物料的及时供应。另外，如果制订的生产计划未考虑生产线的能力，因而在执行时经常偏离计划，计划的严肃性将受到挑战。因此，利用基本 MRP 原理制订的生产计划与采购计划往往容易造成不可行。因为信息是单向的，与管理思想不一致，管理信息必须是闭环的信息流，由输入至输出再循环影响至输入端，从而形成信息回路。因此，随着市场的发展及基本 MRP 的应用与实践，20 世纪 80 年代初在此基础上发展形成了闭环 MRP 理论。

闭环 MRP 理论认为主生产计划与物料需求计划（MRP）应该是可行的，即考虑能力的约束，或者对能力提出需求计划，在满足能力需求的前提下才能保证物料{需求计划的执行和实现。在这种思想要求下，企业必须对投入！产出进行控制，也就是对企业的能力进行校检和执行控制。

现对整个闭环 MRP 的过程进行概述。企业根据发展的需要与市场需求来制订企业生产规划；根据生产规划制订主生产计划，同时进行生产能力与负荷的分析。该过程主要是针对关键资源的能力与负荷的分析过程。只有通过对该过程的分析，才能达到主生产计划基本可靠的要求。再根据主生产计划、企业的物料库存信息、产品结构清单等信息来制订物料需求计划；由物料需求计划、产品生产工艺路线和车间各加工工序能力数据（即工作中心能力，其有关的概念将在后面介绍）生成对能力的需求计划，通过对各加工工序的能力平衡，调整物料需求计划。如果这个阶段无法平衡能力，还有可能修改主生产计划：采购与车间作业按照平衡能力后的物料需求计划执行，并进行能力的控制，即输入输出控制，并根据作业执行结果反馈到计划层。因此，闭环 MRP 能较好地解决计划与控制问题，是计划理论的一次大飞跃（但它仍未彻底地解决计划与控制问题）。

- 主生产计划来源于企业的生产经营规划与市场需求（如合同、订单

等）。

- 主生产计划与物料需求计划的运行（或执行）伴随着能力与负荷的运行，从而保证计划是可靠的。

- 采购与生产加工的作业计划与执行是物流的加工变化过程，同时又是控制能力的投入与产出过程。

- 能力的执行情况最终反馈到计划制订层，整个过程是能力的不断执行与调整的过程。

# 制造资源计划（MRPII)

从闭环 MRP 的管理思想来看，它在生产计划的领域中确实比较先进和实用，生产计划的控制也比较完善。闭环 MRP 的运行过程主要是物流的过程（也有部分信息流），但生产的运作过程，产品从原材料的投入到成品的产出过程都伴随着企业资金的流通过程，对这一点，闭环 MRP 却无法反映出来。并且资金的运作会影响到生产的运作，如采购计划制订后，由于企业的资金短缺而无法按时完成，这样就影响到整个生产计划的执行。

有需求才有发展，市场也是由需求不断推动的。对于新问题的提出，人们就会寻求解决方法。1977 年 9 月，美国著名生产管理专家奥列弗。怀特（Oliver W. Wight）提出了一个新概念一-制造资源计划（Manufacturing Resources Planning），它的简称也是 MRP，但已经是广义的 MRP。为了与传统的 MRP 有区别，其名称改为 MRP-II。MRP-II 对于制造业企业资源进行有效计划具有 -整套方法。它是一个围绕企业的基本经营目标，以生产计划为主线，对企业制造的各种资源进行统一计划和控制的有效系统，也是企业的物流、信息流和资金流并使之畅通的动态反馈系统。

下面对不同于闭环 MRP 逻辑流程的部分加以描述。MRP-II 集成了应收、应付、成本及总账的财务管理。其采购作业根据采购单、供应商信息、收货单及入库单形成应付款信息（资金计划）；销售商品后，会根据客户信息、销售订单信息及产品出库单形成应收款信息（资金计划）；可根据采购作业成木、生产作业信息、产品结构信息、库存领料信息等产生生产成本信息；能把应付款信息、应收款信息、生产成本信息和其他信息等记入总账。产品的整个制造过程都伴随着资金流通的过程。通过对企业生产成本和资金运作过程的掌握，调整企业的生产经营规划和生产计划，因而得到更为可行、可靠的生产计划。

MRP-II 理论从 20 世纪 80 年代初开始在企业中得到广泛的应用，MRP-II 的应用与发展给制造业带来了巨大的经济效益。据 1985 年的不完全统计数字，美国有 160 多家计算机软硬件公司，开发与提供了 300 余种 MRP-II 商品软件，已拥有数万家用户。前西德也有许多软件公司，开发与提供了数十种商品化的 MRP-II 软件。到目前为止，由于 MRP-II 所独有的实用性、通用性和强大的生命力及广泛的市场需求，数百个计算机软硬件公司，在不同的软硬件环境下开发出功能各异的数百个商品化软件包。根据有关统计，在美国，80%以上的大型企业安装了 MRP-II 系统；50%以上中型企业安装了 MRP-II 系统，30%以上小型企业安装了 MRP-II 系统。在德国，95%的大中型企业已应用了计算机系统。在英国，80%的制造业实现了计算机管理。在法国，76%的机械制造企业已应用了计算机管理。

在我国，计算机辅助企业管理起步于 20 世纪 80 年代。1981 年，沈阳鼓风机厂率先引进 IBM 公司的 COPICS 系统，揭开了 MP-II 系统在我国开始应用的序幕。到目前为止，国内已有近 200 家企业引进了十余种国外的 MRP-II 软件产品。但是，纵观这些企业 MRP-II 系统的应用状况可以看到，真正地全面实施并取得整体效益的企业并不多，其原因主要在于管理模式的差异和实施的质量等方面的问题。

# 企业资源计划（ERP) 

## MRP-II 的局限性

前面讨论了基本 MRP、闭环 MRP 和 MRP-II 的理论，这些理论在相应的阶段都发挥了重要的作用，尤其是 MRP-II 的发展与应用。从上节可以看出，MRP-II 对世界的发展与应用产生了深远的影响。随着市场竞争日趋激烈和科技的进步，MRP-II 思想也逐步显示出其局限性，主要表现在以下几个方面：

- 企业竞争范围的扩大，要求在企业的各个方面加强管理，并要求企业有更高的信息化集成，要求对企业的整体资源进行集成管理，而不仅仅对制造资源进行集成管理。

现代企业都意识到，企业的竞争是综合实力的竞争，要求企业有更强的资金实力，*更快的市场响应速度。因此，信息管理系统与理论仅停留在对制造部分的信息集成与理论研究上是远远不够的。与竞争有关的物流、信息及资金要从制造部分扩展到全面质量管理、企业的所有资源（分销资源、人力资源和服务资源等）及市场信息和资源，并且要求能够处理工作流。在这些方面，MRP-II 都已经无法满足。

- 企业规模不断扩大。多集团、多工厂要求协同作战，统一部署，这已超出了 MRP-II 的管理范围。

全球范围内的企业兼并和联合潮流方兴未艾，大型企业集团和跨国集团不断涌现，企业规模越来越大，这就要求集团与集团之间，集团内多工厂之间统一计划，协调生产步骤，汇总信息，调配集团内部资源。这些既要独立，又要统-的资源共享管理是 MRP-II 目前无法解决的。

- 信息全球化趋势的发展要求企业之间加强信息交流和信息共享。企业之间既是竞争对手，又是合作伙伴。信息管理要求扩大到整个供应链的管理，这些更是 MRP-II 所不能解决的。

随着全球信息的飞速发展，尤其是 Intermet 的发展与应用，企业与客户、企业与供应商、企业与用户之间，甚至是竞争对手之间都要求对市场信息快速响应，信息共享。越来越多的企业之间的业务在互联网上进行，这些都向企业的信息化提出了新的要求。ERP 系统实现了对整个供应链信息进行集成管理。 ERP系统采用客户机/服务器(C/S)体系结构和分布式数据处理技术，支持 IntereVIntranet/Extranet、电子商务(E-business. E-commerce）及电子数据交换（EDI）。

## 企业资源计划（Enterprise Resource Planning- -ERP)

随着现代管理思想和方法的提出和发展，如 JIT  (Just In Time 及时生产）. TQC (Total Quality Control--全面质量管理）、OPT (Optimized Production Technology 一优化生产技术）及 DRP  (Distribution Resource Planning- 一分销资源计划）等，又相继出现了 MES  (Manufacturing Execute System---一制造执行系统）、AMS  (Agile Manufacturing System--敏捷制造系统）等现代管理思想。MRP-II 逐步吸收和融合其他先进思想来完善和发展自身理论。20 世纪 90 年代 MRP-II 发展到了一个新的阶段：ERP  (Enterprise Resource Planning

企业资源计划）。

简要地说企业的所有资源包括 3 大流：物流、资金流和信息流。ERP 也就是对这 3 种资源进行全面集成管理的管理信息系统。概括地说，ERP 是建立在信息技术基础上，利用现代企业的先进管理思想，全面地集成了企业的所有资源信息，并为企业提供决策、计划、控制与经营业绩评估的全方位和系统化的管理平台。ERP 系统是一种管理理论和管理思想，不仅仅是信息系统。它利用企业的所有资源，包括内部资源与外部市场资源，为企业制造产品或提供服务创造最优的解决方案，最终达到企业的经营目标。由于这种管理思想必须依附于电脑软件系统的运行，所以人们常把 ERP 系统当成- -种软件，这是一种误解。要想理解与应用 ERP 系统，必须了解 ERP 的实际管理思想和理念，才能真正地掌握与利用 ERP。

ERP 理论与系统是从 MRP-II 发展而来的，它除继承了 MRP-lI 的基本思想（制造、供销及财务）外，还大大地扩展了管理的模块，如多工厂管理、质量管理、设备管理、运输管理、分销资源管理、过程控制接口、数据采集接口。电子通信等模块。它融合了离散型生产和流程型生产的特点，扩大了管理的范围，更加灵活或“柔性”地开展业务活动，实时地响应市场需求。它还融合了多种现代管理思想，进一步提高了企业的管理水平和竞争力。因此 ERP 理论不是对 MRP-II 的否认，而是继承与发展。MRP-II 的核心是物流，主线是计划。伴随着物流的过程，同时存在资金流和信息流。ERP 的主线也是计划，但 ERP 已将管理的重心转移到财务上，在企业整个经营运作过程中贯穿了财务成本控制的概念。总之，ERP 极大地扩展了业务管理的范围及深度，包括质量、设备、分销、运输、多工厂管理、数据采集接口等。ERP 的管理范围涉及企业的所有供需过程，是对供应链的全面管理和企业运作的供需链结构。

一般 ERP 系统包含的模块有：

- 销售管理
- 采购管理
- 库存管理
- 制造标准
- 主生产计划
- 物料需求计划
- 能力需求计划
- 车间管理
- JIT 管理
- 质量管理
- 账务管理
- 成本管理
- 应收账管理
- 应付账管理
- 现金管理
- 固定资产管理
- 工资管理
- 人力资源管理
- 分销资源管理
- 设备管理
- 工作流管理
- 系统管理


## ERP 今后的发展趋势

1990 年，Gartner Group 公司率先提出了 ERP 的概念。10 年之后，该公司又提出了一个新的概念一- ERP-II. ERP 从诞生之日起就在不断发展，这里姑且先不讨论 ERP-II 这个名称叫法。下面从几个方面对 ERP 未来的发展趋势进行展望。

### 管理范围更加扩大

ERP 的管理范围有继续扩大的趋势，继续扩允供需链管理（Supply Chain
Management-- -SCM) SCM 融台企业本身的所有经营业务、企业的办公业务、企业之间的协同商务业务等，如电子商务（Electronic Commerce- -EC, B2 B, B2 C 等）、客户关系管理（Customer Relationship Management-- CRM）、办公室自动化（OA）等都不断地融入 ERP 系统中。协同商务（Collaborative commerce，缩写为 C. Commerce），指企业内部人员，贯穿于贸易共同体的业务伙伴和客户之间的协作及电子化的业务交互过程。贸易共同体可以是一个行业或行业分支，也可以是供应链或供应链的一部分。此外，ERP 系统还日益和 CAD (Computer Aided Design-计算机辅助设计）、CAM (Computer Aided Manufacture-计算机辅助制造）、CAPP  (Computer Aided Process Planning- 一计算机辅助工艺设计）、PDM  (Product Data Management- -产品数据管理）、POS 系统以及自动货仓等系统融合，互相传递数据。这样就将企业管理人员在办公室中完成的全部业务都纳入到了管理范围中，实现了对企业的所有工作及相关内外部环境的全面管理。

### 继续支持与扩展企业的流程重组

企业的外部与内部环境变化是相当快的。企业要适应这种快节奏的变化，就要不断地调整组织机构和业务流程。因此，ERP 的发展必然要继续支持企业的这种变化，使企业的工作流程能够按照业务的要求进行组织，以便集中相关业务人员，用最少的环节，最快的速度和最经济的形式，完成某项业务的处理过程。

### 运用最先进的计算机技术

信息是企业管理和决策的依据，计算机系统能够及时而准确地为企业提供必要的信息，因此 ERP 的发展是离不开先进的计算机技术的。Internet 和 Intranet 技术，使企业内部及企业与企业之间的信息传递更加畅通。面向对象技术的发展使企业内部的重组变得更加快捷和容易。计算机在整个业务过程中产生信息的详尽记录与统计分析，使央策变得更加科学和有目的性。新的计算机技术的不断涌现为 ERP 的发展提供了广阔的前景。
