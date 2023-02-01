<script lang="ts">
    let username = '';
    let password = '';
</script>

<form class="loginForm" on:submit|preventDefault>
	<h1>Zaloguj się {username?.length > 0 ? ', ' + username : ''}</h1>
	<input type="text" placeholder="Login" bind:value={username} required/>
    <input type="password" placeholder="Hasło" bind:value={password} required/>
    <input type="submit" />
</form>

<style>
	.loginForm {
		display: flex;
		justify-content: center;
		max-width: 300px;
		margin: 0px auto;
        flex-direction: column;
	}

	.loginForm h1 {
		grid-column: 1/3;
		display: flex;
		justify-content: center;
        text-align: center;
	}
</style>
