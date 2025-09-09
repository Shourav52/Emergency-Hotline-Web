1.Aanswer:- getElementById : it cam take a single element of id.
              getElementsByClassName:- it use to select all element that have a spacific class name.
              querySelector :- it use to select the first element that matched one or more selector.
              querySelectorAll :- it use to select more element

2.Answer:- First of all create the element use the document.createElement() formula then set content or text then insert the element like appendChild() or append() add 
the new element to the DOM.

3.Answer:- Event bubbling means a event goes from the clicked element up through its parent elements.
           Work:------
            In my project when i click a call button  the event first happens on the button and then moves up to parent section like .cards-section div.
           
4.Answer:-Event Delegation:
          That means means putting one event listener on a parent element so it can handle events  from all of its child elements .
          Its Usefull cause:-
          1. Short code
          2. It works for dynamically added child elements.
          3. It improves performance when there are many elements.

5.Answer:- preventDefault()  its uses to prevent page reload and stopPropagation() is close to event bubbling.
