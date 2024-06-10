<html>
	<body>
		<h1>Car Price Predict Model</h1>
		<p>Construção de um modelo Predito de Preço de Carros</p>
		<p>Fonte dos dados: https://www.kaggle.com/datasets/ayushparwal2026/cars-dataset</p>
		<h2>Sobre o Conjunto de Dados</h2>
		<p>	Esses conjuntos de dados são frequentemente usados ​​para diversos fins, como pesquisa de mercado, 
			desenvolvimento de produtos, modelagem preditiva, avaliação de risco e pesquisa acadêmica em áreas 
			como engenharia de transporte, engenharia automotiva, ciência de dados e aprendizado de máquina. 
			Inúmeras organizações, incluindo fabricantes automóveis, instituições de investigação, agências 
			governamentais e fornecedores de dados, contribuem para a criação e distribuição de conjuntos de dados automóveis. 
			Além disso, muitos conjuntos de dados estão disponíveis gratuitamente online, enquanto outros podem exigir 
			compra ou acesso através de serviços de assinatura.
		</p>
		<h2>Observação Importante:</h2>
		<p> Considerando que os valores da columa Mileage não estão na mesma unidade de medida, se faz necessários algums ajustes:<br><br>
		    CNG: A densidade do CNG varia de acordo com a pressão e composição do gás, mas um valor médio pode ser estimado em 0,72 kg/m³.<br>
    		    CNG ->  km_L_cng = km_kg_cng / 0.72<br><br>
                LPG: A densidade do LPG também varia de acordo com a composição do gás, mas um valor médio pode ser estimado em 0,5 kg/L.<br>
                LPG -> km_L_lpg = km_kg_lpg / 0.5
		</p>
		<h2>Conclusão:</h2>
		<p>Esse foi um exemplo simples de uso das ferramentas de Machine Learning para construir um modelo preditivo, pelo resultado, podemos observar que o RandomForestRegressor 
  		obteve um melhor desempenho  
  		com aproximadamente 91% de acerto nas estimativas realizadas, ou seja, foi o modelo que melhor se ajustou aos dados.<br> 
		Cabe destacar que esse desempenho ainda pode ser melhorado utilizando ajustes nos hiperparametros do modelo, mas não foi o objetivo deste trabalho!
		</p>	
	</body>
 
</html>
