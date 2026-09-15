# 115-iwd-3b315168
      <div>
        <label for="fullname">姓名 <mark>*</mark>：</label>
        <input 
          type="text" 
          id="fullname" 
          name="fullname" 
          placeholder="請輸入您的真實姓名" 
          required
        >
      </div>

      <br>

      <div>
        <label for="email">電子郵件 <mark>*</mark>：</label>
        <input 
          type="email" 
          id="email" 
          name="email" 
          placeholder="example@email.com" 
          required
        >
      </div>

      <br>

      <div>
        <label for="travel-month">報名月份：</label>
        <select id="travel-month" name="travel_month">
          <option value="" disabled selected>-- 請選擇出發月份 --</option>
          <option value="01">一月</option>
          <option value="02">二月</option>
          <option value="03">三月</option>
          <option value="04">四月</option>
          <option value="05">五月</option>
          <option value="06">六月</option>
          <option value="07">七月</option>
          <option value="08">八月</option>
          <option value="09">九月</option>
          <option value="10">十月</option>
          <option value="11">十一月</option>
          <option value="12">十二月</option>
        </select>
      </div>
    </fieldset>

    <br>

    <button type="submit">確認送出報名</button>
  </form>
</section>
