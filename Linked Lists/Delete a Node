Node* Delete(Node *head, int position)
{
    Node* temp=head,*prev;                                  //two pointers, one for the element to delete other for element before that element
    if(position==0){head=head->next; free(temp);}           //if the element to be deleted is at the front of the list
    else
    {
        while(position--)
        {
            prev=temp;
            temp=temp->next;
        }
        prev->next=temp->next;      
        free(temp);
    }
    return head;
  // Complete this method
}
