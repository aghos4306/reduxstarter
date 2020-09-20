This is a project I followed to reinforce my understanding of implementing Redux in react application.
In this project I built a simple react data fetching. The data is fetched from the jsonplaceholder API.
Redux is used to manage two states in this project, fetchpost and create newpost respectively.
Action, Reducer, Components tied together.
The functionality to add a new post, I created the action, sent the type and the payload to the postReducer, the reducer decides how it wants the state to be dispatched down, that single post item gets added to the state,
the state gets updated and the update reflects in within the post component.
