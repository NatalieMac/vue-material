<template>
  <page-content page-title="Components - Input">
    <docs-component>
      <div slot="description">
        <p>Inputs allow users to input text and usually appear in forms. Users may enter text, numbers, or mixed-format types of input.</p>
      </div>

      <div slot="api">
        <api-table name="md-input-container">
          <md-table slot="properties">
            <md-table-header>
              <md-table-row>
                <md-table-head>Name</md-table-head>
                <md-table-head>Type</md-table-head>
                <md-table-head>Description</md-table-head>
              </md-table-row>
            </md-table-header>

            <md-table-body>
              <md-table-row>
                <md-table-cell>md-inline</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Create an inline field with a label or placeholder. <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>md-has-password</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Show a button to toggle the password visibility. <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>md-clearable</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Show a button to clear the input. <br>Default: <code>false</code></md-table-cell>
              </md-table-row>
            </md-table-body>
          </md-table>

          <md-table slot="classes">
            <md-table-header>
              <md-table-row>
                <md-table-head>Name</md-table-head>
                <md-table-head>Description</md-table-head>
              </md-table-row>
            </md-table-header>

            <md-table-body>
              <md-table-row>
                <md-table-cell>md-input-invalid</md-table-cell>
                <md-table-cell>Set the error class</md-table-cell>
              </md-table-row>
            </md-table-body>
          </md-table>
        </api-table>

        <api-table name="md-input">
          <md-table slot="properties">
            <md-table-header>
              <md-table-row>
                <md-table-head>Name</md-table-head>
                <md-table-head>Type</md-table-head>
                <md-table-head>Description</md-table-head>
              </md-table-row>
            </md-table-header>

            <md-table-body>
              <md-table-row>
                <md-table-cell>v-model</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>A required model object to bind the value.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>type</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>Set the type. <br>Default: <code>text</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>debounce</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Debounce the <code>change</code> and <code>input</code> events emission. <br>Default: <code>300</code>ms</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>disabled</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Disable the input and prevent its actions. <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>required</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Apply the required rule to style the label with an "*". <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>placeholder</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>Set the placeholder.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>maxlength</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Set the maxlength and enable the text counter.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>readonly</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Set the component to read only mode.</md-table-cell>
              </md-table-row>
            </md-table-body>
          </md-table>

          <md-table slot="events">
            <md-table-header>
              <md-table-row>
                <md-table-head>Name</md-table-head>
                <md-table-head>Value</md-table-head>
                <md-table-head>Description</md-table-head>
              </md-table-row>
            </md-table-header>

            <md-table-body>
              <md-table-row>
                <md-table-cell>focus</md-table-cell>
                <md-table-cell>Emits the <code>Event</code> object</md-table-cell>
                <md-table-cell>Triggered when the user focuses the input</md-table-cell>
              </md-table-row>
              <md-table-row>
                <md-table-cell>blur</md-table-cell>
                <md-table-cell>Emits the <code>Event</code> object</md-table-cell>
                <md-table-cell>Triggered when the user loses focus of the input</md-table-cell>
              </md-table-row>
            </md-table-body>
          </md-table>
        </api-table>

        <api-table name="md-autocomplete">
          <md-table slot="properties">
            <md-table-header>
              <md-table-row>
                <md-table-head>Name</md-table-head>
                <md-table-head>Type</md-table-head>
                <md-table-head>Description</md-table-head>
              </md-table-row>
            </md-table-header>

            <md-table-body>
              <md-table-row>
                <md-table-cell>v-model</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>A required model object to bind the value.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>debounce</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Set the debounce time. <br>Default: <code>1000</code> milliseconds</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>fetch</md-table-cell>
                <md-table-cell><code>Function</code></md-table-cell>
                <md-table-cell>Set the fetch function mdAutocomplete will call after the debounce is reached. Choosing <code>fetch</code> prop <strong>disables</strong> the use of either <code>list</code> and <code>filterList</code> props.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>list</md-table-cell>
                <md-table-cell><code>Array</code></md-table-cell>
                <md-table-cell>Set an array of possible values. <br>Default: <code>[]</code>. MdAutocomplete will only search in this list if it's set. Chosing <code>list</code> prop <strong>disables</strong> the use of <code>fetch</code> prop.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>filter-list</md-table-cell>
                <md-table-cell><code>Function</code></md-table-cell>
                <md-table-cell>Set a filter function which will be used to filter the <code>list</code> props. Choosing <code>filterList</code> prop <strong>requires</strong> the use of <code>list</code> props and <strong>disables</strong> the use of <code>fetch</code> prop.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>min-chars</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Set the minimum number of characters before making opening the autocomplete options or making a request. <br>Default: <code>3</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>prepare-response-data</md-table-cell>
                <md-table-cell><code>Function</code></md-table-cell>
                <md-table-cell>This function will be called once the <code>fetch</code> prop has a response. It can manipulate the data received from the server. The output should always be an <code>Array</code>.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>print-attribute</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>This prop will be used to print values on the autocomplete list. It shall match an object key expected on the <code>fetch</code> result list. <br>Default: <code>name</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>query-param</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>Set the query parameter. Example: http//api.com/<strong>q</strong>?=SOMETHING. <br>Default: <code>q</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>disabled</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Disable the input and prevent his actions. <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>required</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Apply the required rule to style the label with an "*". <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>placeholder</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>Set the placeholder.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>maxlength</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Set the maxlength and enable the text counter.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>max-height</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Sets the maximum height of the selection menu in terms of the number of items which can be displayed at once. If set to <code>0</code>, the maximum height will be dependant on window height. <br>Default: <code>0</code></md-table-cell>
              </md-table-row>
              
              <md-table-row>
                <md-table-cell>max-res</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Set the maximum number of results to show. If <code>0</code>, results are not limited. <br>Default: <code>0</code></md-table-cell>
              </md-table-row>
            </md-table-body>
          </md-table>

          <md-table slot="events">
            <md-table-header>
              <md-table-row>
                <md-table-head>Name</md-table-head>
                <md-table-head>Value</md-table-head>
                <md-table-head>Description</md-table-head>
              </md-table-row>
            </md-table-header>

            <md-table-body>
              <md-table-row>
                <md-table-cell>change</md-table-cell>
                <md-table-cell>The <code>String</code> selected</md-table-cell>
                <md-table-cell>Triggered when the user selects an item from the autocomplete list</md-table-cell>
              </md-table-row>
              <md-table-row>
                <md-table-cell>input</md-table-cell>
                <md-table-cell>The <code>String</code> selected</md-table-cell>
                <md-table-cell>Triggered when the user selects an item from the autocomplete list</md-table-cell>
              </md-table-row>
              <md-table-row>
                <md-table-cell>selected</md-table-cell>
                <md-table-cell>Emits the <code>Object</code> as well as the <code>String</code> selected.</md-table-cell>
                <md-table-cell>Triggered when the user selects an item from the autocomplete list</md-table-cell>
              </md-table-row>
            </md-table-body>
          </md-table>
        </api-table>

        <api-table name="md-textarea">
          <md-table slot="properties">
            <md-table-header>
              <md-table-row>
                <md-table-head>Name</md-table-head>
                <md-table-head>Type</md-table-head>
                <md-table-head>Description</md-table-head>
              </md-table-row>
            </md-table-header>

            <md-table-body>
              <md-table-row>
                <md-table-cell>v-model</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>A required model object to bind the value.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>debounce</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Debounce the <code>change</code> and <code>input</code> events emission. <br>Default: <code>300</code>ms</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>disabled</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Disable the textarea and prevent its actions. <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>required</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Apply the required rule to style the label with an "*". <br>Default: <code>false</code></md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>placeholder</md-table-cell>
                <md-table-cell><code>String</code></md-table-cell>
                <md-table-cell>Set the placeholder.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>maxlength</md-table-cell>
                <md-table-cell><code>Number</code></md-table-cell>
                <md-table-cell>Set the maxlength and enable the text counter.</md-table-cell>
              </md-table-row>

              <md-table-row>
                <md-table-cell>readonly</md-table-cell>
                <md-table-cell><code>Boolean</code></md-table-cell>
                <md-table-cell>Set the component to read only mode.</md-table-cell>
              </md-table-row>
            </md-table-body>
          </md-table>
        </api-table>
      </div>

      <div slot="example">
        <example-box card-title="Regular fields">
          <div slot="demo">
            <form novalidate @submit.stop.prevent="submit">
              <md-input-container>
                <label>Initial value</label>
                <md-input v-model="initialValue"></md-input>
              </md-input-container>

              <md-input-container>
                <label>Initial value (read only)</label>
                <md-input v-model="initialValue" readonly></md-input>
              </md-input-container>

              <md-input-container>
                <label>Autocomplete (with fetch)</label>
                <md-autocomplete v-model="autocompleteValue" :fetch="fetchAutocomplete"></md-autocomplete>
              </md-input-container>

              <md-input-container>
                <label>With label</label>
                <md-input placeholder="My nice placeholder"></md-input>
              </md-input-container>

              <md-input-container md-inline>
                <label>Inline field</label>
                <md-input></md-input>
              </md-input-container>

              <md-input-container>
                <label>Number</label>
                <md-input type="number"></md-input>
              </md-input-container>

              <md-input-container>
                <label>Textarea</label>
                <md-textarea></md-textarea>
              </md-input-container>

              <md-input-container>
                <label>Disabled</label>
                <md-input disabled></md-input>
              </md-input-container>

              <md-input-container md-clearable>
                <label>Clearable</label>
                <md-input v-model="initialValue"></md-input>
              </md-input-container>
            </form>
          </div>

          <div slot="code">
            <code-block lang="xml">
              &lt;form novalidate @submit.stop.prevent=&quot;submit&quot;&gt;
                &lt;md-input-container&gt;
                  &lt;label&gt;Initial value&lt;/label&gt;
                  &lt;md-input v-model=&quot;initialValue&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;label&gt;Autocomplete (with fetch)&lt;/label&gt;
                  &lt;md-autocomplete v-model=&quot;autocompleteValue&quot; :fetch=&quot;fetchFunction&quot;&gt;&lt;/md-autocomplete&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;label&gt;With label&lt;/label&gt;
                  &lt;md-input placeholder=&quot;My nice placeholder&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container md-inline&gt;
                  &lt;label&gt;Inline field&lt;/label&gt;
                  &lt;md-input&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;label&gt;Number&lt;/label&gt;
                  &lt;md-input type=&quot;number&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;label&gt;Textarea&lt;/label&gt;
                  &lt;md-textarea&gt;&lt;/md-textarea&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;label&gt;Disabled&lt;/label&gt;
                  &lt;md-input disabled&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container md-clearable&gt;
                  &lt;label&gt;Clearable&lt;/label&gt;
                  &lt;md-input v-model=&quot;initialValue&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;
              &lt;/form&gt;
            </code-block>

            <code-block lang="javascript">
              export default {
                data() {
                  return {
                    initialValue: &apos;My initial value&apos;
                  };
                },
                methods: {
                  fetchFunction(param) {
                    // param = { queryParam: query }

                    // &apos;fetchAutocomplete&apos; should return a Promise.

                    // md-autocomplete will call fetchAutocomplete and pass
                    // &apos;param&apos; as an argument.
                    // the &apos;param&apos; is composed by a query param and
                    // a query.
                  },
                },
              };
            </code-block>
          </div>
        </example-box>

        <example-box card-title="Passwords">
          <div slot="demo">
            <form novalidate @submit.stop.prevent="submit">
              <md-input-container>
                <label>Regular Password</label>
                <md-input type="password"></md-input>
              </md-input-container>

              <md-input-container md-has-password>
                <label>Password Reveal</label>
                <md-input type="password"></md-input>
              </md-input-container>
            </form>
          </div>

          <div slot="code">
            <code-block lang="xml">
              &lt;form novalidate @submit.stop.prevent=&quot;submit&quot;&gt;
                &lt;md-input-container&gt;
                  &lt;label&gt;Regular Password&lt;/label&gt;
                  &lt;md-input type=&quot;password&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container md-has-password&gt;
                  &lt;label&gt;Password Reveal&lt;/label&gt;
                  &lt;md-input type=&quot;password&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;
              &lt;/form&gt;
            </code-block>
          </div>
        </example-box>

        <example-box card-title="Icons">
          <div slot="demo">
            <form novalidate @submit.stop.prevent="submit">
              <md-input-container>
                <md-icon class="md-warn">
                  warning
                  <md-tooltip>Be careful. You're almost broken!</md-tooltip>
                </md-icon>
                <label>Money</label>
                <md-input type="number"></md-input>
                <md-icon>attach_money</md-icon>
              </md-input-container>

              <md-input-container>
                <md-icon>phone</md-icon>
                <label>Phone</label>
                <md-input type="tel"></md-input>
              </md-input-container>

              <md-input-container>
                <md-icon>speaker_notes</md-icon>
                <label>Notes</label>
                <md-textarea></md-textarea>
              </md-input-container>
            </form>
          </div>

          <div slot="code">
            <code-block lang="xml">
              &lt;form novalidate @submit.stop.prevent=&quot;submit&quot;&gt;
                &lt;md-input-container&gt;
                  &lt;md-icon class=&quot;md-warn&quot;&gt;
                    warning
                    &lt;md-tooltip&gt;Be careful. You&#039;re almost broken!&lt;/md-tooltip&gt;
                  &lt;/md-icon&gt;
                  &lt;label&gt;Money&lt;/label&gt;
                  &lt;md-input type=&quot;number&quot;&gt;&lt;/md-input&gt;
                  &lt;md-icon&gt;attach_money&lt;/md-icon&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;md-icon&gt;phone&lt;/md-icon&gt;
                  &lt;label&gt;Phone&lt;/label&gt;
                  &lt;md-input type=&quot;tel&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;md-icon&gt;speaker_notes&lt;/md-icon&gt;
                  &lt;label&gt;Notes&lt;/label&gt;
                  &lt;md-textarea&gt;&lt;/md-textarea&gt;
                &lt;/md-input-container&gt;
              &lt;/form&gt;
            </code-block>
          </div>
        </example-box>

        <example-box card-title="Required and Errors">
          <div slot="demo">
            <form novalidate @submit.stop.prevent="submit">
              <md-input-container>
                <label>Required</label>
                <md-input required></md-input>
              </md-input-container>

              <md-input-container class="md-input-invalid">
                <label>Error</label>
                <md-input required></md-input>
              </md-input-container>

              <md-input-container class="md-input-invalid">
                <label>Error with message</label>
                <md-input required></md-input>

                <span class="md-error">Validation message</span>
              </md-input-container>

              <md-input-container class="md-input-invalid">
                <label>Textarea with error</label>
                <md-textarea></md-textarea>

                <span class="md-error">Textarea validation message</span>
              </md-input-container>
            </form>
          </div>

          <div slot="code">
            <code-block lang="xml">
              &lt;form novalidate @submit.stop.prevent=&quot;submit&quot;&gt;
                &lt;md-input-container&gt;
                  &lt;label&gt;Required&lt;/label&gt;
                  &lt;md-input required&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container class=&quot;md-input-invalid&quot;&gt;
                  &lt;label&gt;Error&lt;/label&gt;
                  &lt;md-input required&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container class=&quot;md-input-invalid&quot;&gt;
                  &lt;label&gt;Error with message&lt;/label&gt;
                  &lt;md-input required&gt;&lt;/md-input&gt;

                  &lt;span class=&quot;md-error&quot;&gt;Validation message&lt;/span&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container class=&quot;md-input-invalid&quot;&gt;
                  &lt;label&gt;Textarea with error&lt;/label&gt;
                  &lt;md-textarea&gt;&lt;/md-textarea&gt;

                  &lt;span class=&quot;md-error&quot;&gt;Textarea validation message&lt;/span&gt;
                &lt;/md-input-container&gt;
              &lt;/form&gt;
            </code-block>
          </div>
        </example-box>

        <example-box card-title="Character counter">
          <div slot="demo">
            <form novalidate @submit.stop.prevent="submit">
              <md-input-container>
                <label>Textarea</label>
                <md-textarea maxlength="70"></md-textarea>
              </md-input-container>

              <md-input-container>
                <label>Input</label>
                <md-input maxlength="20"></md-input>
              </md-input-container>
            </form>
          </div>

          <div slot="code">
            <code-block lang="xml">
              &lt;form novalidate @submit.stop.prevent=&quot;submit&quot;&gt;
                &lt;md-input-container&gt;
                  &lt;label&gt;Textarea&lt;/label&gt;
                  &lt;md-textarea maxlength=&quot;70&quot;&gt;&lt;/md-textarea&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container&gt;
                  &lt;label&gt;Input&lt;/label&gt;
                  &lt;md-input maxlength=&quot;20&quot;&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;
              &lt;/form&gt;
            </code-block>
          </div>
        </example-box>

        <example-box card-title="Themes">
          <div slot="demo">
            <form novalidate @submit.stop.prevent="submit">
              <md-input-container md-theme="green">
                <label>Green - Input</label>
                <md-input></md-input>
              </md-input-container>

              <md-input-container md-theme="red">
                <label>Red - Textarea</label>
                <md-textarea></md-textarea>
              </md-input-container>
            </form>
          </div>

          <div slot="code">
            <code-block lang="xml">
              &lt;form novalidate @submit.stop.prevent=&quot;submit&quot;&gt;
                &lt;md-input-container md-theme=&quot;green&quot;&gt;
                  &lt;label&gt;Green - Input&lt;/label&gt;
                  &lt;md-input&gt;&lt;/md-input&gt;
                &lt;/md-input-container&gt;

                &lt;md-input-container md-theme=&quot;red&quot;&gt;
                  &lt;label&gt;Red - Textarea&lt;/label&gt;
                  &lt;md-textarea&gt;&lt;/md-textarea&gt;
                &lt;/md-input-container&gt;
              &lt;/form&gt;
            </code-block>
          </div>
        </example-box>

        <example-box card-title="Autocomplete Example">
          <div slot="demo">
            <form novalidate @submit.stop.prevent="submit">
              <md-input-container md-theme="green">
                <label>Choose a Colour</label>
                <md-autocomplete v-model="colorValue" 
                                 :list="colorData"
                                 print-attribute="name"
                                 :filter-list="colorFilter"
                                 :min-chars="0"
                                 :max-height="6"
                                 @selected="colorCallback"
                                 :debounce="500">
                </md-autocomplete>
              </md-input-container>

              <div class="color-box" :style="{ backgroundColor: selectedColor }"></div>
            </form>
          </div>

          <div slot="code">
            <code-block lang="xml">
              &lt;form novalidate @submit.stop.prevent=&quot;submit&quot;&gt;
                &lt;md-input-container md-theme=&quot;green&quot;&gt;
                  &lt;label&gt;Choose a Colour&lt;/label&gt;
                  &lt;md-autocomplete v-model=&quot;colorValue&quot; 
                                      :list=&quot;colorData&quot;
                                      print-attribute=&quot;name&quot;
                                      :filter-list=&quot;colorFilter&quot;
                                      :min-chars=&quot;0&quot;
                                      :max-height=&quot;6&quot;
                                      @selected=&quot;colorCallback&quot;
                                      :debounce=&quot;500&quot;&gt;
                  &lt;/md-autocomplete&gt;
                &lt;/md-input-container&gt;
              
                &lt;div class=&quot;color-box&quot; :style=&quot;{ backgroundColor: selectedColor }&quot;&gt;&lt;/div&gt;
              &lt;/form&gt;
            </code-block>

            <code-block lang="javascript">
              export default {
                data() {
                  return {
                    colorValue: '',
                    colorData: [
                      {name: "aqua", color: "#00ffff"},
                      {name: "aquamarine", color: "#7fffd4"},
                      {name: "azure", color: "#f0ffff"},
                      {name: "beige", color: "#f5f5dc"},
                      {name: "black", color: "#000000"},
                      {name: "blue", color: "#0000ff"},
                      {name: "brown", color: "#a52a2a"},
                      {name: "crimson", color: "#dc143c"},
                      {name: "cyan", color: "#00ffff"},
                      {name: "deeppink", color: "#ff1493"},
                      {name: "dimgray", color: "#696969"},
                      {name: "fuchsia", color: "#ff00ff"},
                      {name: "gold", color: "#ffd700"},
                      {name: "gray", color: "#808080"},
                      {name: "green", color: "#008000"},
                      {name: "greenyellow", color: "#adff2f"},
                      {name: "grey", color: "#808080"},
                      {name: "hotpink", color: "#ff69b4"},
                      {name: "indigo", color: "#4b0082"},
                      {name: "ivory", color: "#fffff0"},
                      {name: "khaki", color: "#f0e68c"},
                      {name: "lavender", color: "#e6e6fa"},
                      {name: "lime", color: "#00ff00"},
                      {name: "magenta", color: "#ff00ff"},
                      {name: "maroon", color: "#800000"},
                      {name: "navy", color: "#000080"},
                      {name: "olive", color: "#808000"},
                      {name: "orange", color: "#ffa500"},
                      {name: "orangered", color: "#ff4500"},
                      {name: "palegoldenrod", color: "#eee8aa"},
                      {name: "palegreen", color: "#98fb98"},         
                      {name: "pink", color: "#ffc0cb"},
                      {name: "purple", color: "#800080"},
                      {name: "red", color: "#ff0000"},
                      {name: "royalblue", color: "#4169e1"},
                      {name: "seagreen", color: "#2e8b57"},
                      {name: "silver", color: "#c0c0c0"},
                      {name: "skyblue", color: "#87ceeb"},
                      {name: "slateblue", color: "#6a5acd"},
                      {name: "slategrey", color: "#708090"},
                      {name: "teal", color: "#008080"},
                      {name: "turquoise", color: "#40e0d0"},
                      {name: "violet", color: "#ee82ee"},
                      {name: "white", color: "#ffffff"},         
                      {name: "yellow", color: "#ffff00"},
                    ]
                  };
                },
                methods: {
                  colorFilter: function(list, query) {
                    var arr = [];
            
                    for(var i = 0; i &lt; list.length; i++) {
                      if(list[i].name.indexOf(query) !== -1)
                        arr.push(list[i]);
            
                      if(arr.length &gt; 5)
                        break;
                    }
            
                    return arr;
                  },
            
                  colorCallback: function(item) {
                    this.selectedColor = item.color;
                  }
                }
              }; 
            </code-block>
          </div>
        </example-box>
      </div>
    </docs-component>
  </page-content>
