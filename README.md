# NocodeLLM
노코드 LLM 실습 매뉴얼입니다.
<br>
<br>
## 교육 목표

- Nocode 툴을 이용하여 LLM 애플리케이션을 구성해보며 학습한다.

## 주의사항

- 교재에 있는 **화면 캡처**와 **수행코드/결과 예시**는 샘플일 뿐입니다.       
  실습 과정에서 화면이나 결과가 다르게 나타날 수 있습니다.      
  **혼동되시거나 궁금하신 점이 있으시면 실습강사에게 문의**하시기 바랍니다.         

- 아래의 **필수 설치**를 꼭 먼저 수행 부탁드립니다.      

<br>

## 실습


<table class="fixed-width wrapped confluenceTable" >
  <colgroup>
    <col style="width: 6.18034%;"/>
    <col style="width: 24.3161%;"/>
    <col style="width: 60.7427%;"/>
    <col style="width: 9.72644%;"/>
  </colgroup>
  <tbody>
    <tr>
      <td class="highlight-grey confluenceTd" data-highlight-colour="grey" style="text-align: center;"><strong>챕터</strong></td>
      <td class="highlight-grey confluenceTd" data-highlight-colour="grey" style="text-align: center;"><strong>구분</strong></td>
      <td class="highlight-grey confluenceTd" data-highlight-colour="grey" style="text-align: center;"><strong>내용</strong></td>
      <td class="highlight-grey confluenceTd" data-highlight-colour="grey" style="text-align: center;"><strong>시간</strong></td>
    </tr>
    <tr>
      <td style="text-align: center;" class="confluenceTd">1</td>
      <td style="text-align: left;" class="confluenceTd">Nocode LLM 툴 소개</td>
      <td style="text-align: left;" class="confluenceTd">0. Nocode LLM 툴 소개</td>
      <td rowspan="7" style="text-align: center;" class="confluenceTd">8</td>
    </tr>
    <tr>
      <td style="text-align: center;" class="confluenceTd">2</td>
      <td style="text-align: left;" class="confluenceTd">LangChain Chatbot 생성 실습</td>
      <td style="text-align: left;" class="confluenceTd">
        <p><a href="./doc/1.First_Chatbot Chatflow.md">1. 나만의 첫 LLM Chatbot</a></p>
        <p><a href="./doc/2.Multi_Chain_Chatbot Chatflow.md">2. Multi Chain Chatbot</a></p>
        <p>  - LLM Chain</p>
        <p>  - Output parser</p>
        <p>  - Ifelse Function</p></a>
        <p><a href="./doc/3.Memory_Chatbot Chatflow.md">3. Memory Chatbot</a></p>
        <p>  - Conversation Chain</p>
        <p>  - Buffer Memory</p>
        <p>  - Redis Memory</p></a>
        <p><a href="./doc/4.RAG_Chatbot Chatflow.md">4. RAG Chatbot</a></p>
        <p>  - Conversational Retrieval QA Chain</p>
        <p>  - In-Memory Vector Store</p>
        <p>  - External Vector Store</p>
        <p>  - Text Splitter</p>
        <p>  - PDF Document Loader</p>
        <p>  - Web Scraper</p></a>
      </td>
    </tr>
    <tr>
      <td style="text-align: center;" class="confluenceTd">3</td>
      <td style="text-align: left;" class="confluenceTd">LangChain Chatbot 분석</td>
      <td style="text-align: left;" class="confluenceTd">
        <p>5. Langchain 분석</p>
        <p>  - Langsmith</p></td>
    </tr>
    <tr>
      <td style="text-align: center;" class="confluenceTd">4</td>
      <td style="text-align: left;" class="confluenceTd">Agent 활용 Chatbot 생성 실습</td>
      <td style="text-align: left;" class="confluenceTd">
        <p><a href="./doc/6.Agent_Powered_Chatbot.md">6. Agent 활용 Chatbot</a></p>
        <p>  - Calculator</p>
        <p>  - Google Search</p>
        <p>  - RAG Agent</p></a>
      </td>
    </tr>
    <tr>
      <td style="text-align: center;" class="confluenceTd">5</td>
      <td style="text-align: left;" class="confluenceTd">
        <p>추가 모델 사용 Chatbot 생성 시연/실습<span> </span><strong>(LLAMA3.1 등)</strong></p>
      </td>
      <td style="text-align: left;" class="confluenceTd">
        <p>7. Ollama 이용한 Local Chatbot</p>
        <p><a href="./doc/8.Hugging_Face_Chatbot.md">8. HuggingFace Model 이용한 Chatbot</a></p>
        <p><a href="./doc/9.Image_Generation_Chatbot.md">9. 이미지 생성 Chatbot</a></p>
      </td>  
    </tr>
    <tr>
      <td style="text-align: center;" class="confluenceTd">6</td>
      <td style="text-align: left;" class="confluenceTd">
        <p>Chatbot 적용 시연</p>
      </td>
      <td style="text-align: left;" class="confluenceTd">
        <p>10. Web 에 배포</p>
      </td>
    </tr>
    <tr>
      <td style="text-align: center;" class="confluenceTd">7</td>
      <td style="text-align: left;" class="confluenceTd">추가 기능 사용 실습</td>
      <td style="text-align: left;" class="confluenceTd">
        <p><a href="./doc/11.Additional_Use.md">11. 추가 사용 팁</a></p>
        <p>  - Chatbot 커스터마이징</p>
        <p>  - 이미지 업로드</p>
        <p>  - 음성 입력</p>
        <p>  - 시작 Prompt 변경</p>
        <p>  - Security 설정</p>
        <p>  - Feedback 설정</p></a>
      </td>
    </tr>
  </tbody>
</table>


<br>
<br>


<br>
<br>

## 참고    


<table>
<thead>
  <tr>
    <th style="min-width: 40px;"></th>
    <th style="min-width: 190px;">교재</th>
    <th>내용</th>
  </tr>
</thead>
<tbody>
  <!-- 참고 -->
  <tr>
    <td rowspan="3"><center>1</center></td>
    <td>
      <a href="./etc/Requirement.md"> 필수설치 </a>
    </td>
    <td>
      <li>수업 전 필수 설치 목록 가이드</li>
    </td>
  </tr>


</tbody>
</table>
