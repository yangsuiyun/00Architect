**This book writes ICONIX method to realize Use case driven object modeling. **

## Domain Modeling
A domain model is a 'live' dictionary of all the terms used in project and show terms' relationship. It's a simplified class diagram. The domain model shows aggregation and generalization relationships (has-a and is-a relationship) between the domain classes.

The domain model forms the foundation of the static part of your model, while the use cases are the foundation of the dynamic part. The static part describes structure; the dynamic part describes behavior.

### Top 10 Domain Modeling Guidelines
1. Foucus on real-world objects

2. Use generalization(Is-a) and aggregation (Has-a) relationships

    Ninety-five percent of model's class relationships can be modeled using aggregation and generalization relationships. 

3. Limit your initial domain modeling efforts to a couple of hours

    You can't find all domain classes one time. Usually, in initial two hours, you can find 80% domain classes. Others will be discovered in following use cases and robustness diagrams.

4. Organize your classes around key abatractions in the problem domain

    Real world change less than requirements. It's better to organize architecture around real world abstractions.

5. Don't mistake your domain model for a data model

    A table in a relational database often relates a number of things. Con-
versely, classes are better designed if they’re relatively small packets of data and behavior.

6. Don't confuse an object with a database table

    If you call a domain class Book, then you don’t mean a book table—you
mean a single book.

7. Use the domain model as a project glossary

8. Do your domain model before you write your use cases

9. Don't expect your final class diagrams to precisely match your domain model

10. Don't put screens and other GUI-specific classes on your domian model
    Performance optimization classes, helper classes, implementation-specific detail should be kept out of the domain model. The domain model should focus purely on the problem domain.

### Step to build domian modeling
1. Extract nouns and noun phrase from requirement document, put them together

2. Analysis all words

    Delete too broad, too small to be an object, UI element and so on; Keep only one for duplication word; Modify unclear word.
    **External systems are always modeled as actors.**

3. Build aggregation relationship for domain modeling

    By saying 'has-a' to quickly find out relationship between classes.Stilll some domain objects don't match up with anything. Group them on together over on the right and remodify during roboustness analysis.

4. Build generalization relationship for domain modeling

    