# Privacy Policy — Smart Clicker

**Last updated: July 30, 2026**

Languages: [English](#english) · [简体中文](#简体中文) · [繁體中文](#繁體中文) · [Español](#español) · [日本語](#日本語) · [한국어](#한국어) · [Português (Brasil)](#português-brasil)

---

## English

Smart Clicker (“the Extension”) respects your privacy. This policy explains what data the Extension stores locally, what limited product analytics it sends, and how that data is used.

### Data stored locally

The Extension stores the information required to run your timed-click tasks in your browser using `chrome.storage.local`. This may include:

- the page address used to keep a task associated with the correct page;
- target element selectors;
- countdown, repeat, schedule, and wait-condition settings;
- task state and recent results;
- language preference; and
- a randomly generated analytics identifier.

Task data is used only to provide the Extension’s features. Page addresses, domains, selectors, element text, and exact timer values are not included in analytics events and are not uploaded by the Extension.

### Limited product analytics

The Extension sends a limited set of product-usage events to Mixpanel by default. There is no analytics switch in the popup.

The event payload may contain:

- a randomly generated pseudonymous identifier that is not linked to an account;
- event timestamp;
- Extension version;
- selected interface language;
- operating-system platform;
- event name; and
- limited event-specific properties, such as selector category, task mode, a broad delay range, whether a wait condition is enabled, failure category, or selected language.

Only allowlisted product-interaction and task-status events are permitted.

The Extension does not use Mixpanel Autocapture, session replay, page-view tracking, advertising profiles, or Mixpanel user profiles. It does not call Mixpanel `identify`.

The Extension does not intentionally collect or send your name, email address, account credentials, browsing history, page URL, domain, CSS selector, element text, form contents, or exact timer values. As with any internet request, Mixpanel may process technical connection information such as an IP address in accordance with its own policy; the Extension does not add an IP address to the analytics event payload.

### How data is used and shared

Locally stored task data is used only to operate the Extension. Limited analytics is used only to understand feature adoption, diagnose broad failure categories, and improve the Extension.

The Extension does not sell personal data, show advertising, or use cross-site tracking. Limited analytics data is sent only to Mixpanel, our analytics service provider. Mixpanel processes that data under its applicable terms and privacy documentation:

- [Mixpanel Privacy Statement](https://mixpanel.com/legal/privacy-policy/)
- [Mixpanel Data Processing Addendum](https://mixpanel.com/legal/dpa/)

### Permissions

The Extension requests these permissions:

- **activeTab** — access the current supported webpage after user interaction;
- **storage** — store tasks, settings, results, language preference, and the analytics identifier locally;
- **alarms** — keep countdown and scheduled tasks active in the background;
- **notifications** — show task execution results;
- **scripting** — start element selection and execute clicks on supported webpages;
- **contextMenus** — provide the timed-click shortcut in the webpage context menu; and
- **Host access to `https://api.mixpanel.com/*`** — send the limited analytics events described above.

The Extension cannot operate on browser-protected pages or other pages where extensions are not permitted.

### Your choices and data deletion

You may remove locally stored Extension data by removing tasks or uninstalling the Extension. Clearing local data resets the locally generated analytics identifier, but it does not automatically delete events that were previously sent to Mixpanel. The current version does not provide an analytics opt-out switch in the popup.

### Security

We minimize the data included in analytics and restrict event names and properties through an allowlist. Analytics failures are discarded and do not affect task execution. No method of storage or internet transmission is completely secure.

### Policy changes

We may update this policy to reflect changes to the Extension, service providers, or legal requirements. Material changes will be communicated through an Extension update or an updated policy date.

### Contact

For privacy questions or requests, please open an issue in the Smart Clicker GitHub repository.

---

## 简体中文

Smart Clicker（“本扩展”）尊重您的隐私。本政策说明扩展在本地保存哪些数据、会发送哪些有限的产品统计，以及这些数据的用途。

### 本地存储的数据

本扩展使用 `chrome.storage.local` 在浏览器中保存运行定时点击任务所需的信息，可能包括：

- 用于确保任务与正确页面关联的页面地址；
- 目标元素选择器；
- 倒计时、重复、定时和等待条件设置；
- 任务状态和最近结果；
- 语言偏好；以及
- 随机生成的统计标识符。

任务数据仅用于提供扩展功能。页面地址、域名、选择器、元素文本和精确计时值不会包含在统计事件中，也不会由本扩展上传。

### 有限的产品统计

本扩展默认向 Mixpanel 发送有限的产品使用事件，弹窗中不提供统计开关。

事件数据可能包含：

- 与任何账户均不关联的随机假名标识符；
- 事件时间戳；
- 扩展版本；
- 已选择的界面语言；
- 操作系统平台；
- 事件名称；以及
- 有限的事件属性，例如选择器类别、任务模式、大致延迟区间、是否启用等待条件、失败类别或已选择语言。

仅允许发送白名单中的产品交互和任务状态事件。

本扩展不使用 Mixpanel 自动采集、会话回放、页面浏览追踪、广告画像或 Mixpanel 用户画像，也不会调用 Mixpanel `identify`。

本扩展不会主动收集或发送您的姓名、邮箱、账户凭据、浏览历史、页面 URL、域名、CSS 选择器、元素文本、表单内容或精确计时值。与任何网络请求一样，Mixpanel 可能会根据其自身政策处理 IP 地址等技术连接信息；本扩展不会在统计事件数据中主动加入 IP 地址。

### 数据用途与共享

本地任务数据仅用于运行本扩展。有限统计仅用于了解功能使用情况、分析大致失败类别并改进扩展。

本扩展不会出售个人数据，不展示广告，也不进行跨站追踪。有限统计数据仅发送给我们的分析服务提供商 Mixpanel。Mixpanel 根据其适用条款和隐私文件处理这些数据：

- [Mixpanel 隐私声明](https://mixpanel.com/legal/privacy-policy/)
- [Mixpanel 数据处理附录](https://mixpanel.com/legal/dpa/)

### 权限说明

本扩展申请以下权限：

- **activeTab** — 在用户操作后访问当前受支持网页；
- **storage** — 在本地保存任务、设置、结果、语言偏好和统计标识符；
- **alarms** — 在后台维持倒计时和定时任务；
- **notifications** — 显示任务执行结果；
- **scripting** — 在受支持网页上启动元素选择并执行点击；
- **contextMenus** — 在网页右键菜单中提供定时点击快捷入口；以及
- **访问 `https://api.mixpanel.com/*`** — 发送上述有限统计事件。

本扩展无法在浏览器保护页面或其他禁止扩展运行的页面上工作。

### 您的选择与数据删除

您可以通过移除任务或卸载扩展来删除本地保存的扩展数据。清除本地数据会重置本地生成的统计标识符，但不会自动删除此前已发送给 Mixpanel 的事件。当前版本的弹窗不提供关闭统计的选项。

### 安全

我们尽量减少统计数据，并通过白名单限制可发送的事件名称和属性。统计发送失败会被直接丢弃，不会影响任务执行。任何存储或网络传输方式都无法保证绝对安全。

### 政策更新

我们可能根据扩展功能、服务提供商或法律要求的变化更新本政策。重大变更将通过扩展更新或更新政策日期的方式说明。

### 联系方式

如有隐私问题或请求，请在 Smart Clicker GitHub 仓库中提交 Issue。

---

## 繁體中文

Smart Clicker（「本擴充功能」）尊重您的隱私。本政策說明擴充功能在本機儲存哪些資料、會傳送哪些有限的產品分析資料，以及這些資料的用途。

### 儲存在本機的資料

本擴充功能使用 `chrome.storage.local` 在瀏覽器中儲存執行定時點擊任務所需的資訊，可能包括：

- 用於確保任務與正確頁面關聯的頁面位址；
- 目標元素選擇器；
- 倒數、重複、排程及等待條件設定；
- 任務狀態與最近結果；
- 語言偏好；以及
- 隨機產生的分析識別碼。

任務資料只用於提供擴充功能。頁面位址、網域、選擇器、元素文字和精確計時值不會包含在分析事件中，也不會由本擴充功能上傳。

### 有限的產品分析

本擴充功能預設會向 Mixpanel 傳送有限的產品使用事件，彈出視窗中不提供分析開關。

事件資料可能包含：

- 不與任何帳戶連結的隨機假名識別碼；
- 事件時間戳記；
- 擴充功能版本；
- 已選擇的介面語言；
- 作業系統平台；
- 事件名稱；以及
- 有限的事件屬性，例如選擇器類別、任務模式、大致延遲區間、是否啟用等待條件、失敗類別或已選擇語言。

只允許傳送白名單中的產品互動與任務狀態事件。

本擴充功能不使用 Mixpanel 自動擷取、工作階段重播、頁面瀏覽追蹤、廣告設定檔或 Mixpanel 使用者設定檔，也不會呼叫 Mixpanel `identify`。

本擴充功能不會主動收集或傳送您的姓名、電子郵件、帳戶憑證、瀏覽記錄、頁面 URL、網域、CSS 選擇器、元素文字、表單內容或精確計時值。與任何網路請求一樣，Mixpanel 可能依其自身政策處理 IP 位址等技術連線資訊；本擴充功能不會在分析事件資料中主動加入 IP 位址。

### 資料用途與分享

本機任務資料只用於執行本擴充功能。有限分析只用於瞭解功能使用情況、分析大致失敗類別及改善擴充功能。

本擴充功能不會出售個人資料、不顯示廣告，也不進行跨網站追蹤。有限分析資料只會傳送給我們的分析服務供應商 Mixpanel。Mixpanel 依其適用條款及隱私文件處理這些資料：

- [Mixpanel 隱私聲明](https://mixpanel.com/legal/privacy-policy/)
- [Mixpanel 資料處理附錄](https://mixpanel.com/legal/dpa/)

### 權限說明

本擴充功能要求以下權限：

- **activeTab** — 在使用者操作後存取目前受支援的網頁；
- **storage** — 在本機儲存任務、設定、結果、語言偏好及分析識別碼；
- **alarms** — 在背景維持倒數及排程任務；
- **notifications** — 顯示任務執行結果；
- **scripting** — 在受支援網頁上啟動元素選取並執行點擊；
- **contextMenus** — 在網頁右鍵選單中提供定時點擊捷徑；以及
- **存取 `https://api.mixpanel.com/*`** — 傳送上述有限分析事件。

本擴充功能無法在瀏覽器保護頁面或其他禁止擴充功能執行的頁面上運作。

### 您的選擇與資料刪除

您可以移除任務或解除安裝擴充功能，以刪除儲存在本機的擴充功能資料。清除本機資料會重設本機產生的分析識別碼，但不會自動刪除先前已傳送給 Mixpanel 的事件。目前版本的彈出視窗不提供關閉分析的選項。

### 安全

我們盡量減少分析資料，並透過白名單限制可傳送的事件名稱與屬性。分析傳送失敗會直接捨棄，不會影響任務執行。任何儲存或網路傳輸方式都無法保證絕對安全。

### 政策更新

我們可能因擴充功能、服務供應商或法律要求的變更而更新本政策。重大變更將透過擴充功能更新或更新政策日期的方式說明。

### 聯絡方式

如有隱私問題或請求，請在 Smart Clicker GitHub 儲存庫中提交 Issue。

---

## Español

Smart Clicker (“la Extensión”) respeta tu privacidad. Esta política explica qué datos guarda localmente, qué datos limitados de uso envía y cómo se utilizan.

### Datos almacenados localmente

La Extensión utiliza `chrome.storage.local` para guardar en el navegador la información necesaria para ejecutar las tareas de clic programado. Esta puede incluir:

- la dirección de la página utilizada para asociar la tarea con la página correcta;
- selectores de elementos de destino;
- ajustes de cuenta atrás, repetición, programación y condiciones de espera;
- estado de las tareas y resultados recientes;
- preferencia de idioma; y
- un identificador de análisis generado aleatoriamente.

Los datos de las tareas se utilizan únicamente para ofrecer las funciones de la Extensión. Las direcciones de páginas, dominios, selectores, textos de elementos y valores de tiempo exactos no se incluyen en los eventos de análisis ni son cargados por la Extensión.

### Análisis limitado del producto

La Extensión envía de forma predeterminada a Mixpanel un conjunto limitado de eventos de uso del producto. La ventana emergente no incluye un interruptor para desactivar el análisis.

Los eventos pueden contener:

- un identificador seudónimo aleatorio no vinculado a una cuenta;
- marca de tiempo del evento;
- versión de la Extensión;
- idioma seleccionado de la interfaz;
- plataforma del sistema operativo;
- nombre del evento; y
- propiedades limitadas, como categoría del selector, modo de tarea, intervalo general de retraso, uso de una condición de espera, categoría del error o idioma seleccionado.

Solo se permiten eventos incluidos en una lista restringida sobre interacciones con el producto y estados de las tareas.

La Extensión no utiliza Autocapture de Mixpanel, reproducción de sesiones, seguimiento de páginas vistas, perfiles publicitarios ni perfiles de usuario de Mixpanel, y no llama a `identify`.

La Extensión no recopila ni envía intencionadamente tu nombre, correo electrónico, credenciales, historial de navegación, URL, dominio, selector CSS, texto de elementos, contenido de formularios ni valores de tiempo exactos. Como ocurre con cualquier solicitud de Internet, Mixpanel puede procesar información técnica de conexión, como una dirección IP, de acuerdo con su propia política; la Extensión no añade direcciones IP a los eventos.

### Uso y comunicación de los datos

Los datos locales de las tareas se utilizan únicamente para ejecutar la Extensión. El análisis limitado se utiliza únicamente para conocer la adopción de funciones, analizar categorías generales de errores y mejorar la Extensión.

La Extensión no vende datos personales, no muestra publicidad y no realiza seguimiento entre sitios. Los datos limitados de análisis se envían únicamente a Mixpanel, nuestro proveedor de análisis. Mixpanel los procesa conforme a sus términos y documentos de privacidad aplicables:

- [Declaración de privacidad de Mixpanel](https://mixpanel.com/legal/privacy-policy/)
- [Anexo de tratamiento de datos de Mixpanel](https://mixpanel.com/legal/dpa/)

### Permisos

La Extensión solicita los siguientes permisos:

- **activeTab** — acceder a la página compatible actual después de una acción del usuario;
- **storage** — guardar localmente tareas, ajustes, resultados, idioma e identificador de análisis;
- **alarms** — mantener cuentas atrás y tareas programadas en segundo plano;
- **notifications** — mostrar resultados de ejecución;
- **scripting** — iniciar la selección de elementos y ejecutar clics en páginas compatibles;
- **contextMenus** — ofrecer el acceso directo de clic programado en el menú contextual; y
- **Acceso a `https://api.mixpanel.com/*`** — enviar los eventos limitados descritos anteriormente.

La Extensión no puede funcionar en páginas protegidas por el navegador ni en otras páginas donde no se permita ejecutar extensiones.

### Tus opciones y eliminación de datos

Puedes eliminar los datos locales quitando tareas o desinstalando la Extensión. Borrar los datos locales restablece el identificador generado localmente, pero no elimina automáticamente los eventos enviados anteriormente a Mixpanel. La versión actual no ofrece una opción para desactivar el análisis en la ventana emergente.

### Seguridad

Reducimos al mínimo los datos de análisis y limitamos mediante una lista permitida los eventos y propiedades que pueden enviarse. Los fallos de análisis se descartan y no afectan a las tareas. Ningún método de almacenamiento o transmisión por Internet es totalmente seguro.

### Cambios de esta política

Podemos actualizar esta política para reflejar cambios en la Extensión, los proveedores o los requisitos legales. Los cambios importantes se comunicarán mediante una actualización de la Extensión o la fecha actualizada de esta política.

### Contacto

Para preguntas o solicitudes de privacidad, abre una incidencia en el repositorio de GitHub de Smart Clicker.

---

## 日本語

Smart Clicker（以下「本拡張機能」）は、利用者のプライバシーを尊重します。本ポリシーでは、本拡張機能がローカルに保存するデータ、送信する限定的な製品分析データ、およびその利用目的について説明します。

### ローカルに保存されるデータ

本拡張機能は、時間指定クリックタスクの実行に必要な情報を `chrome.storage.local` を使用してブラウザ内に保存します。これには次の情報が含まれる場合があります。

- タスクを正しいページに関連付けるためのページアドレス
- 対象要素のセレクター
- カウントダウン、繰り返し、スケジュール、待機条件の設定
- タスクの状態と最近の結果
- 言語設定
- ランダムに生成された分析用識別子

タスクデータは、本拡張機能の機能を提供するためにのみ使用されます。ページアドレス、ドメイン、セレクター、要素のテキスト、正確なタイマー値は分析イベントに含まれず、本拡張機能によってアップロードされません。

### 限定的な製品分析

本拡張機能は、限定された製品利用イベントをデフォルトで Mixpanel に送信します。ポップアップには分析を無効にするスイッチはありません。

イベントには次の情報が含まれる場合があります。

- アカウントに関連付けられていない、ランダムに生成された仮名識別子
- イベントのタイムスタンプ
- 本拡張機能のバージョン
- 選択された表示言語
- OS プラットフォーム
- イベント名
- セレクター分類、タスクモード、大まかな遅延範囲、待機条件の有無、失敗分類、選択された言語などの限定的なイベント属性

許可リストに含まれる製品操作およびタスク状態のイベントのみ送信できます。

本拡張機能は、Mixpanel Autocapture、セッションリプレイ、ページビュー追跡、広告プロファイル、Mixpanel ユーザープロファイルを使用せず、`identify` も呼び出しません。

本拡張機能は、氏名、メールアドレス、アカウント認証情報、閲覧履歴、ページ URL、ドメイン、CSS セレクター、要素のテキスト、フォームの内容、正確なタイマー値を意図的に収集または送信しません。一般的なインターネット通信と同様に、Mixpanel は独自のポリシーに従って IP アドレスなどの技術的な接続情報を処理する場合があります。本拡張機能がイベントデータに IP アドレスを追加することはありません。

### データの利用と共有

ローカルのタスクデータは、本拡張機能を動作させるためにのみ使用されます。限定的な分析データは、機能の利用状況、一般的な失敗分類の把握、および本拡張機能の改善にのみ使用されます。

本拡張機能は個人データを販売せず、広告を表示せず、クロスサイト追跡を行いません。限定的な分析データは、分析サービス提供者である Mixpanel にのみ送信されます。Mixpanel は、適用される規約とプライバシー文書に従ってデータを処理します。

- [Mixpanel プライバシーステートメント](https://mixpanel.com/legal/privacy-policy/)
- [Mixpanel データ処理補遺](https://mixpanel.com/legal/dpa/)

### 権限

本拡張機能は、次の権限を要求します。

- **activeTab** — 利用者の操作後に、現在の対応ページへアクセスする
- **storage** — タスク、設定、結果、言語設定、分析用識別子をローカルに保存する
- **alarms** — カウントダウンとスケジュール済みタスクをバックグラウンドで維持する
- **notifications** — タスクの実行結果を表示する
- **scripting** — 対応ページで要素選択を開始し、クリックを実行する
- **contextMenus** — ページのコンテキストメニューに時間指定クリックのショートカットを表示する
- **`https://api.mixpanel.com/*` へのアクセス** — 上記の限定的な分析イベントを送信する

本拡張機能は、ブラウザで保護されたページや、拡張機能の実行が許可されていないページでは動作しません。

### 利用者の選択とデータの削除

タスクを削除するか本拡張機能をアンインストールすると、ローカルに保存されたデータを削除できます。ローカルデータを消去すると、ローカルで生成された分析用識別子はリセットされますが、以前に Mixpanel へ送信されたイベントは自動的には削除されません。現在のバージョンでは、ポップアップから分析を無効にできません。

### セキュリティ

分析データを最小限に抑え、許可リストによって送信可能なイベント名と属性を制限しています。分析の送信失敗は破棄され、タスクの実行には影響しません。保存またはインターネット送信の方法に完全な安全性を保証することはできません。

### ポリシーの変更

本拡張機能、サービス提供者、法的要件の変更を反映するため、本ポリシーを更新する場合があります。重要な変更は、本拡張機能の更新または本ポリシーの更新日によってお知らせします。

### お問い合わせ

プライバシーに関する質問や依頼は、Smart Clicker の GitHub リポジトリで Issue を作成してください。

---

## 한국어

Smart Clicker(이하 “확장 프로그램”)는 사용자의 개인정보를 존중합니다. 본 정책은 확장 프로그램이 로컬에 저장하는 데이터, 전송하는 제한적인 제품 분석 데이터 및 그 사용 목적을 설명합니다.

### 로컬에 저장되는 데이터

확장 프로그램은 예약 클릭 작업 실행에 필요한 정보를 `chrome.storage.local`을 사용하여 브라우저에 저장합니다. 여기에는 다음 정보가 포함될 수 있습니다.

- 작업을 올바른 페이지와 연결하기 위한 페이지 주소
- 대상 요소 선택자
- 카운트다운, 반복, 예약 및 대기 조건 설정
- 작업 상태 및 최근 결과
- 언어 설정
- 무작위로 생성된 분석 식별자

작업 데이터는 확장 프로그램의 기능을 제공하는 데에만 사용됩니다. 페이지 주소, 도메인, 선택자, 요소 텍스트 및 정확한 타이머 값은 분석 이벤트에 포함되지 않으며 확장 프로그램에서 업로드하지 않습니다.

### 제한적인 제품 분석

확장 프로그램은 제한된 제품 사용 이벤트를 기본적으로 Mixpanel에 전송합니다. 팝업에는 분석을 끄는 스위치가 없습니다.

이벤트에는 다음 정보가 포함될 수 있습니다.

- 계정과 연결되지 않은 무작위 가명 식별자
- 이벤트 타임스탬프
- 확장 프로그램 버전
- 선택한 인터페이스 언어
- 운영 체제 플랫폼
- 이벤트 이름
- 선택자 범주, 작업 모드, 대략적인 지연 범위, 대기 조건 사용 여부, 실패 범주 또는 선택한 언어와 같은 제한적인 이벤트 속성

허용 목록에 포함된 제품 상호작용 및 작업 상태 이벤트만 전송할 수 있습니다.

확장 프로그램은 Mixpanel Autocapture, 세션 리플레이, 페이지 조회 추적, 광고 프로필 또는 Mixpanel 사용자 프로필을 사용하지 않으며 `identify`를 호출하지 않습니다.

확장 프로그램은 이름, 이메일 주소, 계정 자격 증명, 검색 기록, 페이지 URL, 도메인, CSS 선택자, 요소 텍스트, 양식 내용 또는 정확한 타이머 값을 의도적으로 수집하거나 전송하지 않습니다. 일반적인 인터넷 요청과 마찬가지로 Mixpanel은 자체 정책에 따라 IP 주소와 같은 기술 연결 정보를 처리할 수 있습니다. 확장 프로그램은 분석 이벤트 데이터에 IP 주소를 추가하지 않습니다.

### 데이터 사용 및 공유

로컬 작업 데이터는 확장 프로그램을 실행하는 데에만 사용됩니다. 제한적인 분석 데이터는 기능 사용 현황과 일반적인 실패 범주를 파악하고 확장 프로그램을 개선하는 데에만 사용됩니다.

확장 프로그램은 개인 데이터를 판매하거나 광고를 표시하거나 교차 사이트 추적을 사용하지 않습니다. 제한적인 분석 데이터는 분석 서비스 제공업체인 Mixpanel에만 전송됩니다. Mixpanel은 적용되는 약관 및 개인정보 보호 문서에 따라 데이터를 처리합니다.

- [Mixpanel 개인정보 보호정책](https://mixpanel.com/legal/privacy-policy/)
- [Mixpanel 데이터 처리 부록](https://mixpanel.com/legal/dpa/)

### 권한

확장 프로그램은 다음 권한을 요청합니다.

- **activeTab** — 사용자 작업 후 현재 지원되는 웹페이지에 접근
- **storage** — 작업, 설정, 결과, 언어 설정 및 분석 식별자를 로컬에 저장
- **alarms** — 카운트다운 및 예약 작업을 백그라운드에서 유지
- **notifications** — 작업 실행 결과 표시
- **scripting** — 지원되는 웹페이지에서 요소 선택을 시작하고 클릭 실행
- **contextMenus** — 웹페이지 컨텍스트 메뉴에 예약 클릭 바로가기 제공
- **`https://api.mixpanel.com/*` 호스트 접근** — 위에서 설명한 제한적인 분석 이벤트 전송

확장 프로그램은 브라우저 보호 페이지 또는 확장 프로그램 실행이 허용되지 않는 페이지에서 작동하지 않습니다.

### 사용자 선택 및 데이터 삭제

작업을 삭제하거나 확장 프로그램을 제거하여 로컬에 저장된 데이터를 삭제할 수 있습니다. 로컬 데이터를 지우면 로컬에서 생성된 분석 식별자가 재설정되지만 이전에 Mixpanel로 전송된 이벤트는 자동으로 삭제되지 않습니다. 현재 버전은 팝업에서 분석을 끄는 옵션을 제공하지 않습니다.

### 보안

분석 데이터를 최소화하고 허용 목록을 통해 전송 가능한 이벤트 이름과 속성을 제한합니다. 분석 전송 실패는 폐기되며 작업 실행에 영향을 주지 않습니다. 어떠한 저장 또는 인터넷 전송 방식도 완전한 보안을 보장할 수 없습니다.

### 정책 변경

확장 프로그램, 서비스 제공업체 또는 법적 요구사항의 변경을 반영하기 위해 본 정책을 업데이트할 수 있습니다. 중요한 변경 사항은 확장 프로그램 업데이트 또는 정책의 업데이트 날짜를 통해 안내합니다.

### 문의

개인정보 보호 관련 질문이나 요청은 Smart Clicker GitHub 저장소에서 Issue를 작성해 주세요.

---

## Português (Brasil)

O Smart Clicker (“a Extensão”) respeita a sua privacidade. Esta política explica quais dados a Extensão armazena localmente, quais dados limitados de uso são enviados e como são utilizados.

### Dados armazenados localmente

A Extensão usa `chrome.storage.local` para armazenar no navegador as informações necessárias para executar tarefas de clique programado. Isso pode incluir:

- o endereço da página usado para manter a tarefa associada à página correta;
- seletores dos elementos de destino;
- configurações de contagem regressiva, repetição, agendamento e condições de espera;
- estado das tarefas e resultados recentes;
- preferência de idioma; e
- um identificador de análise gerado aleatoriamente.

Os dados das tarefas são usados somente para fornecer os recursos da Extensão. Endereços de páginas, domínios, seletores, texto de elementos e valores exatos de tempo não são incluídos nos eventos de análise nem enviados pela Extensão.

### Análise limitada do produto

A Extensão envia, por padrão, um conjunto limitado de eventos de uso do produto ao Mixpanel. O popup não contém uma opção para desativar a análise.

Os eventos podem conter:

- um identificador pseudônimo aleatório não vinculado a uma conta;
- data e hora do evento;
- versão da Extensão;
- idioma selecionado da interface;
- plataforma do sistema operacional;
- nome do evento; e
- propriedades limitadas, como categoria do seletor, modo da tarefa, faixa aproximada de atraso, uso de condição de espera, categoria da falha ou idioma selecionado.

Somente eventos de interação com o produto e de estado das tarefas incluídos em uma lista restrita podem ser enviados.

A Extensão não usa o Autocapture do Mixpanel, reprodução de sessão, rastreamento de visualizações de página, perfis de publicidade ou perfis de usuário do Mixpanel e não chama `identify`.

A Extensão não coleta nem envia intencionalmente seu nome, e-mail, credenciais de conta, histórico de navegação, URL da página, domínio, seletor CSS, texto de elementos, conteúdo de formulários ou valores exatos de tempo. Como em qualquer solicitação pela internet, o Mixpanel pode processar informações técnicas de conexão, como endereço IP, conforme sua própria política; a Extensão não adiciona endereços IP aos eventos.

### Uso e compartilhamento dos dados

Os dados locais das tarefas são usados somente para operar a Extensão. A análise limitada é usada apenas para entender a adoção de recursos, analisar categorias gerais de falhas e melhorar a Extensão.

A Extensão não vende dados pessoais, não exibe publicidade e não usa rastreamento entre sites. Os dados limitados de análise são enviados somente ao Mixpanel, nosso provedor de análise. O Mixpanel processa esses dados conforme seus termos e documentos de privacidade aplicáveis:

- [Política de Privacidade do Mixpanel](https://mixpanel.com/legal/privacy-policy/)
- [Adendo de Processamento de Dados do Mixpanel](https://mixpanel.com/legal/dpa/)

### Permissões

A Extensão solicita as seguintes permissões:

- **activeTab** — acessar a página compatível atual após uma ação do usuário;
- **storage** — armazenar localmente tarefas, configurações, resultados, idioma e identificador de análise;
- **alarms** — manter contagens regressivas e tarefas agendadas em segundo plano;
- **notifications** — exibir os resultados das tarefas;
- **scripting** — iniciar a seleção de elementos e executar cliques em páginas compatíveis;
- **contextMenus** — fornecer o atalho de clique programado no menu de contexto; e
- **Acesso a `https://api.mixpanel.com/*`** — enviar os eventos limitados descritos acima.

A Extensão não funciona em páginas protegidas pelo navegador ou em outras páginas onde extensões não podem ser executadas.

### Suas opções e exclusão de dados

Você pode excluir os dados armazenados localmente removendo tarefas ou desinstalando a Extensão. A limpeza dos dados locais redefine o identificador gerado localmente, mas não exclui automaticamente eventos enviados anteriormente ao Mixpanel. A versão atual não oferece uma opção para desativar a análise no popup.

### Segurança

Minimizamos os dados de análise e restringimos por uma lista de permissões os eventos e propriedades que podem ser enviados. Falhas no envio da análise são descartadas e não afetam as tarefas. Nenhum método de armazenamento ou transmissão pela internet é completamente seguro.

### Alterações nesta política

Podemos atualizar esta política para refletir mudanças na Extensão, nos provedores ou nos requisitos legais. Alterações relevantes serão comunicadas por uma atualização da Extensão ou pela nova data desta política.

### Contato

Para dúvidas ou solicitações sobre privacidade, abra uma Issue no repositório do Smart Clicker no GitHub.
