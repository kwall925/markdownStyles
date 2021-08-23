# Svelte

## Basics

## Reactivity

## Props

Components need to communicate with each other. Properties (props) allow data from a component to be passed to its children. This is done via the export keyword. Here we are passing data from component 'Nested' to our main app:

Nested.svelte:

```
<script>
	export let answer;
</script>

<p>The answer is {answer}</p>
```

App.Svelte:

```
<script>
	import Nested from './Nested.svelte';
</script>

<Nested answer={42}/>
```
---
Spread an Object of properties into
a component:

```
<Info {...pkg}/>
```

## Logic

Use Logic directly on HTML elements:
```
<script>
	let user = { loggedIn: false };

	function toggle() {
		user.loggedIn = !user.loggedIn;
	}
</script>

{#if user.loggedIn}
  <button on:click={toggle}>
  	Log out
  </button>
{else}
  <button on:click={toggle}>
  	Log in
  </button>
{/if}
```
---
Looping with each:
