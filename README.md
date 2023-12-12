# Hello 👋

<div style="background-color: green; padding: 10px; color: #fff; text-align: center;">
  <h1>Personal Projects</h1>
  <table>
    <thead>
      <tr>
        <th>Project name</th>
        <th style="width: "100px";">Project Description</th>
        <th>Project link</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>
          <span style="display: flex;">
            eBex API
          </span>
        </td>
        <td>
          <span style="display: flex;">
            <p>An api to parse ebay search result outerHTML</p>
            ```json
            <pre>➡️  return structure
                  {
                  'exact_url': "https://www.ebay.com/sch/i.html?_from=R40&_trksid=p4432023.m570.l1313&_nkw=shoes&_sacat=0",
                  'applied_filters': [] -> A list of filters used on your search e.g Sold Listings, Condition,
                  'categories': [] -> A list of categories that your search is present in,
                  'listings': [{image_url:'', title:'', price: '', link:''}] 
                  'analysis_result': {'keyword':"what keyword did you used in your search",
                                      'other_word_counts':[{Counter: 10, Word: "shoes"}],
                                      'highest_price':"",
                                      'average_price: "",
                                      'middle_price': "",
                                      'lowest_price': "",
                                      'prices_counter': "",
                                     } 
                  }
             </pre>
          </span>
        </td>
        <td>
          <span style="display: flex; text-align: center;">
            <a href='http://wcawasa.pythonanywhere.com/'style="text-decoration: none;" >🔗</a>
          </span>
        </td>
      </tr>
      <!-- Add more rows as needed -->
    </tbody>
  </table>
</div>
