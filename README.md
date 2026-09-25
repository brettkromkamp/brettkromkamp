![Brett Kromkamp - brettkromkamp.com](https://github.com/brettkromkamp/brettkromkamp/blob/master/resources/banner2.png)

## Brett Kromkamp's GitHub Profile

You've reached [Brett Kromkamp](https://brettkromkamp.com/)'s GitHub profile. Find me on [Mastodon](https://indieweb.social/@brettkromkamp).

I contribute to and maintain [Contextualise](https://github.com/brettkromkamp/contextualise), [TopicDB](https://github.com/brettkromkamp/topic-db) and a couple of other open source projects. I also have several published Python packages on [PyPI](https://pypi.org/user/brettkromkamp/).

Projects I am currently working on, include:

* Suite of [iOS](https://developer.apple.com/ios/) apps using [Swift](https://www.swift.org/) and [RealityKit](https://developer.apple.com/documentation/realitykit/), Apple's high-performance 3D framework 
* __Contextualise__, a knowledge management system using the [Python](https://www.python.org/) programming language and [Flask](https://flask.palletsprojects.com/en/2.2.x/) web framework

### Contextualise Projects

#### Contextualise Knowledge Management System
Contextualise is an effective tool particularly suited for organising information-heavy projects and activities consisting of unstructured and widely diverse data and information resources

#### Contextualise: An Ecosystem of Explorable Knowledge

##### What It Is

Contextualise is a set of tools that share one information model: topic maps. A topic map holds knowledge as topics, the associations between them, the occurrences that describe them, and the scope that says in which context each statement is true. The tools do not share a server, an API or common application code. They share a file and a schema.

The ecosystem tests one claim. Topic maps are a meta model, and scope makes them expressive enough to hold many kinds of knowledge without a change to the model. Each tool is evidence for that claim, because each one puts a different kind of knowledge into the same model.

##### Explorable, Not Only Renderable

A report, a diagram or a booklet is a projection of knowledge. A projection runs in one direction. If a reader disagrees with a report, a correction to the report is lost at the next run.

So every tool that makes a projection also makes, or keeps, the topic map behind it. The map is the knowledge in a form that a person can read, query and change. The reader opens the map, corrects the topic, and makes the projection again. This loop is what "explorable" means here. A tool that gives only a document or a picture gives something renderable. A tool that also gives the map gives something explorable.

##### The Rule For Membership

A tool is a member when it reads a topic map, writes one, or does both. No other test applies.

##### The Members

###### Tools That Write Maps

- The pipeline writes a topic map about a subject from source material, in numbered passes. A language model drafts each pass, and a person approves it.
- ```corpus-map``` reads a folder of Markdown documents and writes a map of what they are about. It first proposes the vocabulary as a topic map that a person reviews. Then it chooses the core subjects of the whole set, grouped in areas. Every statement keeps the scope of the document that made it.
- scenario-planner makes possible future scenarios for a domain from real sources, and exports its graph as a topic map.
- topic-map-editor opens a topic map and edits all of it, scope included, then writes the file back.

###### The Shared Foundation

- topic-map-engine holds the model, the traversal and the scope matching, with no framework attached. It also holds TMQL, a small query language that walks, filters and scopes in one query.

###### A Tool That Reads and Writes

- structure-map reads a topic map and writes a diagram for diagrammer, a report with its sources, and the topic map itself. The diagram is a first layout that a person keeps arranging in diagrammer, and a diagram that a person changed is never overwritten.

###### Tools That Read Maps

- diagrammer draws a topic map as an isometric diagram that a person arranges. It has two vocabularies: Place, for subject matter that is spatial, and Structure, for subject matter that is not. Each object binds to a topic or an occurrence, so the diagram is a view onto the map.
- experience-builder turns a topic map into a configurator for a real-world walk. The walker's choices select which scoped variant of each stop's content they read.
- systems-builder reads stocks, flows and feedback loops from a topic map and simulates them. Its whole vocabulary is declared inside the map, not added to the engine.

#### Mixing Art and Code to Build Engaging Web Experiences

Development of web content models, concepts, creation processes and tools: mix art and code to build interactive, [engaging web experiences](https://brettkromkamp.com/posts/engaging-web-experiences/)

### Story Technologies

#### Storytelling With Interactive Visualisation of Semantic Events

Developing a combined Angular and [Pixi.js](https://pixijs.com/)-based web application &mdash;for storytelling purposes&mdash; that allows a user to navigate between a collection of [narrative events](https://brettkromkamp.com/posts/narrative-events/). Each event has an accompanying 2.5D, isometric environment with participants and items that can be interacted with. Interactions include (but, are not limited to) displaying more information about the selected object and high-lighting a set of objects by tag. Narratives are [Contextualise](https://contextualise.dev/) topic maps.

> I will see you again, in the place where no shadows fall. &mdash; Ambassador Delenn, Babylon 5
