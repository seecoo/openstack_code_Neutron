## db
跟数据库相关的操作。因为各项服务根本上的操作都需要跟数据库打交道，因此这部分定义了大量的数据库资源类和相关接口，可以被进一步继承实现。
包括对核心plugin api的实现基础类，其次是一些扩展的资源和方法的支持。
其中model_base.py和models_v2.py中定义了最基础的几个模型类。
