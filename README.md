# Medigy-Classification-Topics
Medigy Topics listing from Ontology (OWL) FIles

# Get topics list

```
import MedigyTopics from '@medigy/Medigy-Classification-Topics
MedigyTopics.getOwlTopics().then((topics: any) => {
  if (topics.owlTopicClassification) {
    const returnObject = topics.owlTopicClassification.data ? topics.owlTopicClassification.data.getClassHierarchy : null;
    }
});