</template>

<style lang="scss" scoped>
  .color-box {
    width: 200px;
    height: 200px;
  }
</style>

<script>
  export default {
    data() {
      return {
        autocompleteValue: '',
        colorValue: '',
        initialValue: 'My initial value',
        listAutocomplete: [
          {name: 'oi'},
          {name: 'hello'},
          {name: 'salut'}
        ],
        colorData: [
          {name: 'aqua', color: '#00ffff'},
          {name: 'aquamarine', color: '#7fffd4'},
          {name: 'azure', color: '#f0ffff'},
          {name: 'beige', color: '#f5f5dc'},
          {name: 'black', color: '#000000'},
          {name: 'blue', color: '#0000ff'},
          {name: 'brown', color: '#a52a2a'},
          {name: 'crimson', color: '#dc143c'},
          {name: 'cyan', color: '#00ffff'},
          {name: 'deeppink', color: '#ff1493'},
          {name: 'dimgray', color: '#696969'},
          {name: 'fuchsia', color: '#ff00ff'},
          {name: 'gold', color: '#ffd700'},
          {name: 'gray', color: '#808080'},
          {name: 'green', color: '#008000'},
          {name: 'greenyellow', color: '#adff2f'},
          {name: 'grey', color: '#808080'},
          {name: 'hotpink', color: '#ff69b4'},
          {name: 'indigo', color: '#4b0082'},
          {name: 'ivory', color: '#fffff0'},
          {name: 'khaki', color: '#f0e68c'},
          {name: 'lavender', color: '#e6e6fa'},
          {name: 'lime', color: '#00ff00'},
          {name: 'magenta', color: '#ff00ff'},
          {name: 'maroon', color: '#800000'},
          {name: 'navy', color: '#000080'},
          {name: 'olive', color: '#808000'},
          {name: 'orange', color: '#ffa500'},
          {name: 'orangered', color: '#ff4500'},
          {name: 'palegoldenrod', color: '#eee8aa'},
          {name: 'palegreen', color: '#98fb98'},
          {name: 'pink', color: '#ffc0cb'},
          {name: 'purple', color: '#800080'},
          {name: 'red', color: '#ff0000'},
          {name: 'royalblue', color: '#4169e1'},
          {name: 'seagreen', color: '#2e8b57'},
          {name: 'silver', color: '#c0c0c0'},
          {name: 'skyblue', color: '#87ceeb'},
          {name: 'slateblue', color: '#6a5acd'},
          {name: 'slategrey', color: '#708090'},
          {name: 'teal', color: '#008080'},
          {name: 'turquoise', color: '#40e0d0'},
          {name: 'violet', color: '#ee82ee'},
          {name: 'white', color: '#ffffff'},
          {name: 'yellow', color: '#ffff00'}
        ]
      };
    },
    methods: {
      colorFilter: function(list, query) {
        var arr = [];

        for (var i = 0; i < list.length; i++) {
          if (list[i].name.indexOf(query) !== -1) {
            arr.push(list[i]);
          }

          if (arr.length > 5) {
            break;
          }
        }

        return arr;
      },

      colorCallback: function(item) {
        this.selectedColor = item.color;
      },

      fetchAutocomplete(param) {
        const myInit = {
          method: 'GET',
          headers: new Headers(),
          mode: 'cors',
          cache: 'default'
        };

        const url = 'https://typeahead-js-twitter-api-proxy.herokuapp.com/demo/search';
        const queryParam = Object.keys(param)[0];
        const queryValue = param[queryParam];
        const queryUrl = `${url}?${queryParam}=${queryValue}`;

        return window.fetch(queryUrl, myInit)
          .then((res) => res.json());
      },
      filterList(list, query) {
        return list.filter((el) => el.name.indexOf(query) !== -1);
      }
    }
  };
</script>
