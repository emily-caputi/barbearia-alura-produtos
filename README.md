# barbearia-alura-produtos
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Contato - Barbearia Alura</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
	</head>
	<body>
		<header>
			<div class="caixa">
				<h1><img src="logo.png" alt="Logo da Barbearia Alura"></h1>

				<nav>
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="produtos.html">Produtos</a></li>
						<li><a href="contato.html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

		<main>
			<form>
				<label for="nomesobrenome">Nome e sobrenome</label>
				<input type="text" id="nomesobrenome" class="input-padrao" required>

				<label for="email">Email</label>
				<input type="email" id="email" class="input-padrao" required placeholder="seuemail@dominio.com">

				<label for="telefone">Telefone</label>
				<input type="tel" id="telefone" class="input-padrao" required placeholder="(XX) XXXXX-XXXX">

				<label for="mensagem">Mensagem</label>
				<textarea cols="70" rows="10" id="mensagem" class="input-padrao" required></textarea>

				<fieldset>
					<legend>Como prefere o nosso contato?</legend>
					<label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email"> Email</label>
					
					<label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone"> Telefone</label>
					
					<label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked> WhatsApp</label>
				</fieldset>

				<fieldset>
					<legend>Qual horário prefere ser atendido?</legend>
					<select>
						<option>Manhã</option>
						<option>Tarde</option>
						<option>Noite</option>
					</select>
				</fieldset>

				<label class="checkbox"><input type="checkbox" checked>Gostaria de receber nossas novidades por email?</label>

				<input type="submit" value="Enviar formulário" class="enviar">
			</form>

			<table>
				<thead>
					<tr>
						<th>Dia</th>
						<th>Horário</th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<td>Segunda</td>
						<td>8h ~ 20h</td>
					</tr>
					<tr>
						<td>Quarta</td>
						<td>8h ~ 20h</td>
					</tr>
					<tr>
						<td>Sexta</td>
						<td>8h ~ 20h</td>
					</tr>
				</tbody>
			</table>
		</main>

		<footer>
			<img src="logo-branco.png" alt="Logo da Barbearia Alura">
			<p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
		</footer>
	</body>
</html>
