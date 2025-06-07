# TCP-traffic-analysis
This is a part of my 'Computer Networks' course for my major.

The goal is to extract metrics such as medium time to establish a TCP handshake, estimated Round Time Trip/ Round Trip Delay, and others.
After gathering those metrics, the assignment requires the display of all those through a web application with plotted graphs to better visualize what was accomplished.

Toolset I opted for:
The bulk of the algorithms built to extract the metrics was built on C++, with a CSV output and one in bare text. The data capture was made with Wireshark and the resulting file was a pcap, which was later on filtered to a "TCP Only" file, another .pcap file. I also used python to guarantee the redundancy of the solution I developed in C++ in order to check on whether the resulting output would be the same for both the C++ and Python programs, which was confirmed.

--

Esse projeto é parte da disciplina "Redes de Computadores" do meu curso de graduação.

O objetivo é extrair métricas, como tempo médio de estabelecimento de conexão/handshake em pacotes TCP, tempo de viagem estimado dos pacotes, dentre outras.
Após reunir essas métricas, o trabalho exige a exposição dessas por meio de uma aplicação web, com gráficos projetados para uma melhor visualização do que foi realizado.


Ferramentas utilizadas:
A maior parte dos algoritmos que extraem essas métricas foi feito em C++, com output em arquivos CSV ou texto. A captura foi feita com Wireshark e o arquivo foi armazenado em um pcap, que foi posteriormente filtrado para um arquivo "Apenas TCP", outro arquivo .pcap. Também utilizei python para redundancia de solução em 2 arquivos diferentes, checando se os resultados seriam os mesmos para as minhas soluções em C++ e Python, o que foi confirmado.
