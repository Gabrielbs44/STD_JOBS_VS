# PRINCIPAL: GPON ("|")

<details class="001 COLOR HILOS ">
    <summary>001 - Fibra de colores</summary>
    1. Azul      --
    2. Naranja   -- 
    3. Verde     --
    4. Café      -- 
    5. Gris      -- 
    6. Blanco    --
    7. Rojo      -- 
    8. Negro     --
    9. Amarillo  --
    10. Violeta  --
    11. Rosado   --
    12. Celeste  --
</details>

<details class="002 INF GENERAL ">
  <summary>002 - información general de OLT a ONT </summary>
    la red gpon cuenta con 128 salidas desde el esplitter que sale desde la olt 
    una OLT puede llegar a tener 1024 clientes 
    puede llegar a tener una distancia de fibra de 20km en B+ y 40km en C+
    maneja 2.488 Gbits/s
     ------------------ejemplo con modulo B+  desde OLT " 1410nm frec bajada"  (-22.56dBm que esta entre RX -8 y -28 )
        (OLT)-(C)-(F)(SPL)-(SPL)-(F)-(DIS <n>Km)-(F)-(C)
        (3dB)-(6dB)-(1dB)-(9.02dB)-(12.04dB)-(1dB)-(0.3dB *<10>Km)-(1dB)-(6dB)
        3 - 0.6 - 0.1 - 9.02   - 12.04   - 0.1   - 3          - 0.1 - 0.6
        valor -22.56 dBs (estando dentro del rango de b+ esta aceptable )
    ------------------ejemplo con modulo B+ desde CJ OB " 1310nm frec subida" (-24.56dBm que esta entre RX -8 y -28 )
        (OLT)-(C)-(F)(SPL)-(SPL)-(F)-(DIS <n>Km)-(F)-(C)
        (3dB)-(6dB)-(1dB)-(9.02dB)-(12.04dB)-(1dB)-(0.5dB *<10>Km)-(1dB)-(6dB)
        3 - 0.6 - 0.1 - 9.02   - 12.04   - 0.1   - 5          - 0.1 - 0.6
        valor -24.56 dBs (estando dentro del rango de b+ esta aceptable )
</details>

<details class="003 SOFTWARE ">
  --------------AUTOCAD-------------
 </details>
