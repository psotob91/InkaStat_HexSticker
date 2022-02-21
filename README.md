
<!-- README.md is generated from README.Rmd. Please edit that file -->
<style>
body {
text-align: justify}
</style>

# InkaStat Hex-Sticker

<a href="https://github.com/psotob/InkaStat_HexSticker"><img src="stickers_png/logo-inkastats-official.png" align="left" width="140" hspace="20" vspace="25"/></a>

<br>

En este repositorio encontrarás el código para reproducir la creación
del Hex-Sticker de **InkaStats Data Science Solutions** y la historia
detrás del concepto artístico que inspiró el logo. Además, encontrarás
algunas versiones alternativas de Hex-Stickers así como gif animados.

<br>

## Arte conceptual

El `quipu` (del quechua `“quipuni”`, nudo en español) fue un sistema
contable elaborado y utilizado por los administradores del imperio Inca,
los quipucamayoc, a principios del siglo XVI. Consiste en un cordón
grueso en la parte superior del que penden numerosos hilos verticales
delgados con nudos de diferentes estilos y colores que representaban
datos relacionados con la contabilidad tributaria incaica, el registro
de los censos, posesión de tierras, el trabajo, la producción, entre
diversos tipos de datos numéricos. Así, el `quipu` no solo funcionaba
como una `base de datos`, también puede considerarsele como la
representación más antigua de la `Estadística`y `Ciencia de Datos` que
tenemos en América Latina.

