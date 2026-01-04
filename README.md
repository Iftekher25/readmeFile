<div align="center">
  <pre>
<code>
<span style="color: #569cd6;">public class</span> <span style="color: #4ec9b0;">MdIftekherChowdhury</span> : <span style="color: #4ec9b0;">Controller</span>
{
    [<span style="color: #4ec9b0;">HttpGet</span>]
    <span style="color: #569cd6;">public</span> <span style="color: #4ec9b0;">IActionResult</span> <span style="color: #dcdcaa;">GetDeveloperProfile</span>()
    {
        <span style="color: #569cd6;">var</span> model = <span style="color: #569cd6;">new</span> <span style="color: #4ec9b0;">DeveloperRole</span> 
        {
            Title = <span style="color: #ce9178;">"Junior Full-Stack Software Developer"</span>,
            Specialization = <span style="color: #ce9178;">"ASP.NET Core & Angular"</span>,
            Focus = <span style="color: #ce9178;">"Scalable Web Solutions"</span>
        };

        <span style="color: #569cd6;">return</span> View(<span style="color: #ce9178;">"~/Views/Profile/Portfolio.cshtml"</span>, model);
    }
}
</code>
  </pre>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=iftychowdhury255&label=Profile%20Views&color=0e75b6&style=flat" alt="Visitors" />
  </p>
</div>
