# joguete_loco
um simples tutorial
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<meta charset="utf-8">
	<style type="text/css">

		div
		{
			background: rgb(70,255,0);/*ou #000000 ou red*/
			width: 100px;
			height: 100px;
		}

	</style>

</head>
<body>

	<div></div>

</body>
</html>

<script>

	const party =
	[
		{
			id : 'juquinha',
			life : 10,
			strength : 10,
			agility : 10,
			armor : 10,
			mana : 10,
			//quer outro heroi ctrl+c e muda os status.
		}
	]

	const backpack = []//mochila

	const bestiary =
	[
		{
			id : 'Giglipuffy',
			life : 3,
			strength : 5,
			agility : 4,
			armor : 4,
			mana : 5,
			//quer outro heroi ctrl+c e muda os status.
		},

		/*
		{
			id : 'Giglipuffy',
			life : 3,
			strength : 5,
			agility : 4,
			armor : 4,
			mana : 5,
			//quer outro heroi ctrl+c e muda os status.
		},

		{
			id : 'Giglipuffy',
			life : 3,
			strength : 5,
			agility : 4,
			armor : 4,
			mana : 5,
			//quer outro heroi ctrl+c e muda os status.
		}
		*/
	]

//=====================

	const places =
	[
		{
			id : 'dark florest',
		},

		{
			id : 'gramado resplandecente',
		},

		{
			id : 'toca do lobo',
		},

		{
			id : 'QG',
		},
	]

//=====================

	const estado =
	{
		places : null
	}

//=====================

	const start = _ =>
	{

	}

//=====================

	const update = _ =>
	{
		//console.log('Xablau')
		update()
		//window.requestAnimationFrame(update)//
	}
	update()//fora da função vc tá chamando ela pra rodar
</script>
