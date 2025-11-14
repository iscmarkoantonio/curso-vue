<script>
import Card from './components/Card.vue';

export default {
  components: {
    Card,
  },
};

</script>

<template>
  <div>
    <h1>Componentes</h1>
    <hr />
    <h2>Redes Sociales</h2>
    <div class="card-container">
      <Card url="https://www.google.com/" title="Google" description="Google is a search engine"
        img="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3c/Google_Favicon_2025.svg/800px-Google_Favicon_2025.svg.png">
      </Card>
      <Card url="https://www.youtube.com/" title="Youtube" description="Youtube is a video plataform"
        img="https://1000marcas.net/wp-content/uploads/2020/02/YouTube-logo-600x338.png">
      </Card>
      <Card url="https://www.facebook.com/" title="Facebook" description="Facebook is a social media plataform"
        img="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAKkAAACUCAMAAADf7/luAAAAk1BMVEX///8Zd/P///4YePIAYuwAbfD8//3Z6/OOtO4Aae6rye/Z6/0AYOUAXufe7/wAaOXm8vs2fOwAcvRhlu290u/3+fzs+PwVdvbc6PW1zfFXlua81ff5/feewe0Ab+aqyfbL3/F8qe6YuupBhOYqeuSsy+pql+c6g+6jwfOYvPMSdOVIi+h2o+Sfxu2FrOtxoOoATdsY+ixoAAAElUlEQVR4nO2cDXOiMBCGQwLUFBWNSsAWD4o9r3p37f//dReonZMPDQkk4DTvTKfTqWwed/O5rgHAyMjIyMjI6O4FVViDCtQraW5OlXLLPaICEDyoUtALX/Gun8N4u7PVabf9EbpF4LqQsp8k3WNCLQspkkUJXqZJx+4KoftyLDAtZcpZKdm9uPKo+agMV3ZOiZAyn1o09wKy8CoEkvNA3kUXmaPQm2U52UJ6GoDBiqiMe0kIkVXwLMcJ3RRrwiwGAsWpK+nStV90UH2o/loq/hDsqS7MMyzZS82q8FVf7L9Q8asU6k+im9QiP0Vn1by7hAfNwWeih1DUpYw00s7JhJ5EJ3+2WvxyBiB1fon2UwjcySCkb+LRH4h04gqG35AqIC36qbal9JJUeOY3pH2Tdo7++VHKRD5F25xytJMiC1HiYNs/7rPTqtDptD/6M0xv29TvU0qs4+9XL9gUAuDzdxD84ZjUTUrJ8m/yuX//vzgWCZM1ur3t0UnKniF4EtYTY8V2ft27T7uMfZI9XN1m9E/aIfrO3+B6Am9MpPaLeyPVOJbos5MseXu+1dSaY0GbTxFJn2+mbEZDSg/B7cztaEhxAm/nFkZCipyU18woSPP8YqKfVGbsI/LObWYUPmWL0+NVa1/Nj2Pdp+jhirGvD4lyn/ZNKhN9crr2tt3NYu55ied58Sj2p86k0RBYROnp6E+nGPtT3nlXz9i36900D3mUEYe2Tcbp8amdNDgUTLBIylAP6dSrm3HfxPIbWkjprIE04cxK3Uklxj6qkbLJKRVMGekZUQ0+3ewE89oDkUI4n4qBDuZTOJ+NkrRh7BtSQ2pIz7oX0vvxqSEdBanVsO6PhtS/lPPhVRqB0Pvwy+JtWNSQoumiSlY3U9ELx6Yin9rzixrKpjrSWl2km5K+SdvMp2g2v/RiPb1bz6YFq95JW/l0Nhe0ya8YGQkpBMnutsXRkMInPMyIEiZ1J7wSrLGQwi2vBEvRXkq8nx6HmflFSdkkxT2qjoU0sfsnVRJ9ECsgVePTd25No7J1X9Bmxs39KNpL5et+eQdStVJWwC+9VbiXKmPVQS//bJGiVEQ6TRYlBTVSt/T/mJ/4UzT26bKkXUOub1d6BRdU4TmK/hc7R9UaYecoevmSAUkvv+PRdDadXn5vo4UG+0RipJneuznvG1JDqp3U5E8NqSE1pIb0u5Gamd+QGtLvSQrg3ZAO6FNR1IFI30S/ccjCL1g72BOp+Hd4IYjoAD61IuHgQ5AstZMia8mts29QcBJqpRef0pV4N2WKsXafOrE4Zn7HiC/WTGdSSv1A7kaM2BG5BqcHn2IplzJthC5u6UyKyGojBwphsuSUOPRKSo4yA/+sZNf+/o6upAxUmpNpfWhdjt+R1Dl0AoUw3NotUeVJ84tw7O2DfOg/Ud3XA3HawEqTUupY2WP3i9sgCKL3bIe5qtegAeh98J/DVpZGvVzbxt6sGyZP0SNPcbU5CIOY+1T0lCykltBG0saPbxteWXuyxX1B5zv7JOGqplpZalOD1vDUGVWWrmKs56sfK8aNjIyMjIyMjCr6B8SqfVwGDCvhAAAAAElFTkSuQmCC">
      </Card>
      <Card url="https://x.com/?lang=es" title="X" description="X is a social media plataform"
        img="https://play-lh.googleusercontent.com/XyI6Hyz9AFg7E_joVzX2zh6CpWm9B2DG2JuEz5meCFVm4-wTKTnHgqbmg62iFKe4Gzca=w240-h480-rw">
      </Card>
    </div>
    <h2>Frameworks</h2>
    <div class="card-container">
      <Card url="https://vuejs.org/" title="Vue" description="Vue is a Progressive framework"
        img="https://vuejs.org/images/logo.png">
      </Card>
      <Card url="https://es.react.dev/" title="React" description="React is a Progressive framework"
        img="https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/React.svg/800px-React.svg.png">
      </Card>
      <Card url="https://angular.dev/" title="Angular"
        description="The framework for building scalable web apps with confidence"
        img="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Angularjsoldicon.png/800px-Angularjsoldicon.png">
      </Card>
    </div>
  </div>
</template>

<style scoped>
h2 {
  color: #007bff;
}

.card-container {
  display: flex;
  flex-wrap: wrap;
}
</style>
