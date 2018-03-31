# night
//typedef 的作用是为一个已存在的类型定义一个别名
typedef int datatype_t;
//定义单链表中 的数据结点的结构体类型
typedef struct _node_
{
    datatype_t data;
    struct _node_*next;
}link_node_t,*link_list_t;
//功能函数的声明
//新建空的单链表
link_list_t create_empty_linklist(void);
//判断单链表是否为空

//求单链表的元素个数

//遍历打印单链表信息

//在单链表的指定位置插入数据元素

//删除单链表制定位置的数据元素

//清空单链表

//销毁单链表
//头文件的内容放在中间
//int g_num=10000;

#endif
