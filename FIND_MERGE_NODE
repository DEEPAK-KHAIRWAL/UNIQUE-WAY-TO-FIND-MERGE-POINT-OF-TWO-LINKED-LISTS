/*
   Find merge point of two linked lists
   Node is defined as
   struct Node
   {
       int data;
       Node* next;
   }
*/
int FindMergeNode(Node *headA, Node *headB)
{
    Node*target=new Node,*p;
    while(headA!=NULL)
    {
        p=headA->next;
        headA->next=target;
        headA=p;
    }
     while(headB!=NULL)
    {
        if(headB->next==target)
        {
            return headB->data;
        }
         headB=headB->next;
    }
    return 0;
}
