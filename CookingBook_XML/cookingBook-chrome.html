<?xml version="1.0" encoding="UTF-8"?>

<xsl:stylesheet xmlns:xsl="http://www.w3.org/1999/XSL/Transform" version="1.0">
  <xsl:output method="html"/> 
  
  <xsl:template match="/">
    <html>
	<head>
	<title>Готварски рецепти</title>

	<link rel="stylesheet" type="text/css" href="styles.css" />
	</head>
	<script>
		function showRecipes() {
			document.getElementById('recipesContainer').style.display = 'inline';
			document.getElementById('regionsContainer').style.display = 'none';
    };
		
		function showRegions() {
            document.getElementById('recipesContainer').style.display = 'none';
			document.getElementById('regionsContainer').style.display = 'inline';
    }
  </script>
	<body>
    <div class="topnav">
    <img id="logo" src="images/logo.png"/>
      <p id="title" style="font-size: 33px; color: #72a15a;">Готварски рецепти</p>
    
	  <a class="button" style="font-size: 33px; color:white;" onclick="showRecipes();">
			Рецепти
  	  </a>
	<a class="button" style="font-size: 33px; color:white;" onclick="showRegions()">
			Региони
  	</a>
</div>
       <xsl:apply-templates/>
    </body></html>
  </xsl:template>

  
  <xsl:template match="/recipes/recipeList">
    <div id="recipesContainer">
    	<xsl:for-each select="/recipes/recipeList/recipe/recipeInfo[id &lt; 11]">
				<xsl:sort
					select = "name"
					data-type="text"
					order = "ascending">
				</xsl:sort>

				<div style="color:white;" class="recipeContainer">
				
					<img src="images/{id}.jpg"/>
					<p id="recipeName"><xsl:value-of select="name"/></p>

                    <div class="products">
						<p id="tag">Продукти  </p>
						<div class="products-content">
							<xsl:for-each select="../ingredients/ingredient">
								<p id="ingredient"><xsl:value-of select="."/></p>
							</xsl:for-each>
						</div>
					</div>
					
					<div id="originInfo">
						<p id="tag">Произход</p>
						<p><xsl:value-of select="location"/></p>
						<p id="tag">Регион</p>
						<p><xsl:value-of select="region"/></p>
					</div>
					<div id="extraInfo">
						<p id="tag">Времетраене</p>
						<p><xsl:value-of select="time"/></p>
						<p id="tag" >Порции</p>
						<p><xsl:value-of select="portions"/></p>
					</div>
                    <div id="recipeSteps">
						<p id="tag">Рецепта</p>
						<p><xsl:value-of select="recipeSteps"/></p>
					</div>
				
				</div> 
  		</xsl:for-each>
  	</div>
  </xsl:template>



<xsl:template match="/recipes/regionList">
    <div id="regionsContainer" style="display:none;">
  		<xsl:for-each select="/recipes/regionList/regionInfo">
				<xsl:variable name="rName"><xsl:value-of select="regionName"/></xsl:variable>
				<xsl:variable name="rId"><xsl:value-of select="reg/@regIdRef"/></xsl:variable>

		<div style="color:white;" class="region">

				<p id="regionTag"><xsl:value-of select="regionName"/></p>
					<div>
						<xsl:for-each select="/recipes/recipeList/recipe/recipeInfo[regionId = $rId]">
															
									<div style="color:white;" class="specialRegion">
									
										<img src="images/{id}.jpg"/>

										<p id="recipeName"><xsl:value-of select="name"/></p>
                                    
										<div id="regInfo">
											<p id="tag" >Произход</p>
											<p><xsl:value-of select="location"/></p>
											<p id="tag" >Времетраене</p>
											<p><xsl:value-of select="time"/></p>
											<p id="tag" >Порции</p>
											<p><xsl:value-of select="portions"/></p>
										</div>
									</div>
						</xsl:for-each>
					</div>
		</div>
		</xsl:for-each>
	</div>
</xsl:template>

</xsl:stylesheet>