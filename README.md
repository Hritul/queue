# queue
##Algorithm for Insert Operation

###Step 1: If if(rear==max-1) then
           Write “Queue is full”
###Step 2: else if(front==-1)front=0;
###Step 3: Take data from user.
		
###Step 4: rear=(rear+1)%max;
		       queue[rear]=x;
           


##Algorithm for Delete Operation

###Step 1: If FRONT = -1 then
           Write “Queue is Underflow”
###Step 2: Return QUEUE [FRONT]
###Step 3: If FRONT = REAR then
           FRONT = 0
           REAR = 0
           Else
           FRONT = FRONT + 1
