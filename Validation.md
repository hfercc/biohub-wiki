## Validation

### Forum
We check each function of our forum to assure that it works as we expected.

+ **Watch**: After clicking the link "**Watch**", the number of watching users increased.
    - Before: ![](images/validation/watch.png)
    - After: ![](images/validation/watch-after.png)

+ **Rate**: After clicking the link "**Rate**", a component designed for rating will appear beneath it. If brick rated by user, the link "**Rate**" will be hidden. The average score will be displayed in terms of stars.
    - Not Rated: ![](images/validation/star-appear.png)
    - Rated: ![](images/validation/after-rate.png)

+ **Star**: The validation can be repeated in the same way.
    - Not Starred: ![](images/validation/not-starred.png)
    - Starred: ![](images/validation/starred.png)

+ **Posting Experiences**: Posting experiences with pictures is a good test case for experiences module.
![](images/validation/post-experience.png)
The Markdown language has been parsed and the image uploaded inserted into the right place.The editor will compile the users' input whenever the content changes, providing real-time preview for better experience.

+ **Experiences Displaying**:
![](images/validation/experience-display.png)
The experience posted just now has the same view as what we get in the editor. An unique key will be assigned to it for direct access.

+ **Comments**:
![](images/validation/leave-comment.png)

### BioSearch
Type anything you want to learn about a part and press Enter, in less than one second you will get the results:

![](images/description/biosearch-result.png)
    
The bricks are ordered by their qualities and creation date, which means you are always able to get the best and latest one to meet your need. The quality of bricks are ranked by several factors, including frequency of use, sample status, and assessments from users in forum, and so on. Each brick is displayed with a progress bar at the right bottom corner, which represents the relative ranking.

BioSearch supports multi-dimensional filtering. You can use `t:<type>` to limit the type of bricks:

![](images/description/biosearch-type-limit.png)

or use `n:<part name>` to precisely locate a brick using its name:

![](images/description/biosearch-limit-name.png)

or add an `h:` filter to mark out the matched words:

![](images/description/biosearch-hl.png)

Multiple filters can also be combined to make complex query:

![](images/description/biosearch-combine.png)


