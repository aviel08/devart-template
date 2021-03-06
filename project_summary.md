# In lak'ech
####I am another you

## Authors
- Alex Leiva / https://github.com/aviel08


## You are another me
“In lak'ech” is a Mayan greeting which means “I am another you” and which your response would be:  “Hala ken” or “you are another me”.  This kind of expression is found in many religions, similar to “Namaste” but perhaps most commonly in Western religious traditions as "Do unto others as you would have them do unto you." However, in lak'ech goes beyond the separation between "I and thou" to suggest that the boundary is non-existent; that separateness is an illusion of this physical world, of our bodies; that our experience of life is just an expression of a vast, collective experience of life.
The project’s goal is to disseminate empathy in people by allowing them to see the world from another’s perspective. In order to achieve this objective, two users will be placed opposite to one another, then gradually and almost imperceptibly their faces will swap. 

![Example Image](project_images/concept_00.jpg?raw=true "Concept")


## Inspiration
The mysterious monolith that appears on 2001: A Space Odyssey is a clear reference on the project.  The object stands still, silently and allows people to approach it with curiosity. The black cubic totem can be placed in different environments and with varying cultural groups as it did in the film and still have a valid reaction from each user.
![Example Image](project_images/concept_02.jpg?raw=true "Concept")


## Example Code
```
void testApp::loadFace(string face){
src.loadImage(face);
if(src.getWidth() > 0) {
srcTracker.update(toCv(src));
srcPoints = srcTracker.getImagePoints();
```
## Libraries

FaceTracker  [Github]( https://github.com/kylemcdonald/FaceTracker "Github")

ofxFaceTracker [Github]( https://github.com/kylemcdonald/ofxFaceTracker "Github")

FaceSubstitution [Github]( https://github.com/arturoc/FaceSubstitution "Github")

clmtrackr [Github]( https://github.com/auduno/clmtrackr "Github")
