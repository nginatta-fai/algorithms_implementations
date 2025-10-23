# Algorithm Implementations

<table>
  <thead>
    <tr>
      <th rowspan="2">Model Name</th>
      <th colspan="2" style="text-align:center">PPO</th>
      <th colspan="2" style="text-align:center">DPO</th>
      <th colspan="2" style="text-align:center">GRPO</th>
    </tr>
    <tr>
      <th style="text-align:center">Present</th>
      <th style="text-align:center">Implementation</th>
      <th style="text-align:center">Present</th>
      <th style="text-align:center">Implementation</th>
      <th style="text-align:center">Present</th>
      <th style="text-align:center">Implementation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/allenai/open-instruct">open-instruct</a> (OLMo 2, Tülu 3)</td>
      <td style="text-align:center">✅</td>
      <td style="text-align:center">copied from <a href="https://github.com/OpenRLHF/OpenRLHF">OpenRLHF</a> and <a href="https://github.com/Open-Reasoner-Zero/Open-Reasoner-Zero">Open Reasoner Zero</a> (<a href="https://github.com/allenai/open-instruct/blob/7ba4cd0122647863b66dd4a41040d329bec7a9a2/open_instruct/ppo_vllm_thread_ray_gtrl.py#L15">source 1</a>, <a href="https://github.com/allenai/open-instruct/blob/7ba4cd0122647863b66dd4a41040d329bec7a9a2/open_instruct/ppo_fast.py#L33">source 2</a>)</td>
      <td style="text-align:center">✅</td>
      <td style="text-align:center">copied from <a href="https://github.com/eric-mitchell/direct-preference-optimization">Eric Mitchell</a> but has optimizations (e.g. <a href="https://github.com/allenai/open-instruct/pull/364">this</a>) (<a href="https://github.com/allenai/open-instruct/blob/7ba4cd0122647863b66dd4a41040d329bec7a9a2/open_instruct/dpo_utils.py#L17">source</a>)</td>
      <td style="text-align:center">✅</td>
      <td style="text-align:center">copied from <a href="https://github.com/OpenRLHF/OpenRLHF">OpenRLHF</a> (<a href="">source</a>)</td>
    </tr>
  </tbody>
</table>
