<template>
  <div class="doc">
    <h2>Radio</h2>
    <p class="component-name-tip">In non-string templates，it is necessary to use <code>h-radio</code>. </p>

    <h3>Basic</h3>
    <example demo="form/radio2"></example>

    <h3>Component</h3>
    <p>It is recommended to use the data mode radio selector, and use js to implement the entire interaction with higher compatibility. </p>
    <p>For the resolution of the object array, the system uses <code>key</code>, <code>title</code> by default. Two parameter names can be modified through global configuration. For details, see <router-link to="/en/component/config">Global Configuration</router-link>.</p>
    <example demo="form/radio1"></example>

    <h3>Custom key, title</h3>
    <example demo="form/radio3"></example>

    <h3>Use dictionary</h3>
    <p>Hey UI will provide a data dictionary system call, and built-in <code>dictMapping</code>methods to display. For details, go to <router-link to="/en/component/config">Global Configuration</router-link>。</p>
    <example demo="form/radio4"></example>

    <h3>Radio Property</h3>
    <table class="table">
      <tr>
        <th>Property</th>
        <th>Description</th>
        <th>Type</th>
        <th>Optional</th>
        <th>Default</th>
      </tr>
      <tr>
        <td>datas</td>
        <td>Data Dictionary</td>
        <td>Array,Object</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <td>dict</td>
        <td>Call the configured dictionary library. For details, please go to <router-link to="/en/component/config">Global Configuration</router-link></td>
        <td>String</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>disabled</td>
        <td>disabled</td>
        <td>Boolean</td>
        <td>-</td>
        <td>false</td>
      </tr>
      <tr>
        <td>value</td>
        <td>Single selection mode</td>
        <td></td>
        <td>-</td>
        <td></td>
      </tr>
      <tr>
        <td>keyName</td>
        <td>Key field name for data</td>
        <td>String</td>
        <td>-</td>
        <td>config <code>dict.keyName</code></td>
      </tr>
      <tr>
        <td>titleName</td>
        <td>title field name for data</td>
        <td>String</td>
        <td>-</td>
        <td>config <code>dict.titleName</code></td>
      </tr>
    </table>

    <h3>Radio Event</h3>
    <table class="table">
      <tr>
        <th>Event</th>
        <th>Description</th>
        <th>Return value</th>
      </tr>
      <tr>
        <td>change</td>
        <td>When data changed</td>
        <td>total object value</td>
      </tr>
      <tr>
        <td>input</td>
        <td>When data changed</td>
        <td>v-model value</td>
      </tr>
    </table>
  </div>
</template>