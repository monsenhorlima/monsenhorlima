<style>body {
        font-family: Arial, sans-serif;
        text-align: center;
        padding: 20px;
        background-color: #f0f0f0;
        margin: 0;
    }
    .container {
        max-width: 400px;
        margin: auto;
        padding: 20px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        border-radius: 8px;
        background-color: #ffffff;
    }
    input {
        width: 90%;
        padding: 10px;
        margin: 10px 0;
        border-radius: 5px;
        border: 1px solid #ccc;
    }
    button {
        width: 95%;
        padding: 10px;
        background-color: #4CAF50;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
    }
    button:hover {
        background-color: #45a049;
    }
    .result {
        margin-top: 20px;
        padding: 10px;
        background-color: #e7f3e7;
        border-radius: 5px;
    }</style>
<div class="container">
  <table style="color: #333333; border: 0px solid #f5ffff; border-radius: 4px; width: 98%; max-width: 578px; mso-border-alt: none;" cellspacing="0" cellpadding="0">
    <tbody>
      <tr style="border: 0px solid #d5ecff; mso-border-alt: none; display: block; border-radius: 3px;">
        <td class="cloudHQ__main_td" style="display: block; padding: 0px; border-radius: 2px; border: 0px solid #99b0e1; font-size: 1em; vertical-align: top; background-color: white;">
          <table class="cloudHQ__second_table" style="border-collapse: collapse; width: 100%; text-align: left;" border="0" cellspacing="0" cellpadding="0">
            <tbody>
              <tr>
                <td style="padding-bottom: 6px;">&nbsp;</td>
              </tr>
              <tr>
                <td style="min-width: 100%; padding-top: 6px; padding-bottom: 6px; line-height: 16px; font-weight: normal; font-size: 13px; font-family: -apple-system, BlinkMacSystemFont, 'segoe ui', Helvetica, Arial, sans-serif, 'apple color emoji', 'segoe ui emoji', 'segoe ui symbol';">&nbsp;</td>
              </tr>
            </tbody>
          </table>
        </td>
      </tr>
    </tbody>
  </table>
  <h2>
    <span style="color: #000000;">Calculadora de Datas</span>
  </h2>
  <label for="dataNascimento">Data de Nascimento:</label> 
  <input id="dataNascimento" type="date"> 
  <label for="dataAtual">Data Atual:</label> 
  <input id="dataAtual" type="date"> 
  <button>Calcular</button>
  <div id="resultado" class="result">&nbsp;</div>
</div>
