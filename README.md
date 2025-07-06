# Logikz

I designed a simple circuit board that can function as three different logic
gates:- `AND`, `OR`, and `NOR`

<p align="center">
  <img src="https://github.com/user-attachments/assets/30a7a17d-0ff3-4758-9647-2a490d5e5336" alt="image of my cute elephant shaped pcb" /><br>
</p>

### Making of Logikz
This is my third PCB and this time around I wanted to know how transistors
work, and also wanted to know how logic gates work. I myself implemented the
`AND` and `OR` gates but had to look up how to do a `NOR` gate. Later I also
changed how my `OR` gate works looking at the implementation of `NOR` gate.

The first iteration would've never worked, because of absolutely no current
calculations done. Used [circuit.js](https://www.falstad.com/circuit/circuitjs.html) to fix my implementation.
Earlier it had like 5 buttons, two for `A` and `B` inputs and the rset for
choosing between the gates. But had to ditch that idea because current it
didn't work in the simulation. Now I have 9 buttons, `A` and `B` for each
gates, so total 3 `A` and 3 `B` input buttons.

Reason why the first iteration didn't work: It had something to do with
"current takes the least resistive path", it is hard to explain in text.

The simulation file is present in `~/logikz_circuitjs.txt`, you can click [this](https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAQiQUgoFMBaMMAKADdxiUQUUAWTtzCFaokH1rYo0mAhYB3QeBFLCAyAtUDM3NVE06Qew8UL6ATjwzdTIbHgG3afDHAPWQTFdgTcvozR8-PjxnbGDQ-UUgz2Ewvzj9AGdxcM8Q2gQMMwYM6QgAMwBDABskuhYUvjT-CmzYlVpC0vLKu0I8BoowBLMmkGKyioAXEBwzPXG7IXBPFGhCbHtIGn5+SEIRbEYEKXnF5dW+dYQ8HB2IMDgQABM6YoBXEuHAhxBbewE9DWi3vWrdOpXo4zJ9wChOj87G8ep0AeDIW14XoEHwvupZoNWlU0rCKGiEfkBi0KpZKL0jPwurReFDrLQGGlQgy0nS0J40vTplEQMyOdw+azNKj0WNsBMgYoML5udlOkKpR1ZUq0IjFGAuDwqRruIYoTqrNw5YaecbVWMVR4NKM8MIjAJbaCZhAGPslqEjus+L5CDs9gt3StIGsJKdiHwLshaHdHs9NI77by7cxuFCRYSE3ioZmIUmzCmeXg0ky9AreaWBXoDdmq5q8MYrfGG0bLan49dGTYevyecRu53wGBxT39UOcrix3MqRphEJJ67tSgarxtLd7kUnsMGCU6DdZmIYJBWOql34V+C0nrND1Lx569pG6NpQlu8+Gv0IBhoDfxWAEKQ4BCRYdmIcBoGOPhCGsJZhFcAEUB2TormjddNxYG07SYbsE1qS45mgGgEEIIjgz4UhhE2BAQJ4aAUFRShiNMao-xQYhqOQtdYxeRVOlqPlajTepaimASWEsQwGA+JVJL6cRXChcVeILPhMILBTpMiFSckiDQqlU7t0yw1NMRJJFMMiQydJMoZNGInICxEtT4xqRIriI98eTc+yVC8qdJWQdyFwEZhhyCnkJMSCSYg0cSPEZGVFI5GVnHk9TeJiRLGTeNKku4TLwgCaJpIK8QOxKnKsoECQWWypEyrePJKqJLEKiqMr2Ua8rrNaMkCQYSI7M8KyXDcXqBCMoxArUuS3CfUKljMESwTwphoGwOUsnCbAh0oVw8EYPRXVgf8fB6VF62EIiIwYKtrhjDc41GKC-AWow4uW2YwHAosOn4ERMDIjpfRunJCAWbIsiuDAbxwU4qJupAOPutDFE6t5-xe2rFAxjl0c1RlhzTfHXuejlCc0Tr2SW9k6Xmqn5vJ7GhLyQgqVyHTbLZsFBqaqFWfGvI4PSDmpUgcawS5XnbLwdK-hl9IyzfJqlfhPn5dyTkZQ1tspS1+ErjZ1Xr1IhWhBWHIjfVc3TYC8clRi22OSVXywppNBAmku0Ir6dxARNMt+a6UmvB5YPOXZAc6S1hzQqcxRvZpOKnF9zxbAkkIeUyqSlO7Crs6GwrJu02gcJFvMC-Lia+fe3Q4rtKF086b3wrrsxDADw2Bq5rGxjF3GBCF9nC6imVG+HuK8hiIf9CAA) link to see my project in action.

### PCB

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/06f9c12e-bf34-4c05-bf65-c2df29d781f4" alt="top pcb image" width="300"/><br>
      <b>Front Of the PCB</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a42a7a64-b207-4534-ba95-aee12923765a" alt="back pcb image" width="300"/><br>
      <b>Back Of the PCB</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/832cce7b-9694-4537-843b-f8480b3259db" alt="back pcb without silkscreen" width="300"/><br>
      <b>Back of the PCB without Silkscreen</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/30a7a17d-0ff3-4758-9647-2a490d5e5336" alt="top pcb image" width="300"/><br>
      <b>Front Of the PCB (3D)</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/491c1f89-e4ea-4ac0-8286-7caf7f1733cc" alt="back pcb image" width="300"/><br>
      <b>Back Of the PCB (3D)</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/52db83fe-d667-4b68-b153-32be83ecdb65" alt="circuit simulation photo" width="300"/><br>
      <b>Simulation in CircuitJS</b>
    </td>
  </tr>
</table>

### SChematic
<p align="center">
  <img src="https://github.com/user-attachments/assets/9d7117c3-b738-418a-af0a-5732e502979e" alt="image of my cute elephant shaped pcb" /><br>
</p>

### BOM
`~/BOM.csv` has BOM of this project.

| QTY            | Name              |
| -------------- | ---------------   |
| 1              | Battery Holder    |
| 1              | LED               |
| 6              | NPN Transistor    |
| 2              | 220 Ohm Resistor  |
| 5              | 4.7k Ohm Resistor |
| 9              | Push Button       |


Made by `@Ankush Roy` in Slack from Hack Club

Made as a part of https://solder.hackclub.com/!
