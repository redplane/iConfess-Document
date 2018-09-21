## ADMIN REAL-TIME EVENTS
* **Description**:
    * This document is for defining real-time messages that will be sent when an action is taken in **Admin** system.

* **Events**
    
    * **Added new catgory group** (api/category-group)
        * **Target**: (`Admin group`)
        * **Hub**: 
            * **Event name**: `event-add_category_group`
            * **Parameters**: (`CategoryGroup` instance)
        * **Push message**
            * **Title**: `TITLE_NEW_CATEGORY_GROUP`
            * **Body**: `MSG_ADD_NEW_CATEGORY_GROUP`
            * **Parameters**: (`CategoryGroup` instance) 
    
    * **Edited new catgory group** (api/category-group)
        * **Target**: (`Admin group`)
        * **Hub**: 
            * **Event name**: `event-add_category_group`
            * **Parameters**: (`CategoryGroup` instance)
        * **Push message**
            * **Title**: `TITLE_NEW_CATEGORY_GROUP`
            * **Body**: `MSG_ADD_NEW_CATEGORY_GROUP`
            * **Parameters**: (`CategoryGroup` instance) 
    
    * **Added new catgory** (api/category)
        * **Target**: (`Admin group`)
        * **Hub**: 
            * **Event name**: `event-add_category`
            * **Parameters**: (`Category` instance)
        * **Push message**
            * **Title**: `TITLE_NEW_CATEGORY`
            * **Body**: `MSG_ADD_NEW_CATEGORY`
            * **Parameters**: (`CategoryGroup` instance) 
    
    * **Edited new catgory** (api/category)
        * **Target**: (`Admin group`)
        * **Hub**: 
            * **Event name**: `event-add_category`
            * **Parameters**: (`Category` instance)
        * **Push message**
            * **Title**: `TITLE_NEW_CATEGORY_GROUP`
            * **Body**: `MSG_ADD_NEW_CATEGORY_GROUP`
            * **Parameters**: (`CategoryGroup` instance) 
    
     * **User account activated** (api/category-group)
        * **Target**: (`Admin group`)
        * **Hub**: 
            * **Event name**: `event-user_registered`
            * **Parameters**: (`User` instance)
        * **Push message**
            * **Title**: `TITLE_USER_REGISTERED`
            * **Body**: `MSG_USER_REGISTERED`
            * **Parameters**: (`User` instance)
    
    * **Added topic report** (api/topic-report)
        * **Target**: (`Admin group`)
        * **Hub**
            * **Event name**: `event-added_topic_report`
            * **Parameters**:
                * `Reporter name`
                * `Topic name`
                * `Report created time`
        * **Push messaage**
            * **Title**: `TITLE_ADDED_TOPIC_REPORT`
            * **Body**: `MSG_ADDED_TOPIC_REPORT`
            * *Parameters**:
                * `Reporter name`
                * `Topic name`
                * `Report created time`
    
    * **Added reply report*** (api/reply-report)
        * **Target**: (`Admin group`)
        * **Hub**
            * **Event name**: `event-added_reply_report`
            * **Parameters**:
                * `Reporter name`
                * `Topic name`
                * `Report created time`
        * **Push messaage**
            * **Title**: `TITLE_ADDED_TOPIC_REPORT`
            * **Body**: `MSG_ADDED_TOPIC_REPORT`
            * *Parameters**:
                * `Reporter name`
                * `Topic name`
                * `Report created time`
    
            
    
                