En **InkaStat** quisimos rendirle tributo a esta milenaria herramienta
de manejo y análisis de datos diseñada por los Incas, por lo que hicimos
un boceto a mano de este, mediante el programa
[`Canva`](https://www.canva.com/es_419/), y lo antepusimos ante un fondo
generado con el paquet [ggplot2](https://ggplot2.tidyverse.org/) de R
usando el tema predefinido `theme_gray()`, lo que generó un plano
cartesiano con aspecto de piedras de construcción incaica.

Asimismo, no perdimos la oportunidad de utilizar al quipu como una base
de datos y almacenar información relevante. Así, cada hilo de nuestro
logo representa un año que consideramos emblemático para la Estadística
y la Ciencia de Datos. Siete fechas clave han sido registradas cuyo
significado se describen a continuación:

    #> Warning in kable_styling(., bootstrap_options = c("striped", "hover",
    #> "condensed", : Please specify format in kable. kableExtra can customize either
    #> HTML or LaTeX outputs. See https://haozhu233.github.io/kableExtra/ for details.

| Hilo                                                                        | Trazo                                                                                                                                                                 | Año                                                       | Significado                                                                                                                                                                                                                                                                                                                                                                |
|:----------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <span style="     color: #2270B8 !important;text-align: c;">Azul</span>     | <span style="     color: #2270B8 !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #2270B8 !important;text-align: c;">——</span> | <span style="     color: #2270B8 !important;">2022</span> | Fundación de InkaStats Data Science Solutions.                                                                                                                                                                                                                                                                                                                             |
| <span style="     color: #C18D00 !important;text-align: c;">Amarillo</span> | <span style="     color: #C18D00 !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #C18D00 !important;text-align: c;">——</span> | <span style="     color: #C18D00 !important;">1935</span> | El matemático, estadístico y biólogo Ronald Aylmer Fisher, basándose en su experiencia en el Rothamsted Research con datos de cultivos agrícolas, publica su libro ‘The Design of Experiments’, libro con el que no solo propone las bases estadísticas, sino también filosóficas, del Diseño de Experimentos.                                                             |
| <span style="     color: #528235 !important;text-align: c;">Verde</span>    | <span style="     color: #528235 !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #528235 !important;text-align: c;">——</span> | <span style="     color: #528235 !important;">1962</span> | El estadístico Jhon Wilder Tukey publica su artículo ‘The future of Data Analysis’, en el que se cuestiona el futuro de la Estadística como ciencia empírica dando así origen a la Ciencia de Datos como disciplina.                                                                                                                                                       |
| <span style="     color: #67229B !important;text-align: c;">Morado</span>   | <span style="     color: #67229B !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #67229B !important;text-align: c;">——</span> | <span style="     color: #67229B !important;">1979</span> | El estadístico Bradley Efron publica su artículo ‘Bootstrap Methods: Another Look at the Jackknife’, publicación que marca el inicio del Bootstrap como método de remuestreo, lo que lo lleva a ser considerado padre de la Estadística Computacional.                                                                                                                     |
| <span style="     color: #424242 !important;text-align: c;">Gris</span>     | <span style="     color: #424242 !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #424242 !important;text-align: c;">——</span> | <span style="     color: #424242 !important;">1910</span> | Conmemoración del fallecimiento de la enfermera, estadística y matemática Florence Nightingale, conocida por crear el Diagrama de Área Polar para contabilizar las muertes durante la Guerra de Crimea, lo que le significó ser elegida como miembro de la Sociedad Estadística de Inglaterra en 1858.                                                                     |
| <span style="     color: #D49264 !important;text-align: c;">Naranja</span>  | <span style="     color: #D49264 !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #D49264 !important;text-align: c;">——</span> | <span style="     color: #D49264 !important;">1966</span> | La investigadora Madeleine Guilbert publica su libro ‘Les fonctions des femmes dans l´industrie’, libro en el que, por primera vez, se utiliza la estadística aplicada para denunciar públicamente un problema social como la discriminación de género en los mercados laborales de la época basándose en la aplicación de la técnica de investigación social por encuesta |
| <span style="     color: #8F0000 !important;text-align: c;">Rojo</span>     | <span style="     color: #8F0000 !important;border-radius: 4px; padding-right: 4px; padding-left: 4px; background-color: #8F0000 !important;text-align: c;">——</span> | <span style="     color: #8F0000 !important;">1950</span> | El matemático e informático teórico Alan Mathison Turing publica lo que hoy se conoce como el Test de Turing, herramienta utilizada para medir la inteligencia de las máquinas, por lo que es considerado pionero en campos como la Inteligencia artificial y el Machine learning, componentes de la Ciencia de Datos                                                      |

## Hex-Wall de Hex-Stickers alternativos

## Gifs animados de Hex-Stickers

## Autores

-   [Anthony Romero](https://github.com/AnthonyRomeroC)
    (<anthony.romeromh@gmail.com>)

    -   Boceto y diseño gráfico del Quipu.

    -   Co-Codeo de Hex-Sticker.

    -   Redacción de arte conceptual.

-   [Christian Vasquez](https://github.com/cvasquezvel)
    (<cvasquezvel@gmail.com>)

    -   Co-creación de nombre InkaStats.

    -   Revisión y aporte con ideas al Hex-Sticker.

    -   Co-ideación de arte conceptual

-   [Percy Soto-Becerra](https://github.com/psotob)
    (<percys1991@gmail.com>)

    -   Co-creación de nombre InkaStats.

    -   Codeo de Hex-Sticker.

    -   Ideación de arte conceptual.

    -   Creación del repositorio GitHub.

## Referencias Bibliográficas

-   Wong Torres Z., Salcedo Guzmán L. Quipus: nudos numéricos y
    parlantes. Quipucamayoc, 2005; 12(24). Disponible en:
    <https://doi.org/10.15381/quipu.v12i24.5435>

-   Macho Stadler M. El quipu: ¿algo más que un registro numérico?
    \[Internet\]. Cuaderno de cultura científica. 2015. Disponible en:
    <https://culturacientifica.com/2015/09/16/el-quipu-algo-mas-que-un-registro-numerico/>

-   Ronald Fisher. Wikipedia, La enciclopedia libre. 2022. Disponible
    en: <https://es.wikipedia.org/wiki/Ronald_Fisher>

-   Tukey J. The Future of Data Analysis. The Annals of Mathematical
    Statistics. 1962; 33(1):1–67. <doi:10.1214/aoms/1177704711>

-   Bradley E. Bootstrap Methods: Another Look at the Jackknife. The
    Annals of Statistics. 1979; 7(1):1-26. Disponible en:
    <https://www.jstor.org/stable/2958830>

-   Young P, Hortis De Smith V, Chambi M, Finn B. Florence Nightingale
    (1820-1910), a 101 años de su fallecimiento. Rev. méd. Chile. 2011;
    139(6):807-813. Disponible en:
    <http://dx.doi.org/10.4067/S0034-98872011000600017>

-   Ballesteros D., Blanco F. Mujeres que aplicaron la estadística para
    transformar el mundo: Florence Nightingale y Madelein Guilbert. VI
    Congreso internacional de Historia de la Estadística y de la
    Probabilidad. 2011. Disponible en: <https://eprints.ucm.es/16911/>

-   Gonzales R. El test de Turing: dos mitos, un dogma. Revista de
    filosofía. 2007; 63:37-53. Disponible en:
    <http://dx.doi.org/10.4067/S0718-43602007000100003>
