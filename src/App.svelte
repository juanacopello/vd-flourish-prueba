<!-- Script JS -->
<script>
</script>

<main>
    <div class="header">
      <img src="./images/premier_league_logo.png" width="200" alt="Logo Premier League" />
      <h3 class="headline">
        <b>Premier League</b>
        Explorando la liga a través de los datos
      </h3>
    </div>

    <!-- Agregar gráficos de Flourish con embed -->
    <div class="chart-wrapper">
        <div class="flourish-embed flourish-chart" data-src="visualisation/19282115"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/19282115/thumbnail" width="100%" alt="Goleadores temporada 23/24" /></noscript></div>
    </div>

    <div class="chart-wrapper">
        <div class="flourish-embed flourish-chart" data-src="visualisation/19282662"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/19282662/thumbnail" width="100%" alt="chart visualization" /></noscript></div>
    </div>

    <div class="chart-wrapper">
        <div class="flourish-embed flourish-chart" data-src="visualisation/19282469"><script src="https://public.flourish.studio/resources/embed.js"></script><noscript><img src="https://public.flourish.studio/visualisation/19282469/thumbnail" width="100%" alt="chart visualization" /></noscript></div>
    </div>

    <!-- Agregar gráficos de Flourish con imágenes -->
    <div class="chart-wrapper">
        <img src="./images/squad.png" width="90%" alt="Manchester City Squad" />
    </div>

</main>

<style>

    @import url('https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&display=swap');

    * {
        font-family: "DM Sans", sans-serif;
    }

    .header {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        margin-top: 50px;
        margin-bottom: 60px;
    }

    .headline {
        font-size: 30px;
        line-height: 1.2;
        font-weight: normal;
        text-align: center;
        margin: 20px;
    }

    .headline b {
        display: block;
        font-size: 35px;
        margin-bottom: 5px;
    }

    .chart-wrapper {
        max-width: 1100px;
        margin: auto;
        margin-bottom: 130px;
    }
        
</style>