<svelte:head>
	<title>Gokusygo</title>
	<meta name="description" content="gokusygo" />
</svelte:head>

<section class="hero">
	<div>
		<h2>Dzielenie się zadaniem domowym jeszcze nigdy dotąd nie było tak proste!</h2>
		<h3>Jak to działa?</h3>
		<p>Krok 1: Załóż konto i otrzymaj 1000 kredytów</p>
		<p>Krok 2: Dodaj zadanie, wraz z jego rozwiązaniem i plikami</p>
		<div>
			<p>
				Krok 3: Wybierz jedną z dwóch opcji udostępniania zadania:
			</p>
			<ul>
				<li>Pay & Forgot - tylko jedna osoba można kupić dane zadanie, później znika ono z serwisu. Sprzedający otrzymuje losowy bonus w postaci kredytów</li>
				<li>Sale - zadanie może kupić nielimitowana liczba osób</li>
			</ul>
		</div>
		<p>Krok 3: Dodaj zadanie, wraz z jego rozwiązaniem i plikami</p>
	</div>
	<img
		src="https://media.giphy.com/media/UevalSWg5twQeqpc8Q/giphy.gif"
		alt="Crab making homework"
	/>
	<a href="/login">
		<button>Do dzieła!</button>
	</a>
</section>

<style type="scss">
	.hero {
		display: grid;
		grid-template-columns: 1fr 1fr;
	}
	img {
		justify-self: end;
	}
</style>
