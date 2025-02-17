class Solution {
public:
    ListNode* deleteDuplicates(ListNode* head) {
        ListNode* current = head;
        while(current && current-> next){
            if(current->val == current->next->val){
                ListNode* temp = current->next; //storing the duplicate value for deletion.
                current->next = current->next->next;
                delete temp; //removing the repeated val.
            }
            else
            current = current->next;
        }
        return head;
        
    }
};
