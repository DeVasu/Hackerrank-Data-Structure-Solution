/*
  Insert Node at the begining of a linked list
  Initially head pointer argument could be NULL for empty list
  Node is defined as 
  struct Node
  {
     int data;
     struct Node *next;
  }
return back the pointer to the head of the linked list in the below method.
*/
Node* Insert(Node *head,int data)
{  
    Node *new_ptr= (Node*) malloc(sizeof(struct Node));   //this allocates space for the newly created pointer
    new_ptr->data=data; 
    new_ptr->next=head;                                   //the new element points to the next first element(head) of the list
    head=new_ptr;                                         //the head attribute of the list is now given to the new element
    return head;                                          //now the head is returned
  // Complete this method
}
